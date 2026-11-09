# Báo cáo nhóm — Day 02 Discovery & Problem Framing

## 1. Thông tin nhóm

- Tên nhóm: G1
- Thành viên: Nguyễn Tấn Dũng, Lê Huy Anh
- Candidate problem được chọn (1 câu): Điều phối yêu cầu nội bộ: tiếp nhận yêu cầu, kiểm tra tính đầy đủ thông tin, xác định đúng bộ phận phụ trách và theo dõi trạng thái xử lý để tránh thất lạc việc khẩn.
- Quyết định cuối: Go / Not Yet / No-Go 
---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

Tổng hợp từ 3 Problem Cards cá nhân của Nguyễn Tấn Dũng và 3 Problem Cards cá nhân của Lê Huy Anh. Các số liệu dưới đây là baseline/ước lượng ban đầu, sẽ được kiểm chứng lại tại CP4.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck / dấu hiệu pain | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Dũng | Khi cuộc họp giao ban nội bộ kết thúc, tôi muốn có danh sách quyết định và action items có người phụ trách, hạn chót rõ ràng để mọi người triển khai đúng tiến độ. | Người ghi biên bản và 6 thành viên nhóm dự án | Họp 3 lần/tuần; mất 45–60 phút/buổi tua lại ghi âm và tổng hợp; tháng trước có 2 việc trễ do hiểu nhầm phân công miệng. | "Làm sao để đảm bảo bản ghi chính xác ghi đúng trong trường hợp những người tham gia cuộc họp nói giọng địa phương hoặc bị ngọng, nói tiếng dân tộc?" (Huy Anh hỏi) |
| 2 | Dũng | Khi hoàn tất chuyến công tác với 15–20 hóa đơn lẻ, tôi muốn điền chính xác thông tin vào bảng kê hoàn ứng để nộp kế toán đúng hạn quy định. | Nhân viên đi công tác và 1 kế toán thanh toán | Gõ tay 7 trường thông tin và cộng nhẩm mất 90 phút/đợt; 2–3 hóa đơn/đợt bị gõ nhầm số tiền hoặc MST làm chậm hoàn ứng 3–5 ngày. | "Làm sao để AI xác nhận được hoá đơn là thật chứ không phải người đi công tác làm giả để trục lợi?" (Huy Anh hỏi) |
| 3 | Dũng | Khi nhận 40–50 email hỗ trợ nội bộ mỗi ngày, tôi muốn chuyển từng yêu cầu đến đúng phòng ban chuyên trách để việc khẩn không bị chậm trễ. | Nhân viên trực hòm thư chung và các phòng ban xử lý (IT, HR, Kế toán) | Đọc và chuyển email thủ công mất 60 phút/ngày; 3–4 email khẩn/tuần bị trễ hơn 4 giờ do phân loại nhầm hoặc bị trôi trong hòm thư. | "Nếu chuyển hòm thư sang Google Forms bắt buộc người gửi chọn danh mục rồi dùng Rule tự chuyển tiếp thì có cần AI nữa không?" (Huy Anh hỏi) |
| 4 | Huy Anh | Khi cần soạn công văn hành chính theo mẫu có sẵn, tôi muốn tạo được bản nháp đúng thể thức từ hồ sơ để hoàn thành nhanh và giảm số lần phải sửa. | Cán bộ soạn thảo văn bản, văn thư hoặc người duyệt | Ước lượng 20–40 phút/văn bản; chưa rõ thời gian mất nhiều nhất ở tìm mẫu, tra cứu căn cứ hay chỉnh sửa câu chữ. | "Biểu mẫu và trường dữ liệu công văn đã đủ chuẩn hóa chưa, việc này dùng template mẫu kết hợp mail merge có nhanh hơn không?" (Dũng hỏi) |
| 5 | Huy Anh | Khi tiếp nhận hồ sơ đề xuất dự án đầu tư tại địa bàn, tôi muốn tập hợp các thông tin và điểm rà soát để thẩm định có hệ thống, không bỏ sót vấn đề cần xin ý kiến. | Cán bộ thẩm định hồ sơ, lãnh đạo và chuyên viên liên quan | Ước lượng mất 2–4 giờ/hồ sơ để đọc và tổng hợp ban đầu; tiêu chí thẩm định phức tạp và tài liệu chưa số hóa đồng bộ. | "Tiêu chí thẩm định có quy định cứng không; Liệu sử dụng AI có rủi ro lộ thông tin mật của các dự án hay nhà thầu cho những bản quy hoạch chưa được công bố không?" (Dũng hỏi) |
| 6 | Huy Anh | Khi một phòng ban gửi yêu cầu cần bộ phận khác xử lý, tôi muốn yêu cầu đủ thông tin, chuyển đúng nơi và theo dõi được trạng thái để tránh bị bỏ sót hoặc nhắc lại. | Nhân viên gửi yêu cầu, đầu mối điều phối, bộ phận xử lý | Mất 10–20 phút/yêu cầu để xác định nơi nhận, bổ sung thông tin và theo dõi; phát sinh khoảng 5–10 yêu cầu/tuần. | "Liệu có cần thiết sử dụng AI cho việc này khi ở môi trường công sở không khi mà tốn thêm chi phí đầu tư mà không thường xuyên sử dụng?" (Dũng hỏi) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| **A — Điều phối và định tuyến yêu cầu nội bộ** | Dũng #3 (Email hỗ trợ nội bộ), Huy Anh #6 (Chuyển yêu cầu giữa các bộ phận) | Tiếp nhận yêu cầu tự do từ nhiều nguồn, cần đọc hiểu ngữ cảnh, kiểm tra thông tin, gắn nhãn chuyển tiếp đúng đơn vị và theo dõi tiến độ xử lý. Đây là điểm hội tụ lớn nhất của cả hai thành viên. |
| **B — Bóc tách & Chuẩn hóa đầu ra hành chính** | Dũng #1 (Biên bản & Action items), Huy Anh #4 (Soạn công văn theo mẫu) | Chuyển đổi dữ liệu thô (ghi chép cuộc họp, hồ sơ sự vụ) thành tài liệu có cấu trúc chuẩn theo quy định để ban hành. |
| **C — Đọc hiểu, đối chiếu và thẩm định hồ sơ** | Dũng #2 (Bảng kê hóa đơn hoàn ứng), Huy Anh #5 (Rà soát rủi ro dự án đầu tư) | Đọc khối lượng lớn chứng từ/tài liệu phức tạp để trích xuất dữ liệu số hoặc lọc điểm rủi ro cần kiểm tra chuyên sâu. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome đo lường được**. Các nhánh chỉ là **Opportunity (Nhu cầu / Nỗi đau)**, không chứa tên công cụ hay giải pháp kỹ thuật.

