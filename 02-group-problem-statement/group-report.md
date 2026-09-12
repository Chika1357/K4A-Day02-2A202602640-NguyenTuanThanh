# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Tuấn Thành | 2A202602640 | Facilitator; tổng hợp Problem Card và workflow nghiên cứu |
| 2   | Nguyễn Đức Anh | 2A202602508 | Research về người dùng, accessibility và giải pháp có sẵn |
| 3   | Lò Văn Long | 2A202602541 | Workflow; mô tả pain trong phát triển sản phẩm HTML5 |
| 4   | Hoàng Quốc Việt | 2A202602563 | Research/validation; tổng hợp candidate trong bối cảnh giáo dục |

**Candidate problem nhóm chọn (1 câu):**

Người Điếc dùng ngôn ngữ ký hiệu gặp khó khi tiếp cận video tiếng Việt trên YouTube vì phụ đề không luôn phù hợp và video hiếm khi có phiên dịch ngôn ngữ ký hiệu.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Tuấn Thành | Lọc paper liên quan khi nhận business problem mới | AI researcher, tech lead và business team chờ hướng giải pháp | Skim 10-20 paper để đánh giá relevance khi thuật ngữ học thuật khác ngôn ngữ business; mất 3-5 giờ/topic | Workflow và metric thời gian rõ; cần human review để tránh bỏ sót paper quan trọng |
| 2 | Nguyễn Tuấn Thành | So sánh nhiều paper cùng topic | AI researcher và tech lead | Chuẩn hóa dataset, metric, baseline và limitation giữa 5-8 paper; mất 1-2 giờ | Có cấu trúc rõ, nhưng chất lượng so sánh cần researcher kiểm số liệu gốc |
| 3 | Nguyễn Tuấn Thành | Handoff research recommendation cho engineer | ML engineer và AI researcher | Note thiếu dataset, baseline, metric nên phát sinh 1-2 vòng hỏi lại | Pain ở handoff rõ; template/checklist có thể đã giải phần lớn |
| 4 | Lò Văn Long | Giải quyết bất đồng UI/UX giữa chuyên viên Hóa học và giám đốc dự án trước khi dev code bài thí nghiệm HTML | Dev HTML5, chuyên viên môn Hóa, giám đốc dự án | UI/UX bị bác sau khoảng 20 giờ code, phải làm lại 16-24 giờ và trễ release 5-7 ngày | Pain sản phẩm thật, workflow trước/sau rõ; cần xác định AI có hơn prototype review sớm hay không |
| 5 | Lò Văn Long | Sinh CSS/Canvas animation mô phỏng phản ứng Hóa học từ mô tả hiện tượng | Frontend/HTML5 developer | Viết hiệu ứng hạt Canvas và CSS keyframes thủ công mất 3-4 giờ/bài | Tăng năng suất code, nhưng phạm vi thiên về kỹ thuật cá nhân |
| 6 | Lò Văn Long | Đóng gói asset ảnh và minify HTML5 dưới 5 MB | Frontend developer, người dùng web trường học | Nén ảnh và minify thủ công mất 45-60 phút/bài, dễ sót file nặng | Bài toán rõ nhưng build tool/rule là lời giải phù hợp hơn AI |
| 7 | Hoàng Quốc Việt | Lập kế hoạch giảng dạy lặp cho 35 tuần | Giáo viên bộ môn | Ghép bài và xếp thứ tự cho từng tuần, lặp 35 lần | Đầu vào/đầu ra có cấu trúc; cần xác minh baseline trước khi khẳng định mức tiết kiệm |
| 8 | Hoàng Quốc Việt | Lọc công văn của quận gửi đến trường | Hiệu trưởng | Đọc toàn văn để tự suy ra phần liên quan tới trường | Đúng thế mạnh trích xuất của LLM, nhưng bỏ sót hạn hành chính là rủi ro cao |
| 9 | Hoàng Quốc Việt | Bật hotspot khi lên xe | Bố của Việt | Tìm mục điểm phát sóng trong Cài đặt | Một điều kiện-một hành động; nên dùng shortcut/rule, không cần AI |
| 10 | Nguyễn Đức Anh | Hỗ trợ người Điếc tiếp cận video YouTube/tin tức bằng ngôn ngữ ký hiệu | Người Điếc dùng ngôn ngữ ký hiệu | Video thường chỉ có phụ đề hoặc phụ đề tự động; phụ đề không luôn là kênh tiếp cận phù hợp | Impact xã hội lớn, nhưng phải hỏi trực tiếp người Điếc Việt Nam trước khi chốt workflow |
| 11 | Nguyễn Đức Anh | Phát hiện sự cố sức khỏe của người cao tuổi sống một mình | Người cao tuổi và người thân | Người thân không thể túc trực 24/7; chưa rõ cảm biến nào khả thi | Rủi ro an toàn cao, đòi hỏi thiết bị và quy trình y tế vượt scope lab |
| 12 | Nguyễn Đức Anh | Hỗ trợ ban đầu cho sinh viên/người trẻ chịu áp lực tâm lý | Sinh viên/người trẻ | Ngại tìm tư vấn vì chi phí, kỳ thị hoặc không biết bắt đầu | Gần người dùng nhưng ranh giới an toàn và escalation tới chuyên gia rất nhạy cảm |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Nghiên cứu và xử lý tri thức | #1, #2, #3, #8 | Tìm, đọc, trích xuất, chuẩn hóa và chuyển giao thông tin để ra quyết định | Cần người kiểm nội dung; #3 và #8 có thể cải thiện đáng kể bằng template/checklist trước |
| B — Sản xuất nội dung EdTech | #4, #5, #7 | Chuyển yêu cầu chuyên môn thành kế hoạch, UI/UX hoặc nội dung số | #4 có pain do rework lớn; #5 là tăng năng suất code; #7 có dữ liệu đầu vào khá cấu trúc |
| C — Tự động hóa rõ luật | #6, #9 | Input/điều kiện rõ, đầu ra xác định | Đây là các ví dụ nên chọn Rule/process fix thay vì AI |
| D — Tiếp cận và chăm sóc nhóm dễ bị tổn thương | #10, #11, #12 | Người dùng bị cản trở tiếp cận thông tin, chăm sóc hoặc hỗ trợ | #10 phù hợp để nghiên cứu tiếp; #11 và #12 có rủi ro an toàn cao hơn scope lab |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #10 — Tiếp cận video YouTube bằng ngôn ngữ ký hiệu | Actor và impact xã hội rõ; đã có research về VSL, thiếu phiên dịch, giới hạn phụ đề và các mô hình human-in-the-loop; so sánh Rule/Workflow/Agent được rõ | Tại thời điểm shortlist: chưa phỏng vấn 5-10 người Điếc Việt Nam, chưa chốt phương ngữ và chưa biết người dùng muốn PiP người thật hay avatar |
| #4 — Chốt UI/UX trước khi dev HTML5 | Handoff giữa ba actor rõ; có thời gian rework, ảnh hưởng tiến độ và workflow dễ vẽ | Cần kiểm chứng nguyên nhân gốc: thiếu prototype/quy trình review hay thiếu công cụ AI; domain khá hẹp theo một dự án |
| #1 — Lọc paper cho business problem | Workflow 6 bước và pain 3-5 giờ/topic rõ; metric thời gian và human boundary cụ thể | Tiêu chí relevance còn chủ quan; cần benchmark/nhãn review để đo không bỏ sót paper quan trọng |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #10 — Ngôn ngữ ký hiệu / YouTube | 5 | 4 | 4 | 5 | 3 | 5 | 3 | **29** |
| #4 — Chốt UI/UX trước khi code | 5 | 5 | 3 | 4 | 4 | 4 | 3 | **28** |
| #1 — Lọc paper cho business problem | 5 | 5 | 3 | 4 | 4 | 4 | 4 | **29** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Người Điếc dùng ngôn ngữ ký hiệu gặp khó khi tiếp cận video tiếng Việt trên YouTube vì phụ đề không luôn phù hợp và video hiếm khi có phiên dịch ngôn ngữ ký hiệu.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn candidate này vì actor bị ảnh hưởng và rào cản tiếp cận được nêu rõ, đồng thời impact không chỉ nằm ở năng suất nội bộ mà ở khả năng tiếp cận thông tin. Research Phase 4 cho thấy phụ đề không thể mặc định thay thế ngôn ngữ ký hiệu và nguồn phiên dịch viên rất hạn chế. Các giải pháp đang có như Signapse và SiMAX đều để AI tạo nháp, sau đó có người dùng/người bản ngữ duyệt, nên human boundary có cơ sở. Candidate #10 và #1 cùng 29 điểm; nhóm ưu tiên #10 vì research đã chỉ ra một khoảng trống tiếp cận có ý nghĩa và những ràng buộc cần thu hẹp bài toán. Đây là lựa chọn tạm thời: trước Phase 5, nhóm phải xác nhận pain trực tiếp với người Điếc Việt Nam.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
Không chọn #4 vì rework UI/UX đáng kể nhưng nguyên nhân có thể được xử lý trước bằng prototype, acceptance criteria và review sớm, không nhất thiết cần AI. Không chọn #1 vì pain và workflow tốt nhưng tiêu chí “paper liên quan” còn phụ thuộc đánh giá chuyên môn; nhóm chưa có bộ dữ liệu/nhãn để kiểm thử trong lab.

