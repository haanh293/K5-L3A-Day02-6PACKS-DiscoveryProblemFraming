# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Đức 
- MSSV: 2A202603644
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 6PACKS 
- Link repo nhóm: https://github.com/haanh293/K5-L3A-Day02-6PACKS-DiscoveryProblemFraming/blob/main/docs/01-worksheet.md

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại · Tốn thời gia |Khi có bảng dữ liệu mới về (có null, sai định dạng, ngoại lai), tôi muốn bảo đảm dữ liệu đạt chuẩn trước khi dùng, để báo cáo phía sau không sai. |Data/analytics engineer (người viết test), người dùng báo cáo (nhận số sai) |Hàng trăm test dbt viết tay (chưa kiểm chứng) · Thời gian: [giờ/tuần] · Tần suất: [mỗi bảng mới?] · Số người: [bao nhiêu người trong đội] · Bằng chứng: [repo, ticket, hoặc lời kể của ai] |
| 2 |Tốn thời gian · Pain từ người khác |Khi cần theo dõi KPI để ra quyết định, tôi muốn thấy số liệu theo khu vực/quý ngay, để không phải chờ nhiều ngày. |Lãnh đạo (người chờ), team BI (người nhận yêu cầu dồn dập) |Chờ “vài ngày” (chưa kiểm chứng) · Thời gian: [từ lúc yêu cầu đến lúc nhận] · Tần suất: [yêu cầu/tuần] · Số người: [bao nhiêu người BI, bao nhiêu người yêu cầu] · Bằng chứng: [ai kể, yêu cầu gần nhất] |
| 3 |Lặp lại · Tốn thời gian · Cần đọc, tổng hợp nhiều thông tin |Khi nhận hàng trăm CV cho một vị trí, tôi muốn nhanh chóng biết ai khớp với JD, để chỉ phải phỏng vấn người phù hợp. |Recruiter, ứng viên (bị đánh giá thiếu nhất quán), hiring manager |Hàng trăm CV/vị trí (chưa kiểm chứng) · Thời gian: [phút/CV] · Tần suất: [vị trí/tháng] · Số người: [số recruiter] · Bằng chứng: [hỏi một recruiter] |
| 4 |Lặp lại · Tốn thời gian · Cần đọc, tổng hợp nhiều thông tin |Khi thấy một JD thực tập phù hợp, tôi muốn nhanh chóng điều chỉnh CV theo yêu cầu và nắm trạng thái các đơn đã nộp, để không bỏ lỡ cơ hội. |Sinh viên đang xin thực tập |Thời gian: [phút/lần chỉnh CV] · Tần suất: [số đơn/tuần] · Số người: [bạn cùng lớp có gặp không] · Bằng chứng: [bảng theo dõi đơn của bạn, tin nhắn hỏi bạn bè] |
| 5 |Lặp lại · Tốn thời gian · Cần đọc, tổng hợp nhiều thông tin |Khi chuẩn bị buổi dạy kèm, tôi muốn có bài tập đúng điểm yếu của học sinh và biết các lỗi sai lặp lại, để buổi học hiệu quả hơn. |Gia sư, học sinh, phụ huynh |Thời gian: [phút soạn + chấm/buổi] · Tần suất: [buổi/tuần] · Số người: [bao nhiêu học sinh, gia sư khác bạn biết] · Bằng chứng: [đề đã soạn, ghi chú lỗi sai] |
| 6 |Lặp lại · Tốn thời gian · Cần đọc, tổng hợp nhiều thông tin · Pain từ người khác |Khi gần kỳ thi với tài liệu rải rác, tôi muốn gom lại và biết mình yếu chủ đề nào, để ôn đúng trọng tâm. |Sinh viên cần ôn nhiều môn |Thời gian: [giờ/tuần cho việc tổng hợp] · Tần suất: [mỗi kỳ thi] · Số người: [hỏi 5–10 bạn] · Bằng chứng: [khảo sát nhanh, ảnh ghi chú] |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Viết test chất lượng dữ liệu bằng tay |Tiềm năng AI: Rất phù hợp để ứng dụng LLM tự động generate dbt tests từ schema, hoặc dùng ML (Anomaly Detection) để phát hiện data drift mà không cần hard-code rule. Impact: Giải quyết nút thắt cổ chai lớn trong Data Pipeline của doanh nghiệp. |Tần suất thực sự phải viết test mới là bao nhiêu (có đủ lớn để cần AI không, hay chỉ cần setup rule 1 lần là xong)?Rủi ro AI sinh ra test sai (hallucination) khiến Data Engineer phải tốn thêm thời gian verify ngược lại?Mức độ phức tạp của business rules thực tế tại các công ty so với khả năng của AI. |
| 2 |Soạn đề và chấm bài cho học sinh kèm |Tiềm năng AI: Ứng dụng RAG/GenAI để trích xuất điểm yếu và sinh ra đề bài cá nhân hóa (Personalized Learning) là một Use Case rất "đẹp" để làm demo Độ khả thi: Scope bài toán vừa vặn, kiểm soát được rủi ro. |- LLM hiện nay (ngay cả các model lớn) thỉnh thoảng vẫn tính toán/giải Toán sai. Làm sao để đảm bảo đề bài AI sinh ra là chính xác 100%?Thời gian Review lại đề do AI soạn có khi còn lâu hơn tự nhặt đề có sẵn? iệu phụ huynh/học sinh có chấp nhận việc học từ tài liệu do AI tổng hợp? |
| 3 |Chỉnh CV và theo dõi đơn thực tập |Lượng User dồi dào: Rất dễ lấy feedback và kiểm chứng thông qua mạng lưới bạn bè. Tiềm năng AI: Khả năng NLP của LLM cực kỳ phù hợp để đối chiếu (matching) giữa JD và CV, trích xuất từ khóa, và tự động viết lại (rewrite) bullet point sao cho khớp ngữ cảnh. |Liệu sinh viên có thực sự chăm chỉ "tay bo" sửa CV cho từng JD không, hay họ có xu hướng rải 1 CV chung cho nhàn (tức là Pain-point có đủ lớn để họ dùng tool không)? Rủi ro AI "over-optimize" CV khiến ứng viên qua được vòng CV nhưng rớt ngay vòng phỏng vấn vì không đúng năng lực thật. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi có bảng dữ liệu mới về (có null, sai định dạng, ngoại lai), tôi muốn có bộ test chất lượng chạy được ngay, để lỗi dữ liệu không lọt vào báo cáo phía sau. |
| Actor |Data/analytics engineer; người dùng báo cáo chịu ảnh hưởng gián tiếp (nhận số sai) |
| Thời điểm / bối cảnh |Mỗi khi onboard bảng/nguồn dữ liệu mới, hoặc khi schema và business rule thay  |
| Quy trình hiện tại (3–7 bước) |1) Nhận bảng mới 2) Khảo sát dữ liệu (null, định dạng, ngoại lai) 3) Viết test dbt bằng tay (unique, not_null, range, format, freshness) 4) Chạy test 5) Sửa test sai/quá nhạy 6) Xử lý lỗi dữ liệu khi test fail |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 2–3: viết hàng trăm test thủ công (chưa kiểm chứng). Mất [điền] phút/bản |
| Impact (nếu không giải thì sao) |Tốn giờ kỹ sư vào việc lặp lại; cột thiếu test nên lỗi lọt và chỉ phát hiện khi người dùng báo |
| Success metric (baseline → target) |Giờ viết test/bảng: [điền] → giảm ví dụ 50%. % cột có test: [điền] → tăng. Số lỗi phát hiện muộn/tháng: [điền] → giảm |
| Phương án không dùng AI |Template test chuẩn theo loại cột; macro/package dbt (dbt_utils, dbt_expectations); sinh test từ schema bằng script |
| Giả thuyết về AI (nếu có) |LLM đọc schema + mẫu dữ liệu để đề xuất test, còn data steward duyệt trước khi áp dụng. Rủi ro: test sai buộc phải verify ngược |
| Cảm nhận nhanh | Rule → Workflow (Rule/template có thể đã giải quyết phần lớn; AI chỉ đáng dùng cho phần rule đặc thù theo nghiệp vụ) |

