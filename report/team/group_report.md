# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: 6PACKS
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Tạo bộ câu hỏi ôn tập bám sát tài liệu
- Quyết định cuối: Not Yet

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 |2A202603605_NguyenHaAnh |Chỉnh sửa CV nhanh chóng để khớp với JD |Ứng viên xin việc |Bước chỉnh sửa thủ công |"Tại sao không dùng chatbot có sẵn mà lại phải dùng sản phẩm này, sản phẩm có gì khác biệt ?" (2A202603644_NguyenDucTrong) |
| 2 |2A202603605_NguyenHaAnh |Lưu kết quả và tham số tự động khi chạy thực nghiệm ML |Sinh viên nghiên cứu, kỹ sư ML |Khi copy/paste vào sheets |"Nếu giải pháp là đơn giản ghi log ra file CSV, có thực sự giải quyết được bài toán so sánh nhiều mô hình cùng lúc, hay chỉ chuyển khó khăn từ việc copy-paste sang việc đọc hiểu một file CSV khổng lồ?" (2A202603617_TranXuanTruong) |
| 3 |2A202603617_TranXuanTruong |Viết Release note cho các pull request/commit |developer/techlead phụ trách release hàng tuần |Tốn 15–20 phút diễn giải từ commit/PR kỹ thuật thô sang ngôn ngữ nghiệp vụ dễ hiểu. | "GitHub đã có sẵn nút auto-generate release notes từ tên PR, tại sao vẫn cần công cụ riêng?"(2A202603605_NguyenHaAnh)|
| 4 |2A202603617_TranXuanTruong |Khi kết thúc họp tuần, tôi muốn ghi lại quyết định và action items kèm người phụ trách để nhóm bám sát tiến độ.|Trưởng nhóm, thành viên nhóm.|Tốn 25–30 phút nghe lại/rà soát ghi chú để trích xuất đúng người - đúng việc và gửi Slack.|"Các bot họp như Otter, Fireflies hay Teams Copilot đều có tính năng này, bài toán này có còn chỗ trống không?"(2A202603630_NgoVanTuan)|
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
 
 #1 (Chỉnh sửa CV): Khó đo lường ranh giới giữa việc dùng một prompt ChatGPT thông thường với một giải pháp chuyên biệt; impact phỏng vấn khó kiểm chứng ngay.

 #3 (Viết Release note): Phụ thuộc nhiều vào ngữ cảnh dự án phần mềm và commit log thực tế, khó xây dựng benchmark đánh giá khách quan.
 
 #5 (Đối chiếu deadline): Vướng rào cản kết nối API vào các nhóm chat/LMS đóng, ranh giới vấn đề nằm ở tính chủ động cá nhân hơn là bài toán công nghệ.
 
 #9 (Sàng lọc bài báo): Tiêu chí bài báo "dùng được" mang tính chủ quan cao theo từng đề tài, khó đo độ chính xác (ground truth).
 
 #11 (Sinh bộ test dữ liệu): Điểm số cao thứ nhì và nghiệp vụ rất rõ, nhưng cần dựng mock database phức tạp và khó chuẩn hóa dataset chuẩn để demo kiểm thử trong thời gian lab.

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

