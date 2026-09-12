# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyen Tuan Thanh
- Mã học viên: 2A202602640
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): AI researcher, thường đọc paper và tìm hướng giải pháp AI phù hợp cho các bài toán doanh nghiệp.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Nhận yêu cầu nghiên cứu hoặc business problem từ team/doanh nghiệp.
  - Tìm paper, technical blog, benchmark hoặc repo liên quan tới bài toán.
  - Đọc và ghi chú các paper theo method, dataset, metric, limitation và khả năng áp dụng.
  - So sánh nhiều hướng giải pháp để viết research brief hoặc recommendation.
  - Trao đổi với engineer/business stakeholder để chuyển kết quả nghiên cứu thành experiment hoặc prototype.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian / AI có thể tốt hơn | Khi nhận một business problem mới, tôi phải tự tìm và lọc nhiều paper để xác định paper nào thật sự liên quan tới bài toán. | AI researcher, tech lead hoặc business team đang chờ hướng giải pháp. | Mỗi topic thường cần skim 10-20 paper trong 3-5 giờ trước khi shortlist được 3-5 paper đáng đọc kỹ. |
| 2 | Lặp lại / Tốn thời gian | Khi đọc paper, tôi phải tự ghi lại problem, method, dataset, metric, limitation và khả năng áp dụng vào note riêng. | AI researcher, engineer nhận lại research note. | Việc này lặp lại với hầu hết paper; mỗi paper mất khoảng 20-40 phút để đọc và ghi note có cấu trúc. |
| 3 | AI có thể tốt hơn / Tốn thời gian | Khó so sánh nhiều paper cùng topic vì mỗi paper dùng dataset, metric, baseline và assumption khác nhau. | AI researcher, tech lead cần chọn hướng thử nghiệm. | Với 5-8 paper cùng chủ đề, tôi thường mất 1-2 giờ để lập bảng so sánh và vẫn dễ bỏ sót limitation. |
| 4 | Pain từ người khác / Tốn thời gian | Business stakeholder thường hỏi "paper này áp dụng được cho bài toán của mình không?", nhưng paper viết theo ngôn ngữ học thuật nên khó chuyển thành khuyến nghị thực tế. | Business team, AI researcher phải giải thích lại. | Mỗi lần cần chuyển từ technical finding sang business recommendation thường mất 30-60 phút. |
| 5 | Lặp lại | Viết research brief cho mỗi hướng giải pháp thường có format gần giống nhau: context, papers reviewed, best approach, risks, next experiment. | AI researcher, manager/tech lead đọc brief. | Lặp lại mỗi khi nghiên cứu một topic mới; mỗi brief mất khoảng 1-2 giờ để tổng hợp và format. |
| 6 | Tốn thời gian / AI có thể tốt hơn | Tìm code implementation hoặc GitHub repo liên quan tới paper mất thời gian vì link có thể cũ, repo thiếu hướng dẫn, hoặc implementation không match paper chính xác. | AI researcher, ML engineer muốn thử nghiệm nhanh. | Mỗi paper thường cần thêm 15-45 phút để kiểm tra repo, dependency, license và mức độ usable. |
| 7 | AI có thể tốt hơn | Khó phát hiện nhanh limitation/risk của paper trước khi đề xuất cho doanh nghiệp, ví dụ dataset nhỏ, chưa test production, assumption không phù hợp. | AI researcher, doanh nghiệp nhận khuyến nghị. | Nếu chỉ đọc abstract/conclusion dễ bỏ sót; cần đọc method/experiment kỹ hơn, thường mất khoảng 30 phút/paper. |
| 8 | Pain từ người khác | Engineer nhận research recommendation nhưng thiếu experiment plan cụ thể, nên phải hỏi lại: dùng dataset nào, baseline nào, metric nào. | ML engineer, AI researcher. | Sau khi gửi research note thường có 1-2 vòng hỏi lại nếu note chưa đủ actionable. |
| 9 | Lặp lại / Tốn thời gian | Cập nhật paper mới trong cùng một domain khó vì paper ra liên tục, phải kiểm tra arXiv, Google Scholar hoặc leaderboard thủ công. | AI researcher theo dõi domain dài hạn. | Mỗi tuần mất khoảng 30-60 phút để scan paper mới cho 1-2 topic đang theo dõi. |
| 10 | Tốn thời gian | Khi cần trích dẫn nguồn cho báo cáo nội bộ, tôi phải quay lại từng paper để lấy đúng claim, metric, dataset và citation. | AI researcher, manager đọc báo cáo. | Mỗi báo cáo mất thêm 30-45 phút để verify lại nguồn và tránh quote sai. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Tôi mô tả vai trò AI researcher thường đọc paper để tìm giải pháp cho doanh nghiệp, sau đó nhờ AI gợi ý thêm problem theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác.
- Ý dùng được: AI giúp tôi nhìn rõ các pain lặp lại như lọc paper, ghi note có cấu trúc, so sánh nhiều paper, viết research brief và chuyển technical finding thành business recommendation.
- Ý bỏ vì không phải pain thật: Tôi bỏ các ý quá rộng như "xây AI research assistant toàn năng" hoặc "tự động đọc toàn bộ paper và ra quyết định thay researcher", vì những ý đó vượt scope và rủi ro cao.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Khi nhận một business problem mới, tôi phải tự tìm và lọc nhiều paper để xác định paper nào thật sự liên quan tới bài toán. | Actor rõ, workflow search-skim-shortlist có thể vẽ được, bottleneck nằm ở bước lọc relevance. Impact lớn vì nếu shortlist sai thì cả hướng nghiên cứu sau đó bị lệch. | Chưa chắc tiêu chí "paper liên quan" nên được chấm bằng keyword, embedding similarity hay human review. |
| 2 | Khó so sánh nhiều paper cùng topic vì mỗi paper dùng dataset, metric, baseline và assumption khác nhau. | Đây là bước quyết định hướng recommendation, tốn 1-2 giờ cho mỗi topic, và AI có thể hỗ trợ trích xuất cấu trúc so sánh. | Chưa chắc có thể chuẩn hóa metric giữa các paper quá khác nhau hay không. |
| 3 | Engineer nhận research recommendation nhưng thiếu experiment plan cụ thể, nên phải hỏi lại: dùng dataset nào, baseline nào, metric nào. | Có pain từ người khác, có handoff rõ giữa researcher và engineer, dễ đo bằng số vòng hỏi lại và thời gian chuẩn bị experiment. | Chưa chắc bottleneck nằm ở research note hay ở việc engineer chưa hiểu business context. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Lọc paper liên quan khi nhận business problem mới

