# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Hà Anh
- MSSV: 2A202603605
- Email trường (không bắt buộc, repo có thể để public): 26ai.anhnh7@vinuni.edu.vn
- Tên nhóm: 6PACKS
- Link repo nhóm: https://github.com/haanh293/K5-L3A-Day02-6PACKS-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Tốn thời gian, Lặp lại |Khi ứng tuyển các vị trí phần mềm, tôi muốn điều chỉnh nội dung CV gốc cho khớp với từ khóa JD nhanh chóng để nộp được nhiều công ty mà không bị vỡ layout 1 trang. |Sinh viên IT năm cuối, ứng viên xin việc |Mất 30–45 phút mỗi lần chỉ để căn lề, chỉnh font size thủ công khi xóa/thêm 1 dòng; trung bình nộp 5-10 CV/tuần. |
| 2 |Lặp lại, Cần tổng hợp |Khi tinh chỉnh mô hình phân loại Machine Learning, tôi muốn tự động lưu lại các chỉ số đánh giá và tham số chạy để so sánh kết quả mà không sợ copy/dán nhầm cột. | Sinh viên nghiên cứu, Kỹ sư ML|Mất 5 phút copy log terminal sau mỗi epoch; thường xuyên quên tham số cũ dẫn đến phải re-train mô hình (mất hàng giờ). |
| 3 |Pain từ người khác |Khi Backend có sự thay đổi schema DB hoặc API, tôi muốn nhận được thông báo cấu trúc chi tiết để cập nhật Model trên app mà không làm crash ứng dụng. | Mobile Developer, Frontend Developer|App bị crash 1-2 lần/tuần do lỗi parse JSON (ví dụ đổi Int sang String), tốn 2-3 tiếng debug mông lung mỗi lần. |
| 4 |Tốn thời gian, Lặp lại |Khi có bản patch game FPS hoặc driver đồ họa mới, tôi muốn tự động thiết lập lại thông số NIS và crosshair tối ưu để duy trì FPS ổn định mà không phải test lại từ đầu. |Game thủ chơi PC (Valorant, CS2) |Tốn 20–30 phút vào Custom Match test lại thông số mỗi khi game cập nhật (1-2 lần/tháng). |
| 5 |Cần tổng hợp nhiều thông tin |Khi xem các franchise anime/phim phức tạp, tôi muốn tra cứu một lộ trình xem chuẩn để hiểu đúng cốt truyện mà không đọc trúng các bình luận tiết lộ nội dung (spoiler). |Người xem anime, người hâm mộ phim |Mất 15-20 phút lướt các Wiki, Reddit; tỷ lệ vô tình đọc trúng spoiler rủi ro rất cao (khoảng 50%). |
| 6 |Tốn thời gian |Khi nấu các món nước truyền thống cho 1 người ăn (như bún mọc), tôi muốn định lượng chính xác nguyên liệu tươi để không bị lãng phí thực phẩm vào cuối tuần. | Sinh viên sống một mình, người đi làm|Thường xuyên mua nguyên liệu đóng khay dư thừa; hàng tuần đều phải vứt bỏ rau củ hoặc thịt không dùng hết. |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Tinh chỉnh CV ATS-compliant |Xảy ra thường xuyên với sinh viên IT năm cuối; tốn thời gian cơ học vô ích (chỉnh margin/font). |Liệu việc dùng tool format có làm mất đi tính cá nhân hóa hoặc làm sai lệch từ khóa so với JD không? |
| 2 |Tracking log kết quả Machine Learning |Ảnh hưởng trực tiếp đến hiệu suất nghiên cứu; rủi ro mất mát dữ liệu do lỗi con người rất cao. |Mức độ đa dạng của các framework (PyTorch, TF, Scikit-learn) có gây khó khăn cho một giải pháp chuẩn hóa không? |
| 3 |Đồng bộ API Contract Backend - Mobile | Gây gián đoạn tiến độ nhóm nghiêm trọng (crash app); là vấn đề muôn thuở trong làm việc nhóm.|Liệu team có chịu đổi thói quen báo miệng sang dùng tool/quy trình mới không? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi ứng tuyển vị trí phần mềm, tôi muốn chỉnh sửa CV cho khớp JD nhanh chóng để nộp nhiều công ty mà không bị vỡ layout 1 trang. |
| Actor |Sinh viên IT năm cuối / Ứng viên xin việc |
| Thời điểm / bối cảnh |Khi tìm thấy một JD phù hợp và bắt đầu chuẩn bị hồ sơ nộp. |
| Quy trình hiện tại (3–7 bước) |1. Đọc JD $\rightarrow$ 2. Mở file Master CV $\rightarrow$ 3. Thêm/bớt keyword $\rightarrow$ 4. Chỉnh sửa thủ công margin/spacing để vừa 1 trang $\rightarrow$ 5. Xuất PDF. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước chỉnh sửa thủ công margin/spacing (mất 30 - 45 phút/CV do nội dung bị đẩy sang trang 2). |
| Impact (nếu không giải thì sao) |Mất cơ hội nộp sớm, nộp được ít công ty hơn, sinh ra tâm lý lười tinh chỉnh CV dẫn đến tỷ lệ rớt ATS cao. |
| Success metric (baseline → target) |Thời gian format layout: 30 phút $\rightarrow$ dưới 5 phút. |
| Phương án không dùng AI |Tạo template chuẩn trên Markdown/LaTeX, chỉ cần thay đổi text, layout tự render lại theo CSS/cấu hình định sẵn. |
| Giả thuyết về AI (nếu có) |AI (Agent) có thể đọc JD, tự trích xuất keyword, tự động map vào các bullet point kinh nghiệm và xuất PDF đúng chuẩn. |
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
[Đọc Job Description] (5 phút)
-> [Copy Master CV thành bản mới & Sửa keyword] (10 phút)
-> [BOTTLENECK: Chỉnh sửa thủ công margin, spacing, font size để không bị tràn 2 trang] (30 - 45 phút)-> [Xuất PDF và Nộp] (2 phút)
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story |Khi chạy nhiều thực nghiệm ML, tôi muốn lưu kết quả và tham số tự động để so sánh dễ dàng mà không sợ ghi nhầm. |
| Actor |Sinh viên nghiên cứu / Kỹ sư Machine Learning |
| Thời điểm / bối cảnh |Giai đoạn tinh chỉnh hyperparameter, chạy vòng lặp train-test liên tục. |
| Quy trình hiện tại (3–7 bước) |1. Đổi hyperparameter $\rightarrow$ 2. Chạy model $\rightarrow$ 3. Chờ log in ra terminal $\rightarrow$ 4. Copy kết quả $\rightarrow$ 5. Paste vào Google Sheets. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước Copy & Paste vào Sheets (mất ~5 phút mỗi lần, dễ quên ghi lại tham số của lần chạy đó). |
| Impact (nếu không giải thì sao) |Phải re-train mô hình từ đầu (tốn hàng giờ) do quên tham số tốt nhất; hoặc chọn sai model do dữ liệu tracking bị lệch dòng. |
| Success metric (baseline → target) |Số lần phải re-train do sai sót log: 1-2 lần/tuần $\rightarrow$ 0 lần/tuần. |
| Phương án không dùng AI |Viết một script Python đơn giản (Rule-based) hook vào hàm evaluation để tự động append dòng dữ liệu (params + metrics) vào file CSV sau mỗi epoch. |
| Giả thuyết về AI (nếu có) |Có thể dùng AI để tự động phân tích file CSV log, tìm ra xu hướng hội tụ và đề xuất bộ hyperparameter tối ưu cho lần chạy tiếp theo. |
| Cảm nhận nhanh |Rule |