```text
OUTCOME: Giảm 60% thời gian từ lúc phát sinh yêu cầu nội bộ đến khi được xác nhận xử lý đúng nơi, hạn chế tối đa việc chuyển nhầm và tồn đọng việc khẩn
├── Opportunity 1 (Pain): Người tiếp nhận phải đọc nội dung tự do và mất nhiều thời gian tự phán đoán phòng ban phụ trách
├── Opportunity 2 (Pain): Nội dung yêu cầu ban đầu gửi đến bị thiếu thông tin cần thiết, buộc phải trao đổi qua lại nhiều lần
├── Opportunity 3 (Pain): Người gửi không nắm được trạng thái xử lý nên liên tục nhắn tin/gọi điện hỏi dồn
└── Opportunity 4 (Pain): Các yêu cầu có tính chất giao thoa nhiều bộ phận hoặc khẩn cấp bị thiếu cơ chế gắn cờ ưu tiên rõ ràng
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- **"Chatbot AI tự động phân loại và trả lời email"**: Gạch bỏ vì chatbot là một công cụ công nghệ (solution), không phải nỗi đau của người dùng. Opportunity thật là: 
- **"Web App / Portal nội bộ để nhân viên gửi ticket theo form bắt buộc"**: Gạch bỏ vì web app là phương án can thiệp quy trình (solution). Opportunity thật là: *"Nội 
- **"Cài Rule tự động chuyển tiếp email bằng script/filter"**: Gạch bỏ vì script/filter là phương án kỹ thuật (solution). Opportunity thật là: 

### 2.4. Chấm điểm shortlist (1–5)

Chấm theo 7 tiêu chí chuẩn từ hướng dẫn của môn học:
1. Actor rõ ràng, tiếp cận được để phỏng vấn.
2. Quy trình hiện tại vẽ được chi tiết từng bước.
3. Bottleneck cụ thể, có số phút đo được.
4. Tác động lớn nếu giải quyết xong.
5. Vừa sức giải quyết trong khuôn khổ lab.
6. Có phương án cải tiến không cần dùng AI (so sánh được No AI / Rule / Workflow / Agent).
7. Cả nhóm cùng hào hứng giải quyết.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Điều phối yêu cầu nội bộ (Dũng #3 + Huy Anh #6)** | 5 | 4 | 4 | 4 | 5 | 5 | 5 | **32** |
| **Action items sau họp nội bộ (Dũng #1)** | 5 | 5 | 4 | 4 | 4 | 4 | 4 | **30** |
| **Soạn công văn theo mẫu (Huy Anh #4)** | 4 | 4 | 3 | 3 | 5 | 5 | 3 | **27** |

**Candidate được chọn:** Điều phối yêu cầu nội bộ: tiếp nhận yêu cầu, kiểm tra tính đầy đủ thông tin, xác định đầu mối phòng ban phụ trách và theo dõi trạng thái xử lý.

**Vì sao chọn:**
- Cả hai thành viên độc lập đều nêu ra cùng một nỗi đau cốt lõi dù ở hai quy mô khác nhau: yêu cầu công việc bị gửi vòng vèo, thiếu thông tin, trôi việc và khó kiểm soát tiến độ.
- Quy trình có điểm đầu và điểm cuối rõ ràng, xác định được actor cụ thể và đo lường được các chỉ số thành công (thời gian chuyển đúng nơi, tỷ lệ yêu cầu phải hỏi lại, thời gian phản hồi SLA).
- Đề tài mở ra không gian so sánh rất tốt giữa 4 mức giải pháp: No AI (chuẩn hóa checklist/form), Rule (lọc từ khóa, gán tag cố định), Workflow (AI phân loại ngữ nghĩa có con người duyệt), và Agent (hệ thống tự động điều phối đa kênh).

**Vì sao loại các candidate còn lại:**
- **Action items sau họp nội bộ (Dũng #1):** Quy trình và baseline rất rõ, nhưng mới chỉ có một thành viên trải nghiệm sâu, chưa tạo được sự giao thoa vấn đề giữa hai thành viên như bài điều phối yêu cầu.
- **Soạn công văn theo mẫu (Huy Anh #4):** Có thể giải quyết phần lớn bằng thư viện biểu mẫu chuẩn hóa và tính năng trộn văn bản (mail merge), chưa làm rõ được điểm nghẽn thực sự có cần đến AI hay không.
- **Rà soát đề xuất dự án đầu tư (Huy Anh #5) & Hóa đơn hoàn ứng (Dũng #2):** Dữ liệu đầu vào quá phức tạp hoặc đặc thù, khó có thể chuẩn bị mẫu thử và kiểm chứng người dùng thực tế một cách toàn diện trong thời gian ngắn của buổi lab.

**Xử lý bất đồng (nếu có):**
Dũng ghi nhận số liệu ở hòm thư chung (40–50 email/ngày, mất 60 phút), trong khi Huy Anh ước lượng theo luồng văn bản/phiếu yêu cầu giữa các bộ phận (5–10 yêu cầu/tuần, mất 10–20 phút/yêu cầu). Hai số liệu này phản ánh hai kênh tiếp nhận khác nhau. Nhóm thống nhất trong CP4 sẽ phỏng vấn người thật để chốt xem nên tập trung vào kênh email văn bản tự do hay phiếu yêu cầu trực tuyến, từ đó chuẩn hóa lại một baseline đo lường duy nhất.
---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người gửi yêu cầu nội bộ rất ngại điền form cứng và vẫn có thói quen gõ email/tin nhắn văn bản tự do | Value | 5 | 2 | Có |
| 2 | Người trực điều phối tốn nhiều thời gian nhất ở khâu đọc hiểu nội dung và tự phán đoán phòng ban tiếp nhận | Value | 5 | 2 | Có |
| 3 | Người tiếp nhận sẵn sàng dùng gợi ý phân loại phòng ban nếu độ chính xác trên 85% | Usability | 4 | 2 | Có |
| 4 | Nội dung yêu cầu nội bộ có thể phân loại chính xác bằng mô hình ngôn ngữ dựa trên ngữ cảnh công việc | Feasibility | 4 | 3 | Không (thử sau) |
| 5 | Các bộ phận chấp nhận cho hệ thống tự động đọc tiêu đề và nội dung yêu cầu nội bộ để điều phối | Viability | 5 | 1 | Không (hỏi sau lab) |

Giả định nhóm kiểm chứng trong buổi này:
- **Giả định #1 & #2:** Xác thực xem người dùng có thực sự né tránh form để gửi text tự do không, và bottleneck có đúng là nằm ở khâu đọc hiểu + xác định đầu mối phòng ban hay không.

---

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn sâu cá nhân theo phương pháp The Mom Test (hỏi về hành vi, sự việc cụ thể và cách xử lý thực tế trong 2–4 tuần gần nhất, không hỏi mớm giải pháp).

#### Interview Snapshot 1

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Hiệu trưởng một trường liên cấp (Tiểu học & THCS) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Phụ huynh lẫn giáo viên hai khối cứ nhắn tin riêng hoặc gửi đơn viết tay chung chung 'nhờ cô xem giúp', tôi đọc xong nhiều khi phải gọi ngược lại hỏi xem đây là việc của khối Tiểu học hay THCS, thuộc mảng học vụ hay bán trú để chuyển đúng Phó Hiệu trưởng."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Đầu tuần trước sau đợt kiểm tra giữa kỳ, có 4 phản ánh của phụ huynh về xếp lịch thi bù gửi lẫn vào hòm thư điện tử của trường và tin nhắn Zalo cá nhân. Do kiêm nhiệm nhiều việc và không có đầu mối phân luồng cụ thể, 1 phản ánh bị sót mất 3 ngày mới chuyển đến Tổ phó phụ trách khảo thí, khiến phụ huynh bức xúc gọi thẳng lên đường dây nóng. |
| Hiện đang xử lý bằng cách nào (workaround)? | Tự đọc lướt vào đầu giờ sáng và cuối giờ chiều, chụp màn hình hoặc forward tin nhắn vào nhóm Zalo "Ban Giám hiệu", gõ thêm một dòng giao việc kèm tag tên người phụ trách. |
| Mất bao lâu, bao lần? | 30–45 phút mỗi ngày làm việc; phát sinh liên tục 15–20 yêu cầu/tuần từ phụ huynh và giáo viên hai cấp học. |
| Insight / opportunity rút ra | Nhu cầu tiếp nhận qua văn bản tự do là có thật vì phụ huynh và giáo viên rất ngại dùng các biểu mẫu phức tạp; điểm nghẽn lớn nhất là đọc hiểu nội dung chưa rõ ràng để xác định đúng người xử lý (học vụ, hành chính, bán trú, kỷ luật). |

#### Interview Snapshot 2

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Cán bộ phụ trách quản lý kinh tế cấp xã |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Người dân gửi đơn hoặc gọi điện lên hỏi về thủ tục đăng ký kinh doanh hộ cá thể, hỗ trợ mặt bằng buôn bán hay cấp phép dịch vụ rất hay nói chung chung; cán bộ phải ngồi gặng hỏi từng ý rồi mới biết việc này thuộc mảng kinh tế hay phải phối hợp với bên địa chính - xây dựng."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Thứ Năm tuần trước, có 3 hộ dân gửi phản ánh về việc ô nhiễm tiếng ồn và lấn chiếm lòng đường kinh doanh. Đơn gửi chung về Ủy ban xã nhưng ghi thông tin lộn xộn, văn thư chuyển sang bộ phận địa chính - môi trường xử lý mất 2 ngày, sau đó bên địa chính chuyển trả lại vì liên quan đến giấy phép kinh doanh buôn bán của phòng kinh tế, làm kéo dài thời gian phản hồi cho dân. |
| Hiện đang xử lý bằng cách nào (workaround)? | Dùng sổ theo dõi tiếp nhận viết tay kết hợp nhóm chat nội bộ; cán bộ đọc đơn, gạch chân các ý chính bằng bút dạ quang rồi phân loại theo từng nhóm việc, việc nào chồng chéo thì mang trực tiếp sang bàn phòng ban khác để trao đổi miệng. |
| Mất bao lâu, bao lần? | Mất khoảng 15–20 phút cho mỗi đơn thư phức tạp; trung bình xử lý 8–12 vụ việc điều phối liên ngành mỗi tuần. |
| Insight / opportunity rút ra | Các yêu cầu mang tính giao thoa liên ngành rất dễ bị chuyển lòng vòng giữa các bộ phận; việc thiếu thông tin ban đầu khiến cán bộ phải xác minh lại nhiều lần trước khi thụ lý. |

#### Interview Snapshot 3 (Tín hiệu phản bác / hoài nghi)

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Phó trưởng Công an xã |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Bên công an có quy trình tiếp nhận tin báo, sổ nhật ký trực ban 24/7 và hệ thống phần mềm chuyên ngành bảo mật riêng của Bộ. Tình huống an ninh trật tự phải xử lý theo đúng điều lệnh và chỉ đạo trực tiếp của chỉ huy trực ban, tuyệt đối không bao giờ đưa dữ liệu lên các nền tảng AI bên ngoài hay để phần mềm tự động điều phối."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Đêm trực cuối tuần có tin báo của người dân về vụ gây mất trật tự công cộng; cán bộ trực ban tiếp nhận điện thoại, ghi sổ trực ban, báo cáo trực tiếp Phó trưởng công an trực chỉ huy và cử tổ tuần tra xuống hiện trường ngay trong 10 phút. |
| Hiện đang xử lý bằng cách nào (workaround)? | Tiếp nhận qua đường dây nóng, cổng Dịch vụ công Bộ Công an hoặc trực ban tiếp dân; phân công trực tiếp bằng mệnh lệnh chỉ huy và ghi sổ nhật ký nghiệp vụ. |
| Mất bao lâu, bao lần? | 1–2 phút cho khâu tiếp nhận và phát lệnh; không có độ trễ trung gian. |
| Insight / opportunity rút ra | **Tín hiệu phản bác mạnh mẽ:** Lực lượng công an xã và các đơn vị lực lượng vũ trang có quy trình trực ban khép kín, phân cấp mệnh lệnh rõ ràng và yêu cầu tối thượng về bảo mật thông tin nhà nước. Không được áp dụng giải pháp điều phối AI vào lĩnh vực an ninh trật tự hoặc các nghiệp vụ thuộc ngành dọc có quy định bảo mật riêng. |

#### Tổng hợp kiểm chứng

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn sâu (The Mom Test) | 3 người (1 Hiệu trưởng trường liên cấp, 1 Cán bộ kinh tế xã, 1 Phó trưởng Công an xã) | - 2/2 đơn vị hành chính - giáo dục dân sự xác nhận: Người gửi có thói quen viết nội dung tự do, mô tả thiếu thông tin khiến người tiếp nhận tốn nhiều thời gian đọc hiểu và phán đoán đầu mối xử lý.<br>- Việc điều phối thủ công qua nhóm chat/sổ tay dễ gây sót việc khẩn (sót đơn 3 ngày) hoặc chuyển nhầm đơn vị liên ngành (mất 2 ngày chuyển lòng vòng). | - 1/3 người (Phó trưởng Công an xã) bác bỏ tính khả thi: Lĩnh vực công an/an ninh có quy trình trực ban theo điều lệnh và nguyên tắc bảo mật thông tin nội bộ nghiêm ngặt, tuyệt đối không đưa dữ liệu nghiệp vụ vào công cụ AI bên thứ ba. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

1. **Khoanh vùng ranh giới tổ chức (Boundary):** Loại bỏ hoàn toàn khối lực lượng vũ trang, an ninh trật tự, công an xã ra khỏi đối tượng áp dụng; giải pháp chỉ tập trung vào **các đơn vị hành chính công vụ dân sự và cơ sở giáo dục** nơi có luồng yêu cầu/phản ánh phát sinh hàng ngày từ người dân, giáo viên, phụ huynh.
2. **Bổ sung tính năng phát hiện thiếu thông tin (Pre-screening):** Qua thực tế tại trường liên cấp và phòng kinh tế xã, vấn đề không chỉ là "chuyển đi đâu" mà là "nội dung gửi đến quá sơ sài". Giải pháp cần thêm bước phân tích xem yêu cầu đã đủ các dữ kiện tối thiểu (đối tượng, cấp học, địa chỉ, sự việc) chưa; nếu thiếu, hệ thống gợi ý câu hỏi để người tiếp nhận bấm gửi yêu cầu người dân/giáo viên bổ sung ngay trước khi chuyển giao.
3. **Giữ nguyên mức hỗ trợ gợi ý (Augment - Human-in-the-loop):** Với các vụ việc giao thoa giữa nhiều mảng (như kinh tế kết hợp địa chính, hoặc học vụ kết hợp khảo thí), AI chỉ đề xuất phòng ban phù hợp kèm mức độ tin cậy và tóm tắt lý do; cán bộ/hiệu trưởng vẫn là người bấm duyệt chuyển tiếp cuối cùng.

---

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Jira Service Management (Virtual Service Agent)** | https://www.atlassian.com/software/jira/service-management | Bước đọc hiểu, phân loại Intent và tự động gán ticket đến đúng nhóm giải quyết (Queue/Team). | Tích hợp sâu vào hệ sinh thái quản lý công việc; tự động học từ lịch sử ticket cũ. | Chi phí bản quyền cao; giao diện phức tạp; đòi hỏi tổ chức phải chuyển hẳn sang dùng cổng Service Portal. | Không ép người dùng dùng portal phức tạp; giải pháp nên xử lý ngay trên luồng email/text quen thuộc. |
| **Zendesk AI (Intelligent Triage & Routing)** | https://www.zendesk.com/service/ai/ | Tự động nhận diện ý định (Intent), ngôn ngữ, cảm xúc và dự đoán phòng ban phụ trách từ email gửi đến. | Xử lý văn bản tự do cực tốt; phân luồng nhanh theo độ ưu tiên và nhãn kỹ thuật. | Đóng gói trong gói Enterprise giá đắt đỏ; là 'hộp đen' khó tùy biến logic ranh giới riêng của từng đơn vị. | Cần cơ chế cho phép con người kiểm tra (Human-in-the-loop) và điều chỉnh linh hoạt danh mục phòng ban nội bộ. |
| **Template n8n: Email AI Classifier & Routing** | https://n8n.io/workflows/ | Đọc email mới từ hòm thư chung -> gọi LLM phân loại phòng ban -> chuyển tiếp email và gắn nhãn. | Mã nguồn mở, linh hoạt kết nối qua webhook, chi phí thấp, đúng kiến trúc Workflow định sẵn. | Bản mẫu mặc định thường tự động forward email ngay mà không có bước con người duyệt (dễ chuyển nhầm nếu AI hallucinate). | Mượn kiến trúc pipeline của n8n, nhưng **bắt buộc thêm bước con người bấm xác nhận** trước khi email được chuyển đi. |
---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ As-is (ASCII Flowchart):

```text
[1. Mở hòm thư / nhận đơn phản ánh tự do từ nhiều kênh] (10 phút)
       │
       ▼
