# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: 6PACKS
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Tạo bộ câu hỏi ôn tập bám sát tài liệu
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 |2A202603605_NguyenHaAnh |Chỉnh sửa CV nhanh chóng để khớp với JD |Ứng viên xin việc |Bước chỉnh sửa thủ công |Tại sao không dùng chatbot có sẵn mà lại phải dùng sản phẩm này, sản phẩm có gì khác biệt ? (2A202603644_NguyenDucTrong) |
| 2 |2A202603605_NguyenHaAnh |Lưu kết quả và tham số tự động khi chạy thực nghiệm ML |Sinh viên nghiên cứu, kỹ sư ML |Khi copy/paste vào sheets |Nếu giải pháp là đơn giản ghi log ra file CSV, có thực sự giải quyết được bài toán so sánh nhiều mô hình cùng lúc, hay chỉ chuyển khó khăn từ việc 'copy-paste' sang việc 'đọc hiểu một file CSV khổng lồ'? (2A202603617_TranXuanTruong) |
| 3 |2A202603617_TranXuanTruong |Viết Release note cho các pull request/commit |developer/techlead phụ trách release hàng tuần |Tốn 15–20 phút diễn giải từ commit/PR kỹ thuật thô sang ngôn ngữ nghiệp vụ dễ hiểu. | GitHub đã có sẵn nút auto-generate release notes từ tên PR, tại sao vẫn cần công cụ riêng?(2A202603605_NguyenHaAnh)|
| 4 |2A202603617_TranXuanTruong |Khi kết thúc họp tuần, tôi muốn ghi lại quyết định và action items kèm người phụ trách để nhóm bám sát tiến độ.|Trưởng nhóm, thành viên nhóm.|Tốn 25–30 phút nghe lại/rà soát ghi chú để trích xuất đúng người - đúng việc và gửi Slack.|Các bot họp như Otter, Fireflies hay Teams Copilot đều có tính năng này, bài toán này có còn chỗ trống không?(2A202603630_NgoVanTuan)|
| 5 |2A202603630_NgoVanTuan |Đối chiếu và kiểm tra các deadline cần thực hiện khi có nhiều công việc chồng chéo |Sinh viên có nhiều môn và tham gia làm bài nhóm. |tìm và đối chiếu deadline trong các nguồn.|"Vấn đề nằm ở việc thiếu công cụ hay tính chủ động khi đã có gg calendar hay notion hỗ trợ ?"(2A202603617_TranXuanTruong)|
| 6 |2A202603630_NgoVanTuan |Tìm và xác định chính xác kiến thức cần ôn tập từ nhiều nguồn tài liệu rải rác.|Sinh viên học nhiều môn hoặc cần ôn tập từ nhiều tài liệu.|tìm nguồn và quyết định ý nào liên quan/trùng lặp.| "Do khả năng sắp xếp tài liệu, lộ trình ôn tập chưa tốt hay thực sự chương trình dạy có thứ tự không hợp lý ?"(2A202603636_HoangDangKien) |
| 7 |2A202603636_HoangDangKien |Tạo câu hỏi trắc nghiệm từ tài liệu ôn tập có sẵn |Sinh viên đại học đang trong giai đoạn ôn thi.|Tìm kiếm và lọc tài liệu.|"Làm sao để đảm bảo chất lượng câu hỏi AI tạo ra ?" (2A202603630_NgoVanTuan)|
| 8 |2A202603636_HoangDangKien |Xây dựng bài test dựa trên slide bài giảng |Sinh viên đến sát ngày thi mới ôn, thiếu thời gian ôn tập.|Đọc thụ động tốn quá nhiều thời gian nhưng độ lưu giữ thông tin cực thấp.|"Làm sao để AI biết nội dung nào cần ôn trong giai đoạn nước rút?" (2A202603641_NguyenSyHuyKien) |
| 9 |2A202603641_NguyenSyHuyKien |Khi viết tổng quan nghiên cứu, tôi muốn biết nhanh bài nào thực sự dùng được để ưu tiên đọc kỹ, thay vì đọc hết.|Sinh viên năm cuối làm đồ án tốt nghiệp |đọc abstract sàng lọc ,đọc sâu|"Vấn đề đọc có thể sử dụng AI, bottleneck thực sự nằm ở việc tìm kiếm tài liệu ?"(2A202603636_HoangDangKien) |
| 10 |2A202603641_NguyenSyHuyKien |Khi có nhiều tài liệu tham khảo, tôi muốn trích dẫn tự động đúng chuẩn để không phải chỉnh từng dòng bằng tay.|Sinh viên làm đồ án, báo cáo.|gõ tay theo chuẩn ,sửa khi bị góp ý |"Nếu nhiều phần trích dẫn có nội dung tương đồng thì sẽ xử lý thế nào ? " (2A202603644_NguyenDucTrong)|
| 11 |2A202603644_NguyenDucTrong|Khi có bảng dữ liệu mới về,muốn có bộ test chất lượng chạy được ngay, để lỗi dữ liệu không lọt vào báo cáo. |Data/analytics engineer |Bước khảo sát dữ liệu và viết test dbt thủ công cho từng bảng, từng cột|"Great Expectations đã sinh test tự động, sao tool hiểu được nghiệp vụ bảng dữ liệu?" (2A202603641_NguyenSyHuyKien)|
| 12 |2A202603644_NguyenDucTrong |Khi chuẩn bị buổi dạy kèm Toán, muốn có bài tập đúng điểm yếu của học sinh và biết lỗi sai nào lặp lại, để buổi học tập trung đúng chỗ. |Gia sư, học sinh(học tại nhà) |Tìm và chọn bài đúng điểm yếu và tổng hợp lỗi sai lặp lại LLM thỉnh thoảng giải/ra đề Toán sai, làm sao bảo đảm đề đúng?|"Thu thập dữ liệu nháp của học sinh bằng cách nào để AI biết đúng lỗi sai?" (2A202603605_NguyenHaAnh) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A.Ôn thi & Đánh giá năng lực |#6, #7, #8, #12 |Chuyển đổi tài liệu thụ động (slide, giáo trình) thành câu hỏi/bài test nhắm đúng trọng tâm và điểm yếu kiến thức.|
| B. Nghiên cứu & Viết học thuật |#9, #10|Giảm tải các thao tác đọc quét tài liệu tham khảo và định dạng trích dẫn thủ công khi làm đồ án tốt nghiệp/báo cáo. |
| C. Tự động hóa Kỹ thuật & MLOps |#2, #3, #11 |Tự động hóa các bước kỹ thuật lặp lại (ghi log thực nghiệm ML, sinh Release Notes, sinh bộ test chất lượng dữ liệu).|
| D.Quản trị công việc & Giao tiếp | #1, #4, #5 |Khớp nối, tóm tắt và đối chiếu thông tin để tránh sót việc (khớp CV với JD, biên bản họp/action items, theo dõi deadline).|

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm 60% thời gian chuẩn bị câu hỏi ôn tập và tăng 40% hiệu quả ghi nhớ kiến thức trọng tâm trước kỳ thi.
├── Opportunity A: Sinh viên tốn nhiều thời gian đọc lại slide/giáo trình một cách thụ động nhưng không đo lường được mình đã thực sự hiểu và nhớ bài hay chưa.
├── Opportunity B: Rất tốn công sức để tự lọc tài liệu và tìm/soạn bộ câu hỏi trắc nghiệm bám sát đúng đề cương của giảng viên trên lớp.
└── Opportunity C: Sinh viên lo sợ các câu hỏi hoặc đáp án tự tạo bị sai lệch/ảo giác kiến thức, dẫn đến việc học vẹt và làm bài thi sai.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| (Chỉnh Sửa CV theo JD)#1|5 |4 |3 |2 |3 |5 |3 |25 |
| (Viết release Note cho theo tuần)#3|5 |3 |2 |2 |3 |4 |3 |22 |
| (Sắp xếp deadline công việc)#5|3 |2 |4 |2 |3 |2 |5 |21 |
| (Tạo ngân hàng câu hỏi ôn tập)#7|5 |4 |5 |5 |3 |4 |5 |31 |
| (Sàng lọc tài liệu nghiên cứu)#9|4 |3 |4 |3 |3 |2 |4 |23 |
| (Tạo bộ test data tự động )#11| 5|5 |3 |2 |3 |2 |4 |29 |

