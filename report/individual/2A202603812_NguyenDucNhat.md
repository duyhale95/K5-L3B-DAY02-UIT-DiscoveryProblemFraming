# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Đức Nhật
- MSSV: 2A202603812
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: UIT
- Link repo nhóm: https://github.com/duyhale95/K5-L3B-Day02-UIT-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | lặp lại - cần đọc, tổng hợp nhiều thông tin |Vào cuối mỗi chu kỳ sprint 2 tuần hoặc ngay trước khi deploy bản vá lỗi/phiên bản mới lên môi trường Staging/Production | Tech Lead, QA, PM | Tốn 45–60 phút/lần release, tần suất 1–2 lần/tuần; trung bình 80–120 commits/sprint; từng xảy ra việc QA test sót tính năng do commit message viết tắt |
| 2 | lặp lại, tốn thời gian | Khi khách hàng đặt đơn online và chuyển khoản qua mã VietQR vào giờ cao điểm, tôi muốn đối chiếu tự động biến động số dư ngân hàng với mã đơn và số tiền trên bảng quản lý đơn hàng, để xác nhận thanh toán tức thì mà không làm gián đoạn việc đóng gói hàng hay bị lừa bởi ảnh chụp màn hình bill giả | Chủ shop online nhỏ, nhân viên trực page, thủ quỹ CLB sinh viên, các cửa hàng SME | Diễn ra 30–50 lần/ngày, mất 2–3 phút mở app ngân hàng và dò Google Sheet mỗi đơn |
| 3 | cần đọc, tốn thời gian | Khi bắt đầu làm khóa luận hoặc đồ án môn học cần khảo sát 20–30 bài báo khoa học tiếng Anh, tôi muốn trích xuất chuẩn xác mô hình, bộ dữ liệu, chỉ số đánh giá và hạn chế của từng bài vào một bảng so sánh chung, để nhanh chóng xác định hướng nghiên cứu mà không bị rối giữa hàng trăm trang tài liệu | Sinh viên năm 3–4 làm đồ án/khóa luận, nhóm nghiên cứu sinh | Mất 2–3 giờ đọc và ghi chép cho mỗi bài báo PDF dài 10–15 trang; tốn tổng cộng 40–60 giờ trong 3 tuần đầu đồ án; bảng Excel tổng hợp thường bị lệch cột chỉ số do mỗi bài báo trình bày kết quả một kiểu |
| 4 | lặp lại, pain từ người khác | Khi kết thúc buổi họp nhóm đồ án kéo dài 60–90 phút trên Google Meet/Discord, tôi muốn chuyển đổi toàn bộ nội dung thảo luận thành danh sách các quyết định đã chốt và bảng phân công nhiệm vụ, để các thành viên nắm rõ trách nhiệm và không bị trễ hạn hay đổ lỗi do quên việc | Nhóm trưởng môn học, các thành viên nhóm đồ án, Scrum Master | Họp định kỳ 2–3 lần/tuần, mất 30–40 phút sau mỗi cuộc họp để nghe lại ghi âm và gõ tóm tắt gửi lên Zalo; từng có 2 thành viên làm trùng task hoặc quên nộp bài vì tin nhắn phân công bị trôi |
| 5 | lặp lại, tốn thời gian | Khi phát triển giao diện mới hoặc kiểm thử API mà database thật chưa có dữ liệu, tôi muốn sinh nhanh bộ dữ liệu mẫu tuân thủ đúng ràng buộc khóa ngoại và bao gồm sẵn các trường hợp biên, để test luồng hiển thị ngay mà không phải ngồi gõ tay từng bản ghi giả lập | Lập trình viên Frontend, Backend, QA/Tester | Xuất hiện 2–3 lần mỗi sprint khi làm tính năng mới; tốn 1.5–2 giờ gõ tay và sửa lỗi cú pháp cho file JSON 50 bản ghi; dữ liệu tự gõ kiểu "test 1, test 2" thường làm sót lỗi tràn chữ trên giao diện thật |
| 6 | Tốn thời gian, lặp lại, cần đọc | Cuối mỗi kì kế toán, tôi phải trích xuất thủ công các tệp log dữ liệu từ hệ thống Gateway trụ xạc trung tâm. Tôi thu thập hóa đơn tiền điện thực tế theo chỉ số công tơ điện lực EVN của từng trạm và đối chiếu dữ liệu giao dịch thanh toán không tiền mặt từ ví điện tử/thẻ của khách hàng. Nhân viên kế toán sử dụng các bảng tính Excel nặng nề để so khớp chéo thủ công các nguồn dữ liệu này. Lập biên bản giải trình cho các phiên sạc lệch và đối chiếu thủ công với các đối tác chủ mặt bằng hoặc chủ trạm nhượng quyền trước khi tiến hành giải ngân | Account, Green SM | Thời gian đối soát 120 – 160 giờ/tháng Tiêu tốn tương đương 1 nhân sự toàn thời gian chỉ để lọc file Excel. Tỷ lệ sai lệch dữ liệu 1.5% – 2.5% doanh thu Gây treo công nợ, rò rỉ dòng tiền do các lỗi rớt mạng |
| 7 | Cần đọc, tổng hợp từ nhiều thông tin, pain từ người khác | Khi server hoặc môi trường staging bắn hàng trăm cảnh báo lỗi sau đợt cập nhật code, tôi muốn tự động gom cụm các dòng stack trace trùng lặp và chỉ ra commit/file vừa thay đổi có liên quan, để tìm ra nguyên nhân gốc và sửa lỗi nhanh trước khi ảnh hưởng đến người dùng | Lập trình viên Backend, DevOps, trực kỹ thuật | Mỗi khi có sự cố, log sinh ra 500–2.000 dòng/giờ; kỹ sư mất 30–60 phút dùng lệnh grep lọc log rác; cảnh báo lặp lại liên tục trên Slack làm cả nhóm bị quá tải thông báo |
| 8 | cần đọc, tốn thời gian | Khi nhận được yêu cầu hỗ trợ kỹ thuật hoặc khiếu nại từ khách hàng sạc xe điện bị trừ tiền nhưng trụ sạc báo lỗi ngắt kết nối giữa chừng, tôi muốn tra cứu tức thì trạng thái giao dịch ngân hàng/ví và log phiên sạc tại đúng thời điểm xảy ra sự cố trên một màn hình duy nhất, để xác minh và hoàn tiền/cấp bù mã sạc trong 5 phút thay vì phải chuyển ticket lòng vòng giữa CSKH, Kỹ thuật và Kế toán | Nhân viên CSKH, Kỹ thuật viên vận hành trạm, Kế toán thanh toán, Tài xế xe điện | Trung bình 20–40 ticket khiếu nại lỗi phiên sạc/ngày; thời gian xử lý hiện tại mất 24–48 giờ do phải chờ 3 bộ phận tự tra file log riêng rồi phản hồi qua lại trên nhóm chat nội bộ |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.
- **Ý giữ lại:** Giữ các bài toán gắn với quy trình kỹ thuật phần mềm và vận hành dữ liệu có cấu trúc rõ ràng (Card #1 về Release Notes, Card #2 về đối soát VietQR, Card #3 về tổng hợp Literature Review, Card #4 về biên bản họp, Card #5 về tạo Mock Data, Card #7 về gom cụm Error Log), đồng thời bổ sung bài toán thực tế chuyên sâu từ nghiệp vụ thật của bản thân là **Card #6 (Đối soát 3 bên dữ liệu trạm sạc Green SM)** và **Card #8 (Xử lý khiếu nại phiên sạc lỗi)**.
- **Ý loại bỏ và lý do:** Bỏ các ý tưởng đời sống cá nhân chung chung do AI gợi ý ban đầu như *"Lên thực đơn đi chợ theo tuần"*, *"Tìm phòng trọ sinh viên trên Facebook"* hay *"Quản lý chi tiêu cá nhân từ SMS"* vì các bài toán này mang tính sở thích cá nhân, quy trình không chuẩn hóa, dữ liệu đầu vào quá phân tán và đã có nhiều ứng dụng thương mại trên thị trường giải quyết.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Card 6: Đối soát 3 bên dữ liệu trạm sạc và quyết toán cho đối tác nhượng quyền Green SM | Nỗi đau thực tế rất lớn và đo lường được ngay bằng tiền và giờ công (120–160 giờ/tháng, lệch 1.5%–2.5% doanh thu); dữ liệu đầu vào có thật nhưng khác định dạng và lệch múi giờ/mất gói tin nên làm thủ công bằng Excel cực kỳ quá tải | Chưa chắc chắn 100% tỷ lệ phiên sạc lệch do lỗi phần cứng trụ sạc so với lỗi timeout từ cổng thanh toán trung gian chiếm bao nhiêu phần trăm trong tổng số ca lệch |
| 2 | Card 1: Tự động hóa tổng hợp Release Notes & Changelog từ lịch sử Git Commit và Jira Ticket | Bài toán sát sườn với mọi nhóm phát triển phần mềm; tần suất lặp lại đều đặn mỗi sprint (1–2 lần/tuần); đầu vào (Git log, PR, Jira) đã có sẵn API rất thuận lợi để áp dụng AI Workflow| Nếu lập trình viên viết commit message quá sơ sài và không gắn mã Jira ticket vào nhánh/commit thì AI có đủ ngữ cảnh để phân loại chính xác không  |
| 3 | Card 2: Đối soát thanh toán chuyển khoản VietQR tự động cho đơn hàng online vào giờ cao điểm | Pain point xảy ra hàng ngày với tần suất cao (30–50 đơn/ngày); tác động trực tiếp đến tốc độ giao hàng và ngăn chặn rủi ro thất thoát tiền do bill chuyển khoản giả mạo | Cần làm rõ ranh giới: bao nhiêu phần trăm trường hợp giải quyết được chỉ bằng Rule-based và khi nào mới thực sự cần tới AI |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi kết thúc mỗi kỳ kế toán tháng phải quyết toán doanh thu và chi phí vận hành trạm sạc, tôi muốn tự động đối khớp chéo 3 nguồn dữ liệu (log phiên sạc từ hệ thống Gateway trụ sạc trung tâm, hóa đơn tiền điện thực tế theo chỉ số công tơ EVN của từng trạm, và lịch sử giao dịch thanh toán không tiền mặt từ ví điện tử/thẻ của khách hàng) kèm phân loại nguyên nhân các phiên sạc lệch, để lập biên bản giải trình nhanh chóng và đối chiếu chính xác với đối tác chủ mặt bằng/chủ trạm nhượng quyền trước khi giải ngân |
| Actor | Accountant, Bộ phận Vận hành trạm sạc Green SM, Đối tác chủ mặt bằng / chủ trạm nhượng quyền |
| Thời điểm / bối cảnh | Cuối mỗi kỳ kế toán hàng tháng hoặc kỳ quyết toán định kỳ trước khi chốt công nợ và giải ngân doanh thu chia sẻ cho đối tác trạm sạc |
| Quy trình hiện tại (3–7 bước) | 1. Tải thủ công các file CSV/Excel log phiên sạc (kWh tiêu thụ, thời gian bắt đầu/kết thúc, mã trụ, Session ID) từ hệ thống Gateway trung tâm.<br>2. Thu thập hóa đơn tiền điện EVN (PDF/XML/ảnh chụp thông báo tiền điện) của từng trạm sạc theo mã công tơ.<br>3. Xuất sao kê giao dịch thanh toán thành công/hoàn tiền từ cổng thanh toán ví điện tử và ngân hàng.<br>4. Đưa toàn bộ dữ liệu vào bảng tính Excel, chuẩn hóa lại cột thời gian, mã trạm và dùng hàm `VLOOKUP`/`SUMIFS` để khớp chéo từng phiên sạc với giao dịch thu tiền và tổng sản lượng điện EVN.<br>5. Lọc ra danh sách các phiên sạc bị lệch (có kWh sạc nhưng chưa thu được tiền, thu tiền 2 lần, hoặc tổng điện năng trụ báo lệch quá ngưỡng hao hụt so với công tơ EVN) để tra log chi tiết tìm nguyên nhân.<br>6. Lập biên bản giải trình cho các khoản chênh lệch, gửi email/Zalo xác nhận thủ công với từng chủ mặt bằng/trạm nhượng quyền.<br>7. Chốt số liệu cuối cùng và trình ký đề nghị giải ngân. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 & Bước 5 (Khớp chéo dữ liệu trên Excel và truy vết nguyên nhân phiên sạc lệch): File Excel hàng trăm nghìn dòng bị treo đơ máy; mã giao dịch và Session ID đôi khi không khớp trực tiếp do rớt mạng lúc kết thúc phiên sạc; tốn 120–160 giờ công/tháng (khoảng 15–20 ngày làm việc của 1 kế toán)` |
| Impact (nếu không giải thì sao) | Sai lệch dữ liệu từ 1.5% – 2.5% tổng doanh thu; gây treo công nợ kéo dài, chậm tiến độ giải ngân làm giảm uy tín với đối tác chủ mặt bằng/nhượng quyền; nguy cơ thất thoát dòng tiền thực tế do bỏ sót các phiên sạc lỗi mạng chưa thu tiền |
| Success metric (baseline → target) | Thời gian đối soát kỳ kế toán: giảm từ 120–160 giờ/tháng xuống còn < 16 giờ/tháng (giảm ~90%). <br>Tỷ lệ giao dịch lệch chưa rõ nguyên nhân tồn đọng cuối kỳ: giảm từ 1.5%–2.5% xuống < 0.1% doanh thu. <br>Thời gian chốt biên bản với đối tác: rút ngắn từ 7–10 ngày xuống 1–2 ngày. |
| Phương án không dùng AI | Xây dựng ETL pipeline cố định bằng Python/SQL kết hợp cơ sở dữ liệu quan hệ để join các bảng theo Session_ID và Transaction_ID, kèm bộ quy tắc (Rule-based) cảnh báo khi độ lệch thời gian < 5 phút hoặc lệch sản lượng điện giữa trụ và công tơ EVN > 5% |
| Giả thuyết về AI (nếu có) | Kết hợp Rule-based cho 85–90% giao dịch khớp chuẩn và dùng AI Workflow cho 10–15% ca ngoại lệ: (1) OCR/LLM bóc tách hóa đơn điện EVN nhiều định dạng (PDF/ảnh chụp từ chủ mặt bằng gửi về); (2) Khớp mờ (Fuzzy/Semantic Matching) các giao dịch bị mất Session_ID dựa trên khung giờ, số tiền, vị trí trạm và lịch sử lỗi rớt mạng của trụ; (3) Tự động tóm tắt nguyên nhân lệch và sinh dự thảo biên bản giải trình cho từng đối tác để kế toán duyệt |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[1. Xuất Log Gateway trụ sạc (CSV)] + [2. Gom hóa đơn điện EVN từng trạm (PDF/Ảnh)] + [3. Xuất sao kê Ví/Thẻ (Excel)]
                                                      │
                                                      ▼
                            [4. Nhập tay & gộp vào file Excel đối soát tổng]
                                                      │
                                                      ▼
                  [5. Chạy VLOOKUP / Pivot khớp Session ID, Số tiền & Sản lượng kWh] ⚠️ (BOTTLENECK 1: Excel treo, lệch định dạng)
                                                      │
                           ┌──────────────────────────┴──────────────────────────┐
                           ▼ (Khớp 100%)                                         ▼ (Lệch 1.5% - 2.5% doanh thu)
        [Tổng hợp bảng kê doanh thu chuẩn]             [6. Dò tay từng dòng log lỗi mạng & tra lịch sử ví] ⚠️ (BOTTLENECK 2: Mất 120-160h/tháng)
                           │                                                     │
                           │                                                     ▼
                           │                           [7. Viết biên bản giải trình & gửi đối tác xác nhận]
                           └──────────────────────────┬──────────────────────────┘
                                                      ▼
                                  [8. Chốt công nợ & Giải ngân cho đối tác]
```


### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | **Khi** đến cuối mỗi chu kỳ sprint 2 tuần hoặc ngay trước khi deploy bản vá lỗi/phiên bản mới lên môi trường Staging/Production, **tôi muốn** tự động lọc và tổng hợp các Git commit kèm ngữ cảnh từ ticket Jira thành bản Release Notes chuẩn hóa, **để** không phải rà soát thủ công hàng trăm dòng commit rời rạc và giúp team QA/PM nắm rõ phạm vi kiểm thử ngay lập tức. |
| Actor | Tech Lead, Release Engineer, QA Engineer, Product Manager. |
| Thời điểm / bối cảnh | Cuối mỗi Sprint (chiều thứ Sáu tuần thứ 2) hoặc trước mỗi đợt релиз/hotfix lên Staging và Production. |
| Quy trình hiện tại (3–7 bước) | 1. Mở terminal chạy lệnh `git log <tag_cũ>..HEAD` để xuất danh sách toàn bộ commit trong sprint.<br>2. Copy danh sách 80–120 commits ra file nháp, đọc và xóa tay các commit rác (`merge branch`, `fix typo`, `wip`).<br>3. Tìm mã ticket (ví dụ `UIT-102`) trong từng commit hoặc tên nhánh, mở Jira để đọc mô tả nghiệp vụ thật sự của thay đổi đó.<br>4. Phân loại thủ công các thay đổi vào 4 nhóm: *New Features*, *Bug Fixes*, *Improvements*, *Breaking Changes*.<br>5. Viết lại câu chữ từ ngôn ngữ code sang ngôn ngữ sản phẩm dễ hiểu cho QA và PM.<br>6. Đăng bản Release Notes lên GitHub Releases và gửi thông báo vào kênh Slack/Zalo của dự án. |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 3 & Bước 5** (Mở từng ticket Jira đối chiếu ngữ cảnh và biên tập lại văn phong): Mất **35–45 phút** trong tổng số 60 phút của quy trình vì phải chuyển qua lại giữa Git, Jira và file tài liệu. |
| Impact (nếu không giải thì sao) | Lập trình viên ngại viết dẫn đến Release Notes sơ sài hoặc chậm trễ; QA không biết chính xác các luồng bị ảnh hưởng để test hồi quy (regression test), dẫn đến lọt lỗi lên Production. |
| Success metric (baseline → target) | • Thời gian soạn Release Notes: giảm từ **45–60 phút/lần** xuống **< 5 phút/lần** (chỉ đọc duyệt).<br>• Độ phủ thông tin thay đổi quan trọng (Features/Breaking Changes): đạt **100%** không bỏ sót ticket nào đã merge. |
| Phương án không dùng AI | Bắt buộc toàn bộ developer tuân thủ nghiêm ngặt chuẩn *Conventional Commits* (`feat:`, `fix:`, `chore:`) kết hợp công cụ CLI như `standard-version` hoặc `release-please` để tự cắt chuỗi tạo file Markdown. |
| Giả thuyết về AI (nếu có) | Dùng **AI Workflow**: Script tự động lấy danh sách PR/Commit + gọi API Jira lấy tiêu đề và mô tả ticket tương ứng, sau đó đưa qua LLM để tóm tắt thành ngôn ngữ nghiệp vụ, gom nhóm thông minh và phát hiện các thay đổi có rủi ro ảnh hưởng hệ thống trước khi Tech Lead bấm duyệt đăng. |
| Cảm nhận nhanh | **AI Workflow** (tự động gom dữ liệu Git + Jira và tóm tắt nháp, Tech Lead kiểm duyệt bước cuối). |

Quy trình nháp hiện tại:

```text
[1. Chạy git log lấy 80-120 commits] ──► [2. Lọc bỏ tay các commit merge/typo/wip]
                                                        │
                                                        ▼
[4. Gom nhóm Feature / Bugfix / Breaking] ◄── [3. Mở từng ticket Jira đọc mô tả nghiệp vụ] ⚠️ (BOTTLENECK: 35-45 phút, mở nhiều tab)
                  │
                  ▼
[5. Viết lại thành ngôn ngữ cho QA/PM] ──► [6. Đăng GitHub Release & thông báo nhóm chat]
```

### Problem Card #3


| Trường | Nội dung |
|---|---|
| Job Story | **Khi** khách hàng đặt đơn online và chuyển khoản qua mã VietQR vào giờ cao điểm, **tôi muốn** đối chiếu tự động biến động số dư ngân hàng với mã đơn và số tiền trên bảng quản lý đơn hàng, **để** xác nhận thanh toán tức thì mà không làm gián đoạn việc đóng gói hàng hay bị lừa bởi ảnh chụp màn hình bill giả. |
| Actor | Chủ shop online nhỏ (SME), nhân viên trực fanpage/chốt đơn, thủ quỹ CLB sinh viên. |
| Thời điểm / bối cảnh | Hàng ngày, đặc biệt căng thẳng vào các khung giờ cao điểm chốt đơn (11h00–13h00 và 20h00–22h30) hoặc các đợt mở bán/livestream. |
| Quy trình hiện tại (3–7 bước) | 1. Tạo đơn hàng trên Google Sheet/phần mềm bán hàng với mã đơn (ví dụ `DH205`) và gửi ảnh mã VietQR cho khách.<br>2. Khách hàng chuyển khoản và gửi ảnh chụp màn hình biên lai qua tin nhắn.<br>3. Nhân viên trực page mở điện thoại có cài App Ngân hàng (hoặc đọc SMS biến động số dư) để kiểm tra tiền đã thực sự vào tài khoản chưa.<br>4. Đọc nội dung chuyển khoản và số tiền, tìm dòng đơn hàng tương ứng trên Google Sheet.<br>5. Nếu khách ghi sai nội dung (chỉ ghi tên hoặc số điện thoại), phải hỏi lại khách hoặc dò theo số tiền và thời gian.<br>6. Đánh dấu "Đã thanh toán" trên Sheet và nhắn tin xác nhận cho khách để bộ phận kho đóng gói. |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 3, 4 & 5** (Mở app ngân hàng kiểm tra thủ công và xử lý các giao dịch ghi sai cú pháp mã đơn): Mất **2–3 phút/đơn**, làm đứt quãng liên tục nhịp tư vấn khách hàng và đóng gói hàng. |
| Impact (nếu không giải thì sao) | Tốn **1.5–2.5 giờ/ngày** chỉ để dò tiền; khách phải chờ xác nhận lâu dễ hủy đơn; nếu chỉ nhìn ảnh khách gửi mà không đối chiếu số dư thật do quá bận vào giờ cao điểm thì rất dễ bị lừa bởi bill chuyển khoản Photoshop. |
| Success metric (baseline → target) | • Thời gian xác nhận thanh toán: giảm từ **2–3 phút/đơn** xuống **< 10 giây/đơn** đối với đơn đúng cú pháp và **< 30 giây** với đơn sai cú pháp.<br>• Tỷ lệ lọt bill giả hoặc nhầm đơn: **0%**. |
| Phương án không dùng AI | Tích hợp Webhook biến động số dư (Casso/SePay) nối thẳng với Google Apps Script dùng biểu thức chính quy (Regex) bắt chính xác chuỗi mã đơn `DHxxx` và so khớp `Số tiền nhận == Tổng tiền đơn`. |
| Giả thuyết về AI (nếu có) | **Rule-based** giải quyết triệt để 85% giao dịch đúng cú pháp mã đơn; chỉ gọi **AI Workflow** nhẹ cho 15% giao dịch ngoại lệ (khách ghi tên riêng, viết tắt sản phẩm, gộp tiền 2 đơn) để AI gợi ý ghép cặp giao dịch ngân hàng với đơn hàng đang chờ trên Sheet cho nhân viên bấm "Xác nhận" 1 chạm. |
| Cảm nhận nhanh | **Rule** (ưu tiên Rule-based Regex + Webhook làm cốt lõi; chỉ bổ sung AI hỗ trợ gợi ý ghép đơn cho các ca ghi sai nội dung). |

Quy trình nháp hiện tại:

```text
[1. Tạo đơn trên Sheet & gửi VietQR] ──► [2. Khách chuyển khoản & gửi ảnh bill qua chat]
                                                        │
                                                        ▼
                                  [3. Mở App Ngân hàng kiểm tra tiền về thật chưa]
                                                        │
                                                        ▼
                         [4. Dò mã đơn & số tiền trên Google Sheet] ⚠️ (BOTTLENECK: 2-3 phút/đơn, dễ nhầm khi khách ghi sai nội dung)
                                                        │
                        ┌───────────────────────────────┴───────────────────────────────┐
                        ▼ (Khớp mã đơn)                                                 ▼ (Sai cú pháp nội dung ~15%)
      [6. Đổi trạng thái "Đã thanh toán"]                              [5. Nhắn hỏi lại khách / Dò tay theo giờ & số tiền]
                        │                                                               │
                        └───────────────────────────────┬───────────────────────────────┘
                                                        ▼
                                        [7. Báo kho đóng gói & gửi hàng]
```


### Card muốn pitch nhất

- Card số: 6
- Vì sao:

    - Nỗi đau thật và quy mô lớn: Tiêu tốn 120–160 giờ công/tháng (1 nhân sự chuyên trách), ảnh hưởng trực tiếp đến 1.5%–2.5% doanh thu hệ thống và làm chậm tiến độ giải ngân cho các đối tác nhượng quyền.

    - Độ phức tạp phù hợp để ứng dụng AI Workflow: Quy trình có 3 nguồn dữ liệu phân tán, nhiều định dạng không đồng nhất (ảnh chụp/PDF hóa đơn EVN, log mạng rớt gói tin) mà các công cụ Excel/Code cứng truyền thống khó xử lý triệt để ngoại lệ.

    - Đầu vào và chỉ số đo lường rõ ràng: Dễ xác định rõ ràng bài toán As-Is, To-Be và kiểm chứng hiệu quả giảm thời gian đối soát từ 7–10 ngày xuống dưới 1–2 ngày.
- Câu hỏi muốn nhóm phản biện:

    - Nếu chỉ dùng cơ sở dữ liệu quan hệ và script ETL tự động (Rule-based) để join Session_ID thì đã giải quyết được bao nhiêu % khối lượng công việc, và 10–15% ca ngoại lệ rớt mạng còn lại có thực sự cần tới AI Workflow hay chỉ cần cải thiện firmware trụ sạc?

    - Rủi ro pháp lý và trách nhiệm tài chính sẽ thế nào nếu AI trích xuất sai chỉ số điện EVN từ ảnh chụp hoặc gợi ý sai biên bản giải trình công nợ dẫn tới giải ngân nhầm cho đối tác?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|1. Job Story ban đầu viết theo dạng mô tả công việc (task description), thiếu cấu trúc chuẩn và mục tiêu cốt lõi. | Đồng ý | Chuẩn hóa lại theo đúng khung Khi… tôi muốn… để…: làm rõ thời điểm (cuối kỳ kế toán tháng), mong muốn (tự động đối khớp 3 nguồn dữ liệu và phát hiện phiên sạc lệch) và mục đích (lập biên bản giải trình nhanh, chốt công nợ đúng hạn cho đối tác). |
|2. Nguy cơ lạm dụng AI để tính toán số liệu kế toán (dễ gây sai số/hallucination tài chính).|Đồng ý hoàn toàn| Phân định ranh giới rõ ràng: 85–90% phép tính cộng trừ, đối khớp Session ID bắt buộc dùng Code/Rule-based (Python/SQL) để đảm bảo chính xác 100%; AI Workflow chỉ can thiệp ở khâu phi cấu trúc (OCR bóc tách hóa đơn EVN dạng ảnh/PDF và dự thảo nội dung văn bản giải trình). |
|3. Đối tượng chịu ảnh hưởng (Actor) liệt kê sơ sài "Account, Green SM", chưa rõ ai là người duyệt và ai nhận tiền.|Đồng ý|Tách rõ thành 3 nhóm tác nhân: Kế toán đối soát (người thực hiện đối khớp), Kỹ sư vận hành hệ thống (người xác minh lỗi rớt mạng trụ sạc) và Đối tác chủ mặt bằng/chủ trạm nhượng quyền (người đối chiếu biên bản và nhận tiền giải ngân).|

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
