# Báo cáo nhóm UIT — Day 02 Discovery & Problem Framing

## 1. Thông tin nhóm

- Tên nhóm: UIT
- Trưởng nhóm: Hà Lê Duy
- Thành viên và phân công: [TEAM.md](../../TEAM.md)
- Candidate được chọn: Đọc và đối chiếu yêu cầu bài lab từ nhiều file hướng dẫn.
- Trạng thái: Hà Lê Duy, trưởng nhóm, xác nhận chọn S1 ngày 09/11/2026. Bắt đầu triển khai CP4–CP5.
- Quyết định Go / Not Yet / No-Go: Chờ kết quả CP4–CP6.

## 2. Hội tụ nhóm (CP3)

### 2.0. Căn cứ và trạng thái biên bản

Bản tổng hợp dựa trên 12 Problem Card trong bốn báo cáo cá nhân tại commit ab664fb. Điểm shortlist là đánh giá đề xuất từ nội dung đã nộp. Chưa có bản ghi cuộc họp để xác nhận người đã hỏi, câu trả lời, biểu quyết hoặc bất đồng của nhóm.

| Thành viên | Nguồn CP2 | Mã candidate |
|---|---|---|
| Hà Lê Duy | [Báo cáo cá nhân](../individual/2A202603851_HaLeDuy.md) | D1–D3 |
| Võ Hồng Lương | [Báo cáo cá nhân](../individual/2A202603839_VoHongLuong.md) | L1–L3 |
| Nguyễn Đức Nhật | [Báo cáo cá nhân](../individual/2A202603812_NguyenDucNhat.md) | N1–N3 |
| Nguyễn Thiên Bảo | [Báo cáo cá nhân](../individual/2A202603861_NguyenThienBao.md) | B1–B3 |

### 2.1. Tổng hợp candidate để pitch

Số tự thuật trong báo cáo cá nhân cần được đối chiếu với hiện vật hoặc quan sát trước khi dùng làm baseline chung.

| Mã | Người đề cử | Candidate theo nhu cầu | Actor | Bottleneck và bằng chứng hiện có | Câu hỏi cần làm rõ |
|---|---|---|---|---|---|
| D1 | Duy | Khi tổng hợp phản hồi, muốn nhận diện các ý cùng vấn đề để đánh giá mức lặp lại. | Người tổng hợp phản hồi | So ngữ cảnh và gom nhóm, 12/30 phút cho 15 phản hồi đều là giả định. | Có người phụ trách và mẫu phản hồi thật để quan sát không? |
| D2 | Duy | Khi kết thúc họp phản hồi, muốn biết việc tiếp theo và người nhận để tiếp tục xử lý. | Người điều phối | Đối chiếu người nhận và hạn, 7/18 phút là giả định. | Biên bản đã ghi việc được chốt hay cần hỏi lại người tham dự? |
| D3 | Duy | Khi đưa nhận định vào báo cáo, muốn truy được phản hồi gốc để kiểm tra căn cứ. | Người viết báo cáo | Tìm lại bản ghi, 10/25 phút cho 3 nhận định là giả định. | Lưu mã nguồn ngay lúc đọc có giải quyết được pain không? |
| L1 | Lương | Khi báo cáo tuần cho mentor, muốn gom việc xong, vướng mắc và kế hoạch để gửi đúng hạn. | Thực tập sinh | Đọc commit và task khoảng 25/60 phút, theo kinh nghiệm intern ghi trong bài. | Có bản báo cáo và dữ liệu được phép dùng để đo lại không? |
| L2 | Lương | Khi nhận đề lab nhiều file, muốn nắm đầu ra, hạn và tiêu chí để tránh bỏ sót. | Học viên | Đọc tìm đầu ra và tiêu chí khoảng 7 phút, tổng 10–15 phút/lần theo tự thuật. | Checklist dẫn nguồn có đủ giúp học viên nắm yêu cầu không? |
| L3 | Lương | Khi chốt họp nhóm, muốn biết khung giờ chung để giảm trao đổi nhiều vòng. | Nhóm 3–4 người | 6–10 vòng trao đổi, khoảng 30 phút chờ theo tự thuật. | Nghẽn ở chọn khung giờ hay chờ mọi người trả lời? |
| N1 | Nhật | Khi quyết toán trạm sạc, muốn đối chiếu log, điện năng và thanh toán để giải trình chênh lệch. | Kế toán, vận hành | Bài nêu 120–160 giờ/tháng và chênh lệch 1,5–2,5% doanh thu, chưa kèm mẫu hoặc nguồn tính. | Có quyền lấy mẫu ẩn danh và người xác nhận quy tắc đối soát không? |
| N2 | Nhật | Khi phát hành phiên bản, muốn tổng hợp thay đổi để QA và PM nắm phạm vi kiểm tra. | Tech Lead, QA, PM | Đối chiếu ticket và biên tập, bài nêu 35–45 phút trong tổng 45–60 phút, chưa có hiện vật đo. | Có bản release và PR/ticket tương ứng để kiểm độ đầy đủ không? |
| N3 | Nhật | Khi khách chuyển khoản, muốn ghép giao dịch với đơn để xác nhận thanh toán đúng. | Chủ shop, nhân viên chốt đơn | Kiểm ngân hàng và dò đơn, bài nêu 2–3 phút/đơn, chưa kèm mẫu đối chiếu. | Có tiếp cận chủ shop và giao dịch đã ẩn danh được không? |
| B1 | Bảo | Khi làm lab mới, muốn nắm nội dung, tiêu chí và cách nộp để làm đúng từ đầu. | Học viên | Ít nhất 30 phút đọc ba tài liệu theo trí nhớ. Bước đối chiếu chưa đo riêng. | Mốc 30 phút có gồm hiểu kiến thức chuyên môn hoặc kiểm lại trước nộp không? |
| B2 | Bảo | Khi làm bài nhóm, muốn biết người phụ trách và trạng thái để giảm hỏi lại. | Thành viên nhóm | Có tự thuật phải hỏi lại trong chat, chưa có số lượt và phút chờ. | Thông tin đã có nhưng khó tìm hay người làm chưa cập nhật? |
| B3 | Bảo | Khi có thông báo đột ngột, muốn nhận biết kịp để thực hiện trước hạn. | Học viên | Có tự thuật suýt bỏ quên, chưa có kênh và mốc thời gian cụ thể. | Nguyên nhân thuộc cài đặt thông báo, thói quen kiểm tra hay thời gian báo trước? |

