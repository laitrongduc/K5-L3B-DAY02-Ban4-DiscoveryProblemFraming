# Báo cáo cá nhân — 2A202603997_NguyenMinhPhuong

> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên: Nguyễn Minh Phương
- MSSV: 2A202603997
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Ban4
- Link repo nhóm: https://github.com/laitrongduc/K5-L3B-DAY02-Ban4-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

**Bối cảnh scan:** tôi scan theo một vai duy nhất, **kế toán công nợ phải trả (AP)** ở doanh nghiệp thương mại/sản xuất 50–300 nhân sự, xử lý vài trăm hóa đơn đầu vào mỗi tháng. Đây là nghề dễ tìm người quen để hỏi và bấm giờ, và hóa đơn điện tử đã bắt buộc ở Việt Nam nên quy trình khá đồng nhất giữa các doanh nghiệp.

Tôi scan 10 problem, vượt mức tối thiểu 5.

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi nhận hóa đơn điện tử đầu vào mà số lượng/đơn giá không khớp đơn mua hàng (PO) hoặc phiếu nhập kho, tôi muốn biết ngay chỗ lệch và người cần hỏi, để hạch toán và thanh toán đúng hạn | Kế toán AP, mua hàng, kho, nhà cung cấp | Ardent Partners 2024 (212 doanh nghiệp, chủ yếu Mỹ): 14% hóa đơn là ngoại lệ, trung bình 9,2 ngày/hóa đơn. Ước 10–15'/hóa đơn để đối chiếu 3 chiều. *Cần bấm giờ 20 hóa đơn* |
| 2 | Lặp lại | Khi tới cuối tháng/quý, tôi muốn đối chiếu số dư công nợ của mình với bảng kê nhà cung cấp gửi, để ký biên bản đối chiếu và không trả thừa/thiếu | Kế toán AP, nhà cung cấp, kế toán trưởng | Ước 20–40'/nhà cung cấp, vài chục nhà cung cấp mỗi kỳ. *Cần đo với 5 nhà cung cấp* |
| 3 | Tốn thời gian | Khi nhận hóa đơn mới, tôi muốn kiểm tra hóa đơn hợp lệ và mã số thuế người bán còn hoạt động, để không bị loại chi phí khi quyết toán | Kế toán AP | Ước khoảng 4'/hóa đơn tra trên cổng hóa đơn điện tử, vài trăm hóa đơn/tháng |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi có thông tư/nghị định mới về thuế hoặc hóa đơn, tôi muốn biết điểm nào áp dụng cho công ty mình, để không bị phạt mà không phải đọc hết văn bản | Kế toán AP, kế toán trưởng | VCCI, PCI 2024: gần 24% doanh nghiệp dành hơn 10% thời gian cho tìm hiểu và thực hiện quy định |
| 5 | Pain từ người khác | Khi nhà cung cấp gọi hỏi "bao giờ được thanh toán", tôi muốn trả lời ngay trạng thái hóa đơn, để không phải lục email và hỏi lại sếp | Nhà cung cấp, kế toán AP | Ước 5–10 cuộc/tuần, dồn vào cuối tháng. *Cần đếm nhật ký cuộc gọi 2 tuần* |
| 6 | Pain từ người khác | Khi đã trình đề nghị thanh toán, tôi muốn biết nó đang chờ ai duyệt, để nhắc đúng người trước hạn trả nhà cung cấp | Kế toán AP, giám đốc tài chính, nhà cung cấp | Ước 1–3 ngày chờ duyệt. *Đo bằng timestamp email trình duyệt* |
| 7 | Tốn thời gian | Khi hóa đơn đã khớp, tôi muốn hạch toán vào phần mềm kế toán mà không gõ lại từng dòng hàng, để không sai mã hàng/tài khoản | Kế toán AP | Ước khoảng 5'/hóa đơn |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi giám đốc hỏi tuần này phải chi bao nhiêu, tôi muốn có báo cáo tuổi nợ và lịch chi tiền, để giám đốc cân đối dòng tiền | Kế toán AP, giám đốc | Ước 45–60'/tuần tổng hợp từ phần mềm và Excel |
| 9 | Lặp lại | Khi hóa đơn ghi sai tên hàng, mã số thuế hoặc thuế suất, tôi muốn yêu cầu nhà cung cấp điều chỉnh/thay thế nhanh, để kịp kỳ kê khai | Kế toán AP, nhà cung cấp | Ước mỗi lần mất 2–3 ngày email qua lại. *Cần đếm số hóa đơn phải điều chỉnh/tháng* |
| 10 | Cần đọc, tổng hợp nhiều thông tin | Khi kiểm toán hoặc cơ quan thuế yêu cầu bộ chứng từ của một khoản chi cũ, tôi muốn tìm đủ hóa đơn, PO, phiếu nhập, ủy nhiệm chi, để nộp đúng hạn | Kế toán AP, kế toán trưởng, kiểm toán | McKinsey Global Institute (2012): nhân viên văn phòng dành khoảng 19% thời gian (1,8 giờ/ngày) để tìm thông tin; số cũ, chỉ định hướng. Ước 10–15'/bộ chứng từ |

