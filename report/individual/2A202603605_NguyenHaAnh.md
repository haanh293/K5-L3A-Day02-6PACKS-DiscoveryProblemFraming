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
```
### Card muốn pitch nhất

- Card số:#1 (Tinh chỉnh CV ATS-compliant)
- Vì sao: Đây là "nỗi đau" cực kỳ phổ biến và cấp bách đối với sinh viên năm cuối. Nút thắt (bottleneck) rất rõ ràng và định lượng được (tốn 30-45 phút chỉ để chỉnh margin/font do tràn trang). Vấn đề này lặp đi lặp lại hàng tuần nhưng chưa có công cụ nào xử lý triệt để việc "khớp keyword + giữ nguyên layout 1 trang" một cách mượt mà.
- Câu hỏi muốn nhóm phản biện:Liệu việc dùng tool/AI để tự động hóa cắt gọt và chèn từ khóa vào CV có khiến hồ sơ của chúng ta trở nên rập khuôn và mất đi tính cá nhân hóa trong mắt nhà tuyển dụng con người không?
 ### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Success metric chưa trọn vẹn: Chỉ đo lường "thời gian format layout giảm xuống" là chưa đủ. Format nhanh nhưng CV vẫn bị hệ thống ATS loại thì vấn đề lõi chưa được giải quyết. |Có |Bổ sung thêm metric cốt lõi: "Tỷ lệ CV lọt qua vòng lọc của hệ thống ATS (được gọi phỏng vấn) tăng lên". |

---
## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Card #1 (Chỉnh sửa CV ATS-compliant) và Card #2 (Tracking log ML) cho cả nhóm. | Đóng góp 2 candidate vào bảng pitch chung; Card #1 lọt vào shortlist chấm điểm (đạt 25 điểm). |
| Phản biện bài của bạn khác | Đặt câu hỏi cho bài #3 của Trần Xuân Trường (Release Notes): "GitHub đã có sẵn nút auto-generate release notes từ tên PR, tại sao vẫn cần công cụ riêng?"; Đặt câu hỏi cho bài #12 của Nguyễn Đức Trọng (Bài tập kèm Toán): "Thu thập dữ liệu nháp của học sinh bằng cách nào để AI biết đúng lỗi sai?" | Giúp nhóm nhận diện rằng một số bài toán đã có công cụ sẵn giải quyết phần lớn, cần phải xác minh rõ giá trị gia tăng thực sự trước khi chọn. |
| Nhận phản biện | Trọng hỏi bài #1 của tôi: "Tại sao không dùng chatbot có sẵn mà lại phải dùng sản phẩm này, sản phẩm có gì khác biệt?"; Trường hỏi bài #2: "Nếu giải pháp là đơn giản ghi log ra file CSV, có thực sự giải quyết được bài toán so sánh nhiều mô hình cùng lúc không?" | Tôi nhận ra Card #1 cần phải làm rõ sự khác biệt so với các chatbot thông thường. Card #2 thì bottleneck thực sự không chỉ ở ghi log mà ở việc so sánh trực quan giữa nhiều lần chạy. |
| Gom cluster / cây OST | Là người chính (theo phân công CP3), điều phối cả nhóm gom 12 candidate thành 4 cluster; viết cây Opportunity Solution Tree với 1 Outcome gốc và 3 Opportunity; gạch bỏ các thẻ mang tính solution. | Thống nhất Outcome chung: "Giảm 60% thời gian chuẩn bị câu hỏi ôn tập và tăng 40% hiệu quả ghi nhớ kiến thức trọng tâm trước kỳ thi." |
| Chọn candidate problem | Thiết lập bảng chấm điểm 7 tiêu chí cho shortlist 6 candidate; điều phối thảo luận so sánh giữa #7 và #11; viết lý do loại từng candidate. | Nhóm chọn Candidate #7 với 31 điểm cao nhất; giải quyết bất đồng giữa #7 và #11 bằng lập luận rằng #7 có sẵn tài liệu kiểm chứng ngay trong lab. |
| Kiểm chứng / research | Tham gia xây dựng Assumption Map (6 giả định); hỗ trợ phân tích kết quả phỏng vấn và log thử nghiệm ChatGPT trực tiếp trên 3 bộ slide. | Nhận ra bottleneck thật sự không phải tốc độ sinh câu hỏi mà là "lost in the middle" và thời gian dò lại đáp án; nhóm đã sửa lại Success Metric từ "dưới 3 phút" thành "dưới 8 phút" (bao gồm cả kiểm duyệt). |
| Quy trình nhóm | Hỗ trợ Hoàng Đăng Kiên hoàn thiện bảng Before/After; góp ý về phương án fallback khi AI sai (retry prompt, nút "Đổi câu khác"). | Đảm bảo quy trình tương lai có đầy đủ Boundary, phương án quay về và bước HITL. |
| Problem Statement | Hỗ trợ Nguyễn Đức Trọng viết Problem Statement v0 (theo phân công CP5); tham gia phản biện và hoàn thiện v1 — đặc biệt bổ sung trường Boundary về việc "AI không hiển thị đáp án ngay" để chống học vẹt. | Problem Statement v1 bổ sung thêm quy tắc chống "hiểu bài giả tạo" sau khi tiếp nhận phản biện từ AI. |
| Mức can thiệp AI | Tham gia phân tích ma trận mơ hồ × phức tạp; lập luận vì sao bài toán nằm ở ô "Mơ hồ cao – Phức tạp thấp" → phù hợp mức Workflow. | Nhóm thống nhất chọn Workflow (RAG + Structured Output) thay vì Agent, vì luồng xử lý tuyến tính và cần kiểm soát rủi ro ảo giác. |
| Quyết định | Là người chính (theo phân công CP6), điều phối cả nhóm đánh giá 4 rủi ro (Value / Usability / Feasibility / Viability); tổng hợp quyết định cuối cùng. | Nhóm quyết định "Not Yet" do rủi ro Viability cao (chi phí API quá lớn cho đối tượng sinh viên); đề xuất hướng thử nghiệm SLM local và semantic caching. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Sau khi tự scan 4 problem, tôi dùng AI gợi ý thêm ý tưởng từ các lăng kính còn thiếu. | Gợi ý thêm góc nhìn "Pain từ người khác" (vấn đề đồng bộ API Backend-Mobile) mà tôi chưa nghĩ tới. | AI gợi ý một số ý quá chung chung ("tạo chatbot hỗ trợ học tập", "ứng dụng AI quản lý thời gian") — là solution trá hình, không phải problem. | Loại bỏ tất cả gợi ý mang tính giải pháp; chỉ giữ lại những ý có quy trình cụ thể và dấu hiệu thật đo được. |
| CP2 Problem Card | Nhờ AI đóng vai "PM hoài nghi" phản biện Card #1 (CV ATS). | AI chỉ ra đúng điểm yếu: Success Metric chỉ đo thời gian format mà chưa đo tỷ lệ lọt qua ATS. | AI gợi ý thêm nhiều metric phụ không cần thiết (NPS score, retention rate) vượt xa phạm vi lab. | Chỉ bổ sung thêm 1 metric cốt lõi: "Tỷ lệ CV lọt qua vòng ATS tăng lên", bỏ qua các metric AI gợi ý quá phức tạp. |
| CP4 Research | Dùng AI tìm kiếm nhanh các công cụ tạo quiz từ tài liệu hiện có trên thị trường. | Liệt kê nhanh Quizlet, Quizgecko, NotebookLM và tính năng chính của từng tool. | Đánh giá quá tích cực về khả năng của các tool (nói Quizgecko "hỗ trợ đa ngôn ngữ tốt") mà thực tế khi thử trên slide tiếng Việt thì kết quả rất kém. | Tự trải nghiệm thực tế các tool và bổ sung nhận định về khoảng trống: thiếu grounding (trích dẫn số trang), không bám sát đề cương cụ thể của giảng viên. |
| CP5 Quy trình | Dùng AI hỗ trợ cấu trúc hóa bảng Before/After và kiểm tra tính nhất quán giữa quy trình hiện tại với quy trình tương lai. | Gợi ý bổ sung cột "Rủi ro mới phát sinh" vào bảng Before/After — rất hữu ích vì nhóm ban đầu chưa nghĩ tới. | AI tự ý thêm các bước phức tạp (tích hợp LMS, hệ thống thông báo tự động) vượt quá phạm vi lab. | Giữ quy trình tương lai đơn giản 5 bước tuyến tính; loại bỏ các bước "nice-to-have" AI thêm vào. |
| CP5–6 Problem Statement | Nhờ AI phản biện Problem Statement v0, tìm lỗ hổng logic. | AI phát hiện mâu thuẫn quan trọng: phần Impact nói cách học cũ gây "hiểu bài giả tạo" nhưng nếu AI cung cấp đáp án ngay thì vấn đề này còn tệ hơn. | AI đề xuất giải pháp quá cực đoan: "AI không bao giờ hiển thị đáp án, chỉ gợi ý". Thực tế sinh viên vẫn cần xem đáp án đúng sau khi đã tự trả lời. | Thiết kế luồng HITL hợp lý: sinh viên phải tự chọn đáp án trước → nếu sai thì nhận Hint (số trang slide) → sau đó mới hiện đáp án đầy đủ. |
| CP6 Mức can thiệp / quyết định | Dùng AI phân tích trade-off 4 mức can thiệp (No AI / Rule / Workflow / Agent) cho bài toán của nhóm. | Phân tích rõ ràng vì sao Rule không đủ (không hiểu ngữ cảnh để sinh câu hỏi tư duy) và Agent quá phức tạp (không cần AI tự quyết bước tiếp). | AI khuyên nên chọn Agent "để tạo trải nghiệm cá nhân hóa hoàn chỉnh cho sinh viên" — quá over-engineering cho phạm vi lab. | Nhóm kiên quyết giữ mức Workflow; bổ sung lập luận rõ ràng vì sao không cần Agent trong bảng so sánh 4 mức. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe các bạn trong nhóm pitch, tôi nhận ra rằng mỗi người nhìn thấy nỗi đau từ góc độ rất khác nhau dựa trên bối cảnh cá nhân,có bạn thấy vấn đề từ phía kỹ thuật (Release Notes, test data), trong khi có bạn lại nhìn thấy nỗi đau sát sườn hơn với đời sống sinh viên (ôn thi, tạo quiz). Bài học lớn nhất là một bài toán có quy trình rõ, actor cụ thể và dễ kiểm chứng ngay tại lớp sẽ luôn tốt hơn một bài toán nghe "kỹ thuật" nhưng khó tiếp cận người dùng thật.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm tôi không gặp phải vấn đề này vì trong giai đoạn CP3, mọi người đều thảo luận rõ về problems mà mỗi cá nhân đặt ra, mỗi thành viên đều lắng nghe và cùng nhau làm rõ vấn đề.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã đổi ý khi nhận phản biện Card #1 (Chỉnh sửa CV) của tôi: "Tại sao không dùng chatbot có sẵn mà lại phải dùng sản phẩm này?" Ban đầu tôi khá tự tin vì bottleneck 30–45 phút chỉnh margin rất rõ ràng. Nhưng câu hỏi phản biện khiến tôi phải thừa nhận rằng ranh giới giữa việc dùng một prompt ChatGPT thông thường với một sản phẩm chuyên biệt rất mờ nhạt, và impact khó kiểm chứng ngay trong lab. Điều này giúp tôi không bảo thủ bảo vệ bài mình và hoàn toàn đồng thuận khi nhóm chọn Candidate #7 thay vì bài của tôi.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Không

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất là tách bạch hoàn toàn giữa mô tả vấn đề và giải pháp. Ngoài ra, việc đặt Success Metric có baseline và target cụ thể cũng rất khó.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi nghĩ mình sẽ không thay đổi gì. Còn về phản biện, bản thân tôi thấy các thành viên đều rất tích cực đưa ra ý kiến của mình để có thể đi đến kết luận chung, thế nên tôi cảm thấy tôn trọng ý kiến và kết luận mà nhóm đã đặt ra.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài toán của nhóm xuất phát từ **problem**: sinh viên tốn rất nhiều thời gian (45 phút/chương) để tự soạn câu hỏi trắc nghiệm ôn thi từ slide bài giảng, và khi thử nhờ ChatGPT thì bị sót ý giữa bài (lost in the middle), đáp án nhiễu ngây ngô, phải mất thêm 15–25 phút tự Ctrl+F dò lại slide để kiểm chứng. 

**Quy trình hiện tại** có 6 bước thủ công từ đăng bài xin đề → chờ đợi → lọc đề → làm bài → dò đáp án, với bottleneck chính ở bước chờ đợi bị động (1–2 ngày) và bước lật slide dò đáp án (30 phút). 

**Metric** thành công: thời gian có bộ 20 câu hỏi giảm từ 45 phút xuống dưới 3 phút; thời gian dò đáp án giảm từ 30 phút xuống dưới 5 phút; tỷ lệ câu hỏi không bịa kiến thức đạt trên 95%. 

**Boundary**: AI tuyệt đối không được bịa kiến thức ngoài tài liệu (grounding), không hiển thị đáp án ngay mà buộc sinh viên tự chọn trước (HITL), và luôn đính kèm trích dẫn số trang slide. 

**Mức can thiệp** là Workflow (RAG + Structured Output JSON) — vì Rule không hiểu ngữ cảnh để sinh câu hỏi tư duy, còn Agent thì quá phức tạp cho luồng xử lý tuyến tính này. 

**Quyết định**: Not Yet — nhu cầu và kỹ thuật đều khả thi nhưng chi phí API quá lớn cho đối tượng sinh viên; cần thời gian nghiên cứu SLM local và semantic caching trước khi Go.

---

## 7. Tài liệu tham khảo


- Lean UX: Designing Great Products with Agile Teams (Jeff Gothelf & Josh Seiden).
- The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you (Rob Fitzpatrick).
- Opportunity Solution Tree Framework (Teresa Torres, Continuous Discovery Habits).
- Building Effective Agents & AI Workflows Guide (Anthropic, 2024).
- People + AI Guidebook (Google PAIR).
- Inspired & Empowered: Product Risk Framework (Marty Cagan, Silicon Valley Product Group).