### 2.2. Cluster

| Cluster | Candidate | Nhu cầu chung | Khác biệt cần giữ |
|---|---|---|---|
| A — Tổng hợp nội dung | D1, L1, N2 | Chuyển thông tin rời rạc thành nội dung người nhận hiểu và sử dụng được. | Phản hồi, tiến độ và thay đổi phiên bản có tiêu chí chất lượng khác nhau. |
| B — Tìm và đối chiếu căn cứ | D3, L2, B1 | Tìm đúng nguồn và đối chiếu nội dung trước khi hành động hoặc trình bày. | L2 và B1 cùng nhu cầu đọc yêu cầu lab. D3 tập trung kiểm căn cứ nhận định. |
| C — Nhận biết và phối hợp công việc | D2, L3, B2, B3 | Biết thời điểm, người phụ trách và việc cần thực hiện. | Chờ phản hồi, thiếu cập nhật và bỏ lỡ thông báo cần đo riêng. |
| D — Đối soát giao dịch | N1, N3 | Đối chiếu dữ liệu để xác nhận khoản đúng và phát hiện ngoại lệ. | Khác quy mô, nguồn dữ liệu và quyền xác nhận. |

L2 và B1 được hợp nhất thành **S1 — Đọc và đối chiếu yêu cầu lab**, giữ nguồn bằng chứng riêng. Mốc 10–15 phút của Lương và ít nhất 30 phút của Bảo chưa có cùng phạm vi đo, nên chưa tính trung bình.

### 2.3. Opportunity Solution Tree rút gọn

Outcome và các nhánh là đề xuất để nhóm xác nhận.

~~~text
OUTCOME — Giảm công sức tìm và đối chiếu thông tin
          để hoàn thành đúng việc cần làm