**AI gợi ý thêm:** tôi dùng AI (Claude) để liệt kê các việc lặp lại trong công việc của kế toán công nợ và tìm số liệu có nguồn. Tôi bỏ ý "trợ lý AI kế toán làm thay toàn bộ" vì quá rộng, không chỉ ra được quy trình hay bước nghẽn cụ thể; các ý còn lại tôi giữ vì có tình huống và người chịu ảnh hưởng rõ.

**Nhận xét sau khi scan:** phần lớn số phút là ước lượng của tôi, chưa có kế toán thật xác nhận; số liệu Ardent là của Mỹ và doanh nghiệp lớn, chỉ dùng để chọn đề, không dùng làm baseline Việt Nam.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Hóa đơn đầu vào bị lệch (#1) | Quy trình lặp lại hằng ngày, bước nghẽn hẹp, đo được bằng đồng hồ; có baseline quốc tế để so sánh | Nghẽn thật ở bước đối chiếu hay ở bước chờ mua hàng/kho giải thích? Doanh nghiệp vừa ở VN có PO/phiếu nhập điện tử không? |
| 2 | Đối chiếu công nợ nhà cung cấp (#2) | Lặp lại mỗi kỳ, có đầu ra rõ (biên bản đối chiếu ký được) | Bảng kê nhà cung cấp gửi mỗi nơi một mẫu; phần nhiều có thể chỉ cần Excel |
| 3 | Tìm lại bộ chứng từ cũ (#10) | Pain rõ khi kiểm toán/quyết toán, có hạn nộp | Tần suất thấp (vài đợt/năm), khó có baseline ngay trong lab |

### Problem Card #1 — Kế toán công nợ phải trả và hóa đơn đầu vào bị lệch

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận hóa đơn điện tử đầu vào mà số lượng/đơn giá không khớp đơn mua hàng hoặc phiếu nhập kho, tôi muốn biết ngay chỗ lệch và người cần hỏi, để hạch toán và thanh toán đúng hạn |
| Actor | Kế toán công nợ phải trả (AP) ở doanh nghiệp thương mại/sản xuất 50–300 nhân sự, xử lý vài trăm hóa đơn/tháng |
| Thời điểm / bối cảnh | Cao điểm tuần cuối tháng và trước kỳ kê khai thuế; nhà cung cấp gọi hỏi tiền |
| Quy trình hiện tại (3–7 bước) | 1. Nhận hóa đơn qua email (2') → 2. Tải XML/PDF, tra cứu hợp lệ trên cổng hóa đơn điện tử (4') → 3. Đối chiếu 3 chiều với PO và phiếu nhập kho (10–15') → 4. Nếu lệch: nhắn mua hàng/kho, chờ phản hồi (vài giờ đến vài ngày) → 5. Hạch toán vào phần mềm kế toán (5') → 6. Trình duyệt thanh toán (5' + chờ duyệt) → 7. Lưu trữ chứng từ (2'). *Ước lượng, cần đo lại* |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: phát hiện lệch (10–15') và tìm đúng người giải thích chỗ lệch (chờ giờ đến ngày) |
| Impact (nếu không giải thì sao) | Ardent Partners 2024: trung bình 9,2 ngày và 9,40 USD/hóa đơn, so với 3,1 ngày và 2,78 USD ở nhóm tốt nhất. Hóa đơn treo gây trả chậm nhà cung cấp, sai kỳ kê khai VAT, dồn việc cuối tháng |
| Success metric (baseline → target) | Baseline: số phút trung bình từ "nhận hóa đơn" đến "sẵn sàng hạch toán" và % hóa đơn phải hỏi lại (đo 20 hóa đơn × 2 kế toán, dùng timestamp email). Target: giảm 50% thời gian với hóa đơn lệch |
| Phương án không dùng AI | Quy định nhà cung cấp ghi số PO trên hóa đơn; mẫu Excel đối chiếu tô màu chỗ lệch; SLA phản hồi 4 giờ cho bộ phận mua hàng |
| Giả thuyết về AI (nếu có) | Đọc XML hóa đơn, tự khớp với PO/phiếu nhập, tóm tắt chỗ lệch và soạn sẵn tin nhắn hỏi đúng người. Giá trị nằm ở hóa đơn không có số PO hoặc tên hàng diễn đạt khác nhau |
| Cảm nhận nhanh | **Rule + Workflow** là chính (khớp số theo quy tắc); phần khớp tên hàng mờ có thể cần mô hình ngôn ngữ. Không cần Agent |

Quy trình nháp hiện tại:

```text
[1 Nhận HĐ: 2'] → [2 Tra cứu hợp lệ: 4'] → [3 Đối chiếu PO + phiếu nhập: 10–15'] ← BOTTLENECK
→ [4 Hỏi mua hàng/kho: chờ giờ–ngày] ← BOTTLENECK → [5 Hạch toán: 5'] → [6 Trình duyệt: 5' + chờ] → [7 Lưu trữ: 2']
(mọi con số phút là giả thuyết, cần đo lại)
```

Card #2 và #3 (tóm tắt):

| Card | Actor | Bottleneck | Metric | Cảm nhận nhanh |
|---|---|---|---|---|
| Đối chiếu công nợ nhà cung cấp | Kế toán AP | So từng dòng sổ công nợ với bảng kê nhà cung cấp, tìm khoản chênh (ước 20–40'/nhà cung cấp) | 30 → 10 phút/nhà cung cấp | Rule (khớp số theo số hóa đơn) |
| Tìm lại bộ chứng từ cũ | Kế toán AP, kế toán trưởng | Lục email, thư mục và phần mềm để gom đủ hóa đơn–PO–phiếu nhập–ủy nhiệm chi (ước 10–15'/bộ) | 15 → dưới 3 phút/bộ | No AI (quy ước lưu trữ theo mã) hoặc Workflow |

### Card muốn pitch nhất

- Card số: 1 *(xếp hạng 1 — tự xác nhận lại)*
- Vì sao: dễ tìm kế toán thật để phỏng vấn, hóa đơn điện tử bắt buộc nên quy trình đồng nhất, bước nghẽn hẹp và đo được bằng đồng hồ; thuộc cluster "đối chiếu chứng từ và xử lý ngoại lệ" có outcome đo rõ.
- Câu hỏi muốn nhóm phản biện: Nghẽn thật ở doanh nghiệp vừa VN nằm ở bước đối chiếu hay bước chờ duyệt? Doanh nghiệp vừa có PO/phiếu nhập điện tử để đối chiếu không?

### AI phản biện card #1

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Số liệu Ardent thiên về doanh nghiệp lớn Mỹ, không dùng làm baseline VN được | Đồng ý | Ghi rõ baseline phải tự đo (20 hóa đơn × 2 kế toán) |
| Nghẽn có thể ở "chờ mua hàng/kho giải thích" chứ không phải "đối chiếu" | Đồng ý | Đưa thành câu hỏi muốn nhóm phản biện và giả định cần kiểm chứng đầu tiên |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Chuẩn bị 3 card (hóa đơn đầu vào bị lệch, giáo viên chấm bài, người bệnh chờ kết quả cận lâm sàng); phần trình bày do thành viên khác đảm nhận | 3 card được đưa vào bảng pitch (dòng #10–12, báo cáo nhóm mục 2.1); nhóm không chọn, lý do loại ở mục 2.4 |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: (1) Nguyễn Bảo Trung, card #2 (đối chiếu yêu cầu PhD): "Có bao nhiêu trường công bố đủ tiêu chí ở trang công khai so với phần bị ẩn trong file hướng dẫn riêng?" (2) Nguyễn Bảo Trung, card #3 (tư vấn bệnh nhân): "Bệnh nhân có đọc hiểu và tuân thủ nếu chuyển sang phiếu hướng dẫn chuẩn hóa in sẵn trước khi gặp bác sĩ không?" (3) Đặng Quang Duy, card #5 (ticket CSKH): "AI có thể xử lý chính xác các trường hợp ngoại lệ như đơn hàng thất lạc, hoàn tiền chậm hoặc khách hàng khiếu nại không?" (4) Đặng Quang Duy, card #6 (đơn COD): "Dữ liệu nào có ảnh hưởng lớn nhất đến khả năng khách từ chối nhận hàng và làm thế nào xử lý khi dữ liệu lịch sử không đầy đủ?" (5) Nhóm 1: "Thị trường đã có những sản phẩm tương tự rồi, vậy sản phẩm của bạn có gì tốt hơn của họ?" | Câu (1)–(4) được ghi ở bảng pitch nhóm (mục 2.1, dòng #2, #3, #5, #6). Câu (2) chỉ ra phương án in sẵn có thể đủ, phù hợp lý do loại card "Tư vấn bệnh nhân lặp lại" (hợp No AI) ở mục 2.4. Câu (5) đẩy nhóm bạn phải so sánh với giải pháp đã có |
| Nhận phản biện | Câu hỏi tôi nhận được: Card #10 (Đặng Quang Duy): nghẽn thật nằm ở bước đối chiếu hay bước chờ duyệt, doanh nghiệp vừa ở VN có PO/phiếu nhập điện tử để đối chiếu không? · Card #11 (Lại Trọng Đức): giáo viên có coi chấm bài là "pain" không, hay là trách nhiệm nghề nghiệp? · Card #12 (Trung): thời gian chạy máy xét nghiệm là giới hạn vật lý, vậy phần nào thật sự cải thiện được? | Tôi đã sửa gì: dự định bổ sung bộ test case tốt hơn cho bài toán và phân tích thêm rủi ro của khách hàng |
| Gom cluster / cây OST | Gom 12 candidate của nhóm thành 4 cluster và viết cây OST rút gọn, gạch các solution đội lốt (báo cáo nhóm mục 2.2–2.3; nháp ban đầu ở Phụ lục A) | Cluster A (tìm, lọc, tổng hợp thông tin) chứa candidate được chọn "Bác sĩ lọc y văn" |
| Chọn candidate problem | Tham gia bỏ phiếu chọn candidate trong shortlist | Nhóm chốt "Bác sĩ lọc y văn" (31 điểm) |
| Kiểm chứng / research | Chuẩn bị bảng giải pháp đã có, câu hỏi phỏng vấn theo The Mom Test và assumption map cho card #1 (xem Phụ lục B, C) | |
| Quy trình nhóm | | |
| Problem Statement | Góp ý phần Boundary | Boundary: AI không quyết định điều trị, không nhập thông tin định danh bệnh nhân, mọi khuyến cáo phải dẫn đoạn gốc |
| Mức can thiệp AI | Tham gia thảo luận chọn mức can thiệp | Nhóm chọn Workflow (Rule + DL + LLM, bác sĩ quyết định), không chọn Agent |
| Quyết định | Tham gia thảo luận quyết định cuối | Go phạm vi hẹp: pilot trên kho chuyên khoa Răng Hàm Mặt |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Dùng Claude liệt kê các việc lặp lại của kế toán công nợ, kèm số liệu có nguồn (không đưa giải pháp) | Nhanh ra đủ 10 việc theo 4 lăng kính; gợi ý nguồn số liệu có tên tổ chức (Ardent, VCCI) | Một ý quá rộng ("trợ lý AI kế toán làm thay toàn bộ"); phần lớn số phút là ước lượng, số liệu chủ yếu của Mỹ | Bỏ ý không có quy trình thật; ghi rõ số phút là ước lượng cần bấm giờ, số liệu quốc tế chỉ dùng để chọn đề |
| CP2 Problem Card | Gợi ý top 3, viết nháp 3 Problem Card và quy trình nháp | Tách được bước nghẽn và đề xuất cách đo cụ thể; chỉ ra phương án không dùng AI | Số phút trong quy trình chủ yếu là ước lượng | Ghi rõ trên từng quy trình là số ước lượng, cần bấm giờ thật |
| CP4 Research | Gợi ý giải pháp đã có (cổng hóa đơn điện tử, MISA, BILL) và câu hỏi phỏng vấn theo The Mom Test | Câu hỏi tập trung vào lần gần nhất và số phút, tránh câu "bạn có muốn…" | Chưa mở kiểm tra từng trang sản phẩm; không có trích dẫn phỏng vấn thật | |
| CP3 Cluster / OST | Dùng ChatGPT để tạo ảnh sơ đồ cluster và cây OST | Vẽ nhanh sơ đồ từ nội dung đã có | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Tôi học được cách mọi người phân tích và đánh giá một bài toán khác nhau như thế nào. Bạn Trung là bác sĩ nên có số phút thật của từng bước, còn card của tôi chủ yếu dựa vào số liệu nước ngoài. Sự khác biệt đó giúp tôi học được khả năng nghiên cứu sâu về một vấn đề ngoài lĩnh vực của mình, như y tế. Khi tham gia vào một vấn đề như vậy, tôi thấy mình học hỏi khá nhanh. Tôi cũng thấy vấn đề của Đức khá chung chung, chưa đủ để gây ấn tượng với các coach.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Không. Lúc đầu mọi người nghĩ ra 3 vấn đề thực tế mà con người đang gặp phải trong đời sống, rồi mới đưa ra các giải pháp để xử lý các vấn đề đó. Nhóm phân tích nhu cầu và tình hình thực tế rồi mới đưa ra giải pháp. Vì đây là vấn đề về y tế nên không thể chọn full Agent được, khả năng AI sai rất cao, nên nhóm quyết định chọn Rule và Workflow.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Lúc suy nghĩ cho bài toán, tôi chỉ nghĩ đối tượng đang nhắm đến là bác sĩ thôi chứ không nghĩ đến cấp bậc. Khi nghe mọi người góp ý, tôi quyết định sửa lại (đổi sang bác sĩ junior và người muốn tìm hiểu kỹ thuật mới) để phù hợp hơn với tệp khách hàng. Ngoài ra, tôi từng hỏi nhóm 1 rằng thị trường đã có sản phẩm tương tự thì sản phẩm của bạn có gì tốt hơn. Câu hỏi đó cũng đúng với bài nhóm mình: sản phẩm tương tự đã có nhưng chỉ ở nước ngoài, nên tôi muốn triển khai ở Việt Nam.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Có. Tôi khá bất ngờ vì tỷ lệ câu hỏi lâm sàng mà bác sĩ không đi tìm câu trả lời (Del Fiol 2014: chỉ 51% câu hỏi được đi tìm) khá cao so với suy nghĩ của tôi. Lúc đầu ấn tượng của tôi là bác sĩ biết rất nhiều nên khả năng trả lời được tất cả câu hỏi là rất cao. Tôi cũng bất ngờ là các công cụ như OpenEvidence, UpToDate đã có nhưng khó dùng ở Việt Nam: rào cản về ngôn ngữ rất lớn, OpenEvidence phải xác minh bằng mã hành nghề của Mỹ (NPI), UpToDate bán theo gói Enterprise nên chi phí cao, và cả hai đều không có phác đồ của Bộ Y tế.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Phải phân tích nhu cầu của nhiều tệp khách hàng. Bác sĩ junior lẫn senior đều cần tới nó, sinh viên cũng cần có các nguồn thông tin đáng tin cậy để nghiên cứu thêm. Một điểm khó khác là đặt metric: tôi muốn tối ưu thời gian, và mức 20 phút là khá phù hợp để mọi người không cảm thấy nản.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ đánh giá và phân tích về rủi ro của sản phẩm hơn là chỉ tập trung vào xử lý vấn đề của người dùng. Ví dụ: AI trích dẫn sai tài liệu, hoặc có những tài liệu mới xuất bản gần đây thì model có cập nhật kịp không. Tôi sẽ test trên nhiều bộ câu hỏi xem hệ thống có đề xuất đúng nhất không; lúc đó tôi phải tạo một lượng data nhất định để làm. Tôi cũng muốn phỏng vấn nhiều người hơn để có thông tin cụ thể.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Vấn đề là bác sĩ tìm các nguồn paper quá lâu. Quy trình hiện tại gồm 5 bước: đặt câu hỏi chuyên môn (5'), search Google / PubMed / UpToDate (15'), scan danh sách kết quả (15'), phân loại giá trị và loại nghiên cứu kém chất lượng / sai quần thể (25'), chốt và đọc kỹ tài liệu tốt (30'). Bottleneck nằm ở bước 4; riêng phần tìm và lọc (bước 1–4) đã mất khoảng 60 phút, còn bước 5 là việc chuyên môn của bác sĩ nên giữ nguyên. Metric: giảm thời gian tìm và lọc từ khoảng 60 phút xuống dưới 20 phút. Để đánh giá, nhóm dùng bộ câu hỏi gán nhãn thủ công hoặc tự động. Boundary: AI không đưa ra quyết định điều trị, không nhập thông tin định danh bệnh nhân, mọi khuyến cáo phải dẫn đoạn gốc. Mức can thiệp: Rule xong tới Workflow. Nếu trích dẫn sai hoặc không có nguồn thì quay về tra cứu thủ công trên PubMed / UpToDate. Nhóm chọn Go phạm vi hẹp: pilot nhỏ trên kho chuyên khoa Răng Hàm Mặt.

---

## Phụ lục A. Gợi ý cluster (CP3) và Opportunity Solution Tree mẫu

| Cluster | Vấn đề thuộc cụm | Pattern |
|---|---|---|
| A. Đối chiếu chứng từ và xử lý ngoại lệ | #1 hóa đơn lệch PO/phiếu nhập, #2 đối chiếu công nợ, #9 hóa đơn sai thông tin | So khớp thủ công hai bản số liệu; khi lệch phải hỏi người khác |
| B. Chờ người khác mà không biết trạng thái | #5 nhà cung cấp hỏi thanh toán, #6 chờ duyệt thanh toán | Không thấy hóa đơn đang ở bước nào, ai đang giữ |
| C. Tìm và tổng hợp thông tin rải rác | #4 quy định mới, #8 báo cáo tuổi nợ, #10 tìm chứng từ cũ | Thông tin có nhưng nằm ở nhiều nơi |
| D. Kiểm tra và nhập liệu lặp lại | #3 tra cứu hợp lệ, #7 hạch toán | Làm cùng một thao tác cho từng hóa đơn |

Pattern mạnh nhất là **A. Đối chiếu chứng từ và xử lý ngoại lệ**, vì outcome đo được rõ (số phút từ khi nhận chứng từ đến khi "sạch để xử lý").

```text
OUTCOME (đo được): Giảm thời gian trung vị từ "nhận chứng từ" đến "chứng từ sạch, sẵn sàng xử lý"
                   từ [baseline tự đo] xuống 50% trong 8 tuần, ở 1 phòng kế toán
│
├── Opportunity 1: "Tôi không biết chứng từ lệch ở đâu cho đến khi tự dò từng dòng"
│     ├── Solution: Mẫu Excel đối chiếu tự tô màu chỗ lệch
│     └── Solution: Quy tắc khớp tự động hóa đơn–PO–phiếu nhập theo mã hàng
├── Opportunity 2: "Khi lệch, tôi không biết hỏi ai và phải chờ người ta trả lời"
│     ├── Solution: Bảng phân công người chịu trách nhiệm theo nhà cung cấp + SLA 4 giờ
│     └── Solution: Tin nhắn hỏi soạn sẵn kèm ảnh chụp chỗ lệch
├── Opportunity 3: "Nhà cung cấp lặp lại cùng một lỗi trên hóa đơn" (sai thuế suất, thiếu số PO)
│     └── Solution: Checklist lỗi thường gặp cập nhật hàng quý, kiểm tra trước khi gửi
└── [GẠCH] "Doanh nghiệp cần một chatbot AI cho kế toán"  ← solution đội lốt, không phải pain
    [GẠCH] "Cần phần mềm ERP mới"                         ← solution đội lốt
```

## Phụ lục B. Research giải pháp đã có cho card #1

> Các link là trang chủ chính thức, chưa mở kiểm tra từng trang; cần xác nhận tính năng hiện hành trước khi trích dẫn.

| Vấn đề | Công cụ/case | Link | Giải bước nào? | Điểm mạnh | Khoảng trống/rủi ro | Bài học |
|---|---|---|---|---|---|---|
| #1 Hóa đơn | Cổng tra cứu hóa đơn điện tử của cơ quan thuế | https://hoadondientu.gdt.gov.vn | Bước 2 (kiểm tra hợp lệ) | Miễn phí, chính thức | Không giải bước 3–4 (đối chiếu nội bộ) | Phần "hợp lệ" đã giải; nghẽn thật nằm ở nội bộ |
| #1 Hóa đơn | MISA (meInvoice, AMIS Kế toán) | https://misa.vn | Bước 2, 5 | Phổ biến ở DN vừa và nhỏ VN | Chưa rõ mức hỗ trợ đối chiếu 3 chiều và hỏi ngoại lệ | Kiểm tra kế toán có dùng tính năng này hay vẫn làm Excel |
| #1 Hóa đơn | BILL (AP automation, Mỹ) | https://www.bill.com | Bước 5–6 (duyệt, thanh toán) | Luồng duyệt nhiều cấp | Thiết kế cho Mỹ, không theo chuẩn hóa đơn điện tử VN | Duyệt thanh toán đã giải tốt; khác biệt nằm ở xử lý ngoại lệ |

## Phụ lục C. Câu hỏi phỏng vấn (The Mom Test) và assumption map

Nguyên tắc: hỏi về lần gần nhất đã xảy ra, về số phút và hành động đã làm; không hỏi "Bạn có muốn…", "Bạn có dùng nếu…".

**#1 Kế toán công nợ**

- Kể lần gần nhất anh/chị gặp một hóa đơn không khớp. Hóa đơn gì, lệch chỗ nào?
- Từ lúc phát hiện lệch đến lúc hạch toán được mất bao lâu? Đã hỏi ai, qua kênh nào?
- Tháng trước có bao nhiêu hóa đơn như vậy? Có ghi lại ở đâu không? (xin xem file Excel nếu được)
- Đã thử cách nào để đỡ việc này chưa? Vì sao bỏ?
- Nếu hóa đơn đó trễ thì chuyện gì xảy ra: nhà cung cấp gọi, sếp nhắc, hay sai kỳ thuế?

**Assumption map** (ưu tiên kiểm chứng ô "quan trọng + ít bằng chứng"):

| Giả định | Mức quan trọng | Bằng chứng hiện có | Cách kiểm chứng trong lab |
|---|---|---|---|
| Kế toán VN mất nhiều thời gian nhất ở bước đối chiếu, không phải chờ duyệt | Cao | Thấp (chỉ có số Mỹ) | Bấm giờ 20 hóa đơn với 2 kế toán |
| Doanh nghiệp vừa có PO/phiếu nhập điện tử để đối chiếu | Cao | Thấp | Hỏi trực tiếp, xin xem màn hình phần mềm |

---

## 7. Tài liệu tham khảo

> Cần mở báo cáo gốc của từng tổ chức để xác nhận trước khi đưa số vào slide.

- Ardent Partners — The State of ePayables 2024: Money Never Sleeps; AP Metrics that Matter; báo cáo 2026.
- VCCI — PCI 2024.
- McKinsey Global Institute — The social economy (2012).
