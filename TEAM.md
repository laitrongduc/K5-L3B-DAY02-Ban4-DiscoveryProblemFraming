# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Ban4
- Candidate problem nhóm chọn (1 câu): Khi gặp vấn đề chuyên môn cần đối chiếu y văn trong ngày, tôi muốn tìm đúng phần khuyến cáo trong guideline / tài liệu và nắm nhanh nội dung cốt lõi, để áp dụng kịp thời cho ca lâm sàng.
- Quyết định cuối (Go / Not Yet / No-Go): Go (Pilot nhỏ trên kho chuyên khoa Răng Hàm Mặt)

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Lại Trọng Đức | 2A202604019 | Chuẩn bị candidate problem,hỗ trợ tổng hợp các candidate vào bảng Pitch (CP3). | laitrongduc |
| 2 | Nguyễn Bảo Trung | 2A202604013 | Thuyết trình (Pitch) & trả lời câu hỏi phản biện & insight + problem| trungnb|
| 3 | Nguyễn Minh Phương | 2A202603997 | Gom cluster / cây OST, chuẩn bị 3 Problem Card, phản biện | minhphuong150505 |
| 4 | Đặng Quang Duy | 2A202603984 | Chuẩn bị candidate problem (Problem Card #4–#6) và pitch; phản biện các card của bạn; góp ý quy trình trước/sau, mức can thiệp AI (phân tích hạn chế của No AI) và phạm vi pilot. | duydang2k4 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Nhóm |Nhóm | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng |  | Nguyễn Bảo Trung| Assumption map, snapshot hoặc survey |
| CP4 — Research | | | Bảng research có link |
| CP5 — Quy trình trước/sau | Nguyễn Bảo Trung | Đặng Quang Duy | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | | | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | | Đặng Quang Duy (phần mức can thiệp AI) | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Nhóm | Nhóm | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenBaoTrung-2A202604013

**Phần việc phụ trách:**

- Đảm nhiệm thuyết trình (Pitch) bài toán của nhóm và trả lời các câu hỏi phản biện khi pitch; đóng vai trò bác sĩ trả lời phỏng vấn/kiểm chứng, cung cấp problems + insight + tham gia xây workflow trước sau -> vote quyết định.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đóng góp Problem Card #1 (*Bác sĩ lọc y văn*), trực tiếp thuyết trình slide `Ban4 — Bác sĩ lọc y văn` và trả lời câu hỏi phản biện trên lớp.
- Tạo (với sự hỗ trợ của AI) và kiểm duyệt bộ eval mẫu 10 test case cho bước LLM, chấm theo 3 tiêu chí ở Mục 7: 4 ca chuẩn, 2 ca lệch quần thể, 2 ca nhạy số liệu, 1 ca outdate, 1 ca không đủ dữ kiện; chốt ground truth theo chuyên môn và ghi rõ giới hạn của bộ eval.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Báo cáo cá nhân: `report/individual/2A202604013_NguyenBaoTrung.md` (commit `d739f2f`)
- Báo cáo nhóm (`report/team/group_report.md`): Mục 1 (Candidate problem & quyết định), Mục 3.2 (trả lời phỏng vấn/kiểm chứng với vai trò bác sĩ & sửa problem sau kiểm chứng), Mục 4.1 (quy trình 5 bước ban đầu), Mục 5 & Mục 7 (Problem Statement v0 → v1: đổi Actor sang bác sĩ trẻ junior + người muốn tìm hiểu kỹ thuật mới, khoanh vùng AI), Mục 8.2 (quyết định Go pilot nhỏ trên kho chuyên khoa RHM & ngưỡng dừng cancel nếu bịa số liệu trích dẫn).
- Bộ eval mẫu: `report/assets/cp6-eval-dataset.md`, link từ Mục 7 của báo cáo nhóm.

**Điều mình học được từ phần nhóm:**

- Học được từ các thành viên trong nhóm về các khía cạnh kỹ thuật (tech).

### LaiTrongDuc-2A202604019

**Phần việc phụ trách:**

- Chuẩn bị candidate problem, Problem Card và quy trình nháp; hỗ trợ tổng hợp các candidate của mình vào bảng Pitch để nhóm có cơ sở so sánh ở CP3.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Chuẩn bị bản nháp 6 candidate dạng Job Story theo 4 lăng kính với sự hỗ trợ của AI; phân biệt dữ kiện trong repo với giả thuyết về pain và ghi rõ bằng chứng còn thiếu.
- Chuẩn bị 3 Problem Card: rà soát phần bài còn thiếu trước khi nộp; tìm đúng yêu cầu của checkpoint; truy nguồn cho nhận định research. Mỗi card có actor, bottleneck dự kiến, success metric, phương án không dùng AI và quy trình nháp 5 bước. Các số phút được ghi rõ là ước tính cần kiểm chứng.
- Tổng hợp 3 candidate vào mục 2.1. Pitch của báo cáo nhóm, dòng 4–6, kèm actor và bottleneck; giữ nguyên các candidate của thành viên khác.
- Ghi lại phản biện của AI và điều chỉnh trong bản nháp: tách phạm vi các card, bổ sung cách đo, yêu cầu kiểm tra nội dung nguồn và cân nhắc phương án đơn giản trước khi chọn AI.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo cá nhân](report/individual/2A202604019_LaiTrongDuc.md): mục 2 (6 candidate), mục 3 (3 Problem Card, 3 quy trình nháp và bảng phản biện của AI).
- [Báo cáo nhóm](report/team/group_report.md): mục 2.1. Pitch, dòng 4–6, người đưa ra là Lại Trọng Đức.

**Điều mình học được từ phần nhóm:**