├── A. Khó tổng hợp thông tin thành nội dung đủ và dễ hiểu
│   ├── D1. Khó gom phản hồi cùng vấn đề
│   ├── L1. Khó gom tiến độ trước khi báo cáo
│   └── N2. Khó tổng hợp thay đổi trước khi phát hành
├── B. Khó tìm đúng căn cứ
│   ├── D3. Khó truy nguồn cho nhận định
│   └── S1 = L2 + B1. Khó đối chiếu yêu cầu lab giữa các file
├── C. Khó nhận biết việc và phối hợp kịp thời
│   ├── D2 + B2. Chưa rõ người nhận, việc đã chốt hoặc trạng thái
│   ├── L3. Chờ nhiều vòng để chốt giờ họp
│   └── B3. Nhận biết thông báo muộn
└── D. Khó xác nhận dữ liệu giao dịch khớp nhau
    ├── N1. Đối soát nhiều nguồn tại trạm sạc
    └── N3. Ghép khoản chuyển với đơn hàng
~~~

Các cụm “tự động hóa release notes”, “đối soát tự động” được diễn đạt lại thành nhu cầu trong bảng candidate. Checklist, webhook và công cụ trích xuất được xem xét ở bước so sánh giải pháp.

### 2.4. Shortlist và chấm điểm đề xuất

Ưu tiên bài toán tìm được người khảo sát ngoài nhóm, lấy mẫu được phép sử dụng và quan sát được một tác vụ trong thời gian lab.

- **S1 = L2 + B1.** Hai thành viên ghi nhận cùng nhu cầu, tài liệu có sẵn để thiết kế lượt đo.
- **S2 = L1.** Có trải nghiệm intern và quy trình báo cáo tương đối rõ.
- **S3 = N2.** Có thể thu hẹp vào một phiên bản với PR/ticket, phù hợp nền tảng phần mềm của nhóm.

Điểm 1–5 lần lượt thể hiện từ nhiều khoảng trống đến điều kiện rõ và thuận lợi trong phạm vi lab. Riêng bằng chứng, mức 3 là tự thuật có bối cảnh, mức 4–5 cần hiện vật hoặc quan sát đối chiếu được. Điểm hiểu domain dựa vào nội dung bốn báo cáo, cần thành viên xác nhận khi thảo luận.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được 4 mức | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| S1 — Đọc và đối chiếu yêu cầu lab | 5 | 4 | 3 | 4 | 5 | 4 | 5 | **30/35** |
| S2 — Báo cáo tiến độ cho mentor | 5 | 4 | 3 | 4 | 3 | 4 | 4 | **27/35** |
| S3 — Tổng hợp thay đổi phiên bản | 5 | 4 | 2 | 4 | 3 | 4 | 4 | **26/35** |

| Candidate | Căn cứ và điểm cần xác minh |
|---|---|
| S1 | Actor cụ thể, tài liệu ngay trong repo, có thể mời học viên nhóm khác. Hai tự thuật cùng pain nhưng chưa có số đo tương đương. Cần tách đọc hiểu và đối chiếu yêu cầu. |
| S2 | Có kinh nghiệm cá nhân và sơ đồ 5 bước có phút. Cần quyền dùng dữ liệu intern và người nhận báo cáo xác nhận họ sử dụng đầu ra thế nào. |
| S3 | Quy trình 6 bước và đầu ra rõ. Cần tách hai bottleneck, bổ sung phút từng bước và quyền đọc ticket. Mục tiêu dưới 5 phút phải tính cả thu thập, kiểm và sửa. |

| Candidate chưa vào shortlist | Lý do |
|---|---|
| D1, D3 | Thời gian hiện là giả định, người dùng thực tế chưa xác nhận tiếp cận được. |
| D2, B2 | Có thể thử bảng phân công trước. B2 cần phân biệt khó tìm với thiếu cập nhật, D2 chưa có biên bản thật. |
| L3 | Dễ khảo sát nhưng số phút chờ và thao tác còn lẫn nhau. Có thể thử poll hoặc lịch cố định ở phạm vi nhỏ. |
| B3 | Cần xác minh kênh và nguyên nhân trước khi chốt quy trình. |
| N1 | Cần dữ liệu nội bộ, quy tắc và người có quyền xác nhận. Sơ đồ hiện có 8 bước, số giờ và tỷ lệ chưa kèm bằng chứng. |
| N3 | Cần dữ liệu đơn hàng/ngân hàng và người đối soát. Tỷ lệ 85%/15% cùng mục tiêu lỗi 0% cần nguồn và cách đo. |

### 2.5. Candidate được chọn và lý do lựa chọn

**Đã chọn S1 — Đọc và đối chiếu yêu cầu bài lab theo xác nhận của trưởng nhóm Hà Lê Duy ngày 09/11/2026.**