**Candidate được chọn: Candidate #7**

**Vì sao chọn: vì trực tiếp thấu hiểu nỗi đau ôn thi, có sẵn slide bài giảng để làm bài lab ngay mà không vướng quyền truy cập, và dễ đo lường kết quả (giảm thời gian từ 45 phút xuống dưới 3 phút) khi so sánh qua 4 cấp độ AI.**

**Vì sao loại các candidate còn lại:**
 #11 (Sinh bộ test dữ liệu): Điểm số cao thứ nhì và nghiệp vụ rất rõ, nhưng cần dựng mock database phức tạp và khó chuẩn hóa dataset chuẩn để demo kiểm thử trong thời gian lab.

 #3 (Viết Release note): Phụ thuộc nhiều vào ngữ cảnh dự án phần mềm và commit log thực tế, khó xây dựng benchmark đánh giá khách quan.

 #1 (Chỉnh sửa CV): Khó đo lường ranh giới giữa việc dùng một prompt ChatGPT thông thường với một giải pháp chuyên biệt; impact phỏng vấn khó kiểm chứng ngay.

 #9 (Sàng lọc bài báo): Tiêu chí bài báo "dùng được" mang tính chủ quan cao theo từng đề tài, khó đo độ chính xác (ground truth).

 #5 (Đối chiếu deadline): Vướng rào cản kết nối API vào các nhóm chat/LMS đóng, ranh giới vấn đề nằm ở tính chủ động cá nhân hơn là bài toán công nghệ.