[2. Đọc chi tiết từng văn bản, tự suy đoán nội dung & đơn vị phụ trách] (35 phút) ⚠ BOTTLENECK
       │
       ▼
[3. Gọi điện / nhắn tin hỏi lại do nội dung thiếu thông tin định danh] (20 phút) ⚠ BOTTLENECK
       │
       ▼
[4. Soạn email chuyển tiếp hoặc mang giấy tờ sang phòng ban liên quan] (15 phút)
       │
       ▼
[5. Ghi sổ nhật ký theo dõi hoặc đánh dấu nhãn thủ công] (5 phút)

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Cán bộ trực tiếp nhận | Email, đơn thư giấy, tin nhắn từ người dân / phụ huynh / giáo viên | Danh sách 30–40 yêu cầu mới cần xử lý | 10 phút (đầu giờ sáng mỗi ngày làm việc) | Tiếp nhận từ nhiều nguồn rải rác |
| 2 | Cán bộ trực tiếp nhận | Nội dung văn bản tự do chưa chuẩn hóa | Phán đoán sơ bộ về thẩm quyền phòng ban xử lý | 35 phút (khoảng 1 phút/yêu cầu) |  BOTTLENECK 1: Mất nhiều thời gian đọc hiểu văn bản lộn xộn |
| 3 | Cán bộ trực tiếp nhận | Yêu cầu thiếu thông tin (thiếu mã định danh, thiếu địa chỉ, sự việc chung chung) | Thông tin bổ sung sau khi xác minh lại với người gửi | 20 phút (phát sinh ở 25–30% số lượng yêu cầu) |  BOTTLENECK 2: Chậm trễ do phải trao đổi qua lại nhiều lần |
| 4 | Cán bộ trực tiếp nhận | Yêu cầu đã xác định được nơi nhận | Email forward hoặc phiếu chuyển giao sang phòng ban phụ trách | 15 phút (trung bình 20–30 giây/thao tác chuyển) | Dễ gõ nhầm địa chỉ hoặc quên đính kèm hồ sơ gốc |
| 5 | Cán bộ trực tiếp nhận | Danh sách các yêu cầu đã chuyển đi | Sổ tay theo dõi hoặc nhãn Gmail/Outlook được cập nhật | 5 phút | Không đồng bộ trạng thái khi phòng ban xử lý xong |