> Khi bắt đầu một bài lab có nhiều file hướng dẫn, tôi muốn xác định đúng sản phẩm cần nộp, tiêu chí bắt buộc và cách nộp, để lập kế hoạch làm bài và kiểm tra đầy đủ trước hạn.

Phạm vi đầu tiên là một bộ tài liệu và một checklist có nguồn. Đo từ lúc mở tài liệu đến khi lập và kiểm xong checklist. Chấm chất lượng theo các yêu cầu bắt buộc, điều kiện và ngoại lệ trong đúng phiên bản tài liệu.

**Vì sao ưu tiên.** Có hai nguồn trải nghiệm trong nhóm, tài liệu dễ tiếp cận và khả năng mời học viên ngoài nhóm. So sánh được cách đọc hiện tại, checklist thủ công và hỗ trợ trích xuất.

**Vì sao chưa chọn S2.** Quyền dùng dữ liệu intern và khả năng tiếp cận mentor chưa rõ. Nếu có dữ liệu được phép dùng cùng người nhận báo cáo, có thể chấm lại mức vừa sức lab.

**Vì sao chưa chọn S3.** Cần tập PR/ticket đầy đủ và người chốt các thay đổi quan trọng. Chưa có hiện vật để kiểm số phút và chất lượng.

**Điều kiện xem xét lại.** Nếu người được hỏi cho biết checklist sẵn có đã đủ, hoặc nghẽn chính là chưa hiểu kiến thức chuyên môn, nhóm cần sửa phạm vi trước khi xét mức can thiệp.

### 2.6. Câu hỏi cần làm rõ và ghi nhận quyết định

Candidate S1 đã được trưởng nhóm chốt. Các câu hỏi dưới đây tiếp tục dùng để làm rõ phạm vi và bằng chứng. Câu trả lời được cập nhật theo trao đổi thực tế.

| Bước | Câu hỏi quyết định | Người dẫn đề xuất | Nội dung cần ghi |
|---|---|---|---|
| Xác nhận cluster | L2 và B1 cùng cần checklist hay B1 chủ yếu khó hiểu kiến thức chuyên môn? | Duy | Căn cứ gộp/tách và phạm vi thống nhất. |
| Chọn opportunity | Trong S1, khó nhất là tìm yêu cầu, nối các yêu cầu hay hiểu thuật ngữ? | Bảo | Ví dụ cụ thể và bước gây khó. |
| Kiểm bằng chứng | Mốc 10–15 phút và 30 phút bắt đầu/kết thúc ở đâu, có đọc lại không? | Lương | Phạm vi từng mốc và cách đo lại. |
| Phản biện giải pháp | Nếu có checklist dẫn nguồn, phần khó nào còn tồn tại? | Nhật | Phần còn vướng và bằng chứng. |
| Kiểm khảo sát | Có thể mời 2–3 học viên ngoài nhóm đã làm lab tương tự và quan sát họ thao tác không? | Duy | Người liên hệ theo vai trò, lịch hẹn, tài liệu sử dụng. |
| Chốt shortlist | S1 có còn dẫn đầu khi tính bằng chứng và quyền tiếp cận dữ liệu? | Cả nhóm | Điểm điều chỉnh, ý kiến khác và lý do chọn/loại. |

**Ghi nhận quyết định và phần thảo luận còn thiếu**

- Thời điểm và người tham dự: Chờ ghi nhận.
- Câu hỏi từng thành viên thực sự đã đặt và câu trả lời: Chờ ghi nhận.
- Quyết định chọn candidate: Hà Lê Duy xác nhận S1 ngày 09/11/2026 qua trao đổi trực tiếp trong chat điều phối, đồng thời yêu cầu triển khai phân công CP4–CP5.
- Bất đồng và cách giải quyết: Chờ ghi nhận.
- Người xác nhận biên bản: Hà Lê Duy sau cuộc họp.

### 2.7. Phân công triển khai S1

Phân công triển khai theo xác nhận của trưởng nhóm. Bảo thực hiện khảo sát, đo hiện trạng và research CP4. Duy duyệt và phản biện bản tổng hợp sau khi Bảo bàn giao. CP5 sử dụng kết quả CP4 đã được tổng hợp.