Interview snapshot (File trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

(Bảng tổng hợp được đặt trong `report/assets/cp4-interview-snapshot-1.md`)

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |


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
| **3** | Người cho đề, Sinh viên | Bài đăng hỏi xin đề | Tệp đề cũ (hoặc không nhận được phản hồi) | 1 – 2 ngày (chờ đợi) | Bị động hoàn toàn: Nếu có người gửi thì qua B4; nếu không ai gửi thì buộc phải tự mò mẫm đọc lại slide (chuyển thẳng B6). |
| **4** | Sinh viên ôn thi | Các tệp đề cũ thu thập được, giáo trình hiện tại | Bộ câu hỏi lọc sơ bộ còn đúng chương trình học | 45 phút / Mỗi đợt xin được đề | Tốn công rà soát: Phải loại bỏ các câu thuộc chương trình cũ đã giảm tải hoặc đổi giáo trình. |
| **5** | Sinh viên ôn thi | Bộ câu hỏi đã lọc | Bài làm với các đáp án đã chọn | 30 phút / Mỗi lần làm thử | Làm bài trong tâm lý bất an vì không chắc đề có chuẩn và có đáp án đúng đi kèm hay không. |
| **6** | Sinh viên ôn thi | Bài làm, tài liệu/slide bài giảng gốc | Điểm số và danh sách câu sai đã được kiểm chứng | 30 phút / Mỗi bài test | Vòng lặp sửa sai: Đề cũ thường thiếu đáp án chuẩn hoặc giải sai, sinh viên phải tự lật từng trang slide để dò; nếu sai lệch quá nhiều lại phải quay lại lọc đề khác (về B4). |


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
| **1** | Tải tài liệu học tập | Con người | Sinh viên | Slide PDF, file giáo trình $\rightarrow$ File thô trên hệ thống | Sinh viên kéo thả file bài giảng (PDF/Docx), chọn số lượng câu hỏi và phạm vi ôn tập. |
| **2** | Tiền xử lý & Trích xuất văn bản | Rule | Hệ thống (Parser) | File PDF thô $\rightarrow$ Clean text chunks kèm Page ID | Hệ thống bóc tách text, lọc bỏ trang bìa/mục lục, chia chunk (500–1000 tokens) và gắn metadata số trang. |
| **3** | Sinh câu hỏi & Trích dẫn nguồn | AI | LLM Engine (RAG) | Clean text chunks $\rightarrow$ Bộ câu hỏi MCQ (JSON) | LLM đọc ngữ cảnh, nhận diện khái niệm chính, sinh 4 lựa chọn (1 đúng, 3 nhiễu) kèm trích dẫn số trang/đoạn văn gốc (grounding). |
| **4** | Kiểm định cấu trúc & Cú pháp | Rule | Hệ thống (Validator) | JSON từ AI $\rightarrow$ Bộ đề hợp lệ trên UI | Kiểm tra schema JSON, đủ 4 đáp án A-B-C-D, đáp án đúng duy nhất. Nếu hợp lệ thì render lên giao diện làm bài. |
| **5** | Làm bài & Đối soát kiến thức | Con người | Sinh viên | Giao diện câu hỏi $\rightarrow$ Kết quả & Insight ôn tập | Sinh viên làm bài chủ động; hệ thống chấm điểm tức thì, xem lời giải và đoạn trích slide đối soát. |

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
| **Actor** | Sinh viên đang trong giai đoạn ôn thi. |
| **Quy trình** | Sinh viên tự tìm kiếm đề thi cũ qua mạng xã hội, rà soát loại bỏ kiến thức lệch giáo trình, tự làm bài và lật giở lại tài liệu gốc để dò tìm đính chính đáp án. |
| **Bottleneck** | Mất 1–2 ngày chờ đợi chia sẻ đề cũ một cách bị động. Tốn thêm 45 phút lọc bỏ kiến thức giảm tải và 30 phút lật từng trang tài liệu tự dò lời giải do đề trôi nổi thường sai hoặc không có đáp án chuẩn. |
| **Impact** | Phá vỡ kế hoạch ôn tập, tốn nhiều thời gian cho các công việc không tạo ra kiến thức (tìm đề, lọc đề, dò đáp án), gây tâm lý bất an và dễ mắc bẫy hiểu bài giả tạo. |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian có đề thực hành: từ 1–2 ngày xuống < 1 phút (đo từ lúc upload tài liệu đến khi có đề). (2) Thời gian xác minh đáp án: từ 30 phút xuống ngay lập tức (đo bằng tốc độ trả lời giải kèm trích dẫn). (3) Tỉ lệ khớp giáo trình: đạt > 95% (đo qua đánh giá của người dùng). |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không được bịa đặt (hallucinate) hoặc suy diễn kiến thức ngoài tài liệu cung cấp. Sinh viên (HITL) sẽ tự đối chiếu và kiểm chứng lại đáp án thông qua tính năng bắt buộc AI trích dẫn nguồn tài liệu cụ thể (ví dụ: "Slide 15"). |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:
### Phản biện từ AI: Mâu thuẫn ở hệ quả "Hiểu bài giả tạo" (Illusion of competence)

**1. Nội dung phản biện:**
Ở phần Impact, dự án có đề cập đến việc cách học cũ gây "hiểu bài giả tạo". Tuy nhiên, nếu AI cung cấp đáp án ngay lập tức kèm trích dẫn (như định hướng ở Success Metric 2), sinh viên rất dễ rơi vào bẫy ỷ lại: Đọc câu hỏi ➔ Xem ngay đáp án của AI ➔ Thấy hợp lý ➔ Tự nghĩ rằng mình đã hiểu bài. Điều này vô tình làm tình trạng "hiểu bài giả tạo" trở nên trầm trọng hơn.

**2. Quyết định của nhóm:**
Đồng ý.

**3. Cách giải quyết:**
*   **Điều chỉnh UX/Luồng tính năng:** Hệ thống sẽ không hiển thị ngay đáp án cuối cùng.
*   **Tương tác bắt buộc (HITL):** Sinh viên bắt buộc phải tự nhập câu trả lời hoặc chọn đáp án trước.
*   **Cung cấp Hint (Gợi ý):** Khi AI chấm bài, nếu sinh viên làm sai, hệ thống chỉ đưa ra gợi ý hoặc trích xuất đoạn tài liệu cần đọc lại (ví dụ: *"Xem lại định nghĩa ở Slide 15"*) trước khi cung cấp đáp án hoàn chỉnh.

---

### 6. Mức can thiệp AI (CP6)

#### 6.1. Ma trận độ mơ hồ × độ phức tạp
* **Bài của nhóm nằm ở ô:** Mơ hồ cao — Phức tạp thấp (High ambiguity, Low complexity).
* **Vì sao:** 
  * *Mơ hồ cao:* Việc đọc hiểu ngữ nghĩa bài giảng, tóm tắt ý chính và sáng tạo ra các đáp án nhiễu (distractors) hợp lý đòi hỏi khả năng xử lý ngôn ngữ tự nhiên linh hoạt, không thể viết bằng các quy tắc if/else truyền thống.
  * *Phức tạp thấp:* Luồng công việc rất tuyến tính và cố định (upload file $\rightarrow$ chia chunk $\rightarrow$ sinh JSON câu hỏi $\rightarrow$ làm bài), không cần AI phải lập kế hoạch nhiều bước (reasoning) hay tương tác với môi trường bên ngoài.

---

#### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|:---|:---|:---|:---|:---:|
| **no AI** (sửa quy trình) | Xin giảng viên ngân hàng đề hoặc tự gõ flashcard thủ công (Quizlet/Anki). | Thi các môn có sẵn ngân hàng đề công khai trên mạng. | Mất nhiều thời gian; rủi ro học nhầm đề cũ lệch giáo trình. | Không |
| **rule** | Dùng Regex quét các từ in đậm/gạch chân trong file Word và làm bài tập "điền vào chỗ trống". | Chỉ cần học thuộc lòng từ vựng rời rạc. | Câu hỏi ngô nghê, không tạo được câu hỏi tư duy trắc nghiệm 4 đáp án. | Không |
| **workflow** | LLM đọc các chunk văn bản, trích xuất ý chính và sinh JSON (MCQ) bám sát nội dung, con người làm bài và rà soát. | Cần tạo đề thi thử nhanh, chính xác, sát tài liệu cá nhân. | AI sinh lỗi JSON hoặc bịa kiến thức (ảo giác). | Có |
| **agent** | AI tự lên lịch học, tự tra cứu web, ép sinh viên làm bài và tự điều chỉnh độ khó. | Cần một "gia sư ảo" kèm cặp toàn diện. | Over-engineering; khó kiểm soát chất lượng; sai mục tiêu "cần bộ đề ngay". | Không |

* **Mức chọn:** Workflow (cụ thể là RAG workflow kết hợp structured output).
* **Vì sao không chọn mức đơn giản hơn:** Các mức no AI và rule-based không thể hiểu được ngữ cảnh chuyên ngành để tóm tắt thành câu hỏi và không đủ khả năng sáng tạo ra 3 đáp án nhiễu hợp logic để đánh lừa sinh viên.

---

#### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|:---|:---|
| **prediction** (AI dự đoán / tạo ra gì?) | Dự đoán và tạo ra nội dung câu hỏi trắc nghiệm (MCQ) cùng 3 đáp án nhiễu từ đoạn văn bản (chunk). |
| **judgment** (con người cân nhắc, quyết định gì?) | Sinh viên đối chiếu câu hỏi với số trang/trích dẫn gốc, quyết định xem câu hỏi có đúng trọng tâm hay bịa đặt trước khi ghi nhớ. |
| **action** (hành động cuối cùng là gì, ai làm?) | Hệ thống hiển thị bài thi; Sinh viên thực hiện hành động click chọn đáp án và xem lời giải. |
| **outcome** (đo kết quả bằng gì?) | Thời gian có bộ đề (dưới 3 phút); Tỷ lệ câu hỏi chính xác, không ảo giác (>95%). |
| **input** (dữ liệu đầu vào gì? có sẵn không?) | File bài giảng (PDF, Word, Slide) của sinh viên. Hoàn toàn có sẵn ngay trên máy tính sinh viên. |
| **feedback** (lấy phản hồi ở đâu để cải thiện?) | Sinh viên dùng nút "báo lỗi câu hỏi" hoặc đánh giá thumbs up/down sau mỗi câu hỏi sinh ra bị lệch kiến thức. |

---

#### 6.4. Hai câu hỏi của Google PAIR

* **Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)?**
  * **Đáp án:** Hỗ trợ (augment).
  * **Bằng chứng:** Sinh viên không cần một con AI "đi thi hộ" hay "tự học thay". Họ cần một công cụ đóng vai trò như người trợ giảng, xử lý khâu lao động chân tay (lọc đề, gõ câu hỏi) để họ có tài liệu luyện tập nhanh nhất. Việc tiếp thu kiến thức và chọn đáp án cuối cùng bắt buộc phải do sinh viên thực hiện.