```text
Problem 1 câu: AI researcher mất nhiều thời gian lọc paper liên quan khi nhận business problem mới, khiến việc đề xuất hướng giải pháp cho doanh nghiệp bị chậm.

Actor: AI researcher chịu trách nhiệm tìm hướng giải pháp AI cho bài toán doanh nghiệp.

Thời điểm / bối cảnh: Khi team hoặc doanh nghiệp đưa ra một bài toán mới, ví dụ cần cải thiện search, recommendation, forecasting, OCR hoặc chatbot nội bộ.

Current workflow 3-7 bước:
1. Nhận business problem và mô tả yêu cầu ban đầu.
2. Tách keyword/domain liên quan để search paper.
3. Tìm paper trên Google Scholar, arXiv, Papers with Code hoặc blog kỹ thuật.
4. Skim title, abstract, introduction và conclusion của 10-20 paper.
5. Đọc kỹ 3-5 paper có vẻ phù hợp.
6. Ghi note và shortlist paper đáng dùng cho recommendation.

Bottleneck: Bước 4 - skim và đánh giá relevance của nhiều paper, vì paper dùng thuật ngữ học thuật khác với ngôn ngữ business.

Impact: Mỗi topic mất khoảng 3-5 giờ trước khi có shortlist tốt. Nếu lọc sai, researcher có thể đi theo hướng giải pháp không phù hợp và làm chậm cả vòng thử nghiệm.

Success metric: Giảm thời gian shortlist từ 3-5 giờ xuống dưới 90 phút, vẫn giữ được ít nhất 3 paper liên quan để đọc kỹ và không bỏ sót paper quan trọng.

Non-AI alternative: Dùng checklist keyword, search query chuẩn, thư mục paper theo domain và template đánh giá relevance.

AI hypothesis: AI có thể đọc abstract/introduction, trích xuất problem-method-dataset-metric và gợi ý relevance score theo business problem. Researcher vẫn duyệt shortlist cuối.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 240 phút

[1 Nhận business problem: 15'] → [2 Tách keyword/search query: 20'] → [3 Search paper: 45'] → [4 Skim 10-20 paper: 120'] → [5 Đọc kỹ 3-5 paper: 60'] → [6 Ghi shortlist: 20']  <-- bottleneck ở bước skim

FUTURE STATE — 90 phút

[1 Nhập business problem + tiêu chí: 10'] → [2 Rule/search lấy candidate papers: 20'] → [3 AI trích xuất abstract/method/metric + gợi ý relevance: 20'] → [4 Researcher review shortlist: 30'] → [5 Chốt 3-5 paper đọc kỹ: 10']  <-- human boundary

Fallback: nếu AI đánh giá relevance sai hoặc bỏ sót hướng quan trọng, researcher quay lại search thủ công bằng keyword/checklist và bỏ phần gợi ý của AI.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — So sánh nhiều paper cùng topic

```text
Problem 1 câu: AI researcher mất nhiều thời gian so sánh nhiều paper cùng topic vì mỗi paper dùng dataset, metric, baseline và assumption khác nhau.

