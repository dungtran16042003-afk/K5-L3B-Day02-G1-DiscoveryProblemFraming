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
| 1 | Dũng | Khi cuộc họp giao ban nội bộ kéo dài 60–90 phút kết thúc, tôi muốn có ngay danh sách Action Items phân công rõ người phụ trách kèm hạn chót, để các bên thực hiện đúng tiến độ mà không phải hỏi lại hay nghe lại ghi âm. | Người ghi biên bản họp, 6 thành viên trong nhóm dự án | Bước tua lại ghi âm (35') và bước tổng hợp bảng Action Items (20') — Tổng nghẽn 55' | "Nếu người họp nói chen lấn, chất lượng ghi âm kém hoặc chỉ có bản gõ nháp vội thì hệ thống có gán sai đầu việc cho người khác không?" (Huy Anh hỏi) |
| 2 | Dũng | Khi kết thúc đợt công tác với 15–20 hóa đơn lẻ và vé tàu xe, tôi muốn điền chính xác thông tin ngày, MST và số tiền vào bảng kê, để kế toán thanh toán đúng hạn quy định. | Nhân viên đi công tác, 1 kế toán thanh toán | Gõ tay 7 trường thông tin từ 15–20 hóa đơn (65') và bấm máy tính cộng dồn đối chiếu chéo (25') — Tổng nghẽn 90' | "Các quán ăn nhỏ dùng hóa đơn giấy viết tay hoặc hóa đơn in nhiệt mờ mực thì xử lý thế nào để không phải ngồi sửa lại bằng tay?" (Huy Anh hỏi) |
| 3 | Dũng | Khi tiếp nhận 40–50 email hỗ trợ nội bộ mỗi ngày, tôi muốn gom nhóm về đúng phòng ban chuyên trách, để chuyển tiếp kịp thời mà không bị trôi việc khẩn cấp. | Nhân viên trực hòm thư nội bộ, các phòng ban (IT, HR, Kế toán) | Đọc chi tiết nội dung email (35') và thao tác chuyển tiếp thủ công (25') — Tổng nghẽn 60' | "Nếu dùng Google Forms bắt buộc người gửi chọn danh mục phòng ban và cài Rule chuyển tiếp tự động thì đã giải quyết được chưa mà cần đến AI?" (Huy Anh hỏi) |
| 4 | Huy Anh | Khi chuẩn bị trước mỗi buổi thuyết trình môn học, tôi muốn kiểm tra và định dạng slide theo đúng mẫu chuẩn của trường, để bài báo cáo không bị trừ điểm hình thức. | Sinh viên báo cáo đồ án / tiểu luận | Ngồi chỉnh sửa thủ công kích thước chữ, khoảng cách lề và căn lề từng slide (mất 45') | "Quy chuẩn slide đã có template mẫu sẵn trên Canva/PowerPoint, tại sao không áp dụng master slide từ đầu?" (Dũng hỏi) |
| 5 | Huy Anh | Khi làm bài tập lớn lập trình nhóm, tôi muốn rà soát nhanh các lỗi cú pháp và chuẩn đặt tên biến trước khi gộp code, để nhánh chính không bị lỗi build. | Sinh viên IT, thành viên nhóm làm đồ án | Đọc dò từng pull request và kiểm tra đối chiếu quy ước đặt tên (mất 30'/lần) | "Các công cụ linter (ESLint, Flake8) và GitHub Actions có sẵn đã chặn được các lỗi này ở mức Rule chưa?" (Dũng hỏi) |
| 6 | Huy Anh | Khi tìm kiếm tài liệu học tập trong kho lưu trữ chung của môn học, tôi muốn tìm đúng đoạn lý thuyết cần đọc, để ôn thi kịp thời mà không phải mở từng file PDF 50 trang. | Sinh viên ôn thi cuối kỳ | Mở từng file tài liệu và nhấn `Ctrl + F` tìm từ khóa (mất 40'/chương) | "Tài liệu môn học có bản quyền hoặc dạng ảnh scan thì việc trích xuất có đảm bảo đủ ngữ cảnh chính xác không?" (Dũng hỏi) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| **A — Bóc tách & Chuẩn hóa thông tin sau trao đổi** | Candidate #1 (Action Items sau họp), Candidate #4 (Định dạng slide thuyết trình) | Chuyển đổi dữ liệu thô, lộn xộn sau quá trình thảo luận/soạn thảo thành văn bản có cấu trúc chuẩn để bàn giao. |
| **B — Rà soát & Phân loại dữ liệu tác vụ** | Candidate #3 (Phân loại email hỗ trợ), Candidate #5 (Rà soát pull request code) | Đọc hiểu nội dung đầu vào tự do và đối chiếu với danh mục/quy chuẩn định sẵn để điều hướng hoặc gắn nhãn. |
| **C — Trích xuất & Nhập liệu chứng từ / tài liệu** | Candidate #2 (Nhập hóa đơn hoàn ứng), Candidate #6 (Tìm tài liệu ôn tập PDF) | Đọc các tài liệu văn bản/ảnh dài, bóc tách các trường dữ liệu quan trọng để đưa vào nơi lưu trữ phục vụ tra cứu. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian hoàn thành biên bản sau cuộc họp từ 70 phút xuống dưới 15 phút mà không sót đầu việc
├── Opportunity 1 (Pain): Mất 35 phút tua đi tua lại băng ghi âm chỉ để xác nhận ai nhận việc gì và hạn chót khi nào
├── Opportunity 2 (Pain): Mất 20 phút ngồi gõ và định dạng lại bảng Action Items từ các đoạn ghi chú thô rời rạc
└── Opportunity 3 (Pain): Các bên hiểu nhầm thỏa thuận miệng trong buổi họp dẫn đến trễ hạn triển khai công việc
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