* **AI sai kiểu nào tệ hơn, báo nhầm hay bỏ sót?**
  * **Đáp án:** Báo nhầm (false positive) tệ hơn rất nhiều so với bỏ sót (false negative).
  * **Vì sao:** Nếu AI bỏ sót một vài đoạn văn không tạo câu hỏi, sinh viên lật slide vẫn có thể tự đọc bù. Nhưng nếu AI báo nhầm bằng cách tự bịa ra một kiến thức sai lệch mà slide không hề dạy, sinh viên học vẹt theo sẽ làm sai bài thi thật, dẫn đến hậu quả nghiêm trọng về điểm số và mất hoàn toàn niềm tin vào sản phẩm.
  * **Thiết kế đã xử lý thế nào:** 
    1. Ép framework RAG chỉ được lấy thông tin trong chunk (grounding). 
    2. Giao diện bắt buộc đính kèm vị trí trích dẫn (số trang, nguyên văn) ngay bên dưới lời giải để sinh viên tự kiểm chứng (human-in-the-loop) thay vì tin tưởng AI 100%.
---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** |Sinh viên đang trong giai đoạn ôn thi nước rút. |
| **Quy trình** |Sinh viên upload file bài giảng -> Hệ thống chia chunk và dùng AI sinh câu hỏi dạng MCQ đính kèm trích dẫn (số trang) -> Sinh viên tự làm bài test -> Nếu sai, hệ thống gợi ý trang cần đọc lại (Hint) -> Sinh viên đối chiếu lại slide gốc và xem đáp án hoàn chỉnh. |
| **Bottleneck** |Tốn quá nhiều thời gian để tự soạn câu hỏi và mất 30 phút tự Ctrl+F dò lại đáp án trong slide gốc do sợ bị sai lệch kiến thức. |
| **Impact** |Phá vỡ kế hoạch ôn tập, tốn thời gian cho việc rà soát thủ công, gây tâm lý bất an và dễ rơi vào bẫy "hiểu bài giả tạo" nếu chỉ học thuộc lòng đáp án do AI cung cấp. |
| **Success Metric** (baseline → target, cách đo) |(1) Tổng thời gian có bộ đề 20 câu: từ 45 phút  dưới 3 phút ->(đo từ lúc upload). (2) Thời gian dò lại đáp án nghi ngờ: từ 30 phút -> dưới 5 phút (nhờ có sẵn số trang đính kèm). (3) Tỷ lệ câu hỏi không bịa đặt kiến thức (ảo giác): đạt >95% (đo qua report của sinh viên). |
| **Boundary** |AI tuyệt đối không được bịa đặt kiến thức ngoài tài liệu cung cấp (Grounding). AI không hiển thị ngay đáp án cuối cùng để chống học vẹt. Sinh viên (HITL) bắt buộc phải tự nhập/chọn đáp án trước khi hệ thống chấm điểm và cung cấp trích dẫn. |
| **AI intervention point** |Tại bước đọc file bài giảng, tóm tắt ý chính và sáng tạo ra câu hỏi trắc nghiệm MCQ cùng 3 đáp án nhiễu. |
| **Mức chọn** | Workflow (Cụ thể: RAG workflow kết hợp structured output JSON).|
| **Rủi ro & người kiểm tra** |Rủi ro lớn nhất là AI bịa kiến thức (báo nhầm - false positive) dẫn đến sinh viên làm sai bài thi thật. Người kiểm tra: Sinh viên tự đối chiếu độ chính xác của câu hỏi thông qua tính năng bắt buộc AI trích dẫn nguồn (số trang) ngay dưới mỗi câu.|

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
|Quy trình |Sinh viên rà soát đề trôi nổi trên mạng và lật mở tài liệu dò đáp án. |Upload file -> AI sinh bộ đề -> Sinh viên làm test -> Gợi ý số trang -> Hiện đáp án. |Đưa giải pháp RAG Workflow vào quy trình để tự động hóa việc sinh đề từ tài liệu chính chủ, khắc phục việc phải đi tìm đề trôi nổi. |
|Boundary |AI không được bịa đặt. Sinh viên tự đối chiếu bằng trích dẫn. |Thêm quy định: Không hiển thị đáp án ngay, buộc sinh viên tự chọn đáp án trước (HITL) và chỉ cung cấp Hint khi làm sai. |Xử lý phản biện ở phần 5: Chống lại bẫy "hiểu bài giả tạo" (ỷ lại vào đáp án có sẵn của AI thay vì tự suy nghĩ). |
|Success Metric |Đo lường "thời gian xác minh đáp án giảm xuống ngay lập tức". |Điều chỉnh thành "thời gian dò lại đáp án giảm xuống dưới 5 phút". |Việc xác minh không thể "ngay lập tức" do con người vẫn cần tự đọc lại trích dẫn (HITL). |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 |Độ bám sát nguồn (Grounding) |Nội dung câu hỏi và đáp án đúng được rút trích 100% từ file bài giảng; có đính kèm đúng số trang slide. |AI tự thêm thắt khái niệm/công thức từ dữ liệu huấn luyện bên ngoài mà slide không hề dạy. |
| 2 |Chất lượng đáp án nhiễu (Distractors) |3 đáp án nhiễu có tính logic, liên quan đến ngữ cảnh bài học, đủ khả năng gây nhầm lẫn để kiểm tra tư duy. |Đáp án nhiễu quá vô lý, ngây ngô (ví dụ: hỏi về thuật toán nhưng đáp án nhiễu là tên món ăn), hoặc trùng lặp hoàn toàn với đáp án đúng. |
| 3 |Định dạng cấu trúc (Structured Output) |Trả về đúng định dạng JSON chuẩn (gồm Question, Options array, Correct_Answer, Citation_Page) để hệ thống render lên giao diện làm bài. |Thiếu field, sai cấu trúc JSON hoặc trộn lẫn text tự do khiến hệ thống app không thể parse để hiển thị.|

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? |Thấp |Nhu cầu thực tế lớn |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |Trung Bình |Người dùng có thể dùng được, có thể hiểu nhưng không sửa được đầu ra của AI |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? |Trung Bình |Nguồn dữ liệu dồi dào, cung cụ đầy, độ khó phụ thuộc vào loại tài liệu |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Cao |Chi phí vận hành lớn |

