# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: A1
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Giáo viên chấm bài IELTS Writing Task 2 online mất khoảng 18 phút/bài, lâu nhất ở bước viết nhận xét cho những kiểu lỗi đã gặp ở bài khác (số liệu ước tính, chưa đo).
- Quyết định cuối: **Not Yet**

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

9 candidate từ 3 bảng top 3 của 3 thành viên, đánh số case 1–9.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Thắng | Khi có video dựng xong, tôi muốn chọn video và sản phẩm trên máy tính để điện thoại tự đăng và gắn thẻ sản phẩm, để không bấm tay hàng chục lần mỗi ngày | Nhân sự vận hành kênh affiliate video ngắn (TikTok Shop / Shopee Video) | Bước 5–6, tìm và chọn đúng thẻ sản phẩm trên màn hình nhỏ: 2–3 phút/video, dễ chọn nhầm phân loại | "Nếu app cập nhật giao diện đổi vị trí nút ghim sản phẩm thì tool chết à?" (chưa ghi ai hỏi) |
| 2 | Thắng | Khi chuẩn bị đợt đăng hàng loạt, tôi muốn nạp danh sách sản phẩm từ file CSV một lần, để không copy từng link | Quản lý kho nội dung affiliate / KOC Lead | Bước 3, copy tay từng dòng sản phẩm sang bảng đối chiếu: 30–45 phút/danh mục | |
| 3 | Thắng | Khi đăng nhiều video cùng một mặt hàng, tôi muốn có caption và hashtag khác nhau cho từng video, để không bị coi là nội dung trùng lặp | Creator làm video review / unboxing | Bước 2–4, nghĩ tiêu đề mới cho cùng một mặt hàng: 10–15 phút/lần | |
| 4 | Hiếu | Khi chấm bài Writing Task 2, giáo viên muốn có sẵn nhận xét nháp theo 4 tiêu chí IELTS, để chỉ cần sửa thay vì viết từ đầu | Giáo viên chấm bài Writing online, khoảng 30–50 bài/tuần (số bài ước tính). Actor có thật: nhóm đang làm việc cùng team chuyên môn | Bước 5, viết nhận xét: khoảng 7/18 phút mỗi bài (ước tính) | |
| 5 | Hiếu | Khi soạn đề Reading/Listening mới, người soạn đề muốn có nháp giải thích cho từng câu, để không mất cả buổi cho 40 câu | Người soạn đề Reading/Listening của Beacon Learner | Bước 2 và 4, dò đoạn chứa đáp án rồi viết giải thích: khoảng 5,5/7 phút mỗi câu (ước tính) | |
| 6 | Hiếu | Khi làm sai một câu Reading, học viên muốn biết đáp án nằm ở đâu và mình mắc bẫy gì, để lần sau không sai cùng kiểu | Học viên tự luyện Reading, band 5.0–6.0 | Bước 3–4, tự dò đoạn và đoán vì sao sai: khoảng 3 phút/câu sai (ước tính) | |
| 7 | Mai | Khi nhận tiền sinh hoạt đầu tháng, tôi muốn chia tiền cho từng khoản, để không tiêu hết trước cuối tháng | Sinh viên sống xa gia đình, tự quản lý tiền | Bước 3, không theo dõi tổng chi trong lúc tiêu nên dễ vượt ngân sách (chưa có số phút) | |
| 8 | Mai | Khi cuối tháng, tôi muốn gom các khoản chi từ nhiều nguồn thanh toán và biết tiền đi đâu, để điều chỉnh tháng sau | Sinh viên dùng tiền mặt, chuyển khoản và ví điện tử | Bước 4–5, nhập lại và tự phân loại từng giao dịch: tổng khoảng 40 phút/tháng | |
| 9 | Mai | Khi gần đến hạn tiền nhà, điện nước, học phí, tôi muốn được nhắc trước, để không quên thanh toán | Sinh viên tự quản lý chi phí sinh hoạt | Bước 2 và 4, tự nhớ nhiều ngày thanh toán; thông tin nằm rải rác trong tin nhắn, email (chưa có số phút) | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Soạn chữ lặp lại cho người khác đọc | Case 3 caption, case 4 nhận xét Writing, case 5 giải thích đáp án | Viết đi viết lại những đoạn chữ cùng khuôn từ dữ liệu đã có |
| B — Hiểu "vì sao" từ dữ liệu có sẵn | Case 6 vì sao sai Reading, case 8 phân tích chi tiêu | Dữ liệu đã có nhưng người dùng không tự rút ra được nhận định |
| C — Nhập liệu và thao tác tay | Case 1 đăng video, case 2 chuẩn hóa CSV, case 7 ghi từng khoản chi | Làm theo các bước cố định, chép dữ liệu từ chỗ này sang chỗ kia |
| D — Nhắc đúng hạn | Case 9 nhắc hạn thanh toán | Quên việc có hạn và chịu hậu quả |