Quy trình nháp hiện tại:

```text
[Thiết lập tham số mô hình] (2 phút)
-> [Chạy script & chờ in log ra terminal] (15 - 60 phút)
-> [BOTTLENECK: Mở Google Sheets và copy/paste thủ công kết quả kèm tham số] (5 phút) -> [So sánh các dòng để quyết định chạy tiếp] (3 phút)
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story |Khi làm việc nhóm, tôi muốn biết chính xác cấu trúc API thay đổi ra sao để cập nhật App mà không bị crash. |
| Actor |Mobile Developer / Frontend Developer |
| Thời điểm / bối cảnh |Khi Backend push tính năng mới hoặc sửa đổi cấu trúc Database. |
| Quy trình hiện tại (3–7 bước) |1. Backend đổi code -> 2. Báo qua nhóm chat -> 3. Mobile dev đọc tin -> 4. Sửa Model trên app -> 5. Test tích hợp. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước báo qua nhóm chat và Mobile dev tự dò lại code (thường báo thiếu/sai kiểu dữ liệu, tốn 2-3 tiếng debug khi tích hợp). |
| Impact (nếu không giải thì sao) |Crash ứng dụng liên tục trong giai đoạn ghép API, gây trễ tiến độ dự án (Sprint). |
| Success metric (baseline → target) |Thời gian debug lỗi parse JSON/Null pointer: 2-3 tiếng/tuần $\rightarrow$ dưới 30 phút/tuần. |
| Phương án không dùng AI |Áp dụng CI/CD Workflow: Tự động generate Swagger/OpenAPI docs mỗi khi code Backend thay đổi và bắn thông báo qua Webhook vào kênh Slack. |
| Giả thuyết về AI (nếu có) |AI (Workflow) nhận diện các file Controller thay đổi trên Git, tự động sinh mã nguồn DTO/Model tương ứng cho Android/iOS và tạo Pull Request. |
| Cảm nhận nhanh |Workflow |

Quy trình nháp hiện tại:

```text
[Backend sửa code DB/Controller & Push lên Repo] (30 phút)
$\rightarrow$ [Nhắn tin thông báo qua nhóm chat] (2 phút)
-> [Mobile Dev đọc tin & cập nhật DTO/Model bên App] (15 phút)
-> [BOTTLENECK: Test tích hợp, crash app do sai Data Type và phải dò lại code Backend để debug] (120 - 180 phút) 
->