**Xử lý bất đồng (nếu có):Nhóm có tranh luận giữa chọn #7 (dễ làm, tệp người dùng rộng) và #11 (tính kỹ thuật và giá trị kỹ sư cao hơn). Nhóm thống nhất chọn #7 để hoàn thành trọn vẹn trong thời hạn lab vì có sẵn tài liệu/slide để đo lường độ chính xác ngay, còn #11 sẽ đưa vào mục hướng phát triển tiếp theo.**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 |Sinh viên ôn thi nước rút thực sự muốn làm trắc nghiệm để nhớ bài nhưng bỏ cuộc vì tự soạn câu hỏi quá tốn thời gian (45–60 phút/chương).|Value |5 |2 |Có |
| 2 |Khi ném cả file slide dài (40–80 trang) vào ChatGPT thông thường, câu hỏi sinh ra bị sót ý giữa bài, lệch trọng tâm đề cương và đáp án nhiễu quá dễ đoán. |Value |5 |2 |Có |
| 3 |Sinh viên bắt buộc phải thấy trích dẫn số trang slide gốc kèm theo mỗi câu hỏi thì mới dám tin tưởng đáp án của AI để học thi (giảm thời gian tự Ctrl+F dò lại). |Usability |5 |1 |Có |
| 4 |Quy trình tách slide theo mục đề cương kết hợp LLM có thể sinh ra các phương án nhiễu (distractors) đủ độ khó tương đương đề thi thật. |Feasibility |4 | 2|Có |
| 5 |Các slide có nhiều sơ đồ, bảng biểu hoặc công thức toán/code vẫn trích xuất được ngữ cảnh sạch mà không làm hỏng nội dung câu hỏi. |Feasibility |4 |3 |Không (kiểm chứng ở bước làm mẫu) |
| 6 |Chi phí xử lý mỗi bộ slide 50 trang qua API (hoặc workflow) đủ thấp để sinh viên sử dụng thường xuyên trong mùa thi mà không gặp rào cản chi phí. |Viability | 3|4 |Không |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này: Tập trung kiểm chứng Giả định #1, #2 và #3 (các giả định thuộc nhóm Value và Usability có mức độ quan trọng cao nhất 5/5 nhưng mức độ bằng chứng ban đầu thấp nhất 1–2/5) để xác định liệu nỗi đau có thật sự nằm ở khâu "tạo câu hỏi" hay nằm ở khâu "kiểm chứng độ chính xác và bám sát đề cương".
### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn nhanh theo nguyên tắc The Mom Test (tập trung vào hành vi ôn thi kỳ gần nhất) kết hợp Log thử nghiệm thực tế (chạy thử 3 file slide bài giảng thật trên ChatGPT thông thường để đo thời gian và tỷ lệ lỗi).

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