- Khi chuẩn bị candidate để nhóm so sánh, cần mô tả rõ actor và bước nghẽn; nhiều yêu cầu hoặc tài liệu chưa đủ chứng minh người dùng thực sự gặp khó khăn. Các ước tính cần được kiểm chứng trước khi dùng làm cơ sở chọn bài toán.
- Với candidate truy nguồn, cần đối chiếu đoạn nội dung có hỗ trợ đúng nhận định hay không. Chỉ có một đường link mở được chưa đủ; cách ghi nguồn và kiểm tra chéo cũng là phương án cần cân nhắc trước khi dùng AI.

### NguyenMinhPhuong-2A202603997

**Phần việc phụ trách:**

- Gom cluster và dựng cây Opportunity Solution Tree rút gọn (CP3); chuẩn bị 3 Problem Card; phản biện.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Scan 10 vấn đề theo 4 lăng kính và chọn top 3 Problem Card: hóa đơn đầu vào bị lệch, giáo viên chấm và nhận xét bài, người bệnh chờ kết quả cận lâm sàng; mỗi card có quy trình nháp, bottleneck, success metric và phương án không dùng AI.
- Đưa 3 card vào bảng pitch (dòng #10–12); gom 12 candidate của nhóm thành 4 cluster, viết cây OST với 1 outcome và 4 nhánh pain, gạch bỏ 5 solution đội lốt; ghi lý do loại 3 card của mình.
- Phản biện các card của Nguyễn Bảo Trung (#2, #3) và Đặng Quang Duy (#5, #6) trong bảng pitch nhóm; phản biện nhóm 1: "Thị trường đã có sản phẩm tương tự, sản phẩm của bạn có gì tốt hơn?"
- Tham gia bỏ phiếu chọn candidate, chọn mức Workflow và góp ý Boundary.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo cá nhân](report/individual/2A202603997_NguyenMinhPhuong.md): mục 2 (scan 10 vấn đề), mục 3 (Problem Card #1 chi tiết, card #2–3 tóm tắt) — commit `b79ed5d`.
- [Báo cáo nhóm](report/team/group_report.md): mục 2.1 dòng #10–12, mục 2.2 Cluster, mục 2.3 OST, mục 2.4 lý do loại — commit `2d83628`.

**Điều mình học được từ phần nhóm:**

- Mỗi người phân tích và đánh giá cùng một bài toán theo cách khác nhau; cần phân tích nhu cầu và tình hình thực tế trước khi đưa ra giải pháp, và phải đánh giá cả rủi ro của sản phẩm chứ không chỉ tập trung xử lý vấn đề của người dùng.

### DangQuangDuy-2A202603984

**Phần việc phụ trách:**

- Chuẩn bị candidate problem và 3 Problem Card (tổng hợp tài liệu ôn thi, hỏi đáp khái niệm trên tài liệu môn học, đối chiếu bài nộp với rubric); pitch 3 candidate #4–#6 cho nhóm; phản biện card của bạn; góp ý quy trình trước/sau, mức can thiệp AI (phân tích hạn chế của No AI) và phạm vi pilot.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 candidate vào bảng pitch nhóm (dòng #4–6): #4 tổng hợp tài liệu ôn thi, #5 ticket CSKH thương mại điện tử, #6 đơn COD có nguy cơ bị từ chối. Card #4 vào shortlist, đạt 30/35 điểm, xếp thứ 2 sau candidate bác sĩ lọc y văn (31 điểm).
- Phản biện candidate #10 (hóa đơn lệch PO) của Nguyễn Minh Phương: hỏi nghẽn thật nằm ở bước đối chiếu hay bước chờ duyệt, và doanh nghiệp vừa ở VN có PO/phiếu nhập điện tử hay không; nhóm dùng đúng hai lý do này khi loại #10.
- Sửa card #1 sau phản biện (của Trung và của AI): thêm metric chất lượng (truy ngược nguồn, bao phủ đề cương, tự kiểm tra 20 câu) và thu hẹp phạm vi về một môn học thay vì chatbot học tập tổng quát.
- Góp ý quy trình trước/sau (5 bước hiện tại, 4 bước tương lai Rule → DL → LLM → Bác sĩ); chỉ ra những khó khăn của phương án No AI khi chọn mức can thiệp; góp ý hướng pilot phạm vi hẹp trên kho Răng Hàm Mặt cùng ngưỡng dừng.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo cá nhân](report/individual/2A202603984_DangQuangDuy.md): mục 2 (scan 8 problem), mục 3 (3 Problem Card, quy trình nháp, bảng phản biện của AI), mục 4 (tham gia CP3 → CP7), mục 5 (dùng AI), mục 6 (reflection).
- [Báo cáo nhóm](report/team/group_report.md): mục 2.1 dòng #4–6, mục 2.2 (cluster A, B, D), mục 2.3 (ý "ChatGPT tóm tắt slide" bị gạch bỏ), mục 2.4 (bảng chấm điểm shortlist), mục 4 (quy trình), mục 6.2 (so sánh 4 mức), mục 8.2 (pilot & ngưỡng dừng).

**Điều mình học được từ phần nhóm:**

- Bottleneck không chỉ nằm ở việc đọc tài liệu mà còn ở việc tìm đúng nguồn và đánh giá chất lượng, mức phù hợp của tài liệu (ví dụ 60 phút/90 phút cho một vấn đề lâm sàng).
- Không nên giao toàn bộ quyết định cho AI: AI chỉ hỗ trợ sàng lọc theo tiêu chí, người dùng (bác sĩ) giữ quyết định cuối và phải đối chiếu đoạn gốc. Các con số ước tính cần được đo thực tế trước khi dùng làm cơ sở chọn bài toán, vì card #4 của mình mất điểm đúng ở mục "Pain có bằng chứng".