Cluster A và B cần đọc hiểu và viết, nên có chỗ cho AI. Cluster C và D phần lớn giải được bằng quy tắc, hợp làm ví dụ cho mức Rule hơn là bài chính.

### 2.3. Opportunity Solution Tree rút gọn

Cây dựng theo case 4, từ quy trình trong Problem Card #1 của Hiếu.

```text
OUTCOME: Giảm thời gian giáo viên chấm và nhận xét một bài Writing Task 2,
         mà nhận xét vẫn chỉ đúng lỗi trong bài và band không lệch
├── Opportunity A: Viết lại nhận xét cho những kiểu lỗi đã gặp ở bài khác (bước 5, khoảng 7'/bài)
├── Opportunity B: Đánh dấu từng lỗi ngữ pháp, từ vựng trong bài mất thời gian (bước 3, khoảng 4'/bài)
├── Opportunity C: Học viên chờ 2–3 ngày mới nhận được bài chấm
└── Opportunity D: Bài chấm cuối đợt có nhận xét ngắn dần vì giáo viên mệt
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ✗ "AI chấm band rồi gửi thẳng cho học viên": là giải pháp, và đi ngược boundary "giáo viên tự chấm band".
- ✗ "Bộ nhận xét mẫu (comment bank)": là giải pháp cho opportunity A, dùng làm phương án No AI ở mục 6.2.
- ✗ "Chatbot chấm bài": là giải pháp, có chữ công cụ ngay trong tầng opportunity.

### 2.4. Chấm điểm shortlist (1–5)

> Điểm chấm sơ bộ bằng AI, chỉ dựa trên chữ trong 3 bảng top 3. AI tự ghi chú: case nào ghi ít thông tin thì điểm thấp hơn thực tế, và AI biết về Beacon nhiều hơn hai domain còn lại nên case 4–6 có thể được lợi.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 5 — Viết giải thích đáp án | 5 | 5 | 4 | 4 | 5 | 4 | 5 | 32 |
| 4 — Chấm và nhận xét Writing | 4 | 5 | 3 | **5** | 5 | **5** | 4 | 31 |
| 6 — Vì sao sai Reading | 4 | 4 | 4 | 3 | 4 | 3 | 5 | 27 |

Các case còn lại: 9 = 24, 3 = 23, 8 = 22, 1 = 21, 7 = 18, 2 = 17.

**Candidate được chọn:** case 4 — Chấm và nhận xét Writing.

**Vì sao chọn:**

- Kém case 5 một điểm (31 so với 32), nhưng cao hơn ở hai tiêu chí quan trọng nhất cho bài này: **Impact đo được** và **So sánh được 4 mức** (cùng 5 so với 4).
- Impact đo được ngay bằng cách nhờ giáo viên bấm giờ từng bài. Đủ 4 mức đều có phương án thật để so: bộ nhận xét mẫu (No AI), đếm số từ và checklist rubric (Rule), AI soạn nháp rồi giáo viên duyệt (Workflow), AI tự chấm, tự gửi (Agent).
- Hai lý do AI dùng để loại case 4 đã có cách xử lý:
  - Rủi ro chấm band ảnh hưởng tới học viên → boundary "giáo viên tự chấm band, AI không đưa ra band".
  - Actor chưa xác minh → actor đã có: nhóm đang làm việc trực tiếp với team chuyên môn chấm bài Writing, nên hỏi và nhờ bấm giờ được ngay. Cột "Actor rõ" của case 4 được AI chấm 4 khi chưa biết điều này.

**Vì sao loại các candidate còn lại:**

- **Case 5** sát điểm nhất. Chưa biết mỗi tháng có bao nhiêu đề mới và đề cũ cần viết lại, nên impact khó đo trong lab. Ghi vào hướng tiếp theo (mục 9).
- **Case 6** là cùng vấn đề với case 5, nhìn từ phía học viên. Nếu giải thích viết sẵn đủ tốt thì No AI là đủ, không còn chỗ để so 4 mức.
- **Case 1 và 2** đang viết dưới dạng giải pháp đã chọn sẵn (điều khiển app qua ADB, `catalog.py`), nên không còn gì để so giữa 4 mức. Phần lớn là tự động hóa thao tác, AI gần như không có vai trò. Case 2 là bước chuẩn bị của case 1, không phải pain riêng. Ngoài ra, tự động thao tác trên app của sàn có thể vi phạm điều khoản sử dụng; điểm này chưa kiểm tra.
- **Case 3**: lý do chọn dựa trên giả thuyết "bị bóp tương tác do spam text", chưa có bằng chứng; conversion rate cần nhiều tuần mới đo được.
- **Case 7** quá rộng: "quản lý chi tiêu" là cả một loại sản phẩm.
- **Case 8**: dữ liệu ngân hàng nhạy cảm, khó lấy trong lab.
- **Case 9**: nhắc theo lịch là việc của quy tắc, hợp làm ví dụ cho mức Rule.

**Xử lý bất đồng (nếu có):**

- AI đề xuất chọn case 5 và gộp case 6 vào làm thước đo kết quả. Hiếu chọn case 4, không gộp, vì các lý do ở trên.
- Thắng đề xuất case 1 vì đã có MVP chạy được (`adb.py`, `ui.py`, `catalog.py`).
- Nhóm chọn case 4. Case 1 được giữ làm ví dụ cho mức Rule và ghi vào hướng tiếp theo (mục 9).

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---|---:|---|
| 1 | Có giáo viên thật chấm bài Writing online cho học viên luyện thi | Value | 5 | 5 | Đã xác nhận: nhóm đang làm việc cùng team chuyên môn |
| 2 | Mỗi giáo viên chấm khoảng 30–50 bài/tuần, mỗi bài khoảng 18 phút, và bước lâu nhất là viết nhận xét (khoảng 7'), không phải bước đánh dấu lỗi | Value | 5 | 1 | ✅ |
| 3 | Sửa một bản nháp nhận xét nhanh hơn tự viết từ đầu | Usability | 5 | 1 | ✅ |
| 4 | Giáo viên chưa có, hoặc đã có nhưng chưa đủ với, bộ nhận xét mẫu (No AI) | Value | 4 | 1 | ✅ |
| 5 | AI chỉ đúng lỗi trong bài và soạn được nhận xét đủ dùng làm nháp | Feasibility | 4 | 2 | Thử trên 10 bài sau khi có giáo viên |
| 6 | Được phép đưa bài của học viên vào công cụ AI bên ngoài | Viability | 4 | 1 | Hỏi team chuyên môn |

Giả định #5 có 2 điểm bằng chứng nhờ research (mục 3.3): đã có công cụ thương mại soạn nháp nhận xét theo rubric, và một nghiên cứu về ChatGPT chấm IELTS Task 2 thấy khớp với giám khảo ở phần lớn bài nhưng có ca lệch.

Giả định #1 đã xác nhận. Giả định cần kiểm tiếp: #2, #3, #4, bằng phỏng vấn giáo viên trong team chuyên môn. **Chưa thực hiện**, xem mục 3.2.

### 3.2. Kiểm chứng

Cách đã dùng: **Research bàn giấy** (mục 3.3). **Chưa phỏng vấn, chưa làm survey.** Mục này chưa có kết quả phỏng vấn, và nhóm không điền kết quả khi chưa hỏi người thật.

Kịch bản phỏng vấn giáo viên trong team chuyên môn (theo The Mom Test, không hỏi thành viên nhóm):

1. Lần gần nhất thầy/cô chấm một đợt bài Writing là khi nào? Đợt đó bao nhiêu bài?
2. Kể lại từng bước khi chấm một bài, từ lúc mở bài tới lúc gửi lại.
3. Bước nào lâu nhất? Bài gần nhất mất khoảng bao nhiêu phút?
4. Hiện thầy/cô viết nhận xét thế nào: tự gõ, chép từ file mẫu, hay dùng công cụ gì?
5. Có kiểu lỗi nào mà tuần nào cũng phải viết lại cùng một nhận xét không? Cho xem một bài đã chấm được không?
6. Có quy định gì về việc đưa bài của học viên ra công cụ bên ngoài không?

Không hỏi: "Thầy/cô có muốn dùng AI không?", "Thầy/cô có trả tiền cho công cụ này không?".

Interview snapshot: **chưa có** — mỗi buổi phỏng vấn điền một bảng, ngay sau khi xong.

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
| Research bàn giấy | 4 nguồn | Turnitin có tính năng QuickMarks riêng cho nhận xét dùng lại; một giáo viên trên blog nói không còn phải "write the same paragraph over and over", tức pain viết lại cùng một nhận xét là có thật. Writable đã bán đúng kiến trúc AI soạn nháp, giáo viên duyệt | Bộ nhận xét dùng lại (No AI) đã có từ lâu, có thể đã đủ (giả định #4). Học viên đã tự lấy band trong vài giây bằng Writing9 mà không cần giáo viên, nên giá trị phải nằm ở nhận xét của giáo viên chứ không ở tốc độ ra band |
| Làm việc với team chuyên môn | — | Actor có thật: có giáo viên chấm bài Writing online cho học viên | Chưa có |
| Phỏng vấn | 0 | Chưa có | Chưa có |

Research bàn giấy chỉ là bằng chứng gián tiếp: nó cho biết pain có ở nơi khác, không cho biết giáo viên trong team chuyên môn có gặp không. Giả định #1 đã xác nhận nhờ làm việc trực tiếp với team chuyên môn; #2–#4 vẫn chưa được kiểm.

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Sửa theo research, chưa sửa theo phỏng vấn:

- **Thêm mốc so sánh No AI:** success metric phải so với cách dùng bộ nhận xét mẫu, không chỉ so với tự viết từ đầu, vì comment bank đã có sẵn trên thị trường (Turnitin QuickMarks).
- **Boundary chặt hơn:** AI không đưa ra con số band nào trong bản nháp. Nghiên cứu Koraishi (2024) thấy ChatGPT khớp giám khảo ở phần lớn bài nhưng có ca lệch, và kết luận AI không nên thay người chấm.
- **Bỏ hướng "chấm band nhanh cho học viên":** Writing9 đã làm việc này cho học viên tự luyện.

### 3.3. Research giải pháp đã có

Link mở và kiểm ngày 09/11/2026. Một nguồn thứ năm (bản PDF một bài báo về ChatGPT chấm IELTS trên dergipark.org.tr) mở không được nên không dùng.

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Turnitin Feedback Studio — QuickMarks | https://www.turnitin.co.uk/blog/grade-assignments-fast-turnitin-quickmark-drag-n-drop-comments | Bước 5: kéo thả nhận xét có sẵn lên bài | Không dùng AI; giáo viên tự tạo bộ nhận xét riêng và chia sẻ trong cả trường | Nội dung nhận xét là câu soạn sẵn, không viết riêng cho câu của học viên; bước 3 đánh dấu lỗi vẫn làm tay. Bài blog từ năm 2016 | Đây là mức **No AI** cần so. Nếu giáo viên đã dùng comment bank thì baseline phải đo với nó |
| Writable — AI feedback | https://intercom.help/writable/en/articles/8325060-what-are-best-practices-for-using-ai-to-grade-and-give-feedback | Bước 3–5: AI đưa điểm nháp và nhận xét nháp cho từng mục rubric | Đúng kiến trúc **Workflow**: AI soạn nháp, khuyến nghị giáo viên xem lại hết trước khi gửi | Chính trang hướng dẫn cảnh báo AI có lúc đưa thông tin sai. AI đưa cả điểm nháp. Trang không nhắc tới rubric IELTS | Mượn kiến trúc, nhưng **không để AI đưa điểm**; giáo viên tự chấm band |
| Writing9 | https://writing9.com/ | Thay cả quy trình cho học viên: chấm và nhận xét tự động | Ra band "in seconds", 14,99 USD/tháng | Trang không nhắc tới bước người kiểm tra nào; dành cho học viên tự luyện, không phải cho giáo viên | Mức **automate** cho học viên đã có sẵn. Bài của nhóm chỉ có giá trị nếu giáo viên vẫn là người chấm |
| Koraishi (2024), *Language Teaching Research Quarterly* 43, 22–42 — ChatGPT 4 chấm IELTS Writing Task 2 | https://avesis.uludag.edu.tr/yayin/9610a41d-001d-4f22-834e-579fe0ae99dd/the-intersection-of-ai-and-language-assessment-a-study-on-the-reliability-of-chatgpt-in-grading-ielts-writing-task-2 | Bước 4: chấm band | So với giám khảo chính thức: khớp cao về điểm trung bình, độ tin cậy đáng kể ở phần lớn bài | Có ca lệch và ngoại lệ; tác giả kết luận AI không nên thay người chấm | Củng cố boundary **giáo viên tự chấm band**; AI chỉ làm phần nhận xét nháp |

**Kết luận research:**

```text
Cả ba mức đã có trên thị trường: comment bank (No AI), AI soạn nháp + giáo viên duyệt (Workflow),
chấm tự động cho học viên (automate). Không có lý do tự xây trước khi biết giáo viên thật đang làm gì.
Hướng hợp lý nếu kiểm chứng xác nhận pain: Rule kiểm số từ → AI nháp nhận xét → giáo viên chấm band,
sửa nháp → giáo viên gửi.
```

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ:

```text
HIỆN TẠI — 6 bước, khoảng 18 phút/bài, 6/6 bước thủ công (ước tính, chưa đo)
Tần suất: 30–50 bài/tuần, buổi tối và cuối tuần

