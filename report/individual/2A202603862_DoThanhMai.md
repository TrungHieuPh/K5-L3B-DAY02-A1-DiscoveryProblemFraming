# Báo cáo cá nhân — 2A202603862_DoThanhMai

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Đỗ Thanh Mai
- MSSV: 2A202603862
- Tên nhóm: A1
- Link repo nhóm: https://github.com/TrungHieuPh/K5-L3B-Day02-A1

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi nhận tiền sinh hoạt đầu tháng, tôi muốn phân chia tiền cho từng khoản, để không tiêu hết trước cuối tháng | Sinh viên | 2/3 tháng gần nhất hết tiền trước ngày nhận tiền tiếp theo |
| 2 | Lặp lại | Khi mua sắm hằng ngày, tôi muốn ghi lại các khoản đã chi, để biết mình đã tiêu bao nhiêu | Sinh viên | Thường quên ghi chép khoảng 5–7 khoản chi mỗi tuần |
| 3 | Tốn thời gian | Khi cuối tháng, tôi muốn tổng hợp các khoản chi từ nhiều ứng dụng thanh toán, để biết tiền đã được sử dụng vào đâu | Sinh viên | Mất khoảng 40 phút/tháng để kiểm tra lịch sử giao dịch |
| 4 | Tốn thời gian | Khi chuẩn bị đi chợ hoặc siêu thị, tôi muốn có danh sách những thứ cần mua, để không mất thời gian suy nghĩ và mua thiếu đồ | Người sống tự lập, sinh viên | Khoảng 15–20 phút mỗi lần lập danh sách |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi muốn tiết kiệm tiền ăn uống, tôi muốn biết những món ăn vừa rẻ vừa đủ dinh dưỡng, để không phải ăn uống thất thường | Sinh viên | Thường xuyên chọn đồ ăn nhanh vì không biết nấu món gì |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi có nhiều khoản chi trong tháng, tôi muốn biết khoản nào đang chiếm nhiều ngân sách nhất, để điều chỉnh thói quen tiêu dùng | Sinh viên | Không xác định được khoản chi lớn nhất nếu không kiểm tra lại giao dịch |
| 7 | Pain từ người khác | Khi sống chung trong phòng trọ, tôi muốn phân chia tiền điện, nước và tiền sinh hoạt rõ ràng, để tránh tranh cãi với bạn cùng phòng | Sinh viên ở ghép | Thường mất 10–15 phút để đối chiếu tiền mỗi tháng |
| 8 | Pain từ người khác | Khi bố mẹ gửi tiền sinh hoạt, bố mẹ muốn biết con sử dụng tiền hợp lý hay không, để yên tâm hơn | Phụ huynh, sinh viên | Cuối tháng thường xuyên phải hỏi lại con đã sử dụng tiền như thế nào |
| 9 | Lặp lại | Khi gần đến hạn đóng học phí, tiền nhà hoặc tiền điện, tôi muốn được nhắc trước, để không quên thanh toán | Sinh viên | Đã từng quên hạn thanh toán ít nhất một lần trong học kỳ |
| 10 | Tốn thời gian | Khi muốn mua một món đồ, tôi muốn so sánh giá ở nhiều cửa hàng, để lựa chọn sản phẩm phù hợp với ngân sách | Sinh viên | Mất khoảng 20–30 phút để tìm và so sánh giá |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Quản lý chi tiêu cá nhân (#1)| Vấn đề phổ biến, xảy ra thường xuyên, có thể đo lường bằng thời gian và số tiền| Người dùng có sẵn sàng nhập từng khoản chi không?|
| 2 | Tổng hợp và phân tích chi tiêu (#3, #6)| Mất thời gian, dữ liệu đến từ nhiều nguồn, AI có thể hỗ trợ phân loại và phân tích| AI phân loại giao dịch có chính xác không?|
| 3 | Nhắc nhở hạn thanh toán (#9)| Có hậu quả thực tế nếu quên, quy trình đơn giản, dễ kiểm chứng| Người dùng có thường xuyên bỏ qua thông báo không?|

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận tiền sinh hoạt đầu tháng, tôi muốn phân chia tiền cho từng khoản, để không tiêu hết trước cuối tháng|
| Actor | Sinh viên sống xa gia đình, tự quản lý tiền sinh hoạt|
| Thời điểm / bối cảnh | Đầu tháng khi nhận tiền từ gia đình hoặc tiền lương làm thêm|
| Quy trình hiện tại (3–7 bước) | 1. Nhận tiền sinh hoạt. 2. Ước lượng các khoản cần chi. 3. Chi tiêu hằng ngày. 4. Kiểm tra số dư tài khoản khi cần. 5. Cuối tháng xem lại tiền còn lại. 6. Xin thêm tiền nếu thiếu|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Không theo dõi tổng chi tiêu trong quá trình sử dụng nên dễ vượt ngân sách|
| Impact (nếu không giải thì sao) | Có thể thiếu tiền sinh hoạt vào cuối tháng, phải vay bạn bè hoặc xin thêm tiền gia đình|
| Success metric (baseline → target) | Giảm số lần vượt ngân sách từ 2 lần/tháng xuống tối đa 0–1 lần/tháng; giảm thời gian theo dõi chi tiêu xuống dưới 10 phút/tuần|
| Phương án không dùng AI | Sử dụng Excel hoặc Google Sheets để ghi chép thu nhập, chi tiêu và đặt giới hạn ngân sách|
| Giả thuyết về AI (nếu có) | AI tự động phân loại các khoản chi, phân tích thói quen tiêu dùng và đưa ra cảnh báo khi người dùng có nguy cơ vượt ngân sách|
| Cảm nhận nhanh | Workflow|

Quy trình nháp hiện tại:

```HIỆN TẠI — Quy trình quản lý chi tiêu

[1 Nhận tiền sinh hoạt]
          ↓
[2 Ước lượng các khoản cần chi]
          ↓
[3 Chi tiêu hằng ngày]
          ↓
[4 Kiểm tra số dư khi cần]
          ↓
[5 Cuối tháng kiểm tra lại]
          ↓
[6 Thiếu tiền → Xin thêm tiền]

          BOTTLENECK
Không theo dõi được tiền đã chi
và không biết mình đang vượt ngân sách.

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cuối tháng, tôi muốn tổng hợp các khoản chi từ nhiều nguồn thanh toán và biết tiền đã được sử dụng vào đâu, để đánh giá tình hình tài chính và điều chỉnh thói quen tiêu dùng cho tháng tiếp theo|
| Actor | Sinh viên sống xa gia đình, thường xuyên sử dụng tiền mặt, chuyển khoản ngân hàng và ví điện tử|
| Thời điểm / bối cảnh | Cuối tháng hoặc khi nhận thấy số dư tài khoản giảm nhanh nhưng không nhớ đã chi tiêu vào những khoản nào|
| Quy trình hiện tại (3–7 bước) | 1. Mở ứng dụng ngân hàng để kiểm tra lịch sử giao dịch. 2. Mở ví điện tử để xem các khoản thanh toán. 3. Kiểm tra lại những khoản chi bằng tiền mặt. 4. Ghi chép các giao dịch vào Excel hoặc Google Sheets. 5. Tự phân loại các khoản chi theo từng danh mục. 6. Tính tổng tiền đã chi cho mỗi danh mục. 7. Đánh giá khoản nào đang tiêu tốn nhiều tiền nhất và điều chỉnh ngân sách|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 và 5: Phải nhập lại dữ liệu từ nhiều nguồn và tự phân loại từng giao dịch. Một số giao dịch có nội dung không rõ ràng khiến người dùng mất thêm thời gian xác định mục đích chi tiêu|
| Impact (nếu không giải thì sao) | Mất khoảng 40 phút mỗi tháng để tổng hợp và phân loại chi tiêu. Người dùng khó nhận ra những khoản chi nhỏ nhưng lặp lại nhiều lần, dẫn đến không kiểm soát được thói quen tiêu dùng|
| Success metric (baseline → target) | Giảm thời gian tổng hợp chi tiêu từ 40 phút xuống dưới 10 phút/tháng; độ chính xác phân loại giao dịch đạt tối thiểu 90%; người dùng xác định được 3 danh mục chi tiêu lớn nhất|
| Phương án không dùng AI | Sử dụng Excel hoặc Google Sheets với các danh mục chi tiêu được thiết lập sẵn. Người dùng nhập giao dịch thủ công, sử dụng hàm SUMIF và biểu đồ để thống kê tổng chi tiêu|
| Giả thuyết về AI (nếu có) | AI có thể đọc dữ liệu giao dịch do người dùng cung cấp, tự động nhận diện nội dung và phân loại các khoản chi theo danh mục. Sau đó, AI tổng hợp báo cáo, phát hiện những khoản chi bất thường và đưa ra nhận xét về thói quen tiêu dùng|
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```HIỆN TẠI — 40 phút/tháng

[1 Mở ứng dụng ngân hàng]
          ↓
[2 Kiểm tra ví điện tử]
          ↓
[3 Kiểm tra khoản chi tiền mặt]
          ↓
[4 Nhập dữ liệu vào Excel] 
          ↓
[5 Tự phân loại giao dịch] ← BOTTLENECK
          ↓
[6 Tính tổng chi tiêu]
          ↓
[7 Đánh giá và điều chỉnh ngân sách]

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến kỳ thanh toán tiền nhà, tiền điện, tiền nước hoặc học phí, tôi muốn được nhắc nhở trước hạn và biết khoản nào cần thanh toán, để không quên thời hạn và tránh phát sinh chi phí không cần thiết|
| Actor | Sinh viên sống xa gia đình, tự quản lý các khoản chi phí sinh hoạt và học tập|
| Thời điểm / bối cảnh | Đầu tháng hoặc những ngày gần đến hạn thanh toán tiền nhà, hóa đơn điện nước và học phí|
| Quy trình hiện tại (3–7 bước) | 1. Nhận thông báo về khoản cần thanh toán từ chủ nhà, nhà trường hoặc đơn vị cung cấp dịch vụ. 2. Ghi nhớ ngày thanh toán hoặc ghi vào ứng dụng ghi chú. 3. Tiếp tục học tập và làm việc. 4. Tự kiểm tra lại các khoản cần đóng khi gần đến cuối tháng. 5. Tìm lại tin nhắn hoặc thông báo chứa thông tin thanh toán. 6. Thực hiện chuyển khoản hoặc thanh toán. 7. Kiểm tra lại xem đã thanh toán đầy đủ hay chưa|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 và 4: Người dùng phải tự ghi nhớ nhiều ngày thanh toán khác nhau. Thông tin thường nằm rải rác trong tin nhắn, email hoặc thông báo nên dễ bị bỏ sót|
| Impact (nếu không giải thì sao) | Có nguy cơ thanh toán trễ hạn, phát sinh phí phạt hoặc bị gián đoạn dịch vụ. Người dùng phải mất thời gian tìm lại thông tin về số tiền và thời hạn thanh toán|
| Success metric (baseline → target) | Giảm số lần quên hạn thanh toán xuống 0 trong 2 tháng thử nghiệm; tỷ lệ thanh toán đúng hạn đạt 100%; thông báo nhắc nhở được gửi trước hạn ít nhất 1–3 ngày|
| Phương án không dùng AI | Sử dụng Google Calendar hoặc ứng dụng nhắc việc để tạo lịch thanh toán định kỳ. Người dùng tự nhập số tiền, ngày đến hạn và thiết lập thông báo nhắc nhở|
| Giả thuyết về AI (nếu có) | AI có thể đọc thông tin thanh toán do người dùng cung cấp từ tin nhắn, email hoặc hình ảnh hóa đơn, nhận diện số tiền và ngày đến hạn, sau đó tạo nhắc nhở và tổng hợp các khoản sắp phải thanh toán|
| Cảm nhận nhanh | Workflow hoặc Agent|

Quy trình nháp hiện tại:

```HIỆN TẠI — Quản lý hạn thanh toán

[1 Nhận thông báo thanh toán]
          ↓
[2 Tự ghi nhớ hoặc ghi chú]
          ↓
[3 Tiếp tục học tập, làm việc]
          ↓
[4 Tự kiểm tra các khoản cần đóng]
          ↓
[5 Tìm lại thông tin thanh toán] ← BOTTLENECK
          ↓
[6 Thực hiện thanh toán]
          ↓
[7 Kiểm tra trạng thái thanh toán]

RỦI RO: Quên hạn → Thanh toán trễ → Phát sinh phí phạt

```

### Card muốn pitch nhất

- Card số: Card #2 – Tổng hợp và phân tích chi tiêu cá nhân
- Vì sao: Đây là vấn đề mà nhiều sinh viên có thể gặp phải khi sử dụng nhiều phương thức thanh toán khác nhau như tiền mặt, ngân hàng và ví điện tử. Việc tổng hợp và phân loại các khoản chi thường mất thời gian, đặc biệt khi người dùng phải thực hiện thủ công. Vấn đề có quy trình rõ ràng, có thể đo lường thời gian xử lý và độ chính xác phân loại. Ngoài ra, AI có thể hỗ trợ trực tiếp ở công đoạn đọc, phân loại và tổng hợp dữ liệu
- Câu hỏi muốn nhóm phản biện: Liệu việc sử dụng AI để phân loại và phân tích chi tiêu có thực sự mang lại giá trị hơn so với việc sử dụng Excel hoặc Google Sheets? Làm thế nào để đảm bảo AI phân loại giao dịch chính xác?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chưa xác định rõ nguồn dữ liệu đầu vào cho AI| Đồng ý| Bổ sung phương án người dùng tải file Excel/CSV hoặc nhập dữ liệu thủ công|
| Chưa có tiêu chí đánh giá độ chính xác phân loại|Đồng ý|Bổ sung metric so sánh kết quả AI với dữ liệu được phân loại thủ công|
|Chưa chứng minh AI tốt hơn Excel|Đồng ý|Làm rõ AI hỗ trợ tự động nhận diện và phân loại giao dịch thay vì yêu cầu người dùng nhập từng danh mục|
|AI có thể phân loại sai giao dịch|Đồng ý|Bổ sung bước người dùng xác nhận hoặc chỉnh sửa kết quả|

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày Card #2 về việc tổng hợp và phân tích chi tiêu cá nhân| Giúp nhóm hiểu rõ khó khăn khi phải tổng hợp dữ liệu từ nhiều nguồn|
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Người dùng có thực sự cần AI để giải quyết vấn đề này hay chỉ cần một ứng dụng nhắc việc thông thường?| Giúp thành viên xem xét lại tính cần thiết của AI|
| Nhận phản biện | Câu hỏi tôi nhận được: AI lấy dữ liệu giao dịch từ đâu?| Tôi bổ sung phương án nhập thủ công và tải file CSV|
| Gom cluster / cây OST | Tham gia nhóm các vấn đề liên quan đến quản lý tài chính, theo dõi chi tiêu và thanh toán| Giúp nhóm xác định các cơ hội giải quyết vấn đề|
| Chọn candidate problem | So sánh mức độ nghiêm trọng, tần suất và khả năng ứng dụng AI của các vấn đề| Đề xuất vấn đề phân tích chi tiêu|
| Kiểm chứng / research | Tìm hiểu cách sinh viên quản lý chi tiêu và các công cụ đang được sử dụng| Có cơ sở so sánh giải pháp AI với giải pháp truyền thống|
| Quy trình nhóm | Tham gia mô tả các bước kiểm tra giao dịch, nhập dữ liệu và phân loại chi tiêu| Xác định công đoạn nhập và phân loại dữ liệu là điểm nghẽn|
| Problem Statement | Tham gia xác định đối tượng, bối cảnh, nhu cầu và kết quả mong muốn| Giúp Problem Statement cụ thể hơn|
| Mức can thiệp AI | Đề xuất AI tự động phân loại và phân tích, nhưng người dùng xác nhận kết quả| Xác định ranh giới giữa AI và người dùng|
| Quyết định | Tham gia thảo luận và lựa chọn giải pháp AI hỗ trợ phân tích chi tiêu| Giúp nhóm thống nhất hướng phát triển|

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Tìm thêm các vấn đề thường gặp trong cuộc sống sinh viên| Gợi ý thêm các góc nhìn và vấn đề chưa nghĩ đến| Một số ý tưởng quá rộng, chưa có bằng chứng thực tế| Loại bỏ ý tưởng chung chung, giữ lại những vấn đề có quy trình cụ thể|
| CP2 Problem Card | Hỗ trợ xây dựng Job Story, Bottleneck và Success Metric| Giúp hệ thống hóa nội dung theo cấu trúc Problem Card| Đưa ra một số số liệu chưa có nguồn kiểm chứng| Phân biệt số liệu minh họa với số liệu khảo sát thực tế|
| CP4 Research | Hỗ trợ xác định thông tin cần tìm hiểu về thói quen chi tiêu| Gợi ý câu hỏi khảo sát và các yếu tố cần kiểm chứng| Chưa thể thay thế dữ liệu từ người dùng thật| Bổ sung khảo sát và phỏng vấn để kiểm chứng|
| CP5 Quy trình | Mô tả các bước người dùng quản lý chi tiêu| Giúp trình bày quy trình theo thứ tự rõ ràng| Có thể đưa ra các bước không phù hợp với thói quen thực tế| Điều chỉnh quy trình dựa trên trải nghiệm và kết quả research|
| CP5–6 Problem Statement | Hỗ trợ diễn đạt vấn đề và xác định nhu cầu người dùng| Giúp câu mô tả rõ ràng, tránh lan man| Một số câu vẫn tập trung vào giải pháp thay vì vấn đề| Viết lại theo hướng tập trung vào khó khăn của người dùng|
| CP6 Mức can thiệp / quyết định | Phân tích mức độ phù hợp của AI trong quy trình| Giúp so sánh tự động hóa và AI Agent| Có xu hướng đề xuất AI can thiệp quá sâu| Giới hạn AI ở việc phân loại, phân tích và đề xuất; người dùng quyết định|

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?** Tôi học được cách nhìn nhận vấn đề từ nhiều góc độ hơn vì không chỉ quản lý tiền bạc mà con người ta cũng cần quản lý thời gian, học tập, giao tiếp...

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?** Nhóm đã chuyển từ tư duy "muốn xây dựng sản phẩm gì" sang "người dùng đang cần giải quyết vấn đề gì"

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.** Ban đầu tôi cho rằng AI nên tự động phân loại toàn bộ giao dịch mà không cần người dùng kiểm tra. Sau đó, thành viên khác hỏi nếu AI phân loại sai thì sao?

Tôi nhận ra AI không phải lúc nào cũng chính xác và quyết định bổ sung bước xác nhận kết quả.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?** Tôi nghĩ sinh viên gặp khó khăn chủ yếu vì không biết ghi chép chi tiêu. Nhưng sau khi khảo sát, tôi nhận ra nhiều người có ghi chép nhưng vẫn khó phân tích các khoản chi từ nhiều nguồn khác nhau.

Đây là một phát hiện có thể khiến nhóm thay đổi trọng tâm từ "ghi chép chi tiêu" sang "tổng hợp và phân tích chi tiêu"

**6.5. Điều khó nhất khi viết Problem Statement là gì?** Ban đầu nhóm viết "Sinh viên cần một ứng dụng AI để quản lý tài chính".

Nhưng đây là mô tả giải pháp, không phải vấn đề.

Có thể chỉnh thành:

"Sinh viên thường gặp khó khăn khi tổng hợp và phân loại các khoản chi từ nhiều nguồn thanh toán khiến họ mất thời gian và khó đánh giá thói quen tiêu dùng."

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?** Nếu làm lại sẽ không chỉ hỏi người dùng có gặp khó khăn trong quản lý chi tiêu hay không mà còn hỏi họ đang xử lý vấn đề như thế nào, mất bao nhiêu thời gian và đã từng thử giải pháp nào


**6.7. Hiểu bài: giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.** Đầu tiên, nhóm xác định vấn đề thực tế là sinh viên gặp khó khăn trong việc quản lý và tổng hợp các khoản chi tiêu cá nhân từ nhiều nguồn thanh toán khác nhau. Sau đó, nhóm phân tích quy trình hiện tại để hiểu người dùng đang quản lý chi tiêu như thế nào, những khó khăn xảy ra ở đâu và xác định công đoạn mất nhiều thời gian nhất. Tiếp theo, nhóm đưa ra các metric để đo lường hiệu quả của giải pháp, chẳng hạn như thời gian tổng hợp chi tiêu và độ chính xác khi phân loại các khoản giao dịch. Nhóm cũng xác định boundary để giới hạn phạm vi AI được phép xử lý, đồng thời xác định những công việc cần có sự kiểm tra và xác nhận của người dùng. Từ đó, nhóm lựa chọn mức độ can thiệp phù hợp, để AI hỗ trợ tự động phân loại, tổng hợp và phân tích chi tiêu, thay vì tự ý thực hiện các giao dịch tài chính. Cuối cùng, nhóm quyết định xây dựng trợ lý AI hỗ trợ quản lý chi tiêu cá nhân nhằm tiết kiệm thời gian và giúp người dùng kiểm soát tài chính tốt hơn. Mục tiêu quan trọng nhất là giải quyết đúng khó khăn thực tế của sinh viên, chứ không phải cố gắng đưa AI vào mọi hoạt động quản lý chi tiêu.

---

## 7. Tài liệu tham khảo

- [docs/01-worksheet.md](../../docs/01-worksheet.md): hướng dẫn chi tiết từng checkpoint, prompt phản biện Problem Card
- [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md): bài mẫu, dùng để học cách viết Job Story, Problem Card và quy trình nháp