Actor: AI researcher và tech lead cần chọn hướng giải pháp để thử nghiệm.

Thời điểm / bối cảnh: Sau khi đã shortlist được 5-8 paper liên quan và cần quyết định paper/method nào đáng dùng cho prototype.

Current workflow 3-7 bước:
1. Mở từng paper đã shortlist.
2. Đọc method, experiment, dataset và baseline.
3. Ghi lại metric chính của từng paper.
4. Tự lập bảng so sánh trong note hoặc spreadsheet.
5. Đọc limitation và assumption để đánh giá rủi ro.
6. Viết recommendation cho tech lead/business team.

Bottleneck: Bước 4-5 - chuẩn hóa bảng so sánh và phát hiện limitation, vì mỗi paper trình bày metric và setup khác nhau.

Impact: Với 5-8 paper, tôi thường mất 1-2 giờ để so sánh. Nếu bảng so sánh thiếu limitation, team có thể chọn method đẹp trên paper nhưng khó áp dụng vào dữ liệu thật.

Success metric: Giảm thời gian lập comparison table từ 90 phút xuống dưới 30 phút, có đủ các cột method, dataset, metric, baseline, limitation và business fit.

Non-AI alternative: Dùng spreadsheet template cố định và checklist đọc paper thủ công.

AI hypothesis: AI có thể trích xuất các field chuẩn từ paper và tạo bảng so sánh nháp. Researcher kiểm lại các số liệu và limitation quan trọng trước khi dùng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 100 phút