### 8.2. Kết luận

**Quyết định:** Not Yet

**Lý do:**

Dự án được đánh giá là **hoàn toàn khả thi về mặt kỹ thuật và có giá trị thực tiễn rất cao**:
* **Nhu cầu rõ ràng (Value):** Sinh viên có nhu cầu cấp thiết về việc tạo đề trắc nghiệm chủ động từ tài liệu học tập để phục vụ ôn thi.
* **Kỹ thuật trong tầm tay (Feasibility):** Công nghệ hiện tại (RAG kết hợp LLM) đã đủ trưởng thành để bóc tách slide và sinh câu hỏi trắc nghiệm kèm trích dẫn nguồn với độ chính xác cao.

**Rào cản then chốt khiến dự án phải dừng ở mức Not Yet:**
Dự án chưa thể bấm nút "Go" ngay lúc này vì vướng phải bài toán **chi phí vận hành và bài toán đầu tư tài chính (Viability)**:
1. **Gánh nặng chi phí API quá lớn:** Mỗi lượt sinh bộ câu hỏi đòi hỏi đọc hàng chục slide, chia chunk và gọi LLM xử lý context dài, tiêu tốn lượng token đáng kể. Với đối tượng người dùng là sinh viên (khả năng chi trả thấp hoặc chỉ quen dùng miễn phí), chi phí API sẽ nhanh chóng vượt quá khả năng tự duy trì của nhóm nếu lượng người dùng tăng đột biến.
2. **Thiếu nguồn lực đầu tư ban đầu:** Nhóm chưa có nguồn vốn tài trợ hoặc phương án doanh thu khả thi để trang trải hạ tầng máy chủ, chi phí token và công cụ bóc tách OCR chất lượng cao cho các tài liệu scan/hình ảnh.
3. **Cần thời gian kiểm chứng giải pháp tối ưu chi phí:** Dự án không bị hủy bỏ hoàn toàn ("No Go") mà được xếp vào "Not Yet" để nhóm có thời gian nghiên cứu các giải pháp tiết kiệm hơn trước khi ra mắt chính thức:
   * Chuyển sang thử nghiệm các mô hình mã nguồn mở gọn nhẹ chạy local (SLM / Open-source LLM) để cắt giảm phụ thuộc vào API thương mại đắt đỏ.
   * Xây dựng cơ chế semantic caching (lưu trữ và tái sử dụng câu hỏi của các môn học chung giữa nhiều sinh viên) để giảm thiểu số lượt gọi LLM lặp lại.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