**Bottleneck chính:** 
- **Bước 2 (35 phút):** Đọc hiểu và phân tích các văn bản phi cấu trúc, lộn xộn để xác định đúng thẩm quyền phòng ban.
- **Bước 3 (20 phút):** Tốn thời gian liên hệ ngược lại để hỏi bổ sung các thông tin tối thiểu do người gửi không điền đủ dữ kiện ngay từ đầu.
- Tổng thời gian nghẽn: **55 phút/ngày** (chiếm gần 65% tổng thời gian quy trình).

---

### 4.2. Quy trình tương lai

Sơ đồ To-be (Workflow phân định rõ Rule, AI, Con người):

```text
[1. Gom yêu cầu tự do từ các kênh vào hàng đợi tập trung] (1 phút)           ← RULE (Script / Webhook)
       │
       ▼
[2. Phân tích nội dung, kiểm tra trường thiếu & gợi ý phòng ban + độ tin cậy] (1 phút) ← AI (LLM trích xuất ngữ nghĩa)
       │
       ▼
[3. Cán bộ rà soát thẻ đề xuất: bấm Duyệt chuyển hoặc bấm Yêu cầu bổ sung] (12 phút) ← CON NGƯỜI (HITL - Boundary)
       │
       ▼
[4. Tự động chuyển tiếp đến phòng ban được duyệt & cập nhật bảng trạng thái] (1 phút)  ← RULE (Automation Router)

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| **Số bước quy trình** | 5 bước | 4 bước | Tự động hóa khâu gom yêu cầu và khâu chuyển tiếp sau khi duyệt |
| **Tổng thời gian xử lý** | 85 phút/ngày | 15 phút/ngày | Tiết kiệm 70 phút mỗi ngày cho cán bộ trực tiếp nhận |
| **Số bước thủ công** | 5/5 bước | 1/4 bước | Con người chỉ tập trung vào duy nhất Bước 3 (kiểm tra và phê duyệt) |
| **Bottleneck chính** | Đọc hiểu và phán đoán nơi nhận (35') | Cán bộ duyệt thẻ đề xuất (12') | Điểm nghẽn mới là chốt chặn kiểm soát chất lượng cần thiết (HITL) |
| **Rủi ro mới phát sinh** | Chuyển nhầm do cảm tính, sót việc do quên ghi sổ | Ảo giác AI (phân loại sai ranh giới giao thoa); cán bộ ỷ lại bấm duyệt vội mà không đọc | Khắc phục bằng hiển thị mức độ tin cậy (Confidence) và highlight từ khóa chứng cứ |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Cán bộ tiếp nhận và điều phối công việc hành chính tại các cơ quan hành chính công vụ dân sự và đơn vị giáo dục (chịu trận trực tiếp xử lý hòm thư chung). |
| **Quy trình** | Hằng ngày tiếp nhận 30–40 yêu cầu tự do $\rightarrow$ đọc hiểu và suy đoán thẩm quyền $\rightarrow$ liên hệ hỏi lại nếu thiếu dữ kiện $\rightarrow$ chuyển tiếp thủ công đến phòng ban chuyên trách $\rightarrow$ ghi sổ theo dõi. |
| **Bottleneck** | Mất 35 phút đọc hiểu để phán đoán phòng ban tiếp nhận và 20 phút liên hệ hỏi bổ sung thông tin thiếu; tỷ lệ phân loại sai hoặc chuyển vòng vèo giữa các phòng ban chiếm khoảng 12%. |
| **Impact** | Tốn 85 phút/ngày cho công tác trung gian; trung bình mỗi tuần có 3–4 việc khẩn bị xử lý trễ quá 4 tiếng do chuyển lòng vòng; gây ách tắc tiến độ giải quyết công việc chung của đơn vị. |
| **Success Metric** (baseline $\rightarrow$ target, cách đo) | - **Thời gian điều phối trung gian:** Từ 85 phút/ngày giảm xuống dưới 20 phút/ngày (đo bằng log thời gian cán bộ thao tác trên hệ thống hàng ngày).<br>- **Tỷ lệ chuyển đúng phòng ban ngay lần đầu:** Từ 88% tăng lên trên 98% (công thức: $1 - \frac{\text{Số yêu cầu bị phòng ban trả lại}}{\text{Tổng yêu cầu tiếp nhận}} \times 100\%$, đo liên tục trong 4 tuần pilot).<br>- **Tỷ lệ yêu cầu sót thông tin bị chuyển giao:** Giảm từ 25% xuống dưới 3% nhờ khâu phát hiện thiếu dữ liệu ngay tại cổng vào. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | - AI **tuyệt đối không được tự động phát lệnh chuyển tiếp** hoặc gửi email ra bên ngoài mà không có con người bấm duyệt.<br>- AI **không được tự ý bác bỏ/từ chối** yêu cầu của người gửi.<br>- AI **không áp dụng cho các dữ liệu thuộc khối an ninh, quốc phòng, điều tra** (tuân thủ kết quả kiểm chứng CP4).<br>- **Bắt buộc Human-in-the-loop (HITL):** Cán bộ trực tiếp nhận phải rà soát và bấm nút xác nhận đối với mọi đề xuất phân luồng trước khi thông tin được gửi đi. |

**Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:**

- **Phản biện nhận được:** *"Nếu người gửi cố tình viết một bức thư rất dài nhưng thực chất khiếu nại 3 vấn đề thuộc 3 phòng ban khác nhau thì hệ thống gợi ý 1 phòng ban duy nhất sẽ làm sót việc của các phòng ban còn lại; đồng thời metric đo thời gian nếu chỉ tính thời gian chạy của máy thì không phản ánh đúng thời gian con người phải ngồi đọc lại."*
- **Nhóm có đồng ý không:** **Đồng ý hoàn toàn.** Nhóm bổ sung giải pháp cho phép AI trích xuất đa nhãn (multi-label) để chia tách thành các sub-task riêng biệt nếu phát hiện nhiều nội dung độc lập; đồng thời metric thời gian được xác định rõ là bao gồm cả thời gian con người ngồi rà soát và bấm nút duyệt (12 phút) chứ không chỉ tính thời gian xử lý của mô hình.

---

## 6. Mức độ can thiệp của AI (CP6)

### 6.1. So sánh 4 mức độ can thiệp

| Mức độ | Cơ chế vận hành | Ưu điểm | Rủi ro / Nhược điểm | Đánh giá lựa chọn |
|---|---|---|---|---|
| **Mức 0: No AI / Rule-based** | Bắt buộc người gửi điền biểu mẫu (form) cứng với các trường cố định; dùng bộ lọc từ khóa tĩnh (Regex/If-Else) để phân loại. | Chi phí phát triển = 0; không có ảo giác (hallucination); tốc độ xử lý tức thì. | Người dân/giáo viên ngại điền form dài, tiếp tục lách luật gửi văn bản tự do qua Zalo/Email cá nhân; không xử lý được ngôn ngữ tự nhiên. |  **Loại**: Thất bại ngay từ khâu tiếp nhận (không giải quyết được hành vi thực tế của người dùng). |
| **Mức 1: AI Feature (Hỗ trợ cục bộ)** | Cán bộ văn thư mở email/đơn thư, bấm nút "Hỏi AI" để AI tóm tắt nội dung ngay trong khung xem trước; cán bộ vẫn tự chọn phòng ban thủ công. | Dễ tích hợp (dưới dạng extension/plugin); cán bộ nắm quyền kiểm soát hoàn toàn từng bước. | Không giải quyết được khâu gom dữ liệu đa kênh; cán bộ vẫn phải thao tác thủ công chuyển tiếp và ghi sổ theo dõi từng việc. |  **Loại**: Chỉ giảm nhẹ thao tác đọc, không tối ưu hóa được toàn bộ luồng điều phối (thời gian giảm không đáng kể). |
| **Mức 2: AI Workflow (Bán tự động + HITL)** | Rule tự động gom yêu cầu đa kênh; LLM phân tích ngữ nghĩa, kiểm tra trường thiếu và đề xuất phòng ban kèm độ tin cậy; cán bộ chỉ bấm Duyệt/Hỏi lại; Rule tự động định tuyến. | Giải quyết trọn vẹn điểm nghẽn đọc hiểu và chuyển tiếp; kiểm soát 100% rủi ro nhờ chốt chặn con người (HITL); người gửi giữ nguyên thói quen nhắn tin tự do. | Phụ thuộc vào chất lượng mô hình prompt; cán bộ có nguy cơ ỷ lại nếu không có cơ chế highlight bằng chứng trực quan. |  **CHỌN**: Cân bằng tối ưu giữa hiệu quả tự động hóa và an toàn nghiệp vụ công vụ. |
| **Mức 3: Autonomous Agent (Tự động hoàn toàn)** | AI tự nhận tin nhắn, tự động quyết định chuyển thẳng vào hòm thư phòng ban hoặc tự động soạn thư trả lời/từ chối người dân mà không cần người duyệt. | Tối đa hóa tốc độ xử lý (thời gian phản hồi < 5 giây); không tốn nhân lực trực tiếp nhận. | Nguy cơ ảo giác nghiêm trọng; vi phạm nguyên tắc phát ngôn hành chính nhà nước; gây hậu quả pháp lý nếu phân loại nhầm việc khẩn/khiếu nại. |  **Loại (Vi phạm Boundary)**: Tuyệt đối không giao quyền tự quyết định gửi/từ chối văn bản cho AI. |

---

### 6.2. Lý do chốt chọn Mức 2 (AI Workflow - Human-in-the-Loop)

1. **Phù hợp với đặc thù hành chính & giáo dục:** Trong khu vực công và trường học, trách nhiệm giải trình (accountability) là yếu tố sống còn. AI đóng vai trò "trợ lý bóc tách và phân loại", còn con người giữ vai trò "người chịu trách nhiệm phê duyệt".
2. **Giải quyết đúng điểm nghẽn cốt lõi (55 phút đọc hiểu & hỏi lại):** AI giải phóng cán bộ khỏi công việc thủ công bằng cách tóm tắt sự việc trong 2 dòng, tự động phát hiện trường thông tin thiếu và đề xuất sẵn phòng ban kèm mức độ tin cậy (Confidence Score).
3. **Tính khả thi kỹ thuật cao:** Không đòi hỏi huấn luyện lại mô hình nền (foundation model) phức tạp; chỉ cần kết hợp Webhook gom tin, mô hình LLM trích xuất cấu trúc (Structured Output/JSON) và giao diện duyệt thẻ 1-chạm.

---

## 7. Problem Statement v1 (CP6)

| Trường | Nội dung hoàn thiện |
|---|---|
| **Actor** | Cán bộ văn thư / tiếp nhận và điều phối công việc hành chính tại các cơ quan hành chính công vụ dân sự cấp xã/phường và đơn vị giáo dục (trường liên cấp). |
| **Quy trình** | Tiếp nhận 30–40 yêu cầu/ngày từ Zalo OA, Mail công vụ -> Hệ thống gom về hàng đợi tập trung -> AI phân tích ngữ nghĩa, trích xuất tóm tắt, kiểm tra trường thiếu và đề xuất phòng ban -> Cán bộ duyệt 1-chạm (Duyệt chuyển hoặc Yêu cầu bổ sung) -> Hệ thống tự động chuyển tiếp và cập nhật bảng trạng thái. |
| **Bottleneck** | Khâu đọc hiểu văn bản tự do lộn xộn (35 phút) và liên hệ hỏi lại dữ kiện thiếu (20 phút). Điểm nghẽn mới sau can thiệp: Thời gian cán bộ rà soát và bấm duyệt thẻ đề xuất (12 phút/ngày). |
| **Impact** | Cắt giảm 70 phút lãng phí mỗi ngày cho cán bộ trực tiếp nhận (từ 85 phút xuống dưới 15–20 phút); xóa bỏ hoàn toàn tình trạng trôi sót việc khẩn (giảm từ 3–4 việc trễ/tuần xuống 0). |
| **Success Metric** | - **Thời gian điều phối trung gian:** Giảm từ 85 phút/ngày $\rightarrow$ dưới 20 phút/ngày (đo bằng log hệ thống).<br>- **Độ chính xác chuyển đúng nơi ngay lần đầu:** Tăng từ 88% $\rightarrow$ trên 98% (công thức: `1 - [Số yêu cầu bị trả lại / Tổng yêu cầu tiếp nhận] * 100`).<br>- **Tỷ lệ văn bản thiếu dữ kiện lọt vào phòng ban:** Giảm từ 25% $\rightarrow$ dưới 3%.<br>- **Tỷ lệ cán bộ chấp nhận gợi ý của AI (Acceptance Rate):** Đạt trên 85% trong quá trình vận hành pilot. |
| **Boundary & Fallback** | - **Boundary:** AI không tự gửi văn bản ra ngoài; không tự ý từ chối yêu cầu; không xử lý dữ liệu mật/an ninh điều tra; bắt buộc có tài khoản cán bộ bấm duyệt.<br>- **Fallback:** Khi mất kết nối API hoặc điểm tin cậy $< 65\%$, hệ thống tự động giữ nguyên trạng thái chờ duyệt thủ công để cán bộ phân loại bằng tay như quy trình cũ. |

---

## 8. Quyết định Go / No-Go & Kế hoạch thử nghiệm (CP6)

### 8.1. Ma trận đánh giá tính khả thi

| Trụ cột đánh giá | Trạng thái | Căn cứ đánh giá |
|---|:---:|---|
| **Desirability (Nhu cầu thực tế)** | **PASS** | Phỏng vấn Mom Test xác nhận 2/2 cán bộ dân sự và trường học đều đang chịu áp lực lớn từ hòm thư lộn xộn và rất cần công cụ giảm tải đọc hiểu. |
| **Feasibility (Tính khả thi kỹ thuật)** | **PASS** | Tận dụng LLM hiện có qua API để trích xuất JSON cấu trúc; tích hợp webhook Zalo/Gmail là công nghệ chuẩn hóa, không có rủi ro nghiên cứu thuật toán. |
| **Viability (Hiệu quả chi phí)** | **PASS** | Chi phí token API ước tính cho 30–40 yêu cầu/ngày chỉ khoảng $0.05–$0.10/ngày; tiết kiệm hơn 30 giờ công lao động mỗi tháng cho một cán bộ. |
| **Safety & Compliance (An toàn & Ranh giới)** | **PASS** | Đã loại trừ khối an ninh/công an; quy trình có HITL chốt chặn tuyệt đối, đảm bảo dữ liệu không bị tự động phát tán sai lệch ra bên ngoài. |

**QUYẾT ĐỊNH CHUNG CUỘC: GO (ở mức AI Workflow có HITL)**

---

### 8.2. Kế hoạch thử nghiệm nhỏ nhất (MVP / Pilot Plan)

* **Phạm vi thử nghiệm:** 01 đơn vị (Văn phòng Trường liên cấp hoặc Bộ phận tiếp nhận Một cửa cấp xã).
* **Quy mô mẫu:** Thử nghiệm trên **100 yêu cầu/đơn thư thực tế** trong vòng **02 tuần liên tục**.
* **Các chỉ tiêu theo dõi (Pilot Metrics):**
  1. Độ chính xác gợi ý phòng ban của AI (so sánh giữa gợi ý của AI và quyết định cuối cùng của cán bộ).
  2. Thời gian trung bình cán bộ thao tác trên mỗi thẻ đề xuất.
  3. Số trường hợp AI phát hiện chính xác thông tin bị thiếu.
* **Ngưỡng dừng an toàn (Stopping Threshold):**
  * Nếu sau 100 yêu cầu đầu tiên, **độ chính xác gợi ý của AI đạt dưới 75%** hoặc thời gian cán bộ phải sửa lại đề xuất lâu hơn quy trình đọc thủ công cũ $\rightarrow$ **DỪNG DỰ ÁN NGAY LẬP TỨC**, hủy bỏ can thiệp AI và chuyển về giải pháp tối ưu hóa biểu mẫu cứng (No AI / Rule).
---

## 9. Đóng góp thành viên & Ma trận rủi ro

### 9.1. Bảng phân công và đóng góp thành viên

| Thành viên | Vai trò | Hạng mục phụ trách chính | Tỷ lệ đóng góp |
|---|---|---|:---:|
| **Nguyễn Tấn Dũng** | Lead Product / Problem Framing | - Khởi xướng bài toán điều phối hòm thư chung (Problem Card #3).<br>- Thực hiện phỏng vấn The Mom Test với Phó trưởng Công an xã và Cán bộ kinh tế xã.<br>- Xây dựng luồng As-is và bóc tách các điểm nghẽn (bottlenecks) về thời gian.<br>- Tổng hợp báo cáo nhóm từ CP3 đến CP6. | 50% |
| **Lê Huy Anh** | Tech Lead / Solution Architect | - Đóng góp bài toán đối chiếu luồng văn bản liên phòng ban (Problem Card #4 & #5).<br>- Phỏng vấn The Mom Test với Hiệu trưởng trường liên cấp.<br>- Thiết kế kiến trúc To-be phân tầng (Rule - AI - Con người) và cơ chế Fallback.<br>- Xây dựng Success Metrics, bộ prompt mẫu cho bài thuyết trình và slide pitch. | 50% |

### 9.2. Ma trận rủi ro & Phương án giảm thiểu (Risk Register)

| Rủi ro tiềm ẩn | Mức độ | Hậu quả | Phương án kiểm soát & Giảm thiểu |
|---|:---:|---|---|
| **Ảo giác AI (Hallucination)** phân loại nhầm phòng ban chuyên trách | Trung bình | Yêu cầu bị chuyển sai đơn vị, gây trễ hạn xử lý việc khẩn | Bắt buộc cơ chế **Human-in-the-Loop (HITL)**: Cán bộ trực phải bấm duyệt; hiển thị điểm tin cậy (% Confidence) và highlight từ khóa ngữ cảnh để cán bộ thẩm định nhanh. |
| **Lệch ranh giới bảo mật (Compliance Breach)** | Cao | Đưa nhầm dữ liệu an ninh, quốc phòng hoặc thông tin mật lên hệ thống AI | Thiết lập bộ lọc từ khóa cấm ngay tại tầng Rule tiếp nhận; loại trừ hoàn toàn các đơn vị vũ trang/an ninh ra khỏi đối tượng triển khai (bài học Mom Test CP4). |
| **Cán bộ ỷ lại (Automation Bias)**, duyệt vội không đọc lại | Trung bình | Lọt yêu cầu sai hoặc sót nội dung nghiêm trọng | Thiết kế UX giao diện dạng thẻ tóm tắt 2 dòng kèm cờ cảnh báo (flag) với các đơn có điểm tin cậy $< 80\%$. |
| **Sự cố kỹ thuật (Mất mạng, sập API)** | Thấp | Tắc nghẽn luồng tiếp nhận công việc | Kích hoạt kịch bản **Fallback**: tự động chuyển về hàng đợi thủ công truyền thống để cán bộ phân loại bằng tay như quy trình cũ. |

## 10. Tài liệu tham khảo (References)

Dưới đây là các tài liệu nền tảng, căn cứ pháp lý và tài liệu kỹ thuật chính thức được nhóm trích dẫn và áp dụng xuyên suốt từ CP3 đến CP6:

### Phương pháp luận phát triển sản phẩm & Khám phá khách hàng
1. **The Mom Test (Phương pháp phỏng vấn không mớm giải pháp):**
   * Tác giả: Rob Fitzpatrick.
   * Tham khảo nguyên tắc phỏng vấn hành vi quá khứ và cách nhận diện tín hiệu phản bác: [The Mom Test Official Site](https://momtestbook.com/) | [Simon & Schuster Publisher Page](https://www.simonandschuster.co.uk/books/The-Mom-Test/Rob-Fitzpatrick/9798893312560)
2. **Lean UX (Định dạng Problem Statement, Giả định & Success Metrics):**
   * Tác giả: Jeff Gothelf & Josh Seiden.
   * Cấu trúc Problem Statement 6 trường và đo lường giả thuyết: [Lean UX Official Resource & Canvas](https://leanuxbook.com/)

### Thiết kế tương tác AI & Cơ chế Human-in-the-Loop (HITL)
3. **People + AI Guidebook (Google PAIR):**
   * Nguồn tài liệu thực hành thiết kế sản phẩm AI lấy con người làm trung tâm, hướng dẫn lựa chọn mức độ tự trị (User Autonomy), cơ chế con người kiểm soát (Human-in-the-loop) và hiển thị độ tin cậy (Confidence & Explanations): [Google People + AI Guidebook](https://pair.withgoogle.com/guidebook/)
4. **Guidelines for Human-AI Interaction (Microsoft Research):**
   * Bộ 18 nguyên tắc vàng khi thiết kế ứng dụng AI hỗ trợ quy trình làm việc và xử lý khi AI mắc lỗi: [Microsoft Human-AI Interaction Guidelines](https://www.microsoft.com/en-us/research/project/guidelines-for-human-ai-interaction/)
