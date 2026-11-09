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

Cách đã dùng: Phỏng vấn sâu cá nhân theo phương pháp The Mom Test (hỏi về trải nghiệm và sự việc cụ thể trong 2 tuần gần nhất).

#### Interview Snapshot 1

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Cán bộ trực hòm thư hỗ trợ sinh viên & hành chính khoa |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Nhiều bạn sinh viên gửi mail tiêu đề ghi mỗi chữ 'Em chào thầy cô', nội dung thì vừa xin hoãn thi vừa hỏi đổi lịch học, mình đọc xong chẳng biết nên chuyển cho phòng Khảo thí hay phòng Đào tạo."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Sáng thứ Hai đầu tuần, hòm thư nhận gần 30 email sau 2 ngày cuối tuần. Có 2 email xin cấp bảng điểm gấp bị trôi xuống dưới do cán bộ mải trả lời các câu hỏi thủ tục chung. |
| Hiện đang xử lý bằng cách nào (workaround)? | Đọc lướt từng mail, gắn nhãn màu thủ công (Label) trên Gmail theo kinh nghiệm, cái nào không chắc thì forward vào nhóm Zalo chung của các phòng ban để hỏi 'việc này bên nào xử lý'. |
| Mất bao lâu, bao lần? | Khoảng 45–60 phút mỗi buổi sáng, diễn ra đều đặn từ thứ Hai đến thứ Sáu. |
| Insight / opportunity rút ra | Nỗi đau đọc hiểu và phân định ranh giới phòng ban là có thật; email thường xuyên bị thiếu thông tin định danh (như mã số sinh viên, lớp). |

#### Interview Snapshot 2

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Nhân sự vận hành nội bộ (Operations Executive) công ty công nghệ |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Dù công ty đã có mẫu Google Form riêng nhưng nhân viên vẫn cứ tiện tay ping Slack hoặc gửi email tự do vì bảo 'điền form lâu lắm'."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tuần trước có nhân viên báo hỏng máy in qua email chung của phòng Hành chính - Nhân sự, nhưng người quản lý thiết bị nghỉ phép đột xuất, email không được chuyển tiếp kịp nên việc in hợp đồng bị đình trệ cả buổi sáng. |
| Hiện đang xử lý bằng cách nào (workaround)? | Cài đặt rule lọc từ khóa đơn giản trong Outlook; tuy nhiên chỉ bắt được các từ chuẩn (như 'hóa đơn', 'nghỉ phép'), còn các từ viết tắt hoặc mô tả lỗi máy móc phức tạp thì rule bị trượt, vẫn phải mở ra đọc tay. |
| Mất bao lâu, bao lần? | Mất khoảng 15–20 phút/ngày để rà lại các email lọt qua bộ lọc từ khóa. |
| Insight / opportunity rút ra | Rule lọc từ khóa cố định không đủ linh hoạt; người dùng có tâm lý chuộng viết văn bản tự do hơn là tuân thủ form cứng. |

#### Interview Snapshot 3 (Tín hiệu phản bác / hoài nghi)

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Trưởng nhóm kỹ thuật dự án phần mềm |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Quy mô team dưới 20 người thì cứ tag thẳng tên nhau trên Slack mà làm cho nhanh, tạo quy trình điều phối AI làm gì cho rườm rà và thêm điểm nghẽn."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi một bạn tester báo lỗi qua kênh chung, dev đọc được tự nhận việc luôn, không cần ai đứng ra phân chia hay gán ticket. |
| Hiện đang xử lý bằng cách nào (workaround)? | Trao đổi trực tiếp, không dùng hệ thống hòm thư tập trung hay phiếu yêu cầu. |
| Mất bao lâu, bao lần? | Không mất thời gian điều phối trung gian. |
| Insight / opportunity rút ra | **Tín hiệu phản bác:** Bài toán điều phối yêu cầu chỉ thực sự phát sinh nỗi đau khi quy mô tổ chức đủ lớn (có nhiều phòng ban chuyên biệt và hòm thư chung). Với các nhóm nhỏ hoặc nội bộ dự án ít người, trao đổi trực tiếp là phương án tối ưu nhất. |

#### Tổng hợp kiểm chứng

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn sâu (The Mom Test) | 3 người (1 cán bộ hành chính, 1 nhân sự vận hành, 1 tech lead) | - 2/2 người ở quy mô tổ chức có hòm thư chung xác nhận người gửi thường xuyên bỏ qua form cứng để gửi text tự do.<br>- Cán bộ trực mất 45–60 phút/ngày phân loại thủ công.<br>- Rule lọc từ khóa hay bị sập với văn bản viết tắt/đa nội dung. | - 1/3 người (tech lead nhóm nhỏ) khẳng định nhóm dưới 20 người không có nhu cầu điều phối qua trung gian; dùng AI điều phối là rườm rà không cần thiết. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
1. **Thu hẹp tệp Actor & Bối cảnh:** Không áp dụng giải pháp cho các nhóm làm việc nhỏ (dưới 20 người); tập trung chính xác vào **đầu mối tiếp nhận tại các tổ chức/doanh nghiệp có hòm thư chung tiếp nhận 30–50 yêu cầu tự do mỗi ngày**.
2. **Không tự động hóa 100% việc chuyển tiếp (Automate) mà chuyển sang Hỗ trợ gợi ý (Augment):** Phỏng vấn cho thấy có nhiều yêu cầu phức tạp giao thoa giữa các phòng ban; AI không được tự ý forward email đi mà chỉ đóng vai trò phân tích nội dung, trích xuất thông tin còn thiếu và đề xuất phòng ban phù hợp kèm độ tin cậy để con người duyệt trước khi chuyển.

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