###9.1. Hạn chế của hệ thống

1. **Phụ thuộc vào chất lượng và định dạng tài liệu đầu vào:**
   * Hệ thống xử lý tốt nhất với tài liệu văn bản thuần túy (PDF vector, Word). Với slide bài giảng chứa nhiều sơ đồ, hình vẽ, bảng số liệu hoặc PDF dạng ảnh scan, bộ bóc tách văn bản (parser) dễ bị mất dữ liệu nếu không có OCR chuyên sâu.
   * Các slide có quá ít chữ hoặc chỉ chứa từ khóa rời rạc không đủ ngữ cảnh để LLM suy luận và sinh câu hỏi trắc nghiệm chất lượng.

2. **Gánh nặng chi phí token và độ trễ:**
   * Việc chunking và gửi toàn bộ nội dung giáo trình dài lên các API thương mại tiêu tốn lượng token lớn và tạo độ trễ xử lý (30–90 giây), khó mở rộng quy mô nếu không có nguồn tài trợ hạ tầng.

3. **Khả năng tạo câu hỏi tư duy và tính toán còn hạn chế:**
   * Mô hình làm rất tốt các câu hỏi dạng nhận biết và định nghĩa lý thuyết, nhưng dễ sinh lỗi ở các câu hỏi đòi hỏi tính toán công thức số học, giải mã thuật toán hoặc suy luận logic nhiều bước.