Quy trình nháp hiện tại:

```text
Nhận bảng mới -> Khảo sát dữ liệu (null/định dạng/ngoại lai) -> Viết test dbt bằng tay
-> Chạy test -> Sửa test sai/quá nhạy -> Xử lý lỗi dữ liệu khi test fail
   (nghẽn ở bước 2-3: lặp lại cho từng bảng, từng cột)
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị buổi dạy kèm Toán, tôi muốn có bài tập đúng điểm yếu của học sinh và biết lỗi sai nào lặp lại, để buổi học tập trung đúng chỗ. |
| Actor |Gia sư (người làm), học sinh; phụ huynh chịu ảnh hưởng gián tiếp |
| Thời điểm / bối cảnh |Trước mỗi buổi dạy (soạn đề) và sau mỗi bài kiểm tra/bài tập (chấm, ghi lỗi) |
| Quy trình hiện tại (3–7 bước) |1) Nhớ/xem lại lỗi sai buổi trước 2) Tìm bài trong sách/đề có sẵn 3) Chọn/sửa bài cho vừa trình độ 4) In hoặc gửi đề 5) Chấm bài 6) Ghi chú lỗi sai để buổi sau dùng |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 2–3 (tìm và chọn bài đúng điểm yếu) và bước 6 (tổng hợp lỗi lặp lại). Mất [điền] phút soạn + [điền] phút chấm/buổi |
| Impact (nếu không giải thì sao) |Đề không sát điểm yếu nên học sinh tiến bộ chậm; lỗi sai lặp lại không được phát hiện; gia sư mất thời gian ngoài giờ dạy |
| Success metric (baseline → target) |Phút chuẩn bị/buổi: [điền] → giảm ví dụ 30%. Tỷ lệ lỗi lặp lại giữa các buổi: [điền] → giảm. Tỷ lệ bài đề xuất đúng không cần sửa: [điền] → mục tiêu ca |
| Phương án không dùng AI |Sổ/Excel ghi lỗi sai theo chủ đề; ngân hàng đề phân loại theo dạng bài và mức độ; chọn đề từ nguồn có đáp án sẵn |
| Giả thuyết về AI (nếu có) |AI tổng hợp lỗi sai theo chủ đề và gợi ý dạng bài cần luyện; việc chọn/duyệt đề vẫn do gia sư. Rủi ro lớn nhất: AI giải/ra đề Toán sai |
| Cảm nhận nhanh | Workflow (có bước cố định, AI hỗ trợ một phần; gia sư kiểm tra đáp án, nên tránh để AI tự sinh đề mà không soát) |

Quy trình nháp hiện tại:

```text
Xem lại lỗi buổi trước -> Tìm bài trong sách/đề -> Chọn/sửa cho vừa trình độ
-> Gửi/in đề -> Chấm bài -> Ghi chú lỗi sai cho buổi sau
   (nghẽn ở bước 2-3 và 6)
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi thấy một JD thực tập phù hợp, tôi muốn nhanh chóng chỉnh CV cho khớp yêu cầu và nắm trạng thái các đơn đã nộp, để không bỏ lỡ cơ hội. |
| Actor |Sinh viên đang xin thực tập |
| Thời điểm / bối cảnh |Mỗi lần nộp đơn mới, và khi theo dõi kết quả/hạn nộp các đơn đã gửi |
| Quy trình hiện tại (3–7 bước) |1) Tìm JD 2) Đọc JD, xác định kỹ năng yêu cầu 3) Đối chiếu với CV hiện có 4) Sửa CV (bullet, từ khóa) 5) Nộp đơn 6) Ghi trạng thái vào Excel/Notion 7) Nhớ hạn và theo dõi phản hồi |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 2–4 (đọc JD, đối chiếu, sửa CV) và bước 6–7 (theo dõi thủ công). Mất [điền] phút/đơn |
| Impact (nếu không giải thì sao) |Hoặc rải một CV chung (khớp kém), hoặc tốn nhiều giờ chỉnh từng đơn; dễ quên hạn/trạng thái |
| Success metric (baseline → target) |Phút chỉnh CV/đơn: [điền] → giảm ví dụ 50%. Số đơn quá hạn/bỏ sót: [điền] → 0. Tỷ lệ có phản hồi: [điền] (cần theo dõi) |
| Phương án không dùng AI |CV có phần “master” + checklist từ khóa theo vị trí; bảng theo dõi đơn có nhắc hạn (Notion/Sheets) |
| Giả thuyết về AI (nếu có) |LLM đối chiếu JD với CV, gợi ý từ khóa và cách viết lại bullet; người dùng duyệt để không phóng đại năng lực. Rủi ro: CV “tối ưu quá” không khớp năng lực thật |
| Cảm nhận nhanh | Workflow (các bước cố định, AI hỗ trợ đối chiếu/viết lại; người quyết định nội dung cuối) |