Các candidate #2, #3, #5, #7 và #8 đều có ích nhưng thiên về chuẩn hóa template hoặc hỗ trợ năng suất trong một workflow nội bộ. #6 và #9 phù hợp hơn với Rule/process fix. #11 và #12 có hệ quả sức khỏe và an toàn cao, đòi hỏi thiết bị, chuyên gia và quy trình escalation vượt phạm vi của bài lab hiện tại.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Nhóm có lo ngại hợp lý rằng chưa ai có bằng chứng trực tiếp từ cộng đồng Điếc, cũng chưa chắc người dùng muốn avatar thay cho người phiên dịch thật. Nhóm không giải quyết bằng cách giả định thay người dùng: vẫn chọn #10 để đi tiếp research, nhưng chốt Phase 4 là phải phỏng vấn/survey 5-10 người Điếc bằng phương thức tiếp cận phù hợp và chỉ thiết kế workflow sau khi có phản hồi.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview người dùng | 7 người Điếc; 4 dùng phương ngữ TP.HCM, 3 dùng Hà Nội | Đa số xem YouTube 5-7 ngày/tuần, 1,5-3 giờ/ngày; khi phụ đề khó hiểu thường tua lại rồi bỏ video. “Bản A chữ chạy nhanh quá... Bản B có cô phiên dịch... tôi hiểu ngay.” — P1, bản dịch được người tham gia xác nhận | 1/7 chỉ chấp nhận người thật, không chấp nhận avatar; 6/7 chỉ chấp nhận AI nếu người Điếc bản ngữ hoặc phiên dịch có chứng chỉ duyệt | Chọn PiP người thật là baseline trải nghiệm; AI chỉ được tạo nháp và phải có người Điếc/phiên dịch có năng lực duyệt |
| A/B test trên cùng mẫu | 7 người, cùng xem video 2 phút 15 giây về cấp đổi CCCD/VNeID | Bản A chỉ phụ đề: trung bình 2,3/5 câu đúng. Bản B phụ đề + PiP người thật: 4,7/5; 7/7 chọn B. Tỉ lệ sai mốc thời gian/giấy tờ: 58% ở A, 14% ở B | Đây là so sánh trên cùng 7 người, không phải hai nhóm độc lập; chưa đo bản avatar/AI | Dùng 5 câu hỏi nội dung bằng VSL làm baseline; pilot AI phải so với cả A và PiP người thật, không chỉ so với A |
| Phỏng vấn chuyên gia | 2 phiên dịch viên/chuyên gia NNKH | Sản xuất 1 phút video có kịch bản sẵn mất 60-90 phút; nếu phải sửa trên 25-30% số câu AI nháp thì không còn tiết kiệm thời gian | Đã có một pilot AI trên 1 video; chưa đủ mẫu để suy rộng tốc độ, chi phí chỉnh animation hoặc độ ổn định | Đặt ngưỡng utility: tỉ lệ câu phải sửa không vượt 30%; lỗi nghiêm trọng về nghĩa/văn hóa/ngữ pháp = 0 |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Phỏng vấn xác nhận pain trực tiếp: khi phụ đề khó hiểu, người tham gia thường tua lại rồi bỏ video; với thông tin bắt buộc mới nhờ người thân hoặc phiên dịch giải thích. A/B test sơ bộ trên cùng 7 người cho thấy PiP người thật + phụ đề giúp điểm hiểu nội dung tăng từ 2,3/5 lên 4,7/5 và được 7/7 người chọn. Tuy nhiên, đây chưa phải bằng chứng rằng avatar/AI hiệu quả: 1/7 từ chối avatar; nhóm đã chạy pilot AI hẹp bằng phương ngữ Hà Nội nhưng chưa đo mức hiểu của người dùng với bản AI.
```

Bằng chứng đính kèm: `02-group-problem-statement-interview-notes.md` (đã ẩn danh; gồm 7 interview, A/B test và 2 ý kiến chuyên gia).

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| VDS 2023 và Thông tư 17/2020/TT-BGDĐT | https://www.nso.gov.vn/tin-tuc-thong-ke/2024/11/thong-cao-bao-chi-ve-ket-qua-dieu-tra-nguoi-khuyet-tat-nam-2023/ ; https://tulieuvankien.dangcongsan.vn/he-thong-van-ban/van-ban-quy-pham-phap-luat/thong-tu-so-172020tt-bgddt-ngay-2962020-cua-bo-giao-duc-va-dao-tao-ban-hanh-quy-dinh-chuan-quoc-gia-ve-ngon-ngu-ki-hieu-6587 | Xác định bối cảnh tiếp cận và giới hạn chuẩn VSL hiện có | VDS 2023 là nguồn thống kê chính thức; Thông tư là văn bản quy phạm pháp luật được lưu trữ công khai; chuẩn nêu 408 từ/ngữ ký hiệu | Tỷ lệ khuyết tật nghe không đồng nghĩa số người Điếc dùng ký hiệu; chưa nói trực tiếp về YouTube | Không suy rộng quy mô người dùng; phải thu hẹp theo nhóm, phương ngữ và loại video |
| Signapse | https://www.signapse.ai/post/ai-sign-language-interpreter-fluency | Sinh bản dịch ký hiệu từ nội dung, sau đó đánh giá mức dễ hiểu | Có nhiều người bản ngữ duyệt đầu ra | Là tiếng Anh/BSL; không thể áp thẳng sang VSL | Đặt người Điếc/người bản ngữ ở bước duyệt, không để AI tự phát hành |
| SiMAX / Signtime và WFD/WASLI | https://theventury.com/case-studies/signtime/ ; https://wfdeaf.org/wfd-wasli-issue-statement-signing-avatars/ | Tạo gợi ý ký hiệu/animation bán tự động | Người Điếc tinh chỉnh trước phát hành | Avatar không nên thay phiên dịch viên người thật; VSL có khác biệt phương ngữ | Pilot chỉ nên làm một tập video ngắn, một phương ngữ, AI tạo nháp và người thật duyệt |
| YouTube Help — captions/subtitles chính thức | https://support.google.com/youtube/answer/4792576?hl=en ; https://support.google.com/youtube/answer/2734796?hl=en-uk | Creator thêm phụ đề, closed captions hoặc auto-caption bằng speech recognition | Có sẵn trên nền tảng, là baseline miễn phí và phổ biến để so sánh | Tài liệu chỉ mô tả nội dung chữ; không chứng minh phụ đề tương đương NNKH hoặc thay được người duyệt | Pilot phải so sánh video chỉ phụ đề với video có ký hiệu, thay vì giả định phụ đề đã giải quyết bài toán |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không nên build “avatar dịch mọi video YouTube sang VSL” hoặc để AI tự xuất bản. Hướng đáng thử là workflow human-in-the-loop cho một nhóm video ngắn, có kịch bản sẵn, một phương ngữ được cộng đồng xác nhận: AI hỗ trợ tạo nháp/chú giải, người Điếc hoặc người ký hiệu có năng lực duyệt và chỉnh trước khi công bố. Theo WFD/WASLI, pilot cũng không nên áp dụng cho nội dung live, phức tạp hoặc hệ trọng như tin khẩn cấp/y tế/chính trị. Quick validation đã xác nhận pain và baseline PiP; trước khi mở rộng pilot, nhóm cần đo độ phủ vốn từ và test mức hiểu của người dùng với bản AI đã được duyệt.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 Video xong, có phụ đề: đã có]
→ [2 Tìm phiên dịch NNKH: __ ngày, thường KHÔNG tìm được]  <-- bottleneck
→ [3 Phiên dịch dịch + quay riêng: __]
→ [4 Ghép video phiên dịch vào góc màn hình (PiP), thủ công: __]
→ [5 Xuất bản: đã có]

Thực tế: bước 2 chặn hầu hết các video lại. Đa số creator bỏ qua toàn bộ
4 bước sau và xuất bản chỉ với phụ đề, vì bước ký hiệu không nằm trong quy
trình sản xuất mặc định.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Creator | Video đã dựng | Video + phụ đề tự động | Mỗi video | Bước duy nhất luôn xảy ra |
| 2 | Creator | Nhu cầu thêm ký hiệu | Phiên dịch (nếu tìm được) | 24-48 giờ để liên hệ, gửi kịch bản và chờ chốt lịch | Baseline ghi nhận trong pilot; cần log thêm nếu muốn suy rộng sang nhiều creator |
| 3 | Phiên dịch NNKH | Nội dung video | Video phiên dịch quay riêng | 35-50 phút / 1 phút video | Gồm chuyển ngữ kịch bản 20-30 phút và quay 15-20 phút |
| 4 | Editor | 2 video: gốc và phiên dịch | Video ghép PiP | 25-40 phút / 1 phút video | Hậu kỳ, đồng bộ timecode, PiP và kiểm tra tương phản |
| 5 | Creator | Video đã ghép | Video xuất bản | Mỗi video | |

**Bottleneck chính (2-3 câu):**

```text
Bước 2. Không phải “làm chậm” mà là hầu như không có ai để làm bước này.
Hệ quả là bước 2-4 gần như không xảy ra trong thực tế và người Điếc mặc định
chỉ có phụ đề.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Lấy phụ đề có sẵn, tách câu và sinh VSL gloss: 20 giây — Rule + AI]
→ [2 AI render bản nháp ký hiệu trong khung PiP: 2 phút 10 giây]
→ [3 Người Điếc bản ngữ duyệt và sửa: 8 phút 45 giây]  <-- human boundary, bắt buộc
→ [4 Render xuất bản lần cuối: 1 phút 15 giây]