4. **Trải nghiệm người dùng chưa khép kín:**
   * Giao diện hiện tại chưa hỗ trợ trình biên tập để người học tự chỉnh sửa trực tiếp câu hỏi hoặc sửa đáp án sai của AI trước khi bắt đầu làm bài.

---

### 9.2. Hướng phát triển tiếp theo 

1. **Tối ưu chi phí và hạ tầng mô hình:**
   * Nghiên cứu chuyển đổi từ các API thương mại đắt đỏ sang các mô hình mã nguồn mở gọn nhẹ (SLM như Llama 3, Qwen) có thể tự host hoặc chạy trên môi trường cục bộ để đưa chi phí vận hành về mức tối thiểu.
   * Xây dựng cơ chế bộ nhớ đệm ngữ nghĩa (semantic caching): lưu trữ và tái sử dụng ngân hàng câu hỏi đã qua kiểm duyệt cho các môn học chung, tránh gọi LLM sinh lặp lại cùng một nội dung slide.

2. **Nâng cấp năng lực xử lý đa phương thức (Multimodal):**
   * Tích hợp Vision-Language Model hoặc OCR nâng cao để đọc hiểu trực tiếp bảng biểu, sơ đồ kiến trúc và công thức toán học trên slide bài giảng.

3. **Hoàn thiện vòng lặp phản hồi (Human-in-the-loop UX):**
   * Phát triển tính năng cho phép sinh viên trực tiếp sửa câu hỏi, tùy chỉnh độ khó (nhận biết, thông hiểu, vận dụng) và chọn số lượng câu hỏi theo từng chương cụ thể.
   * Tận dụng dữ liệu câu hỏi được người dùng gắn cờ (báo lỗi/đánh giá tốt) để xây dựng tập dữ liệu mẫu chuẩn (few-shot dataset), phục vụ việc tinh chỉnh prompt hoặc đánh giá tự động (LLM-as-a-judge) cho các phiên bản tiếp theo.

## 10. Tài liệu tham khảo

- Lean UX: Designing Great Products with Agile Teams (Jeff Gothelf & Josh Seiden).
- The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you (Rob Fitzpatrick).
- Opportunity Solution Tree Framework (Teresa Torres, Continuous Discovery Habits).
- Building Effective Agents & AI Workflows Guide (Anthropic, 2024).
- People + AI Guidebook (Google PAIR).
- Inspired & Empowered: Product Risk Framework (Marty Cagan, Silicon Valley Product Group).