Quy trình nháp hiện tại:

```text
Tìm JD -> Đọc JD, xác định kỹ năng -> Đối chiếu với CV -> Sửa CV -> Nộp đơn
-> Ghi trạng thái (Excel/Notion) -> Theo dõi hạn và phản hồi
   (nghẽn ở bước 2-4 và 6-7)
```

### Card muốn pitch nhất

- Card số: 1. Viết test chất lượng dữ liệu bằng tay
- Vì sao:
1. Đây là việc lặp lại theo từng bảng, từng cột, nên dễ đo bằng số: giờ viết test/bảng,
     % cột có test, số lỗi phát hiện muộn.
  2. Bài toán có ranh giới rõ nên phân loại được mức can thiệp: phần nào Rule/template
     giải quyết được, phần nào mới cần AI (rule đặc thù theo nghiệp vụ). Vì vậy
     kết luận Go / Not Yet / No-Go sẽ có lập luận cụ thể.
  3. Người dùng AI có thể kiểm soát rủi ro: AI chỉ đề xuất test, người duyệt trước
     khi áp dụng, nên hallucination không đi thẳng vào production.
  4. Tôi sẵn sàng đóng vai người kiểm chứng kỹ thuật cho nhóm và tìm người làm
     dbt/data để phỏng vấn
- Câu hỏi muốn nhóm phản biện:
1. Nhóm không ai làm data: nhóm thấy mình có kiểm chứng được vấn đề này không,
     hay nên chọn card 3 (dễ phỏng vấn bạn bè) để có bằng chứng chắc hơn?
  2. Nếu template/dbt_utils/dbt_expectations đã giải quyết phần lớn, AI còn đáng
     làm không? Nhóm thấy kết luận "No AI / Rule" có thuyết phục không?
  3. Chi phí verify test do AI sinh ra có lớn hơn chi phí tự viết không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

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