(Bảng tổng hợp cũng được đặt trong `report/assets/cp4-interview-snapshot-1.md`)

**Nhóm đã sửa problem thế nào sau kiểm chứng:

1.Dịch chuyển trọng tâm Bottleneck: Ban đầu ở CP3, nhóm nghĩ bottleneck chỉ là "tốn thời gian tìm kiếm và lọc tài liệu để soạn câu hỏi". Sau kiểm chứng, nhóm nhận ra sinh viên đã biết dùng ChatGPT nhưng bị nghẽn nặng ở 2 bước: (1) Câu hỏi sinh ra bị lệch trọng tâm/bỏ sót phần giữa tài liệu dài và (2) Tốn 15–25 phút phải tự Ctrl+F đối chiếu đáp án với slide gốc vì sợ AI ảo giác.

2.Điều chỉnh Success Metric thực tế hơn: Thay vì đặt mục tiêu giảm thời gian từ 45 phút xuống < 3 phút (phi thực tế vì con người vẫn cần đọc duyệt lại), nhóm sửa Target Metric thành giảm tổng thời gian chuẩn bị + kiểm duyệt một bộ 20 câu hỏi chuẩn xác từ 45 phút xuống < 8 phút (nhờ mỗi câu hỏi đều đính kèm số trang slide và trích đoạn gốc để duyệt nhanh).**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
|Quizlet / Anki (Tự tạo hoặc AI Magic Notes) |[https://quizlet.com] |Bước lưu trữ câu hỏi và luyện tập ghi nhớ lặp lại (Spaced Repetition). |Giao diện học và làm test rất mượt; cộng đồng lớn. |Nhập tay tốn 45 phút/chương; tính năng AI miễn phí bị giới hạn và chưa bám sát cấu trúc đề cương tiếng Việt. |Không cần tự xây lại giao diện học phức tạp, hãy tập trung vào chất lượng đầu ra của bộ câu hỏi & đáp án. |
|ChatGPT / Claude (Upload PDF + Prompt trực tiếp) |[https://chatgpt.com] |Bước đọc file PDF và sinh nhanh danh sách câu hỏi trắc nghiệm. |Tốc độ nhanh (< 1 phút), miễn phí, hiểu tiếng Việt tốt. |Bỏ sót kiến thức ở giữa file dài (lost in the middle); đáp án nhiễu ngây ngô; không tự động gắn chính xác số trang slide cho từng câu để kiểm chứng. |Một prompt đơn lẻ là không đủ; cần chia nhỏ quy trình (Workflow): Tách slide theo mục -> Sinh câu hỏi theo trọng tâm -> Gắn trích dẫn trang. |
|Google NotebookLM |[https://notebooklm.google.com] |Bước đọc hiểu tài liệu nguồn và trả lời/tạo Study Guide có trích dẫn (Citation). |Grounding cực kỳ tốt, bám sát tài liệu gốc, có nút bấm nhảy tới đoạn trích dẫn. |Chưa hỗ trợ sinh bộ trắc nghiệm 4 lựa chọn (MCQ) theo đúng ma trận mức độ khó (Nhớ / Hiểu / Vận dụng) kèm kiểm định chất lượng phương án nhiễu. |Học tập cơ chế Grounding (bắt buộc trích dẫn nguồn/số trang slide) làm tiêu chí bắt buộc (Boundary & Eval) cho giải pháp của nhóm. |
|Quizgecko / Wayground AI |[https://quizgecko.com] |Bước chuyển đổi tài liệu PDF/văn bản thành bài quiz tương tác. |Tự động hóa từ đầu đến cuối (upload file -> ra bài test tính điểm). |Bản miễn phí giới hạn số trang rất thấp; không đối chiếu được với đề cương riêng của giảng viên; đôi khi cắt sai ngữ cảnh ở các slide nhiều bullet rời rạc. |Cần bước tiền xử lý: Cho phép sinh viên chọn/nhập trọng tâm ôn tập trước khi sinh câu hỏi để tránh hỏi lan man vào phần giới thiệu. |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ Mermaid - Link ảnh trong `report/assets/process-diagram.png`

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|:---:|:---|:---|:---|:---|:---|
| **1** | Sinh viên ôn thi | Slide bài giảng, file PDF/Word giáo trình | Danh sách các chương, khái niệm chính cần ôn | 30 phút / 1–2 tuần trước kỳ thi | Đọc thụ động, tạo cảm giác hiểu bài giả tạo (illusion of competence). |
| **2** | Sinh viên ôn thi | Nhu cầu tìm đề thực hành | Tin nhắn/bài đăng trên nhóm Zalo, Facebook, diễn đàn | 15 phút / Mỗi môn học | Đăng bài hỏi xin đề thi thử, file quiz cũ của các khóa trước. |
| **3** | Người cho đề, Sinh viên | Bài đăng hỏi xin đề | Tệp đề cũ (hoặc không nhận được phản hồi) | **1 – 2 ngày** (chờ đợi) | **Bị động hoàn toàn:** Nếu có người gửi thì qua B4; nếu không ai gửi thì buộc phải tự mò mẫm đọc lại slide (chuyển thẳng B6). |
| **4** | Sinh viên ôn thi | Các tệp đề cũ thu thập được, giáo trình hiện tại | Bộ câu hỏi lọc sơ bộ còn đúng chương trình học | **45 phút** / Mỗi đợt xin được đề | **Tốn công rà soát:** Phải loại bỏ các câu thuộc chương trình cũ đã giảm tải hoặc đổi giáo trình. |
| **5** | Sinh viên ôn thi | Bộ câu hỏi đã lọc | Bài làm với các đáp án đã chọn | **30 phút** / Mỗi lần làm thử | Làm bài trong tâm lý bất an vì không chắc đề có chuẩn và có đáp án đúng đi kèm hay không. |
| **6** | Sinh viên ôn thi | Bài làm, tài liệu/slide bài giảng gốc | Điểm số và danh sách câu sai đã được kiểm chứng | **30 phút** / Mỗi bài test | **Vòng lặp sửa sai:** Đề cũ thường thiếu đáp án chuẩn hoặc giải sai, sinh viên phải tự lật từng trang slide để dò; nếu sai lệch quá nhiều lại phải quay lại lọc đề khác (về B4). |


**Bottleneck chính:**

1. **Điểm nghẽn chờ đợi & phụ thuộc (Bước 2 & 3):** Rơi vào thế hoàn toàn bị động, mất từ vài giờ đến 1–2 ngày chờ người khác chia sẻ đề. Nếu không có ai gửi, kế hoạch ôn tập bị gãy và rơi vào tình trạng nước đến chân mới nhảy.
2. **Điểm nghẽn sàng lọc & kiểm chứng (Bước 4 & 6):** 
   * Tốn 45 phút lọc đề trôi nổi nhưng vẫn rủi ro học lệch kiến thức do giáo trình thay đổi qua các năm.
   * Mất thêm 30 phút lật từng trang slide để tự giải và đính chính đáp án do đề cũ thiếu lời giải giải thích, tạo thành vòng lặp tốn thời gian giữa B6 và B4.

---
### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

#### Bảng chi tiết quy trình (Rule / AI / Human)

| Bước | Tên bước | Loại hình | Tác tử (Actor) | Input $\rightarrow$ Output | Chi tiết thao tác & Ranh giới |
|:---:|:---|:---:|:---|:---|:---|
| **1** | Tải tài liệu học tập | **Con người** | Sinh viên | Slide PDF, file giáo trình $\rightarrow$ File thô trên hệ thống | Sinh viên kéo thả file bài giảng (PDF/Docx), chọn số lượng câu hỏi và phạm vi ôn tập. |
| **2** | Tiền xử lý & Trích xuất văn bản | **Rule** | Hệ thống (Parser) | File PDF thô $\rightarrow$ Clean text chunks kèm Page ID | Hệ thống bóc tách text, lọc bỏ trang bìa/mục lục, chia chunk (500–1000 tokens) và gắn metadata số trang. |
| **3** | Sinh câu hỏi & Trích dẫn nguồn | **AI** | LLM Engine (RAG) | Clean text chunks $\rightarrow$ Bộ câu hỏi MCQ (JSON) | LLM đọc ngữ cảnh, nhận diện khái niệm chính, sinh 4 lựa chọn (1 đúng, 3 nhiễu) kèm trích dẫn số trang/đoạn văn gốc (grounding). |
| **4** | Kiểm định cấu trúc & Cú pháp | **Rule** | Hệ thống (Validator) | JSON từ AI $\rightarrow$ Bộ đề hợp lệ trên UI | Kiểm tra schema JSON, đủ 4 đáp án A-B-C-D, đáp án đúng duy nhất. Nếu hợp lệ thì render lên giao diện làm bài. |
| **5** | Làm bài & Đối soát kiến thức | **Con người** | Sinh viên | Giao diện câu hỏi $\rightarrow$ Kết quả & Insight ôn tập | Sinh viên làm bài chủ động; hệ thống chấm điểm tức thì, xem lời giải và đoạn trích slide đối soát. |

#### Phân định ranh giới (Boundaries)
* **Human Boundary (Con người):** Chỉ tham gia ở hai đầu mút: cung cấp tài liệu đầu vào (Bước 1) và thực hành làm bài, đối soát kết quả đầu ra (Bước 5).
* **System Boundary (Rule vs AI):**
  * **Rule:** Xử lý các tác vụ tiền/hậu kỳ có tính xác định (deterministic) như bóc tách text, chia chunk, đếm token, gán metadata số trang và kiểm định schema JSON output.
  * **AI:** Chỉ tập trung vào tác vụ nhận thức phi cấu trúc (non-deterministic) gồm thấu hiểu ngữ nghĩa, tổng hợp khái niệm cốt lõi, sinh câu hỏi và tạo đáp án nhiễu (distractors) hợp lý.

#### Phương án xử lý khi AI sai (Fallback Plan)
* **Trường hợp 1: AI trả sai định dạng / Lỗi cấu trúc JSON:**
  * *Xử lý:* Rule Validator tự động kích hoạt prompt retry (tối đa 2 lần). Nếu vẫn không đúng schema, hệ thống tự động loại bỏ chunk lỗi và chuyển sang chunk tiếp theo để không ngắt quãng luồng sinh câu hỏi.
* **Trường hợp 2: AI bị ảo giác (Hallucination) hoặc sinh câu hỏi lệch:**
  * *Cơ chế Human-in-the-loop:* Luôn hiển thị nút "Xem trích dẫn gốc (Slide số X)" dưới mỗi câu hỏi để người học tự đối chiếu trong 3 giây.
  * *Tính năng Fallback:* Người dùng bấm "Đổi câu khác (Regenerate)" để AI sinh lại câu hỏi từ đoạn văn đó, hoặc bấm "Báo lỗi câu hỏi" để hệ thống gắn cờ (flag).

---

### 4.3. Before / after

| Chỉ số | Trước (Quy trình thủ công) | Sau (Kỳ vọng với AI & Automation) | Ghi chú |
|:---|:---|:---|:---|
| **Số bước** |6 bước (từ đăng bài xin đề đến tra slide dò đáp án) | 3 bước từ góc nhìn người dùng (Upload $\rightarrow$ AI xử lý $\rightarrow$ Luyện tập) | Cắt bỏ hoàn toàn các bước chờ đợi và tìm kiếm trung gian. |
| **Tổng thời gian** | 1 – 2 ngày (chờ đề) + 150 – 180 phút (sàng lọc & tự giải) | Dưới 3 phút để tạo hoàn chỉnh bộ 20–30 câu trắc nghiệm | Sinh viên bắt đầu ôn tập chủ động ngay khi có bài giảng. |
| **Số bước thủ công** | 5 / 6 bước đều đòi hỏi sinh viên thao tác thủ công | 1 bước duy nhất (Kéo thả tài liệu lên hệ thống) | Toàn bộ khâu bóc tách, soạn đề và tạo đáp án được tự động hóa. |
| **Bottleneck chính** | Chờ xin đề trên nhóm (1–2 ngày) và tốn 45 phút lọc xem đề có đúng giáo trình mới | Thời gian bóc tách file & độ trễ gọi LLM API (khoảng 30 – 90 giây tùy độ dài tài liệu) | Chuyển từ điểm nghẽn "chờ con người" sang "độ trễ xử lý kỹ thuật". |
| **Rủi ro mới phát sinh** | Học lệch kiến thức do đề cũ lỗi thời; nản lòng quay lại đọc slide thụ động |  Tài liệu scan/ảnh khó bóc tách text nếu không có OCR tốt.<br>* Ảo giác kiến thức nhẹ nếu slide quá ngắn hoặc rời rạc. | Cần áp dụng module OCR cho PDF ảnh và kiểm soát context threshold khi chunking. |


## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** |Sinh viên đại học đang ôn thi |
| **Quy trình** |1. Đọc lướt tài liệu - 2. Lên group xin đề - 3. Chờ đợi người gửi - 4. Lọc xem đề nào còn phù hợp giáo trình - 5. Tự làm và mò mẫm dò lại đáp án. |
| **Bottleneck** |Mất từ vài giờ đến vài ngày chờ đợi nhưng không đảm bảo chất lượng. |
| **Impact** | Mất nhiều thời gian tìm kiếm thay vì thực sự học; tâm lý bất an vì đề trôi nổi.|
| **Success Metric** (baseline → target, cách đo) |Thời gian để có bộ đề 50 câu (kèm đáp án và giải thích) giảm từ vài giờ/ngày xuống dưới 3 phút. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) |AI không được làm: Tự sáng tạo (hallucinate) kiến thức, thuật ngữ ngoài tài liệu cung cấp; không cam kết trúng đề thật. HITL: Sinh viên phải upload tài liệu chuẩn ban đầu; tự đối chiếu lại các câu hỏi tính toán/logic phức tạp; báo lỗi khi thấy đáp án mâu thuẫn để AI hiệu chỉnh dựa trên phản hồi. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

AI phản biện người dùng (Actor): Quá rộng và ôm đồm
Vấn đề: "Sinh viên đại học" là một tệp quá rộng. Khả năng xử lý của AI rất khác nhau tùy theo ngành học. AI làm rất tốt đề trắc nghiệm Luật, Quản trị kinh doanh, Lịch sử Đảng (thiên về text, khái niệm); nhưng sẽ dễ bị "ảo giác" (hallucinate) và tính toán sai với các môn như Giải tích, Cơ học lượng tử, hay Kế toán vĩ mô.
Đề xuất: Thu hẹp Actor hoặc định rõ phạm vi (Scope). Ví dụ: "Sinh viên đại học khối ngành Kinh tế/Xã hội" hoặc quy định rõ AI chỉ hỗ trợ định dạng câu hỏi lý thuyết, khái niệm, tình huống (case study), không hỗ trợ giải phương trình hay tính toán phức tạp ở giai đoạn 1.
=> Nhóm đồng ý với phản biện này.

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