[1 Mở từng paper: 10'] → [2 Đọc method/experiment: 35'] → [3 Ghi metric/dataset/baseline: 25'] → [4 Lập bảng so sánh: 20'] → [5 Viết recommendation: 10']  <-- bottleneck ở bước trích xuất và chuẩn hóa thông tin

FUTURE STATE — 35 phút

[1 Upload/dán paper sections: 5'] → [2 AI trích xuất field chuẩn: 10'] → [3 AI tạo comparison table nháp: 5'] → [4 Researcher review số liệu/limitation: 15']  <-- human boundary

Fallback: nếu AI trích metric hoặc baseline sai, researcher dùng spreadsheet template và điền thủ công từ paper gốc.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Handoff research recommendation cho engineer

```text
Problem 1 câu: Engineer khó triển khai thử nghiệm từ research recommendation vì note thiếu experiment plan cụ thể như dataset, baseline, metric và bước chạy thử.

Actor: ML engineer nhận research recommendation và AI researcher handoff kết quả nghiên cứu.

Thời điểm / bối cảnh: Sau khi researcher đã chọn hướng giải pháp và cần chuyển cho engineer để làm experiment hoặc prototype.

Current workflow 3-7 bước:
1. Researcher viết research note hoặc brief.
2. Researcher gửi recommendation cho engineer.
3. Engineer đọc note và xác định cần làm experiment gì.
4. Engineer hỏi lại researcher về dataset, baseline, metric hoặc scope.
5. Researcher giải thích thêm hoặc sửa note.
6. Engineer mới bắt đầu setup experiment.

Bottleneck: Bước 4-5 - vòng hỏi lại giữa engineer và researcher vì recommendation chưa đủ actionable.

Impact: Thường phát sinh 1-2 vòng hỏi lại sau khi gửi note. Mỗi vòng có thể làm chậm experiment từ vài giờ tới một ngày tùy lịch của hai bên.

Success metric: Giảm số vòng hỏi lại từ 1-2 vòng xuống tối đa 1 vòng, và engineer có thể tạo experiment plan đầu tiên trong dưới 30 phút sau khi nhận brief.

Non-AI alternative: Dùng template handoff bắt buộc gồm objective, dataset, baseline, metric, steps, risk và owner.

AI hypothesis: AI có thể kiểm tra research note trước khi gửi và chỉ ra field còn thiếu; hoặc tạo experiment plan nháp từ recommendation. Researcher vẫn duyệt nội dung trước khi gửi engineer.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 1-2 vòng hỏi lại

[1 Researcher viết note: 60'] → [2 Gửi engineer: 5'] → [3 Engineer đọc: 20'] → [4 Engineer hỏi lại: vài giờ chờ phản hồi] → [5 Researcher sửa/giải thích: 30']  <-- bottleneck ở handoff thiếu field

FUTURE STATE — dưới 30 phút để engineer có experiment plan nháp

[1 Researcher viết note theo template: 45'] → [2 AI kiểm thiếu field và draft experiment plan: 10'] → [3 Researcher review/sửa: 15'] → [4 Engineer nhận brief đầy đủ: 5']  <-- human boundary

Fallback: nếu AI tạo experiment plan không sát thực tế, researcher chỉ dùng checklist field bắt buộc và tự sửa trước khi handoff.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 - Lọc paper liên quan khi nhận business problem mới.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Tôi muốn pitch card này vì workflow rất rõ: nhận problem -> search paper -> skim -> đọc kỹ -> shortlist -> recommendation. Bottleneck nằm ở bước skim 10-20 paper, thường mất 3-5 giờ cho một topic mới. Nếu giải quyết tốt bước này, researcher có thể tạo shortlist nhanh hơn và giúp team chọn hướng thử nghiệm sớm hơn.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Tiêu chí "paper liên quan" nên đo thế nào để không chỉ dựa vào cảm giác của researcher? Với bài này, rule/checklist search đã đủ chưa hay thật sự cần AI hỗ trợ đọc và đánh giá abstract?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Actor và workflow rõ, nhưng metric "paper liên quan" có thể còn chủ quan; nếu không có human review thì AI dễ đánh giá sai relevance.
- Tôi sửa gì: Tôi thêm human boundary ở bước researcher review shortlist, và đặt success metric là giảm thời gian shortlist nhưng vẫn giữ ít nhất 3 paper liên quan để đọc kỹ.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