Tổng: 12 phút 30 giây cho 1 phút video, gồm 8 câu đơn và 126 từ tiếng Việt.
Scope pilot: phương ngữ Hà Nội, vốn từ đã duyệt trước, 1 người Điếc bản ngữ duyệt.

Fallback: nháp sai quá nhiều hoặc người duyệt bác bỏ → dùng PiP người thật
cho đúng video đó; không để AI tự xuất bản. Từ hoặc cấu trúc ngoài vốn từ đã
duyệt phải được đánh dấu để đánh vần ngón tay hoặc chuyển người duyệt xử lý,
không tự bịa ký hiệu.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Thời gian làm 1 phút video | 60-90 phút làm hoàn toàn bằng người | 12 phút 30 giây | Giảm 79-86% so với baseline sản xuất thủ công |
| Tổng thời gian | 24-48 giờ tìm phiên dịch + 60-90 phút/1 phút video | 12 phút 30 giây/1 phút video trong pilot | Pilot không cần tìm phiên dịch riêng, nhưng vẫn cần sắp lịch người Điếc duyệt; thời gian sắp lịch này chưa được đo |
| Số bước | 5, nhưng hiếm khi xảy ra hết | 4 | Bước lấy/tách phụ đề và sinh gloss được gộp trong 20 giây |
| Số bước thủ công | 4/5: tìm, dịch, quay, ghép | 1/4: người Điếc duyệt/sửa | Render cuối do hệ thống thực hiện |
| Tỉ lệ câu người duyệt phải sửa | Không áp dụng khi làm hoàn toàn bằng người | 25%: 2/8 câu, đạt ngưỡng ≤30% | Một câu sai trật tự Topic-Comment, một câu chọn nhầm cử chỉ đa nghĩa |
| Bottleneck chính | Thiếu người phiên dịch; chờ 24-48 giờ | Duyệt/sửa 8 phút 45 giây, là cổng chất lượng cố ý giữ lại | Bottleneck đổi từ tìm người sang kiểm chất lượng |
| Risk mới | Không có track ký hiệu để xuất bản | Bản nháp sai văn hóa/ngữ pháp mà người duyệt bỏ sót | Pilot không tự xuất bản; dừng khi có lỗi nghiêm trọng |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Người Điếc dùng ngôn ngữ ký hiệu (NNKH) làm ngôn ngữ thứ nhất, xem nội dung video tiếng Việt trên YouTube |
| **Workflow** | Video được sản xuất và xuất bản kèm phụ đề tự động; bước thêm ký hiệu không có trong quy trình mặc định vì nguồn phiên dịch NNKH rất hạn chế |
| **Bottleneck** | Bước thêm ký hiệu bị bỏ qua ở hầu hết video, không phải vì làm tệ mà vì gần như không có người để làm |
| **Impact** | Trong A/B test sơ bộ với 7 người, video chỉ phụ đề đạt trung bình 2,3/5 câu đúng; video phụ đề + PiP người thật đạt 4,7/5. Khi phụ đề không đủ, người dùng thường tua lại rồi bỏ video; thông tin bắt buộc mới nhờ người khác giải thích |
| **Success Metric** | Với cùng mẫu người dùng xem cả hai điều kiện, điểm hiểu nội dung bằng 5 câu hỏi VSL phải cao hơn baseline chỉ phụ đề 2,3/5; benchmark PiP người thật hiện là 4,7/5. Pilot AI theo dõi tỉ lệ câu phải sửa ≤30% và lỗi nghiêm trọng lọt qua = 0 |
| **Boundary** | Video dịch vụ công có kịch bản sẵn, phương ngữ Hà Nội, 126 từ nằm trong vốn từ đã duyệt; nội dung ngoài vốn từ phải đánh vần/chuyển người duyệt. Không làm live, tin khẩn cấp, y tế/chính trị hệ trọng và không để máy tự xuất bản |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Đã có baseline phụ đề/PiP người thật và một pilot AI hẹp, nhưng chưa có đo lường mức hiểu của người dùng với bản AI; mới có một video và chưa đo độ phủ vốn từ.
- Tôi sửa gì: Giữ quyết định `Not Yet` cho việc mở rộng; chỉ coi pilot Hà Nội là tín hiệu ban đầu về thời gian và tỉ lệ sửa, không suy ra AI đạt hiệu quả hiểu nội dung như PiP người thật.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Có nhiều cách diễn đạt ký hiệu vẫn đúng nếu truyền đúng ý.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Phối hợp phụ đề, danh mục 408 từ chuẩn, ngữ pháp không gian NNKH và video gốc.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ phức tạp cao × độ mơ hồ cao. Agent có thể phù hợp theo ma trận, nhưng nhóm chọn Workflow vì trình tự bước không thay đổi.
```

**Vì sao (2-3 câu):**

```text
Hai chiều phức tạp và mơ hồ đều cao, nhưng AI không cần tự quyết định bước kế tiếp: tách câu → sinh gloss → dựng nháp → người Điếc duyệt → xuất bản. Độ mơ hồ nằm ở nội dung đầu ra, không nằm ở quy trình. Vì vậy đây là Workflow có bước AI khó, không phải Agent tự lập kế hoạch.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Từ điển tra 1-1: chữ tiếng Việt → ký hiệu trong danh mục 408 từ | Chỉ đủ cho thuật ngữ cố định: chữ cái, số, tên riêng | NNKH có ngữ pháp không gian riêng; ghép từng từ dễ ra câu vô nghĩa | Không; chỉ dùng làm lớp nền bên trong Workflow |
| **Workflow** | Máy tách câu → sinh gloss → dựng bản nháp ký hiệu trong khung PiP → người Điếc duyệt bắt buộc → xuất bản | Nội dung có kịch bản cố định, trình tự bước giống nhau | Nháp sai mà người duyệt bỏ sót khi mệt hoặc số lượng lớn | Có; dùng cho toàn bộ pipeline |
| **Agent** | Máy tự tìm ngữ cảnh, tự chọn hành động và tự xuất bản không cần duyệt | Chỉ khi phải xử lý quy mô cực lớn mà không có người duyệt | Avatar thay người hoàn toàn, sai văn hóa/ngữ pháp không ai bắt được | Không |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule không giải được 70-80% case; danh mục 408 từ không phủ nội dung tự do và không xử lý ngữ pháp NNKH.
2. Các bước đi theo một đường cố định: tách câu → gloss → dựng nháp → duyệt → xuất bản.
3. Không cần Agent tự lập kế hoạch hoặc gọi tool; AI chỉ chạy các bước đã định nghĩa.
4. Người Điếc duyệt phát hiện đầu tiên ở bước 4; nháp bị sửa hoặc bác bỏ trước khi xuất bản.
5. Có thể hạ từng phần xuống Rule cho thuật ngữ cố định, nhưng toàn bộ bài toán không thể hạ xuống Rule.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Pipeline cố định, AI không cần tự quyết định bước tiếp theo. Signapse và SiMAX đều dùng mô hình máy sinh nháp rồi có người bản ngữ/người Điếc duyệt đầu ra, nên Workflow có human-in-the-loop phù hợp hơn Agent. Người duyệt là boundary bắt buộc, không phải bước tùy chọn.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Danh mục chuẩn quốc gia theo Thông tư 17/2020 chỉ có 408 từ/ngữ ký hiệu, không thể phủ nội dung tự do của video. Dịch từng từ sang từng ký hiệu còn có nguy cơ sai ngữ pháp không gian của NNKH, khiến người xem không hiểu đúng ý.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Người Điếc dùng NNKH làm ngôn ngữ thứ nhất, xem video tiếng Việt trên YouTube |
| **Workflow** | Hiện tại bước ký hiệu không có trong quy trình; pilot Hà Nội cho thấy máy dựng bản nháp ký hiệu trong khung PiP, người Điếc duyệt rồi mới xuất bản |
| **Bottleneck** | Thiếu phiên dịch khiến bước ký hiệu bị bỏ qua mặc định |
| **Impact** | A/B test sơ bộ trên cùng 7 người: điểm hiểu nội dung tăng từ 2,3/5 với phụ đề lên 4,7/5 với phụ đề + PiP người thật; 7/7 chọn PiP. Đây là evidence cho PiP, chưa phải evidence cho avatar/AI |
| **Success Metric** | Pilot AI phải cải thiện so với baseline phụ đề 2,3/5, được so sánh với benchmark PiP 4,7/5 trên 5 câu hỏi VSL. Theo dõi tỉ lệ câu phải sửa ≤30%, thời gian làm 1 phút video và lỗi nghiêm trọng lọt qua = 0 |
| **Boundary** (làm / không làm) | Làm video dịch vụ công có kịch bản sẵn bằng phương ngữ Hà Nội, 126 từ duyệt trước và người Điếc bản ngữ duyệt bắt buộc. Từ ngoài vốn từ phải đánh vần/chuyển người duyệt; không live, tin khẩn cấp, y tế/chính trị hệ trọng hoặc AI tự xuất bản |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Sau khi có phụ đề, trước khi người Điếc duyệt: tách câu, sinh gloss, dựng bản nháp ký hiệu trong khung PiP |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow vì trình tự cố định và bắt buộc có người duyệt cuối |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Nháp sai văn hóa/ngữ pháp lọt qua khi người duyệt mệt; người Điếc duyệt từng video và dừng pilot nếu có một lỗi nghiêm trọng lọt qua |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Đã phỏng vấn 7 người Điếc; hành vi xem, điểm bỏ video và ưu tiên PiP/phụ đề/avatar đã có evidence trực tiếp |
| Baseline + metric đo được chưa? | Yes | Có A/B test sơ bộ: 2,3/5 với phụ đề, 4,7/5 với PiP; có ngưỡng sửa AI ≤30% từ 2 chuyên gia |
| Data/input đủ dùng chưa? | Not Yet | Pilot đã chốt Hà Nội và 126 từ duyệt trước, nhưng mới có 1 video 8 câu; chưa biết độ phủ trên nhiều video và chưa có test với từ ngoài vốn từ |
| AI sai, hậu quả chấp nhận được không? | Yes | Có bước duyệt bắt buộc; nháp bị bác trước khi xuất bản |
| Có người review/owner không? | Yes | Người Điếc duyệt là bước bắt buộc trong thiết kế |
| Có cách non-AI đơn giản hơn không? | Yes | PiP người thật đúng nhưng không scale khi nguồn phiên dịch rất hạn chế |

