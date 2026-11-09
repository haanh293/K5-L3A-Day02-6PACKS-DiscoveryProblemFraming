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
| 2 |2A202603605_NguyenHaAnh |Lưu kết quả và tham số tự động khi chạy thực nghiệm ML |Sinh viên nghiên cứu, kỹ sư ML |Khi copy/paste vào sheets |"Nếu giải pháp là đơn giản ghi log ra file CSV, có thực sự giải quyết được bài toán so sánh nhiều mô hình cùng lúc, hay chỉ chuyển khó khăn từ việc 'copy-paste' sang việc 'đọc hiểu một file CSV khổng lồ'?" (2A202603617_TranXuanTruong) |
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