### Card muốn pitch nhất

- Card số:
- Vì sao: #1 (Tinh chỉnh CV ATS-compliant)
- Câu hỏi Đây là "nỗi đau" cực kỳ phổ biến và cấp bách đối với sinh viên năm cuối. Nút thắt (bottleneck) rất rõ ràng và định lượng được (tốn 30-45 phút chỉ để chỉnh margin/font do tràn trang). Vấn đề này lặp đi lặp lại hàng tuần nhưng chưa có công cụ nào xử lý triệt để việc "khớp keyword + giữ nguyên layout 1 trang" một cách mượt mà. muốn nhóm phản biện:
 Liệu việc dùng tool/AI để tự động hóa cắt gọt và chèn từ khóa vào CV có khiến hồ sơ của chúng ta trở nên rập khuôn và mất đi tính cá nhân hóa trong mắt nhà tuyển dụng con người không?
### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |
Success metric chưa trọn vẹn: Chỉ đo lường "thời gian format layout giảm xuống" là chưa đủ. Format nhanh nhưng CV vẫn bị hệ thống ATS loại thì vấn đề lõi chưa được giải quyết.CóBổ sung thêm metric cốt lõi: "Tỷ lệ CV lọt qua vòng lọc của hệ thống ATS (được gọi phỏng vấn) tăng lên".
|Rủi ro niềm tin (Trust/Safety): Nếu AI tự động map keyword từ JD vào CV, ứng viên có thể nộp một bản CV phóng đại, chứa những kỹ năng họ không thực sự có.| Có|Bổ sung giới hạn (Boundary) vào giải pháp: AI chỉ được phép đối chiếu và gợi ý sắp xếp lại những kinh nghiệm đã có sẵn trong Master CV, tuyệt đối không tự bịa thêm dòng kinh nghiệm mới.. |---

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