| Phần việc | Người chính | Người hỗ trợ/kiểm tra | Đầu ra và mốc |
|---|---|---|---|
| CP4 — Giả định và điều phối | Duy | Bảo | 4–6 giả định, ưu tiên pain và mức sử dụng checklist, trước khi phỏng vấn. |
| CP4 — Phỏng vấn | Bảo | Duy duyệt | Phỏng vấn 2–3 người ngoài nhóm có trải nghiệm thực tế. Ghi snapshot và tín hiệu phản bác. |
| CP4 — Research | Bảo | Duy duyệt | So 2–3 công cụ hoặc pattern, gồm checklist thủ công. Ghi link, bước hỗ trợ, điều kiện dùng và khoảng trống trước CP5. |
| CP4 — Quan sát và đo | Bảo | Duy duyệt | Ít nhất một lượt đọc tài liệu/lập checklist. Ghi thời gian từng bước, mục thiếu và phạm vi mẫu. |
| CP5 — Quy trình trước/sau | Bảo | Nhật | Sơ đồ và bảng bước có actor, input, output, phút, điểm kiểm tra và phương án quay về. |
| CP5 — Metric và v0 | Duy | Lương | Nhóm tự chốt sáu trường v0 từ CP4. Lương đối chiếu số liệu và phạm vi phép đo. |
| CP6 — Mức can thiệp | Nhật | Bảo | Bảng bốn mức và lý do chọn mức đủ dùng. Canvas/PAIR nếu áp dụng. |
| CP6 — Eval và v1 | Lương | Nhật | 3–5 tiêu chí đạt/không đạt, thay đổi v0→v1 và ví dụ để nhóm kiểm. |
| CP6 — Quyết định, tổng hợp | Duy | Cả nhóm | Bốn rủi ro, Go/Not Yet/No-Go, bước tiếp theo và ngưỡng dừng. |

Nếu đổi candidate, Duy điều chỉnh đầu vào và đối tượng khảo sát trước khi thực hiện. Mỗi người tự ghi đóng góp đã hoàn thành vào TEAM.md và báo cáo cá nhân.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Cách kiểm chứng và thứ tự ưu tiên |
|---:|---|---|---:|---:|---|
| A1 | Học viên phải mở lại nhiều file để xác định đầu ra, tiêu chí và cách nộp trong một bài lab cụ thể. | Value | 5 | 3 | Ưu tiên 1. Hỏi về bài lab gần nhất và xin ví dụ một yêu cầu đã phải tra lại. Nếu tài liệu tóm tắt hiện có đủ dùng, ghi nhận trường hợp đó. |
| A2 | Đối chiếu yêu cầu giữa các file chiếm công sức đáng kể trong quá trình lập danh sách việc. | Value | 5 | 2 | Ưu tiên 1. Quan sát một lượt và ghi riêng thời gian tìm, đọc hiểu, đối chiếu, ghi và kiểm lại. Kiểm tra xem bước tốn công nhất có nằm ở kiến thức chuyên môn hay ở việc tìm yêu cầu. |
| A3 | Việc đọc và đối chiếu nhiều nguồn dẫn tới ít nhất một lần phải làm lại hoặc sửa checklist vì thiếu, sai yêu cầu. | Value | 4 | 1 | Ưu tiên 2. Hỏi lần gần nhất phát hiện thiếu hoặc sai yêu cầu, đối chiếu bản nháp với tài liệu gốc nếu có. |
| A4 | Khi gặp yêu cầu có điều kiện hoặc ngoại lệ, học viên cần mở được nguồn gốc từ checklist để tự kiểm trước khi làm hoặc nộp. | Usability | 4 | 1 | Ưu tiên 2. Hỏi lần gần nhất người học đã kiểm một điều kiện, sau đó quan sát họ tìm căn cứ cho một mục cụ thể. |
| A5 | Có thể chuẩn bị một bộ tài liệu lab đúng phiên bản và một danh sách yêu cầu tham chiếu để so sánh các cách làm trên cùng phạm vi. | Feasibility | 4 | 3 | Chuẩn bị trước lượt đo. Chọn một bài lab, ghi commit hoặc phiên bản tài liệu, rồi nhờ hai thành viên rà danh sách tham chiếu và chốt các ngoại lệ. |

