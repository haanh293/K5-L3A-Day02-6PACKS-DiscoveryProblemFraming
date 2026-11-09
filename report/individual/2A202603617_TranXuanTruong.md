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
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi tích hợp một thư viện/API mới từ bên thứ ba, tôi muốn nắm nhanh các endpoint chính, tham số xác thực và mã lỗi thường gặp, để dựng mã mẫu chạy thử | Developer | Mất 2–3 tiếng đọc qua doc dài 30–40 trang trước khi viết dòng code đầu tiên |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận được 50–100 phản hồi khảo sát/đánh giá của học viên hoặc người dùng, tôi muốn phân loại các ý kiến phàn nàn theo từng chủ đề, để ban quản lý biết đâu là 3 điểm nóng cần sửa ngay | Quản trị viên, Giảng viên/PM | Mất khoảng 2 tiếng đọc từng dòng phản hồi vào mỗi cuối tháng |
| 9 | Pain từ người khác | Khi developer nhận một bug report từ tester/người dùng chỉ ghi chung chung "bị lỗi", developer muốn có đủ các bước tái hiện và môi trường gặp lỗi, để không phải nhắn tin hỏi đi hỏi lại | Developer, Tester | Developer phải nhắn tin hỏi lại 3–4 lần/bug; trung bình mất thêm 20–30 phút/bug chỉ để giao tiếp |
| 10 | Pain từ người khác | Khi quản lý dự án cần biết tiến độ của 5 thành viên trước giờ báo cáo cấp trên, quản lý muốn có trạng thái cập nhật từng task, để không phải đi nhắn tin giục từng người | Quản lý dự án, Thành viên nhóm | 2 lần/tuần, quản lý phải gửi 5–7 tin nhắn "nhắc nợ" cập nhật trạng thái trên Jira/Trello |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Tự scan trước:** Tôi tự scan 6 vấn đề thường gặp từ trải nghiệm học tập và làm việc thực tế (#1, #2, #3, #5, #6, #9).
- **AI gợi ý thêm:** Tôi dùng AI để mở rộng góc nhìn ở lăng kính *Tốn thời gian* và *Cần đọc, tổng hợp nhiều thông tin*.
  - **Ý giữ lại:** Ý #4 (chuẩn hóa dữ liệu Excel), #7 (tổng hợp doc API mới), #8 (phân loại phản hồi khảo sát), #10 (theo dõi cập nhật task) vì đây là các nỗi đau có quy trình cụ thể, lặp lại và có số liệu thời gian đo lường rõ ràng.
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
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
