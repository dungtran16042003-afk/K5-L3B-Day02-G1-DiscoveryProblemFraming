# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:G1
- Thành viên: Nguyễn Tấn Dũng, Lê Huy Anh
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Dũng | Khi cuộc họp giao ban nội bộ kéo dài 60–90 phút kết thúc, tôi muốn có ngay danh sách Action Items phân công rõ người phụ trách kèm thời hạn, để triển khai việc ngay mà không phải tua lại ghi âm. | Người ghi biên bản họp, 6 thành viên nhóm dự án | Bước 3 (tua lại file ghi âm: 35') và Bước 4 (tổng hợp gõ bảng Action Items: 20') — Tổng nghẽn 55' | "Nếu file âm thanh bị ồn hoặc người họp nói chen ngang, hệ thống có nguy cơ gán nhầm việc của người này sang người khác không?" (Huy Anh hỏi) |
| 2 | Dũng | Khi hoàn tất chuyến công tác với 15–20 hóa đơn lẻ và vé xe, tôi muốn chuyển đổi chính xác thông tin ngày, MST và số tiền vào bảng kê, để kế toán thanh toán đúng hạn quy định. | Nhân viên đi công tác, 1 kế toán thanh toán | Bước 3 (gõ tay 7 trường thông tin: 65') và Bước 4 (bấm máy tính cộng dồn đối chiếu chéo: 25') — Tổng nghẽn 90' | "Các hóa đơn in nhiệt từ quán ăn nhỏ rất hay bị mờ mực hoặc rách mép, OCR đọc sai số tiền thì người dùng vẫn phải ngồi dò lại từng dòng à?" (Huy Anh hỏi) |
| 3 | Dũng | Khi tiếp nhận 40–50 email yêu cầu hỗ trợ nội bộ mỗi ngày, tôi muốn gom nhóm về đúng phòng ban chuyên trách, để chuyển giao kịp thời mà không bị trôi việc khẩn cấp. | Nhân viên trực hòm thư nội bộ, các phòng ban (IT, HR, Kế toán) | Bước 2 (đọc chi tiết nội dung email: 35') và Bước 3 (xác định phòng ban và chuyển tiếp thủ công: 25') — Tổng nghẽn 60' | "Nếu chuyển hòm thư sang Google Forms bắt buộc người gửi chọn sẵn danh mục rồi dùng Rule tự chuyển tiếp thì có cần AI nữa không?" (Huy Anh hỏi) |
| 4 | Huy Anh | Khi hệ thống kiểm thử phát sinh hàng chục file log lỗi sau đợt cập nhật phần mềm, tôi muốn gom cụm các lỗi giống nhau, để giao đúng lập trình viên sửa mà không phải đọc thủ công từng stack trace. | Kỹ sư đảm bảo chất lượng (QA), nhóm phát triển phần mềm | Đọc dò từng đoạn stack trace và so sánh ngữ cảnh lỗi giữa các tệp log (mất 45'/đợt) | "Các công cụ APM hay Sentry hiện nay đã có rule gom cụm theo exception signature rồi, tại sao không dùng rule sẵn có?" (Dũng hỏi) |
| 5 | Huy Anh | Khi nhận tài liệu đặc tả yêu cầu kỹ thuật (SRS) dài 30–40 trang từ đối tác, tôi muốn trích xuất nhanh các tiêu chí nghiệm thu và ràng buộc logic, để lập kế hoạch triển khai mà không mất cả ngày đọc lướt. | Lập trình viên chính, kỹ sư phân tích nghiệp vụ | Đọc toàn văn tài liệu và nhặt các điều kiện ràng buộc rải rác trong nhiều chương (mất 75'/tài liệu) | "Tài liệu kỹ thuật của đối tác có nhiều thuật ngữ nghiệp vụ riêng, làm sao đo được việc AI trích xuất có bị thiếu các ràng buộc ngầm không?" (Dũng hỏi) |
| 6 | Huy Anh | Khi chuẩn bị bộ hồ sơ nghiệm thu đồ án kỹ thuật, tôi muốn kiểm tra nhanh tính đồng bộ giữa mã nguồn và tài liệu hướng dẫn cài đặt, để không bị hội đồng trả về vì thiếu bước cấu hình. | Sinh viên làm đồ án tốt nghiệp, người đánh giá kỹ thuật | Mở máy ảo chạy thử từng lệnh cấu hình theo tài liệu và ghi nhận lỗi không khớp (mất 50'/lần) | "Viết một script Dockerfile hoặc shell script tự động chạy thử từ đầu đến cuối có kiểm tra được việc này nhanh hơn không?" (Dũng hỏi) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| **A — Bóc tách & Chuẩn hóa thông tin sau trao đổi** | Candidate #1 (Action Items sau họp), Candidate #5 (Trích xuất yêu cầu tài liệu SRS) | Biến văn bản thô, dài hoặc ngôn ngữ nói thành danh sách các đầu mục hành động có cấu trúc chặt chẽ. |
| **B — Rà soát & Kiểm tra tính đồng bộ hồ sơ** | Candidate #2 (Nhập hóa đơn hoàn ứng), Candidate #6 (Kiểm tra hồ sơ nghiệm thu đồ án) | Đối chiếu chéo giữa chứng từ/tài liệu với biểu mẫu quy định để phát hiện sai lệch trước khi bàn giao. |
| **C — Phân loại & Điều phối dữ liệu vận hành** | Candidate #3 (Điều phối email hỗ trợ), Candidate #4 (Gom cụm log lỗi kiểm thử) | Đọc hiểu dữ liệu đầu vào phi cấu trúc (email, log) và gắn nhãn để điều hướng đến đúng người phụ trách. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome đo được**. Các nhánh chỉ là **Opportunity (Pain/Nhu cầu)**, không chứa tên công cụ hay giải pháp kỹ thuật.

```text
OUTCOME: Giảm thời gian hoàn thành biên bản sau cuộc họp nội bộ từ 70 phút xuống dưới 15 phút mà không sót đầu việc
├── Opportunity 1 (Pain): Người ghi chép mất 35 phút tua lại file ghi âm chỉ để nghe lại ai nhận việc gì và hạn chót khi nào
├── Opportunity 2 (Pain): Mất 20 phút ngồi tổng hợp, chuẩn hóa và gõ lại bảng Action Items từ các đoạn ghi chú thô rời rạc
└── Opportunity 3 (Pain): Các thành viên dự họp hiểu nhầm hoặc quên các cam kết miệng dẫn đến trễ hạn triển khai công việc
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
