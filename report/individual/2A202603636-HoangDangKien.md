# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Hoàng Đăng Kiên 
- MSSV: 2A202603636
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 6PACKS
- Link repo nhóm:  https://github.com/haanh293/K5-L3A-Day02-6PACKS-DiscoveryProblemFraming/tree/main

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại|Khi bắt đầu ôn thi một môn học mới, từ những tài liệu được cung cấp sẵn, tôi muốn có một bộ câu hỏi trắc nghiệm ôn tập bám sát những tài liệu đó để không tốn thời gian tạo thủ công. | Toàn bộ sinh viên|Mỗi khi kì thi sắp tới, một số lượng lớn sinh viên đăng bài hỏi trên các hội nhóm về bộ câu hỏi ôn tập hoặc độ tin cậy của bộ câu hỏi có sẵn. |
| 2 |Lặp lại |Khi quyết định làm flashcard, tôi muốn hệ thống tạo thành các câu hỏi và đưa vào các thẻ để tôi không phải tốn thời gian thao tác Copy-Paste hàng trăm lần. |Những sinh viên chăm chỉ hoặc giảng viên môn học. |Mất hàng giờ đồng hồ chỉ để thực hiện thao tác (Ctrl+C, Ctrl+V) trên các hệ thống tạo flashcard như Quizle |
| 3 | Tốn thời gian|Tôi muốn hệ thống tạo ra các câu hỏi trắc nghiệm bao quát đủ các ý chính để tôi có thể học thuộc nhanh thông qua việc làm bài tập thay vì đọc slide.".| Sinh viên không có nhiều thời gian|Thường diễn ra vào 3-7 ngày trước kỳ thi. Sinh viên phải dành rất nhiều giờ chỉ để đọc hết 1 lượt slide hoặc tài liệu dài vài trăm trang. |
| 4 | Tốn thời gian| Khi sử dụng một bộ Quizlet do khóa trước để lại, tôi muốn biết chắc chắn nó chưa bị lỗi thời để không mất điểm vì chương trình học đã cập nhật giáo trình mới.| Sinh viên sử dụng tài liệu có sẵn trên mạng|Mất 3-5 phút cho mỗi câu hỏi nghi ngờ để mở file gốc ra dò lại mục tương ứng. Gây đứt đoạn mạch học tập. |
| 5 | Cần đọc, tổng hợp thông tin| Khi gặp các định nghĩa trên slide, tôi muốn ví dụ thực tế hoặc tình huống vận dụng để  làm được các câu hỏi vận dụng cao.| Toàn bộ sinh viên|Đề thi thực tế thường có 20-30% là câu hỏi tình huống chứ không hỏi định nghĩa thuần. Khó kết nối kiến thức vì slide phân bổ rải rác. |
| 6 |Pain từ người khác | Khi đi thi, tôi muốn đã được làm quen trước với các "câu hỏi bẫy", phương án nhiễu để không bị mất điểm bởi những câu hỏi mẹo của giảng viên ra đề.| Sinh viên cần thành tích cao|Sinh viên thường làm sai thậm chí bị trừ điểm vì những câu hỏi mẹo, ảnh hưởng đến kết quả và có tỉ lệ bị học lại môn do không đủ điểm yêu cầu. |


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tạo bộ MCQ bám sát tài liệu (#1)| Nhu cầu cốt lõi và phổ biến nhất của sinh viên. Volume thị trường lớn.|AI xử lý các định dạng file phức tạp (PDF scan, hình ảnh chứa công thức) tốt đến mức nào? |
| 2 |Học vội qua bài test tổng hợp (#3) | Đánh trúng nỗi đau thực tế cực lớn (cramming trước thi). Giá trị nhận được (thời gian) có thể đo lường ngay lập tức.|AI có khả năng trích xuất bao quát đúng 100% trọng tâm mà không bị sót ý quan trọng không? |
| 3 | Luyện câu hỏi bẫy/nhiễu (#6)| Tạo lợi thế khác biệt hoàn toàn, đánh mạnh vào tâm lý sợ mất điểm, dễ thuyết phục user trả phí.| AI có đủ tinh tế để tạo ra các phương án nhiễu logic như một giảng viên thật ra đề hay không?|

### Problem Card #1 - Tạo bộ câu hỏi ôn tập bám sát tài liệu

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu ôn thi, từ tài liệu sẵn có, tôi muốn có bộ câu hỏi trắc nghiệm bám sát nội dung để tự đánh giá năng lực và an tâm ôn tập. |
| Actor |Sinh viên đại học đang trong giai đoạn ôn thi. |
| Thời điểm / bối cảnh |1-2 tuần trước kỳ thi, khi sinh viên bắt đầu tổng hợp tài liệu. |
| Quy trình hiện tại (3–7 bước) |1. Đọc lướt tài liệu - 2. Lên group xin đề cũ - 3. Chờ đợi người gửi - 4. Lọc xem đề nào còn phù hợp giáo trình - 5. Tự làm và mò mẫm dò lại đáp án. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, 3, 4 (Tìm kiếm và lọc đề): Mất từ vài giờ đến vài ngày chờ đợi nhưng không đảm bảo chất lượng.|
| Impact (nếu không giải thì sao) |Mất nhiều thời gian tìm kiếm thay vì thực sự học; tâm lý bất an vì đề trôi nổi. |
| Success metric (baseline → target) |Thời gian để có bộ đề 50 câu (kèm đáp án và giải thích) giảm từ vài giờ/ngày xuống dưới 3 phút. |
| Phương án không dùng AI | Mua đề cương từ các bên cung cấp. |
| Giả thuyết về AI (nếu có) | AI đọc hiểu nội dung file PDF/Word/Slide, trích xuất ý chính và tự động sinh ra bộ MCQ đúng trọng tâm, kèm giải thích vị trí kiến thức.|
| Cảm nhận nhanh | Bị phụ thuộc hoàn toàn vào sự trợ giúp của người khác (xin đề) khiến quá trình ôn thi bị đình trệ. |

Quy trình nháp hiện tại:

```
HIỆN TẠI — Vài giờ đến 1-2 ngày
[1 Đọc tài liệu: 30'] - [2 Lên group xin đề: 15'] - [3 Chờ đợi: 1-2 ngày] - BOTTLENECK - [4 Lọc đề: 45'] - [5 Làm & dò đáp án: 60']
```

### Problem Card #2 - Học vội bằng bài test bao quát ý chính

| Trường | Nội dung |
|---|---|
| Job Story | Khi cầm slide hàng trăm trang, tôi muốn tạo ngay một bài test bao quát các ý chính để học thuộc qua việc làm đề thay vì đọc chữ dàn trải. |
| Actor |Sinh viên đến sát ngày thi mới ôn, thiếu thời gian ôn tập. |
| Thời điểm / bối cảnh |3-7 ngày trước kỳ thi, đối mặt với khối lượng slide khổng lồ chưa từng đọc. |
| Quy trình hiện tại (3–7 bước) | 1. Mở slide - 2. Đọc từ đầu đến cuối thụ động - 3. Cố highlight - 4. Gấp sách lại quên sạch - 5. Tìm bừa đề trên mạng để làm.|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 4: Đọc thụ động tốn quá nhiều thời gian nhưng độ lưu giữ thông tin cực thấp.|
| Impact (nếu không giải thì sao) | Mất nhiều giờ đọc vẹt, kiệt sức nhưng kết quả thi vẫn thấp vì không nhớ được trọng tâm cốt lõi.|
| Success metric (baseline → target) |Sinh viên hoàn thành 1 bài test 30 câu bao phủ 80% ý chính của slide trong 30 phút và nhớ được bài ngay. |
| Phương án không dùng AI |Nhờ bạn bè học giỏi tóm tắt hộ hoặc mua tài liệu tóm tắt vắn tắt. |
| Giả thuyết về AI (nếu có) | AI chia nhỏ tài liệu, học cuốn chiếu (Tóm tắt 1 đoạn ngắn -> Test 3 câu ngay -> Đúng thì đi tiếp, sai thì giải thích). |
| Cảm nhận nhanh | Việc nạp kiến thức một chiều quá tốn sức nhưng hiệu quả ghi nhớ lại bằng 0, cần chuyển sang cơ chế vừa học vừa test. |

Quy trình nháp hiện tại:

```
HIỆN TẠI — > 3 tiếng
[1 Mở slide: 2'] - [2 Đọc thụ động: 120']  - [3 Highlight: 30'] - [4 Quên/Học lại: 60']
```

### Problem Card #3 - Luyện câu hỏi bẫy / phương án nhiễu

| Trường | Nội dung |
|---|---|
| Job Story | Khi luyện đề, tôi muốn làm quen trước với các câu hỏi bẫy và phương án nhiễu (distractors) để luyện phản xạ, không mất điểm oan. |
| Actor | Sinh viên mục tiêu điểm cao.|
| Thời điểm / bối cảnh | Giai đoạn luyện đề nước rút, tổng duyệt kiến thức (1-2 ngày trước thi).|
| Quy trình hiện tại (3–7 bước) | 1. Làm đề thi thử - 2. Tự gạch chân các từ khóa nhạy cảm - 3. Đi thi thật vẫn dính bẫy vì giảng viên đổi 1 chữ - 4. Xem điểm, nuối tiếc.|
| Bottleneck (bước nào, mất bao nhiêu phút) |Không có môi trường hay tài nguyên nào để luyện câu hỏi mẹo một cách có chủ đích trước khi thi thật. |
| Impact (nếu không giải thì sao) |Đánh mất 1-2 điểm oan uổng, tuột mất mục tiêu do sai sót mặt chữ hoặc bẫy logic. |
| Success metric (baseline → target) | Tỉ lệ sai của sinh viên khi làm bài thi giảm.|
| Phương án không dùng AI | Tự trao đổi với nhóm học tập, nhờ các anh chị khóa trước truyền đạt lại phương pháp ra đề của từng thầy cô.|
| Giả thuyết về AI (nếu có) | Khi sinh MCQ, AI được prompt đặc biệt để chủ động thiết kế 3 phương án nhiễu cực kỳ tinh vi (sai 1 chữ, sai ngữ cảnh nhỏ) và cung cấp phần "Giải thích lý do " khi user chọn sai.|
| Cảm nhận nhanh | Không có bước test ngừa rủi ro, hậu quả chỉ được nhận ra khi đã thi xong. |

Quy trình nháp hiện tại:

```
HIỆN TẠI — Hậu quả xảy ra sau thi
[1 Làm đề bình thường] - [2 Đi thi: dính bẫy] - [3 Xem điểm: Nuối tiếc]
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: Đánh trúng tập người dùng đông đảo (sinh viên ôn sát ngày thi) với nỗi đau lớn nhất và thường xuyên nhất (quá tải thông tin). Giải pháp tạo bài test tổng hợp giúp đổi phương pháp từ "đọc thụ động" sang "chủ động recall", mang lại giá trị có thể thấy được ngay lập tức (tiết kiệm thời gian, thuộc bài tại chỗ) và rất dễ demo thực tế.
- Câu hỏi muốn nhóm phản biện: Làm sao để đảm bảo AI quét và trích xuất đủ 80% ý chính mà không bỏ sót những trọng tâm ẩn trong các file slide dài 100-200 trang?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|1. Về Card #2 (Sai lầm sư phạm): Sinh viên chưa từng đọc slide mà lao vào làm ngay 1 bài test 30 câu sẽ dẫn đến việc đánh lụi 100%, gây nản chí thay vì ghi nhớ. Phương pháp "Active Recall" (làm test) chỉ hiệu quả khi não bộ đã được nạp sơ bộ. |Đồng ý |Sửa Giả thuyết AI & Trải nghiệm: Thay vì tạo 1 bài test 30 câu ngay lập tức, AI sẽ chia slide thành các cụm nhỏ. Trải nghiệm mới: AI tóm tắt 1 đoạn (dài 3 dòng) -> Test 3 câu ngay lập tức -> Đúng thì qua đoạn tiếp, Sai thì giải thích. Học cuốn chiếu. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Trình bày ý tưởng |Nhóm cân nhắc lựa chọn ý tưởng |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Do khả năng sắp xếp tài liệu, lộ trình ôn tập chưa tốt hay thực sự chương trình dạy có thứ tự không hợp lý ? |Nhóm quyết định bỏ ý tưởng này |
| Nhận phản biện | Câu hỏi tôi nhận được: Làm sao để đảm bảo chất lượng câu hỏi AI tạo ra ?| Tôi đã sửa gì: |
| Gom cluster / cây OST |Đóng góp ý kiến xây dựng và chỉnh sửa |Nhóm đã chốt phương án cuối cùng |
| Chọn candidate problem |Thảo luận chấm điểm shorlist và lựa chọn Candidate |Nhóm quyết định lựa chọn Candidate #7 |
| Kiểm chứng / research |Tham gia đóng góp ý kiến |Nhóm chốt phương án và hoàn thành sau thảo luận |
| Quy trình nhóm |Tham gia đóng góp ý kiến |Nhóm chốt phương án và hoàn thành sau thảo luận |
| Problem Statement |Nhận ý kiến và góp ý của thành viên nhóm để hoàn thành |Hoàn thành Problem Statement |
| Mức can thiệp AI |Tham gia đóng góp ý kiến |Nhóm hoàn thành CP6 |
| Quyết định |Góp ý để đưa ra quyết định cuối |Nhóm đưa ra quyết định cuối cùng |

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