Điểm bằng chứng phản ánh tình trạng trước khảo sát. Mức 1 là chưa có quan sát trực tiếp, mức 2–3 là có tự thuật hoặc có tài liệu đối chiếu nhưng còn thiếu xác nhận từ người ngoài nhóm. A1 và A2 quyết định có giữ trọng tâm đối chiếu tài liệu cho CP5 hay thu hẹp sang một bước cụ thể hơn.

### 3.2. Kiểm chứng

**Dữ liệu hiện có**

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác hoặc giới hạn |
|---|---|---|---|
| CP2 của [Lương](../individual/2A202603839_VoHongLuong.md) và [Bảo](../individual/2A202603861_NguyenThienBao.md) | 2 tự thuật trong nhóm | Lương ước lượng 10–15 phút/lượt. Bảo ước lượng khoảng 30 phút đọc ba file và khoảng 20 phút đối chiếu, kiểm lại. Cả hai mô tả việc phải đối chiếu nhiều file. | Các mốc có phạm vi khác nhau và chưa được bấm giờ theo cùng cách. Chưa xác định phần công sức thuộc về đọc hiểu, tìm thông tin hay đối chiếu. |
| Đối chiếu tài liệu lab Day 02 | 1 bộ tài liệu | [CHECKPOINTS.md](../../CHECKPOINTS.md) nêu đầu ra của từng CP. [RUBRIC.md](../../RUBRIC.md) nêu điều kiện chấm. [SUBMISSION.md](../../SUBMISSION.md) nêu tên file, cách nộp và hạn theo ca lab. | [SUBMISSION.md](../../SUBMISSION.md) đã có checklist trước khi nộp. Đây là cách làm có sẵn cần đưa vào quan sát để biết học viên còn phải đối chiếu thêm ở đâu. |
| Phỏng vấn ngoài nhóm và quan sát có bấm giờ | Chưa có kết quả trong repo | Chờ snapshot và bản đo của Bảo. | Chưa có căn cứ xác định mức độ lặp lại, baseline chung hoặc bước nghẽn thực tế. |

**Kế hoạch kiểm chứng**

- **Bảo** phỏng vấn tổng cộng 2–3 học viên ngoài nhóm đã làm bài lab có nhiều file hướng dẫn. Hỏi về một lần cụ thể, các nguồn đã mở, chỗ phải tra lại, cách xử lý và hậu quả đã xảy ra. Ghi cả trường hợp dùng checklist sẵn có và hoàn thành thuận lợi.
- **Bảo** quan sát ít nhất một lượt theo cách làm thông thường của học viên. Bắt đầu khi học viên mở bộ tài liệu, kết thúc khi người đó báo đã kiểm xong danh sách yêu cầu. Ghi phiên bản tài liệu, các phút tìm, đọc, đối chiếu, lập và kiểm lại. Tách thời gian gián đoạn khỏi thời gian thao tác. Đối chiếu đầu ra với danh sách tham chiếu để đếm mục thiếu, hiểu sai hoặc thiếu nguồn.
- **Bảo** tổng hợp mỗi snapshot theo mã, vai trò, ngày, phương thức, tình huống gần nhất, cách xử lý, số liệu và nguồn. Giữ riêng lời kể, số bấm giờ và các ý chưa xác nhận. Ghi trích dẫn nguyên văn khi có ghi chép, cùng tín hiệu xác nhận và phản bác.

**Câu hỏi về lần làm gần nhất**

1. Bạn đã mở tài liệu nào trước? Sau đó bạn làm gì để xác định các yêu cầu phải nộp?
2. Lần đó có chỗ nào bạn phải đọc lại hoặc mở file khác để kiểm không? Bạn đã xử lý thế nào?
3. Bạn đã dùng checklist hay ghi chú nào? Nó giúp chốt được những việc gì, còn mục nào bạn phải kiểm riêng?
4. Có yêu cầu nào bạn phát hiện thiếu hoặc hiểu sai sau khi đã bắt đầu làm không? Chuyện gì xảy ra tiếp theo?

**Nhóm đã sửa problem thế nào sau kiểm chứng.** Chờ kết quả CP4. Nếu quan sát cho thấy nghẽn nằm ở một nhóm yêu cầu cụ thể như cách nộp hoặc điều kiện chấm, thu hẹp vào nhóm đó. Nếu học viên chủ yếu mất thời gian để hiểu kiến thức hoặc checklist hiện có đã đủ dùng, xem lại phạm vi trước khi chốt v0.

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