**Decision:**

```text
Not Yet — chưa mở rộng ngoài pilot hẹp Hà Nội
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Khung Rule/Workflow/Agent và boundary người/máy đã rõ, có cơ sở từ WFD/WASLI, Signapse, SiMAX, Thông tư 17/2020 và phỏng vấn người dùng. A/B test sơ bộ xác nhận phụ đề + PiP người thật hiệu quả hơn phụ đề đơn thuần với đúng nhóm người dùng đã phỏng vấn. Nhóm cũng đã chạy một pilot AI hẹp bằng phương ngữ Hà Nội, đo được thời gian và tỉ lệ câu sửa. Tuy nhiên, pilot mới có một video, chưa đo mức hiểu của người dùng với bản AI so với PiP người thật và chưa biết độ phủ trên nội dung ngoài 126 từ duyệt trước. Vì vậy nhóm chưa Go cho việc mở rộng, dù pilot hẹp đã có tín hiệu ban đầu tích cực.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Pilot hẹp đã chạy: 1 video 60 giây, phương ngữ Hà Nội, 126 từ duyệt trước, 1 người Điếc bản ngữ duyệt. Bước kế tiếp trước khi Go mở rộng là lặp trên ít nhất 5 video và cho cùng mẫu người dùng xem bản phụ đề, PiP người thật và bản AI đã duyệt, rồi trả lời 5 câu hỏi qua video ký hiệu. Đo điểm hiểu nội dung, tỉ lệ câu phải sửa, thời gian làm 1 phút video và số lỗi nghiêm trọng lọt qua bước duyệt.
```

