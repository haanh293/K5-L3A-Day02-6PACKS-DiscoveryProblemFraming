# Báo cáo cá nhân — 2A202603617_TranXuanTruong

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Xuân Trường
- MSSV: 2A202603617
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 6PACKS
- Link repo nhóm: https://github.com/haanh293/K5-L3A-Day02-6PACKS-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi đến đợt release/deploy tính năng mới, tôi muốn tổng hợp các pull request và commit trong tuần thành Release Notes, để người dùng và QA nắm được các thay đổi | Developer, Tech Lead, QA | Mất 40–50 phút mỗi chiều thứ Sáu; trung bình xem 15–20 PR mỗi đợt |
| 2 | Lặp lại | Khi kết thúc buổi họp nhóm/họp dự án hàng tuần, tôi muốn ghi lại các quyết định chính và action items kèm người phụ trách, để cả nhóm bám sát tiến độ | Trưởng nhóm, thành viên nhóm | 2 buổi/tuần, mỗi lần mất 25–30 phút nghe lại/viết lại ghi chú và gửi Slack |
| 3 | Lặp lại | Khi chuẩn bị buổi standup hàng ngày, tôi muốn điểm lại những việc mình đã làm hôm qua và việc vướng mắc, để cập nhật nhanh trong 2 phút | Thành viên nhóm, Scrum Master | Mất 10–15 phút mỗi sáng rà lại git log, tin nhắn chat và ticket Jira |
| 4 | Tốn thời gian | Khi nhận file dữ liệu/báo cáo dạng Excel từ đối tác, tôi muốn chuẩn hóa các cột và định dạng lỗi về đúng cấu trúc hệ thống, để import vào cơ sở dữ liệu | Data/Business Analyst, Kỹ sư dữ liệu | Mất 60–90 phút mỗi tuần xử lý tay các ô lỗi, khoảng trắng thừa, sai định dạng ngày |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi tích hợp một thư viện/API mới từ bên thứ ba, tôi muốn nắm nhanh các endpoint chính, tham số xác thực và mã lỗi thường gặp, để dựng mã mẫu chạy thử | Developer | Mất 2–3 tiếng đọc qua doc dài 30–40 trang trước khi viết dòng code đầu tiên |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận được 50–100 phản hồi khảo sát/đánh giá của học viên hoặc người dùng, tôi muốn phân loại các ý kiến phàn nàn theo từng chủ đề, để ban quản lý biết đâu là 3 điểm nóng cần sửa ngay | Quản trị viên, Giảng viên/PM | Mất khoảng 2 tiếng đọc từng dòng phản hồi vào mỗi cuối tháng |
| 7 | Pain từ người khác | Khi quản lý dự án cần biết tiến độ của 5 thành viên trước giờ báo cáo cấp trên, quản lý muốn có trạng thái cập nhật từng task, để không phải đi nhắn tin giục từng người | Quản lý dự án, Thành viên nhóm | 2 lần/tuần, quản lý phải gửi 5–7 tin nhắn "nhắc nợ" cập nhật trạng thái trên Jira/Trello |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Tự scan trước:** Tôi tự scan 4 vấn đề thường gặp từ trải nghiệm học tập và làm việc thực tế (#1, #2, #3, #7).
- **AI gợi ý thêm:** Tôi dùng AI để mở rộng góc nhìn ở lăng kính *Tốn thời gian* và *Cần đọc, tổng hợp nhiều thông tin*.
  - **Ý giữ lại:** Ý #4 (chuẩn hóa dữ liệu Excel), #5 (tổng hợp doc API mới), #6 (phân loại phản hồi khảo sát), #7 (theo dõi cập nhật task) vì đây là các nỗi đau có quy trình cụ thể, lặp lại và có số liệu thời gian đo lường rõ ràng.
  - **Ý bỏ:** AI gợi ý ý tưởng *"Trợ lý AI quản lý toàn bộ task dự án"* và *"Chatbot tự động giải đáp mọi thắc mắc của khách hàng"*. Tôi bỏ các ý này vì phạm vi quá rộng, không có một quy trình làm việc cụ thể và đã nhảy ngay sang giải pháp (vi phạm nguyên tắc Problem-first).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp Release Notes (#1) | Quy trình lặp lại hàng tuần, bottleneck rõ (tóm tắt PR kỹ thuật thành narrative dễ hiểu), đo được baseline chính xác | Độ chính xác của AI khi gặp PR có nhiều commit kỹ thuật phức tạp |
| 2 | Ghi chú & Theo dõi Action Items sau họp (#2) | Nỗi đau thực tế của cả nhóm, nhiều người gặp, ảnh hưởng trực tiếp đến việc trễ deadline | Khó ghi nhận âm thanh hoặc ghi chú viết vội nếu nhiều người nói chen nhau |
| 3 | Chuẩn hóa dữ liệu Excel từ đối tác (#4) | Tốn nhiều thời gian (80 phút/tuần), tác động trực tiếp đến tính toàn vẹn của dữ liệu | Liệu dùng script Rule (Python/Pandas) đã giải quyết được 80% chưa và có thực sự cần AI? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến đợt release/deploy tính năng mới, tôi muốn tổng hợp các pull request và commit trong tuần thành Release Notes, để người dùng và QA nắm được các thay đổi |
| Actor | Developer / Tech Lead phụ trách release hàng tuần |
| Thời điểm / bối cảnh | Chiều thứ Sáu hàng tuần, trước khi deploy lên môi trường staging/production |
| Quy trình hiện tại (3–7 bước) | 1. Lọc danh sách PR đã merge trong tuần trên GitHub (10') · 2. Đọc từng PR description và commit message (15') · 3. Phân loại theo category: Tính năng, Sửa lỗi, Hiệu năng (10') · 4. Viết lại narrative tóm tắt dễ hiểu cho QA/người dùng (15') · 5. Gửi lên kênh Slack #announcement và GitHub Releases (5') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: Viết lại tóm tắt narrative (khoảng 15 phút, tốn thời gian diễn đạt từ thuật ngữ kỹ thuật thô sang ngôn ngữ người dùng) |
| Impact (nếu không giải thì sao) | Mất 55 phút/tuần; viết vội dễ sót thay đổi quan trọng; QA không nắm rõ phạm vi để test dẫn đến lọt bug |
| Success metric (baseline → target) | Tổng thời gian soạn Release Notes giảm từ 55 phút xuống dưới 15 phút; số lần QA hỏi lại về thay đổi giảm về 0 |
| Phương án không dùng AI | Dùng GitHub Release auto-generate changelog + PR template bắt buộc: gom PR nhanh nhưng nội dung vẫn là commit thô kỹ thuật |
| Giả thuyết về AI (nếu có) | AI đọc diff/PR summary đã gom để soạn nháp Release Notes chia nhóm rõ ràng; Dev review và chỉnh sửa trước khi publish |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 55 phút/tuần

[1. Lọc PR GitHub: 10'] → [2. Đọc PR & commit: 15'] → [3. Phân loại category: 10']
→ [4. Viết narrative tóm tắt: 15'] ← BOTTLENECK
→ [5. Gửi Slack & GitHub Releases: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi kết thúc buổi họp nhóm/họp dự án hàng tuần, tôi muốn ghi lại các quyết định chính và action items kèm người phụ trách, để cả nhóm bám sát tiến độ |
| Actor | Trưởng nhóm / Thư ký cuộc họp dự án |
| Thời điểm / bối cảnh | Ngay sau các buổi họp sync sprint planning hoặc review định kỳ (2 lần/tuần) |
| Quy trình hiện tại (3–7 bước) | 1. Đọc lại sổ ghi chú nhanh trong cuộc họp (5') · 2. Lọc ra các quyết định đã chốt và việc cần làm (10') · 3. Gán người phụ trách (assignee) và deadline cụ thể (10') · 4. Định dạng thành tin nhắn Slack/bảng Notion gửi cho team (5') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 3: Lọc việc và gán trách nhiệm (khoảng 20 phút, dễ tranh luận lại hoặc quên ai nhận việc gì) |
| Impact (nếu không giải thì sao) | Mất 30 phút/buổi (60 phút/tuần); các cuộc họp trước từng bị trễ 2 task quan trọng vì không ai nhận trách nhiệm rõ ràng |
| Success metric (baseline → target) | Thời gian soạn recap giảm từ 30 phút xuống dưới 10 phút/buổi; 100% action items có người nhận và deadline |
| Phương án không dùng AI | Dùng template Google Docs cố định sẵn cột [Quyết định, Việc cần làm, Người làm, Hạn chót], vừa họp vừa gõ trực tiếp|
| Giả thuyết về AI (nếu có) | AI trích xuất action item và quyết định từ bản nháp ghi chú cuộc họp; thư ký chỉ rà soát 3 phút trước khi gửi |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 30 phút/buổi (60 phút/tuần)

[1. Đọc lại ghi chép thô: 5'] → [2. Lọc quyết định & việc: 10'] ← BOTTLENECK
→ [3. Gán người phụ trách & deadline: 10'] ← BOTTLENECK
→ [4. Format gửi Slack/Notion: 5']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận file dữ liệu/báo cáo dạng Excel từ đối tác, tôi muốn chuẩn hóa các cột và định dạng lỗi về đúng cấu trúc hệ thống, để import vào cơ sở dữ liệu |
| Actor | Data Analyst / Kỹ sư dữ liệu |
| Thời điểm / bối cảnh | Sáng thứ Hai hàng tuần khi đối tác gửi file tổng hợp số liệu tuần cũ |
| Quy trình hiện tại (3–7 bước) | 1. Mở file Excel đối tác và kiểm tra cấu trúc (10') · 2. Xóa khoảng trắng thừa, sửa lỗi font và ngày tháng (25') · 3. Đổi tên cột về schema hệ thống (15') · 4. Chạy script import (15') · 5. Sửa tay các dòng bị reject và import lại (15') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 5: Tìm và sửa tay các ô sai định dạng/lỗi dữ liệu (tổng cộng 40 phút) |
| Impact (nếu không giải thì sao) | Mất 80 phút mỗi sáng thứ Hai; nếu import sót/lỗi dẫn đến sai lệch số liệu trên dashboard tuần của ban lãnh đạo |
| Success metric (baseline → target) | Thời gian chuẩn hóa giảm từ 80 phút xuống 20 phút; tỷ lệ dòng bị reject khi import giảm từ 15% xuống dưới 2% |
| Phương án không dùng AI | Viết script Python (Pandas) / VBA Macro với bộ quy tắc cố định (Rule) để tự động làm sạch các lỗi phổ biến |
| Giả thuyết về AI (nếu có) | Dùng AI để phát hiện và tự động mapping các cột schema mới bị thay đổi tên mà rule chưa bao quát |
| Cảm nhận nhanh | Rule (hoặc Workflow) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 80 phút/tuần

[1. Kiểm tra cấu trúc: 10'] → [2. Sửa lỗi font, ngày tháng: 25'] ← BOTTLENECK
→ [3. Đổi tên cột schema: 15'] → [4. Chạy script import: 15']
→ [5. Sửa tay các dòng reject: 15'] ← BOTTLENECK
```

### Card muốn pitch nhất

- Card số: Card #1 (Tổng hợp Release Notes từ PR/commit)
- Vì sao: Quy trình có cấu trúc rất rõ ràng, diễn ra đều đặn hàng tuần, bottleneck cụ thể (soạn narrative từ commit kỹ thuật thô), có baseline thời gian đo lường được ngay (55 phút), ranh giới can thiệp an toàn (AI soạn nháp, Dev review trước khi publish).
- Câu hỏi muốn nhóm phản biện: "Nếu chỉ cần dùng GitHub Release tự động gom tên PR thì tại sao vẫn cần AI? Bước tóm tắt narrative của AI có thật sự mang lại giá trị hơn changelog thô của GitHub không?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Nếu bắt buộc dev điền summary chuẩn vào PR template thì không cần AI tóm tắt | Đồng ý một phần | Thực tế dev thường viết PR vội ("fix bug", "update logic"). Đã sửa: Làm rõ rằng AI gom cả PR title + context commit để tạo bản thảo narrative thay vì dựa hoàn toàn vào tự giác của dev. |
| Tại sao không để AI tự động publish thẳng lên Slack và GitHub Releases (Agent)? | Không đồng ý | Release Notes gửi cho toàn bộ người dùng và ban điều hành; nếu AI hallucinate tính năng sẽ gây hậu quả lớn. Phải giữ boundary: Dev bắt buộc phải review và bấm publish (HITL). |
| Con số 55 phút có phải là ước lượng cảm tính không? | Đồng ý | Đã bấm giờ thật ở 2 lần release gần nhất: lần 1 mất 50 phút, lần 2 mất 60 phút (trung bình 55 phút). |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Card #1 (Viết Release note cho PR/commit) và Card #2 (Action items sau họp tuần) | Đóng góp 2 candidate vào bảng pitch chung của nhóm; Card #1 đạt điểm cao và lọt vào shortlist cân nhắc của nhóm |
| Phản biện bài của bạn khác | Đặt câu hỏi cho bài #2 của Hà Anh (Lưu log ML): "Nếu giải pháp đơn giản là ghi log ra CSV thì có giải quyết được việc so sánh nhiều model cùng lúc hay chỉ chuyển khó khăn sang việc đọc file CSV khổng lồ?"; Đặt câu hỏi cho bài #5 của Tuấn (Đối chiếu deadline): "Vấn đề nằm ở thiếu công cụ hay do tính chủ động khi đã có Google Calendar/Notion?" | Giúp nhóm nhận diện được các rào cản về phạm vi và tính khả thi của các candidate, loại bỏ giải pháp mang tính chủ quan |
| Nhận phản biện | Hà Anh hỏi: "GitHub đã có sẵn nút auto-generate release notes từ tên PR, tại sao vẫn cần công cụ riêng?"; Tuấn hỏi: "Bot họp như Otter/Fireflies đã có tóm tắt, bài toán có còn chỗ trống không?" | Giải trình rõ: Auto-generate của GitHub chỉ liệt kê commit thô kỹ thuật, không tổng hợp được narrative nghiệp vụ cho người dùng/QA; bổ sung ranh giới Workflow cho bài toán |
| Gom cluster / cây OST | Cùng nhóm phân loại 12 candidate thành 4 cụm; đưa Card #1 vào Cụm C (Kỹ thuật/MLOps) và Card #2 vào Cụm D (Quản trị công việc); tham gia xây dựng Opportunity Tree | Thống nhất Outcome chung của nhóm hướng tới việc tối ưu hóa thời gian chuẩn bị và học tập ôn thi |
| Chọn candidate problem | Tham gia chấm điểm shortlist theo 7 tiêu chí; thảo luận so sánh giữa Candidate #7 (Tạo câu hỏi trắc nghiệm ôn tập) và #11 (Sinh bộ test data) | Đồng thuận chọn Candidate #7 vì có tệp người dùng trực tiếp, có sẵn slide/tài liệu để kiểm chứng ngay trong buổi lab |
| Kiểm chứng / research | Đóng góp ý kiến xây dựng Assumption Map (tập trung vào giả định AI hallucinate sinh câu hỏi/đáp án sai lệch); rà soát các công cụ sinh câu hỏi từ tài liệu hiện có (Quizlet, Anki, Quizgecko), Phụ trách chính CP4 — Research: nghiên cứu giải pháp, đối thủ, liên kết tài liệu. | Giúp nhóm xác định rõ khoảng trống: các tool hiện tại thường sinh câu hỏi bề mặt hoặc trích nguyên văn, thiếu khả năng phân loại theo mức độ Bloom và bám sát slide giáo trình |
| Quy trình nhóm | Đóng góp xây dựng quy trình tương lai (Future Workflow) và đề xuất bước Human-in-the-loop (Sinh viên soát lại câu hỏi trước khi học) | Đảm bảo quy trình có boundary rõ ràng và có phương án quay về (fallback) nếu AI sinh câu hỏi sai |
| Problem Statement | Cùng nhóm phản biện và hoàn thiện Problem Statement v0 và v1, đặc biệt ở tiêu chí Success Metric (đo thời gian chuẩn bị và tỷ lệ câu hỏi chính xác) | Giúp Problem Statement chặt chẽ, không bị lẫn giải pháp công nghệ vào phần định nghĩa bài toán |
| Mức can thiệp AI | Phân tích bài toán theo thang can thiệp No AI -> Rule -> Workflow -> Agent; lập luận vì sao chọn Workflow thay vì Agent tự động hoàn toàn | Nhóm thống nhất mức can thiệp là Workflow (AI trích xuất và sinh câu hỏi nháp, con người review) để kiểm soát rủi ro sai sót kiến thức |
| Quyết định | Đánh giá 4 rủi ro (Value, Usability, Feasibility, Viability) và thiết lập ngưỡng dừng (stopping threshold) | Nhóm đi đến quyết định Not Yet (Dự án chưa thể chọn Go ngay lúc này vì vướng phải bài toán chi phí vận hành và bài toán đầu tư tài chính|

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Mở rộng góc nhìn tìm kiếm nỗi đau theo 4 lăng kính từ bối cảnh kỹ thuật và học tập | Gợi ý thêm các khía cạnh tốn thời gian như chuẩn hóa Excel hay phân loại khảo sát | Gợi ý giải pháp quá sớm (cần chatbot AI quản lý task, tool tự động code) | Gạt bỏ các gợi ý mang tính giải pháp, viết lại thuần túy dạng Job Story gắn với bối cảnh và số liệu đo lường thật |
| CP2 Problem Card | Đóng vai PM hoài nghi để phản biện Card #1 (Tổng hợp Release Notes) | Chỉ ra điểm yếu: chưa chứng minh được sự khác biệt giữa AI và auto-generate sẵn có của GitHub | Ban đầu gợi ý biến thành Agent tự động publish thẳng lên Slack/GitHub mà bỏ qua bước con người duyệt | Giữ vững lập trường HITL (Human-in-the-loop): bắt buộc Dev phải review trước khi công bố để tránh hallucination |
| CP4 Research | Tìm kiếm các giải pháp trắc nghiệm/flashcard AI hiện có trên thị trường | Liệt kê nhanh các công cụ như Quizgecko, Anki AI, StudySmarter và tính năng chính | Đưa ra thông tin chung chung, không chỉ rõ điểm nghẽn thực tế khi xử lý slide tiếng Việt hoặc công thức | Tự đối chiếu và bổ sung nhận định về rủi ro nhận diện sai thuật ngữ chuyên ngành tiếng Việt |
| CP5 Quy trình | Chuyển đổi mô tả các bước thành cú pháp sơ đồ luồng quy trình | Định dạng nhanh cú pháp text/Mermaid mạch lạc, dễ nhìn | Thường tự ý gộp bước đọc hiểu slide và chọn trọng tâm, làm lu mờ bottleneck | Tách riêng bước lọc nội dung trọng tâm thành một bước độc lập có thời gian cụ thể |
| CP5–6 Problem Statement | Rà soát lỗi logic và tìm kiếm từ ngữ mang tính giải pháp bị lẫn vào bài toán | Phát hiện câu chữ còn mơ hồ trong Success Metric | Đề xuất metric chung chung như tăng trải nghiệm học tập, học nhanh hơn | Sửa lại thành metric định lượng: Giảm thời gian chuẩn bị câu hỏi từ 45' xuống < 3, Tỷ lệ câu hỏi chính xác đạt >= 90% |
| CP6 Mức can thiệp / quyết định | So sánh trade-off giữa Workflow và Agent; gợi ý các tiêu chí đánh giá (Eval) | Đưa ra cấu trúc phân tích 4 rủi ro (Cagan) và gợi ý khung Eval đạt/không đạt | Khuyên làm Agent tự động giải đề và chấm điểm (quá phức tạp, vượt quá năng lực kiểm soát trong lab) | Nhóm giữ vững quyết định chọn Workflow, thiết lập ngưỡng dừng: Nếu sau 2 tuần tỷ lệ câu hỏi lỗi > 15% thì dừng pilot |

---

## 6. Reflection (CP7)

Trắc nghiệm và tự soi rọi qua trải nghiệm thực tế trong buổi làm việc nhóm:

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi lắng nghe phần pitch của các thành viên trong nhóm 6PACKS, tôi nhận ra góc nhìn về nỗi đau của mỗi người phụ thuộc rất lớn vào bối cảnh làm việc hàng ngày của họ. Các bạn thiên về kỹ thuật (như bài log ML của Hà Anh hay test dbt của Trọng) thường nhìn thấy vấn đề ở tầng hệ thống và dữ liệu, trong khi các bạn khác lại đau đáu về các vấn đề sát sườn trong đời sống sinh viên (như việc sửa CV, đối chiếu deadline hay ôn thi nước rút của Kiên và Tuấn). Bài học lớn nhất là một vấn đề nghe có vẻ to tát về mặt công nghệ chưa chắc đã là một bài toán tốt cho lab nếu thiếu người dùng thực tế để kiểm chứng ngay. Ngược lại, một bài toán tưởng chừng bình dị như việc ôn thi trước slide bài giảng lại có tần suất lặp lại dày đặc, nỗi đau rõ ràng và dễ tiếp cận người dùng thật ngay tại lớp.
  

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm bị solution-first rõ nhất ở giai đoạn đầu của CP3 khi pitch và gom cụm. Khi bàn về bài toán ôn thi, phản xạ tự nhiên của hầu hết mọi người là ngay lập tức thảo luận xem nên dùng mô hình ngôn ngữ nào, prompt RAG ra sao, hay làm con chatbot hỏi đáp tài liệu. Nhóm nhận ra điều này khi bắt tay vào vẽ cây Opportunity Solution Tree (OST) và phát hiện ra các thẻ như Chatbot AI tạo đề thi hay Dashboard tra cứu thực chất là tính năng và giải pháp chứ không phải nỗi đau người dùng. Nhóm đã xử lý bằng cách kiên quyết gạch bỏ các thẻ này khỏi tầng Opportunity, ép bản thân phải quay lại trả lời câu hỏi cốt lõi: Nỗi đau thật của sinh viên là gì? Đó là việc tốn quá nhiều thời gian đọc slide thụ động mà không biết mình hổng kiến thức ở đâu và nỗi sợ câu hỏi trắc nghiệm tự làm bị sai lệch.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã có sự thay đổi nhận thức rõ rệt sau khi nhận phản biện từ Hà Anh về bài toán Release Notes (#1 của tôi). Ban đầu, tôi khá tự tin vì đây là bài toán tôi gặp hàng tuần và đã có baseline 55 phút rất rõ. Tuy nhiên, khi Hà Anh chất vấn: GitHub đã có sẵn tính năng auto-generate release notes từ PR, tại sao nhóm phải làm công cụ riêng?, tôi buộc phải nhìn nhận lại một cách nghiêm túc. Tôi nhận ra rằng nếu chỉ giải quyết việc gom thông tin, các công cụ sẵn có (Rule/Template) đã làm được 70-80%. Giá trị gia tăng của AI chỉ nằm ở bước viết diễn giải (narrative) cho người dùng cuối. Điều này giúp tôi không bảo thủ bảo vệ bài của mình khi nhóm chấm điểm shortlist, và hoàn toàn đồng thuận chuyển sang chọn bài toán câu hỏi ôn tập (#7) vì bài toán đó có độ mơ hồ cao hơn và giá trị can thiệp của AI rõ ràng hơn hẳn.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điều làm tôi bất ngờ nhất khi nhóm đối chiếu và phỏng vấn nhanh các bạn sinh viên xung quanh là: sinh viên không hề thiếu câu hỏi để luyện (trên mạng có rất nhiều đề trôi nổi), nhưng họ cực kỳ sợ việc học phải các câu hỏi trắc nghiệm ảo giác hoặc không bám sát trọng tâm mà giảng viên sẽ ra thi. Rất nhiều bạn chia sẻ rằng họ từng thử copy slide vào ChatGPT để nhờ tạo câu hỏi trắc nghiệm, nhưng các câu hỏi tạo ra thường quá dễ, hỏi mẹo từ ngữ vụn vặt hoặc hỏi những phần giảng viên đã dặn giảm tải. Bằng chứng hành vi này cho thấy vấn đề cốt lõi không phải là tạo ra thật nhiều câu hỏi, mà là tạo ra câu hỏi đúng chuẩn đề cương và có trích dẫn nguồn slide minh chứng để đối chiếu.


**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó khăn nhất là tách bạch hoàn toàn giữa Vấn đề và Giải pháp, đồng thời đặt ra một Success Metric thực sự đo lường được. Trong quá trình viết Problem Statement v0, nhóm liên tục bị cám dỗ chèn các từ ngữ như công cụ hỗ trợ tự động, trợ lý thông minh. Việc loại bỏ các từ này để giữ mô tả thuần túy về Actor, Quy trình và Bước nghẽn đòi hỏi kỷ luật tư duy rất cao. Ngoài ra, việc xác định Success Metric có baseline (hiện tại mất bao lâu) và target đo được (thời gian giảm bao nhiêu, tỷ lệ câu hỏi đạt chuẩn là bao nhiêu) cũng rất thách thức, vì nếu đặt mục tiêu chung chung như "giúp sinh viên học tốt hơn" thì hoàn toàn vô nghĩa và không thể nghiệm thu.


**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu được làm lại từ đầu buổi, tôi sẽ thúc đẩy nhóm tiến hành khảo sát và phỏng vấn người dùng (Mom Test) sớm hơn một nhịp, ngay từ lúc chọn shortlist thay vì chờ đến CP4 mới đi hỏi sâu. Ngoài ra, tôi sẽ phản biện nhóm quyết liệt hơn ở khâu rà soát công cụ đã có trên thị trường: nhóm cần thử nghiệm thực tế 1-2 công cụ miễn phí như Quizlet AI hay Quizgecko trên chính slide mẫu để chỉ ra chính xác điểm yếu của chúng, thay vì chỉ đọc qua tính năng trên trang chủ của họ. Điều này sẽ giúp cho phần Boundary và Eval của nhóm sắc bén hơn rất nhiều.


**6.7. Hiểu bài:** chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình:

Bài toán của nhóm xuất phát từ **Problem**: sinh viên mất trung bình 45 phút đọc lướt slide thủ công để tự nhặt ý chính và soạn câu hỏi ôn tập trước kỳ thi, nhưng câu hỏi tự soạn thường thiếu bao quát và dễ sai lệch. **Quy trình hiện tại** gồm 5 bước thủ công (Tải slide $\rightarrow$ Đọc lướt $\rightarrow$ Trích xuất ý chính $\rightarrow$ Soạn câu hỏi/đáp án $\rightarrow$ Tự giải và rà soát), trong đó bước soạn câu hỏi và đáp án là bottleneck lớn nhất (chiếm 25 phút). **Metric** thành công được đo lường bằng việc giảm thời gian tạo bộ 10 câu hỏi từ 45 phút xuống dưới 3 phút, với tỷ lệ câu hỏi chuẩn xác bám sát slide đạt $\ge 90\%$. **Boundary** được thiết lập nghiêm ngặt: AI tuyệt đối không tự ý thêm các kiến thức ngoài slide giáo trình, không tự quyết định câu hỏi nào là đạt mà bắt buộc phải có sinh viên kiểm tra (Human-in-the-loop), kèm trích dẫn số trang slide tương ứng để đối chiếu. Do đầu ra có độ mơ hồ cao nhưng quy trình tuần tự rõ ràng, **Mức can thiệp AI** được xác định là **Workflow** (kết hợp Script đọc slide $\rightarrow$ AI sinh nháp câu hỏi $\rightarrow$ Sinh viên duyệt), kiên quyết không dùng Agent tự hành. Cuối cùng, nhóm đưa ra **Quyết định Not Yet** Dự án được đánh giá là hoàn toàn khả thi về mặt kỹ thuật và có giá trị thực tiễn rất cao tuy nhiên chưa thể chọn Go ngay lúc này vì vướng phải bài toán chi phí vận hành và bài toán đầu tư tài chính.

---

## 7. Tài liệu tham khảo

- Lean UX: Designing Great Products with Agile Teams (Jeff Gothelf & Josh Seiden).
- The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you (Rob Fitzpatrick).
- Opportunity Solution Tree Framework (Teresa Torres, Continuous Discovery Habits).
- Building Effective Agents & AI Workflows Guide (Anthropic, 2024).
- People + AI Guidebook (Google PAIR).
- Inspired & Empowered: Product Risk Framework (Marty Cagan, Silicon Valley Product Group).