[1 Mở bài + đọc đề: 1'] → [2 Đọc lần 1: 3'] → [3 Đánh dấu lỗi: 4']
→ [4 Chấm band: 2'] → [5 Viết nhận xét: 7'] ← BOTTLENECK
→ [6 Gửi: 1'] → học viên
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Giáo viên | Bài nộp online + đề bài | Nắm yêu cầu của đề | 1'/bài | |
| 2 | Giáo viên | Bài viết | Nắm ý chính, ước band sơ bộ | 3'/bài | |
| 3 | Giáo viên | Bài viết | Bài có đánh dấu lỗi ngữ pháp, từ vựng | 4'/bài | Có thể là bottleneck thật (giả định #2) |
| 4 | Giáo viên | Bài đã đánh dấu + band descriptors 4 tiêu chí | Band 4 tiêu chí + overall | 2'/bài | Phán đoán chuyên môn |
| 5 | Giáo viên | Lỗi đã đánh dấu + band | Nhận xét và gợi ý sửa | 7'/bài | Phần lớn là viết lại kiểu lỗi đã gặp ở bài khác |
| 6 | Giáo viên → học viên | Bài đã chấm | Học viên nhận kết quả | 1'/bài | Học viên chờ 2–3 ngày |

**Bottleneck chính:** bước 5, viết nhận xét, khoảng 7/18 phút mỗi bài. Đây là số ước tính, cần giáo viên bấm giờ thật (giả định #2).

### 4.2. Quy trình tương lai

```text
TƯƠNG LAI — 7 bước, khoảng 11 phút/bài (kỳ vọng, chưa đo), 5/7 bước thủ công

[1 Đếm số từ, gắn cờ nếu Task 2 dưới 250 từ: 0']        ← RULE (script, chạy khi học viên nộp)
→ [2 Đánh dấu lỗi + nháp nhận xét 4 tiêu chí,
     mỗi nhận xét trích câu trong bài: chạy nền, 0' chờ]  ← AI
→ [3 Giáo viên mở bài, đọc đề + đọc bài: 4']              ← CON NGƯỜI
→ [4 Giáo viên kiểm từng lỗi AI đánh dấu: giữ / xóa / thêm: 2'] ← CON NGƯỜI
→ [5 Giáo viên tự chấm band 4 tiêu chí: 2']               ← CON NGƯỜI
→ [6 Giáo viên sửa nháp nhận xét: 2']                     ← CON NGƯỜI
→ [7 Giáo viên gửi: 1']                                   ← CON NGƯỜI

BOUNDARY: AI không đưa ra band, không gửi gì cho học viên, không sửa bài của học viên,
          không nhận xét câu không có trong bài.
PHƯƠNG ÁN QUAY VỀ: nháp sai hoặc nhạt → giáo viên bỏ nháp, dùng bộ nhận xét mẫu + checklist rubric.
                   AI ngừng hoạt động → chấm theo quy trình hiện tại.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 6 | 7 | Thêm 1 bước Rule và 1 bước AI, cả hai chạy trước khi giáo viên mở bài |
| Tổng thời gian | khoảng 18' | khoảng 11' | Cả hai đều là ước tính. Target ở v0 là dưới 10' |
| Số bước thủ công | 6/6 | 5/7 | Giáo viên vẫn đọc, chấm band, sửa và gửi |
| Bottleneck chính | Viết nhận xét (7') | Đọc bài (4') | Chấp nhận được: giáo viên phải đọc bài mới chấm được band |
| Rủi ro mới phát sinh | — | AI đánh dấu nhầm lỗi; giáo viên tin nháp mà không kiểm; nhận xét giữa các bài na ná nhau | Xử lý bằng bước 4 bắt buộc + tiêu chí đánh giá ở mục 7 |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Giáo viên chấm bài IELTS Writing Task 2 online cho học viên luyện thi, khoảng 30–50 bài/tuần |
| **Quy trình** | Buổi tối và cuối tuần, sau khi học viên nộp bài: mở bài, đọc đề → đọc bài → đánh dấu lỗi → chấm band 4 tiêu chí → viết nhận xét và gợi ý sửa → gửi lại |
| **Bottleneck** | Viết nhận xét: khoảng 7/18 phút mỗi bài, phần lớn là viết lại những kiểu lỗi đã gặp ở bài khác |
| **Impact** | Khoảng 18 phút/bài × 40 bài ≈ 12 giờ/tuần cho 1 giáo viên; học viên chờ 2–3 ngày; bài chấm cuối đợt có nhận xét ngắn dần. Tất cả là ước tính |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian mỗi bài từ khoảng 18' xuống dưới 10'; (2) giáo viên phải viết lại dưới 50% bản nháp; (3) band giáo viên chấm không lệch so với trước. Cách đo: giáo viên tự bấm giờ 10 bài trước và 10 bài sau |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không chấm band và không gửi gì cho học viên. Giáo viên kiểm mọi nhận xét trước khi gửi |

Phản biện nhận được (chạy prompt phản biện Problem Statement của worksheet CP5 với AI):

- **Baseline 18' chưa đo**, nên metric chưa có baseline thật. → Giữ nguyên ở v1, ghi rõ "chưa đo"; baseline chỉ có khi giáo viên bấm giờ (giả định #2).
- **"Viết lại dưới 50% bản nháp" chưa định nghĩa** thế nào là viết lại. → v1 định nghĩa: một nhận xét bị xóa, hoặc bị sửa quá nửa câu, tính là viết lại.
- **"Band không lệch so với trước" không nói đo bằng gì.** → v1: giáo viên chấm lại 5 bài cũ đã chấm, có nháp AI bên cạnh, so band từng tiêu chí.
- **Bottleneck nói "phần lớn là viết lại kiểu lỗi đã gặp".** Nếu đúng thế thì bộ nhận xét mẫu (No AI) đã giải được phần lớn, mà problem chưa nói vì sao bộ mẫu chưa đủ. → Đưa thành giả định #4, kiểm trước; v1 thêm metric so với No AI.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ mơ hồ cao × độ phức tạp thấp** → Workflow có AI ở một bước thường đủ.

Vì sao:

- **Mơ hồ cao:** cùng một lỗi có nhiều cách nhận xét đều chấp nhận được; không có một đáp án đúng duy nhất.
- **Phức tạp thấp:** chỉ có một nguồn input (đề + bài viết), các bước cố định, không rẽ nhánh, bước sau không cần tự quyết.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Bộ nhận xét mẫu cho các kiểu lỗi hay gặp + checklist theo 4 tiêu chí rubric (kiểu Turnitin QuickMarks) | Học viên chấp nhận nhận xét chung; bottleneck thật là "viết lại cùng một câu" | Nhận xét không chỉ vào câu cụ thể của học viên; bước 3 đánh dấu lỗi vẫn làm tay | Giữ làm **phương án quay về** và mốc so sánh |
| **Rule** | Script đếm số từ, gắn cờ Task 2 dưới 250 từ, đếm số đoạn | Lỗi chủ yếu là đếm được | Không nhận xét được Task Response, Coherence | **Dùng cho bước 1** |
| **Workflow** | Rule kiểm số từ → AI đánh dấu lỗi + nháp nhận xét 4 tiêu chí, trích câu trong bài → giáo viên kiểm lỗi, chấm band, sửa nháp → giáo viên gửi | Các bước cố định; AI chỉ làm phần đọc và viết nhận xét | AI đánh dấu nhầm; nháp nhạt khiến sửa lâu bằng tự viết | **Chọn** (có điều kiện, xem bên dưới) |
| **Agent** | AI tự chấm band, tự viết nhận xét, tự gửi và tự trả lời câu hỏi của học viên | Khi bước tiếp theo không đoán trước được, mà bài này không như vậy | Koraishi (2024): có ca lệch so với giám khảo; sai band ảnh hưởng thẳng tới học viên; mức này đã có cho học viên (Writing9) | Không chọn |

**Mức chọn:** Workflow.

**Vì sao không chọn mức đơn giản hơn:**

- **Lý do hiện có:** bộ nhận xét mẫu không viết riêng cho câu của học viên, và không giảm bước đánh dấu lỗi (4'). Rule không nhận xét được Task Response và Coherence.
- **Điểm yếu nhất của lập luận:** nhóm **chưa có bằng chứng từ người dùng** rằng No AI không đủ. Nếu phỏng vấn cho thấy giáo viên đã dùng bộ mẫu và thấy đủ, mức đúng là No AI (xem ngưỡng dừng ở mục 8).

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Vị trí các lỗi trong bài, kèm bản nháp nhận xét theo 4 tiêu chí; mỗi nhận xét trích câu gốc |
| **Judgment** — con người cân nhắc, quyết định gì? | Giáo viên quyết định lỗi nào đúng là lỗi, nhận xét nào giữ, và band của từng tiêu chí |
| **Action** — hành động cuối cùng là gì, ai làm? | Giáo viên sửa nháp và gửi bài đã chấm cho học viên |
| **Outcome** — đo kết quả bằng gì? | Phút/bài; tỉ lệ nhận xét bị viết lại; độ lệch band khi chấm có nháp so với không có nháp |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Đề bài và bài viết của học viên (có sẵn khi nộp online); band descriptors 4 tiêu chí (công khai). Chưa biết có được phép đưa bài ra công cụ ngoài không (giả định #6) |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Phần giáo viên xóa hoặc sửa trong nháp mỗi bài; lỗi AI đánh dấu nhầm bị giáo viên xóa |

### 6.4. Hai câu hỏi của Google PAIR

- **Augment hay automate?** Augment.
  - Bằng chứng: chưa có từ người dùng, vì chưa phỏng vấn. Theo worksheet, câu này phải trả lời bằng kiểm chứng, nên đây mới là giả thuyết.
  - Bằng chứng gián tiếp: Writable khuyến nghị giáo viên xem lại hết trước khi gửi; Koraishi (2024) kết luận AI không nên thay người chấm.
- **Báo nhầm hay bỏ sót, kiểu nào tệ hơn?** **Báo nhầm** tệ hơn.
  - AI đánh dấu một câu đúng là sai mà lọt tới học viên thì học viên học sai quy tắc, và giáo viên mất tin vào nháp.
  - Bỏ sót ít tệ hơn, vì giáo viên vẫn đọc cả bài ở bước 3 và tự thêm được lỗi.
  - Thiết kế nghiêng về độ chính xác:
    - mỗi lỗi phải trích câu và nêu quy tắc;
    - giáo viên xác nhận từng lỗi ở bước 4;
    - tiêu chí đánh giá #1 đặt ngưỡng cho lỗi đánh dấu nhầm.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Giáo viên chấm bài IELTS Writing Task 2 online cho học viên luyện thi, khoảng 30–50 bài/tuần. Actor có thật (team chuyên môn nhóm đang làm việc cùng); số bài/tuần chưa xác minh (giả định #2) |
| **Quy trình** | Mở bài, đọc đề → đọc bài → đánh dấu lỗi → chấm band 4 tiêu chí → viết nhận xét → gửi |
| **Bottleneck** | Viết nhận xét: khoảng 7/18 phút mỗi bài (ước tính) |
| **Impact** | Khoảng 12 giờ/tuần cho 1 giáo viên; học viên chờ 2–3 ngày (ước tính) |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian mỗi bài từ baseline đo thật (giáo viên bấm giờ 10 bài gần nhất; ước tính 18') xuống dưới 12'. (2) Thấp hơn thời gian khi giáo viên chỉ dùng bộ nhận xét mẫu. (3) Dưới 50% nhận xét trong nháp bị viết lại; một nhận xét bị xóa hoặc sửa quá nửa câu tính là viết lại. (4) Giáo viên chấm lại 5 bài cũ có nháp bên cạnh, band lệch không quá 0,5 ở mỗi tiêu chí so với lần chấm cũ. Cách đo: giáo viên tự ghi giờ và đánh dấu nhận xét bị sửa, 2 tuần pilot |
| **Boundary** | AI không đưa ra band hay con số điểm nào, không gửi gì cho học viên, không sửa bài của học viên, không nhận xét câu không có trong bài. Giáo viên kiểm mọi lỗi và nhận xét trước khi gửi |
| **AI intervention point** | Sau khi học viên nộp bài và Rule đã đếm số từ, trước khi giáo viên mở bài để chấm |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | AI đánh dấu nhầm lỗi, nhận xét chung chung, nhận xét câu không có trong bài, nhận xét kéo band của giáo viên lệch đi → giáo viên kiểm từng lỗi ở bước 4 và tự chấm band ở bước 5 |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric — target thời gian | Dưới 10' | Dưới 12' | Quy trình tương lai (mục 4.2) giữ đọc bài và chấm band cho giáo viên, ước tính còn khoảng 11'; dưới 10' không khớp với boundary |
| Success Metric — mốc so sánh | Chỉ so với tự viết | Thêm: phải nhanh hơn dùng bộ nhận xét mẫu | Research: comment bank đã có sẵn (Turnitin QuickMarks) |
| Success Metric — cách đo | "Viết lại dưới 50%", "band không lệch" chưa định nghĩa | Định nghĩa "viết lại"; cách đo band bằng chấm lại 5 bài cũ | Phản biện của AI ở mục 5 |
| Boundary | AI không chấm band, không gửi | Thêm: không có con số điểm nào trong nháp, không nhận xét câu không có trong bài | Koraishi (2024): AI có ca lệch so với giám khảo; Writable cho AI đưa điểm nháp, nhóm không đi hướng đó |
| Actor | Giáo viên chấm online, 30–50 bài/tuần | Ghi rõ actor là team chuyên môn nhóm đang làm việc cùng; số bài/tuần vẫn là ước tính | Actor có thật; chưa hỏi team về khối lượng bài |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Lỗi đánh dấu đúng | Giáo viên giữ lại ít nhất 9/10 lỗi AI đánh dấu | Hơn 1/10 lỗi bị giáo viên xóa vì không phải lỗi |
| 2 | Có trích dẫn | Mọi nhận xét trích được câu cụ thể trong bài | Có nhận xét chung chung, không chỉ vào câu nào |
| 3 | Đủ 4 tiêu chí | Task Response, Coherence & Cohesion, Lexical Resource, Grammatical Range & Accuracy đều có ít nhất 1 nhận xét | Thiếu tiêu chí nào |
| 4 | Không đưa điểm | Nháp không có con số band hay điểm nào | Có bất kỳ con số band nào |
| 5 | Sửa được nhanh | Giáo viên sửa xong nháp trong khoảng 2' | Giáo viên mất lâu hơn tự viết, hoặc bỏ cả nháp |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Cao** | Actor đã có (team chuyên môn nhóm đang làm việc cùng), nhưng chưa hỏi họ bước nào mất thời gian nhất và có đang dùng bộ nhận xét mẫu không. Research chỉ cho thấy pain "viết lại cùng một nhận xét" có ở nơi khác, và comment bank (No AI) đã có sẵn |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | TB | Giáo viên chỉ sửa văn bản, không phải học công cụ mới; nhưng chưa thử xem sửa nháp có nhanh hơn tự viết không (giả định #3) |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | TB | Input có sẵn (đề + bài + band descriptors); đã có sản phẩm thương mại làm đúng kiến trúc này (Writable). Chưa thử AI trên bài thật để biết tỉ lệ đánh dấu nhầm |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | TB | Chưa hỏi team chuyên môn có cho đưa bài của học viên ra công cụ ngoài không (giả định #6); chưa so chi phí |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:** Actor đã có, nhưng Value vẫn ở mức Cao: giả định quan trọng nhất (giáo viên mất thời gian thật ở bước viết nhận xét, và bộ nhận xét mẫu chưa đủ) chưa có bằng chứng. Nhóm đang làm việc trực tiếp với team chuyên môn nên kiểm được nhanh bằng 2–3 buổi phỏng vấn và một đợt bấm giờ, vì vậy là Not Yet, không phải No-Go.

**Nếu Go — pilot nhỏ nhất:** (dùng khi kiểm chứng xong và Value xuống TB)

- Không xây gì. 1 giáo viên, 10 bài, dán đề + bài vào một prompt chuẩn có sẵn boundary.
- Giáo viên ghi giờ từng bài, đánh dấu nhận xét bị sửa, chấm nháp theo 5 tiêu chí ở mục 7.

**Nếu Not Yet — cần kiểm chứng gì trước:**

1. Phỏng vấn 2–3 giáo viên trong team chuyên môn theo kịch bản ở mục 3.2 → kiểm giả định #2, #4.
2. Nhờ 1 giáo viên bấm giờ 10 bài gần nhất, ghi riêng thời gian từng bước → baseline thật cho metric (1).
3. Hỏi giáo viên đang dùng bộ nhận xét mẫu chưa, còn thiếu gì → quyết định No AI hay Workflow.
4. Hỏi team chuyên môn về quy định đưa bài của học viên ra ngoài → giả định #6.

**Nếu No-Go — nên làm gì thay AI:** Bộ nhận xét mẫu theo 4 tiêu chí + checklist rubric (mức No AI ở mục 6.2).

**Ngưỡng dừng:**

- Nếu 2/3 giáo viên được phỏng vấn nói mỗi bài mất dưới 10', hoặc đã dùng bộ nhận xét mẫu và thấy đủ → **No-Go**, khuyến nghị No AI.
- Nếu giáo viên trong team chuyên môn đều chấm dưới 20 bài/tuần → đổi candidate sang case 5.
- Khi pilot: nếu 2 tuần liên tiếp giáo viên viết lại trên 70% nhận xét trong nháp → quay về bộ nhận xét mẫu.
- Khi pilot: nếu có 1 lỗi AI đánh dấu nhầm mà giáo viên không phát hiện, lọt tới học viên → dừng pilot, xem lại bước 4.

---

## 9. Hạn chế và hướng tiếp theo

- **Chưa phỏng vấn, chưa survey.** Actor đã có (team chuyên môn nhóm đang làm việc cùng), nhưng mọi số phút và số bài/tuần trong bài vẫn là ước tính, kể cả baseline 18'. Phần lớn mục 5–8 phải xem lại sau khi hỏi team.
- **Bảng chấm điểm ở mục 2.4 do AI chấm sơ bộ**, trong khi worksheet CP3 yêu cầu nhóm tự pitch, tự phản biện, không dùng AI. Nhóm nên tự chấm lại.
- **Case 5** (viết giải thích đáp án khi soạn đề) là candidate cho vòng sau: actor rõ, có việc tồn đọng thật.
- **Case 1** (đăng video affiliate) là ví dụ tốt cho mức Rule, nếu nhóm muốn làm thêm.

## 10. Tài liệu tham khảo

- Turnitin, *Grade Assignments Fast: Turnitin QuickMark Drag-n-Drop Comments* (blog, 2016): https://www.turnitin.co.uk/blog/grade-assignments-fast-turnitin-quickmark-drag-n-drop-comments
- Writable Help Center, *What are best practices for using AI feedback?* (12/2025): https://intercom.help/writable/en/articles/8325060-what-are-best-practices-for-using-ai-to-grade-and-give-feedback
- Writing9: https://writing9.com/
- Koraishi, O. (2024). The Intersection of AI and Language Assessment: A Study on the Reliability of ChatGPT in Grading IELTS Writing Task 2. *Language Teaching Research Quarterly*, 43, 22–42. DOI 10.32038/ltrq.2024.43.02: https://avesis.uludag.edu.tr/yayin/9610a41d-001d-4f22-834e-579fe0ae99dd/the-intersection-of-ai-and-language-assessment-a-study-on-the-reliability-of-chatgpt-in-grading-ielts-writing-task-2
- [docs/01-worksheet.md](../../docs/01-worksheet.md), [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md)
