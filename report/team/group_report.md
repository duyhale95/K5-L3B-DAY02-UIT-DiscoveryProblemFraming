# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: UIT
- Trưởng nhóm: Hà Lê Duy
- Thành viên và phân công: [TEAM.md](../../TEAM.md)
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

Danh sách chuẩn bị pitch lấy từ CP2 của [Hà Lê Duy](../individual/2A202603851_HaLeDuy.md#3-top-3-problem-cards--quy-trình-nháp-cp2), [Võ Hồng Lương](../individual/2A202603839_VoHongLuong.md#3-top-3-problem-cards--quy-trình-nháp-cp2), [Nguyễn Đức Nhật](../individual/2A202603812_NguyenDucNhat.md#3-top-3-problem-cards--quy-trình-nháp-cp2) và [Nguyễn Thiên Bảo](../individual/2A202603861_NguyenThienBao.md#3-top-3-problem-cards--quy-trình-nháp-cp2). Số trong mã tương ứng với số Problem Card. Các mốc thời gian đến từ báo cáo cá nhân và cần được xác nhận trước khi dùng làm baseline.

Mỗi người phụ trách phản biện một card của mỗi thành viên còn lại. Câu hỏi chuẩn bị lấy từ CP2 hoặc [worksheet CP3](../../docs/01-worksheet.md#bước-1--pitch-12). Trong buổi pitch, người nghe tự đặt câu hỏi theo nội dung trình bày, rồi ghi câu đã hỏi, người hỏi và điểm cần kiểm chứng.

| Mã | Người pitch | Candidate (Job Story ngắn) | Actor | Bottleneck theo CP2 | Người phụ trách phản biện | Câu hỏi chuẩn bị |
|---|---|---|---|---|---|---|
| D1 | Duy | Khi tổng hợp phản hồi, tôi muốn nhận ra các ý cùng nói về một vấn đề để đánh giá mức độ lặp lại. | PM tổng hợp phản hồi | So ngữ cảnh và gom nhóm, giả định 12 phút cho 15 phản hồi. | Lương | Khi hai phản hồi dùng từ giống nhau nhưng xuất phát từ hai trở ngại khác nhau, nhóm sẽ dùng bằng chứng nào để quyết định gộp hay tách? |
| D2 | Duy | Khi kết thúc họp về phản hồi, tôi muốn biết việc đã chốt và người phụ trách để theo dõi việc thực hiện. | Người điều phối cuộc họp | Phân biệt đề xuất với việc đã chốt và tìm phần phân công, giả định 7 phút. | Nhật | Nếu dùng bảng ghi việc ngay trong cuộc họp, còn bước nào phải làm lại? |
| D3 | Duy | Khi đưa nhận định vào báo cáo, tôi muốn truy lại phản hồi gốc để kiểm tra căn cứ. | PM viết bản tổng hợp | Tìm lại phản hồi gốc từ câu diễn giải, giả định 10 phút. | Bảo | Nếu lưu nguồn ngay từ đầu, còn nhu cầu tìm kiếm nâng cao không? |
| L1 | Lương | Khi báo cáo tuần cho mentor, tôi muốn gom việc đã xong, vướng mắc và kế hoạch để gửi đúng hạn. | Thực tập sinh | Đọc lại commit và task, khoảng 25 phút theo tự thuật. | Bảo | Lần gần nhất chuyện này xảy ra là khi nào? Mất bao lâu? |
| L2 | Lương | Khi nhận đề lab nhiều file, tôi muốn biết đầu ra, hạn nộp và tiêu chí chấm để tránh bỏ sót. | Sinh viên làm lab theo nhóm | Đọc tìm yêu cầu rải rác, khoảng 7 phút trong 10–15 phút/lần theo tự thuật. | Duy | Nếu giảng viên chỉ cần đặt một trang tóm tắt “nộp gì, hạn nào, chấm thế nào” ở đầu mỗi lab, bài toán này còn đáng giải bằng AI không? |
| L3 | Lương | Khi cần họp nhóm, tôi muốn biết giờ mọi người cùng rảnh để giảm nhắn qua lại. | Thành viên nhóm 3–4 người | Chờ trả lời và đề xuất giờ khác, khoảng 6–10 vòng và 30 phút chờ theo tự thuật. | Nhật | Bottleneck thật là bước này, hay là bước trước nó? |
| N1 | Nhật | Khi quyết toán trạm sạc, tôi muốn đối chiếu phiên sạc, điện năng và thanh toán để giải trình chênh lệch trước khi chốt công nợ. | Kế toán và vận hành trạm sạc | Khớp dữ liệu và truy nguyên nhân sai lệch, CP2 nêu 120–160 giờ công/tháng. | Bảo | Đối chiếu theo mã phiên sạc xử lý được bao nhiêu phần trăm khối lượng công việc, và còn lại những ca ngoại lệ nào? |
| N2 | Nhật | Khi chuẩn bị phát hành, tôi muốn tổng hợp thay đổi để QA và PM biết phạm vi cần kiểm thử. | Tech Lead hoặc người phụ trách phát hành | Tra ticket và viết lại thay đổi cho QA/PM, CP2 nêu 35–45 phút. | Lương | Bottleneck thật là bước này, hay là bước trước nó? |
| N3 | Nhật | Khi khách chuyển khoản lúc cao điểm, tôi muốn ghép khoản tiền nhận được với đúng đơn để xác nhận thanh toán. | Chủ shop hoặc nhân viên chốt đơn | Kiểm tra tiền vào và dò đơn khi nội dung chuyển khoản sai, CP2 nêu 2–3 phút/đơn. | Duy | Ai ngoài bạn gặp vấn đề này? Bạn có bằng chứng không? |
| B1 | Bảo | Khi bắt đầu lab mới, tôi muốn nắm đủ đầu ra, tiêu chí và cách nộp để làm đúng từ đầu. | Học viên làm và nộp bài lab | Đối chiếu ba file thành danh sách việc, khoảng 15 phút theo ước lượng cá nhân. | Nhật | Nếu đã có một checklist mẫu dùng lại cho mọi lab, bước đối chiếu còn tốn thời gian không, và có cần AI nữa không? |
| B2 | Bảo | Khi làm bài nhóm, tôi muốn biết ai phụ trách từng phần và đã xong chưa để biết mình nên làm tiếp việc gì. | Thành viên nhóm làm bài trên cùng repo | Chờ người phụ trách cập nhật, khoảng 30 phút theo ước lượng cá nhân. | Lương | Lần gần nhất chuyện này xảy ra là khi nào? Mất bao lâu? |
| B3 | Bảo | Khi lớp có thông báo đột ngột, tôi muốn biết việc cần làm và hạn xử lý đủ sớm để kịp thực hiện. | Học viên nhận thông báo từ nhiều kênh | Phát hiện thông báo muộn, khoảng 10 giờ trong lần gần nhất được kể lại. | Duy | Ai ngoài bạn gặp vấn đề này? Bạn có bằng chứng không? |

**Ghi trong buổi pitch**

| Mã | Người hỏi | Câu hỏi đã hỏi | Câu trả lời hoặc điều cần kiểm chứng |
|---|---|---|---|
| | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Cây dưới đây là bản chuẩn bị để nhóm rà lại sau khi gom cụm ở mục 2.2. Đo outcome bằng thời gian trôi qua trên từng tác vụ cùng loại, từ lúc phát sinh nhu cầu xử lý đến lúc có đủ thông tin để thực hiện đúng.

```text
OUTCOME — Rút ngắn thời gian để có đủ thông tin thực hiện đúng một tác vụ.
├── A. Khó tổng hợp thông tin rời rạc thành nội dung người nhận dùng được.
│   ├── D1. Khó nhận ra phản hồi nào nói về cùng một vấn đề.
│   ├── L1. Khó gom đủ việc đã làm, vướng mắc và kế hoạch cho báo cáo tuần.
│   └── N2. Khó xác định những thay đổi QA và PM cần biết trước khi phát hành.
├── B. Khó tìm đúng căn cứ để kiểm tra nhận định hoặc yêu cầu.
│   ├── D3. Khó truy phản hồi gốc cho nhận định trong báo cáo.
│   └── L2, B1. Khó đối chiếu đầu ra, tiêu chí và cách nộp giữa các file lab.
├── C. Khó biết kịp việc cần làm, người phụ trách hoặc thời điểm.
│   ├── D2. Khó phân biệt việc đã chốt với ý kiến đang bàn sau cuộc họp.
│   ├── L3. Mất nhiều vòng chờ để biết khung giờ chung.
│   ├── B2. Phải chờ phản hồi để biết ai đang làm gì và tiến độ ra sao.
│   └── B3. Phát hiện thông báo muộn nên còn ít thời gian xử lý.
└── D. Khó xác nhận các bản ghi giao dịch tương ứng với nhau.
    ├── N1. Khó khớp phiên sạc với thanh toán và giải thích phần chênh lệch.
    └── N3. Khó tìm đúng đơn khi khoản chuyển thiếu hoặc sai mã đơn.
```

Các phương án để ngoài tầng cơ hội gồm bảng phân công chung, checklist yêu cầu lab, tự động tạo ghi chú phát hành và tự động ghép thanh toán.

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