**Nếu Not Yet — cần validate gì trước:**

```text
1. Lặp pilot phương ngữ Hà Nội trên ít nhất 5 video để kiểm tra độ ổn định; pilot hiện mới có 1 video 8 câu.
2. Lấy phụ đề 5 video mẫu, đối chiếu danh mục 408 từ để đo độ phủ và xác định phần phải chuyển người duyệt.
3. Test bản AI/animation đã được người Điếc duyệt với cùng phương án PiP người thật; evidence hiện có về hiểu nội dung là PiP người thật, chưa phải AI.
4. Đọc nghiên cứu JASigning/SiGML tiếng Việt trước khi mở rộng pilot.
```

**Nếu No-Go — làm gì thay AI:**

```text
Ưu tiên PiP người thật cho các video giáo dục hoặc y tế công cộng quan trọng; hợp tác trực tiếp với phiên dịch viên có sẵn thay vì triển khai AI khi chưa đủ điều kiện an toàn.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng dùng AI cho một video ngay khi người duyệt phát hiện lỗi nghiêm trọng về nghĩa, văn hóa hoặc ngữ pháp. Quay về PiP người thật nếu có phiên dịch; nếu không, chỉ xuất bản phụ đề và gắn video vào danh sách chờ xử lý thủ công. Không xuất bản track ký hiệu AI chưa được người Điếc duyệt.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
