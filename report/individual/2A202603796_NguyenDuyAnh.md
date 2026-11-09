# Báo cáo cá nhân — 2A202603796_NguyenDuyAnh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyen Duy Anh
- MSSV: 2A202603796
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: K1
- Link repo nhóm: https://github.com/ThangVu2303/K5-L3B-Day02-K1-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Pain từ người khác | Khi có nhân viên mới vào làm, tôi muốn họ có sẵn hướng dẫn về cách tự cấu hình wifi và máy in, để tôi không phải qua hướng dẫn họ mỗi khi có lỗi | IT Helpdesk | Đợt onboard có 3 người mới, IT phải chạy bàn 6 lần để cài máy in và wifi, mỗi lần tốn 10 phút
| 2 | Lặp lại | Khi giữa kỳ/cuối kỳ có họp phụ huynh, tôi muốn có bảng tóm tắt điểm số và biểu hiện của các em học sinh từ các bộ môn khác, để có thể viết đánh giá mà không mất cả ngày | Giáo viên chủ nhiệm | Mất trung bình 15 phút cho từng em, lớp 40-60 học sinh tốn khoảng hơn 10 tiếng liên tục làm, tốn 2 ngày cuối tuần chỉ làm
| 3 | Tốn thời gian | Khi khách hàng nhắn tin hỏi về phí ship và bảng size, tôi muốn có sẵn câu trả lời chuẩn xác để gửi ngay, để không phải gõ thủ công nhiều lần mỗi ngày | Chủ shop online/Nhân viên shop bán hàng | Đếm trên fanpage, có 7-12 tin nhắn hỏi cùng một câu hỏi về phí ship/size mỗi ngày; tốn 1–2 phút copy/paste hoặc gõ lại cho mỗi tin (khoảng 20 phút/ngày chỉ làm việc lặp lại)
| 4 | Tốn thời gian | Khi nhận về 50 CV ứng tuyển, tôi muốn lọc nhanh những người đáp ứng đủ yêu cầu kỹ năng cứng, để không phải mở và đọc thủ công từng file | Tuyển dụng(HR) | Mất trung bình 2–3 phút để mở và đọc lướt 1 CV, đợt tuyển dụng tuần trước tốn khoảng 2 tiếng liên tục; phát hiện bị mỏi mắt đọc sót thông tin kỹ năng của vài ứng viên.
| 5 | Lặp lại | Khi tiêu tiền mỗi ngày, tôi muốn các khoản chuyển khoản hoặc quẹt thẻ tự động được phân loại, để không phải nhập tay từng khoản vào file Excel mỗi tối | Người tự quản lý tài chính cá nhân | Bỏ ra 36 phút mỗi cuối tuần để đối chiếu app ngân hàng và bảng chi tiêu; tháng trước bỏ sót 2 khoản quẹt thẻ do lỡ lướt qua, dẫn đến lệch sổ.
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi chốt xong danh sách khách, tôi muốn phân bổ chỗ ngồi tự động dựa trên mối quan hệ nhóm, để không ai bị lẻ loi mà không phải kéo thả Excel cả ngày | Cô dâu/chú rể/người tổ chức sự kiện | Mất 2 tiếng đồng hồ kéo thả tên trên file Excel vào tuần trước.

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Lọc nhanh CV ứng viên | Tốn nhiều thời gian lọc CV bằng tay, quy trình trích xuất kỹ năng cứng rất phù hợp với thế mạnh xử lý ngôn ngữ tự nhiên của AI. | Không chắc AI có khả năng nhận diện thiếu kỹ năng cứng nếu ứng viên dùng các từ khóa đồng nghĩa hoặc cách diễn đạt khác
| 2 | Tổng hợp nhận xét học sinh cuối kỳ | Tốn rất nhiều thời gian lặp đi lặp lại giữa các bộ môn | Không biết nhà trường cho phép sự riêng tư để đưa điểm số của các học sinh ra AI bên ngoài không
| 3 | Trả lời tin nhắn khách hàng hỏi ship/size | Tần suất lặp lại liên tục hàng ngày (tốn 20 phút/ngày chỉ để copy-paste) | Liệu vấn đề này có thực sự cần can thiệp bằng AI không, hay chỉ cần dùng mức "No AI / Rule" (tính năng Tin nhắn trả lời nhanh có sẵn của Fanpage) là đã giải quyết triệt để?

### Problem Card #1

Quy trình nháp hiện tại:

```text

| Trường | Nội dung |
| Job Story | Khi nhận về 50 CV ứng tuyển, tôi muốn lọc nhanh những người đáp ứng đủ yêu cầu kỹ năng cứng, để không phải mở và đọc thủ công từng file |
| Actor | Tuyển dụng (HR) |
| Thời điểm / bối cảnh | Sau khi đóng cổng nhận đơn ứng tuyển, cần lọc CV vòng đầu|
| Quy trình hiện tại (3–7 bước) | 1. Tải 50 file CV (thường là PDF) về máy - 2. Mở từng file - 3. Đọc lướt tìm từ khóa kỹ năng cứng - 4. Đánh giá Đạt/Không đạt vòng hồ sơ - 5. Cập nhật trạng thái vào file Excel tổng hợp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 và 4: mất trung bình 2–3 phút mỗi CV, tổng cộng mất khoảng 100–150 phút (hơn 2 tiếng) cho 50 CV |
| Impact (nếu không giải thì sao) | Tốn hơn 2 tiếng làm việc lặp lại, mỏi mắt dẫn đến sai sót (đã từng đọc sót thông tin kỹ năng của ứng viên tiềm năng) |
| Success metric (baseline → target) | Thời gian đọc và lọc 50 CV giảm từ 120 phút xuống dưới 30 phút. Tỉ lệ bỏ sót kỹ năng cứng có trong CV: 0% |
| Phương án không dùng AI | Yêu cầu ứng viên điền Google Form (tick chọn các kỹ năng đang có) thay vì chỉ nộp file PDF tự do. |
| Giả thuyết về AI (nếu có) | AI đọc hàng loạt file PDF, trích xuất các kỹ năng cứng đối chiếu với JD và xuất ra một bảng tóm tắt Có/Không, HR chỉ cần nhìn bảng để quyết định Đạt/Loại|
| Cảm nhận nhanh | Workflow (Các bước cố định, AI làm bước trích xuất dữ liệu, HR làm bước quyết định) | 


```

HIỆN TẠI — 125 phút / 50 CV (Trung bình 2.5 phút/CV)

[1 Tải 50 file CV về máy: 5'] → [2 Mở lần lượt từng file: 10'] 
→ [3 Đọc lướt CV tìm từ khóa kỹ năng cứng: 75'] ← BOTTLENECK
→ [4 Ra quyết định Đạt/Loại: 20'] → [5 Điền trạng thái vào Excel tổng hợp: 15']

### Problem Card #2

Quy trình nháp hiện tại:

```text

| Trường | Nội dung |
| Job Story | Khi giữa kỳ/cuối kỳ có họp phụ huynh, tôi muốn có bảng tóm tắt điểm số và biểu hiện của các em học sinh từ các bộ môn khác, để có thể viết đánh giá mà không mất cả ngày|
| Actor | Giáo viên chủ nhiệm |
| Thời điểm / bối cảnh | Cuối học kỳ, thời điểm cần hoàn thành sổ liên lạc/phiếu đánh giá trước buổi họp phụ huynh |
| Quy trình hiện tại (3–7 bước) | 1. Xem điểm và nhận xét của giáo viên bộ môn trên hệ thống - 2. Mở file nhận xét của từng em - 3. Tổng hợp ý chính từ các môn và điểm số - 4. Viết đoạn văn nhận xét chung - 5. Rà soát lỗi chính tả và lưu lại|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 và 4: mất trung bình 15 phút cho từng em. Với lớp 40–60 em, tổng thời gian lên tới 10–15 tiếng |
| Impact (nếu không giải thì sao) | Chiếm trọn 2 ngày nghỉ cuối tuần của giáo viên; mệt mỏi dễ dẫn đến việc copy-paste các lời nhận xét rập khuôn, chung chung cho nhiều học sinh |
| Success metric (baseline → target) | Thời gian viết nhận xét giảm từ 15 phút/em xuống còn dưới 5 phút/em |
| Phương án không dùng AI | Xây dựng file Excel có sẵn các câu nhận xét mẫu và dùng hàm nối chữ để tự tạo đoạn văn |
| Giả thuyết về AI (nếu có) | AI nhận đầu vào là bảng điểm và dòng ghi chú ngắn của các môn, tự động soạn nháp 1 đoạn văn nhận xét tổng hợp mềm mại, đúng văn phong sư phạm. Giáo viên đọc duyệt và sửa lại nếu cần |
| Cảm nhận nhanh | Workflow (Rule lấy số liệu + AI viết nháp + Con người duyệt) |

```
HIỆN TẠI — 15 phút / học sinh (Tổng: ~600 phút / lớp 40 học sinh)

[1 Mở hệ thống & xem điểm/ghi chú các môn: 3'] → [2 Tổng hợp ý chính ra nháp: 3'] 
→ [3 Viết đoạn văn nhận xét tổng hợp: 7'] ← BOTTLENECK
→ [4 Rà soát lỗi & lưu lại: 2']

### Problem Card #3


Quy trình nháp hiện tại:

```text
| Trường | Nội dung |
| Job Story | Khi khách hàng nhắn tin hỏi về phí ship và bảng size, tôi muốn có sẵn câu trả lời chuẩn xác để gửi ngay, để không phải gõ thủ công nhiều lần mỗi ngày |
| Actor | Chủ shop online / Nhân viên trực page bán hàng |
| Thời điểm / bối cảnh | Trong ca làm việc hàng ngày, khi khách hàng mới inbox hỏi các thông tin cơ bản nhất |
| Quy trình hiện tại (3–7 bước) | 1. Đọc tin nhắn của khách - 2. Phân loại câu hỏi (hỏi ship hay hỏi size) - 3. Mở file note lưu sẵn câu trả lời mẫu - 4. Copy câu trả lời - 5. Dán vào khung chat, sửa lại thông tin cho phù hợp ngữ cảnh - 6. Bấm gửi |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, 4, 5: mất 1–2 phút cho mỗi tin nhắn. Ngày 10 tin mất khoảng 20 phút |
| Impact (nếu không giải thì sao) | Tốn 20 phút lắt nhắt mỗi ngày cho những việc lặp lại không tạo ra doanh thu trực tiếp, lúc đông khách có thể phản hồi chậm làm khách bỏ đi |
| Success metric (baseline → target) | Thời gian xử lý 1 câu hỏi cơ bản giảm từ 1-2 phút xuống dưới 10 giây |
| Phương án không dùng AI | Thiết lập tính năng "Tin nhắn trả lời nhanh" có sẵn trên Meta Business Suite hoặc cài phím tắt gõ tắt trên bàn phím |
| Giả thuyết về AI (nếu có) | Agent Chatbot tự động đọc tin, phân loại ý định và tự gửi thẳng tin nhắn phản hồi cho khách không cần người can thiệp |
| Cảm nhận nhanh | No AI / Rule (Chỉ cần dùng tính năng Rule trả lời nhanh có sẵn của fanpage là đủ giải quyết, không đáng để xây AI). |
```
HIỆN TẠI — 20 phút / ngày (Trung bình 2 phút/tin nhắn)

[1 Đọc & phân loại ý định khách hàng: 3'] → [2 Mở file/app note để tìm câu trả lời mẫu: 4'] 
→ [3 Copy & dán vào khung chat: 5'] ← BOTTLENECK
→ [4 Đọc lướt lại và sửa tên/thông tin cho hợp ngữ cảnh: 6'] ← BOTTLENECK
→ [5 Bấm gửi: 2']

### Card muốn pitch nhất

- Card số: 2
- Vì sao: Impact rất lớn và rõ ràng cho thời gian của giáo viên, việc tổng hợp rất phù hợp với khả năng của AI, vượt trội hơn hẳn phương án No AI/Rule
- Câu hỏi muốn nhóm phản biện: Nếu rủi ro bảo mật dữ liệu cao, thì có cách nào làm ẩn danh tên và thông tin nhạy cảm của học sinh trước khi đưa vào prompt không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

Rủi ro rò rỉ dữ liệu: Đưa tên thật, điểm số và thông tin cá nhân của học sinh lên các công cụ AI công cộng (như ChatGPT bản free) có thể vi phạm chính sách bảo mật/quyền riêng tư của nhà trường. | Đồng ý | Thêm một bước Rule: Ẩn danh hóa dữ liệu, chỉ đưa Mã học sinh dùng cho AI hoặc tên viết tắt vào prompt
Metric bỏ qua chất lượng: Success metric hiện tại chỉ tập trung vào tốc độ (giảm từ 15 phút xuống 5 phút). Nếu AI viết nhanh nhưng giọng văn "vô hồn" hoặc giống hệt nhau (văn mẫu), phụ huynh sẽ phàn nàn. | Đồng ý | Thêm metric chất lượng: Tỉ lệ bản nháp bị giáo viên gạch bỏ/viết lại hoàn toàn phải dưới 20%
Rủi ro AI "bịa" thông tin (Hallucination): Để câu văn mượt mà, AI có xu hướng tự sáng tác thêm các hành vi hoặc thành tích (ví dụ: tự khen em tích cực phát biểu dù đầu vào không có). | Đồng ý | Thêm ranh giới cứng: AI chỉ được dùng dữ liệu từ đầu vào, không được tự suy diễn hành vi. Giáo viên bắt buộc đối chiếu bản nháp với dữ liệu gốc trước khi chốt
---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 candidate: Lọc CV ứng viên (#4), Nhận xét học sinh (#5), Trả lời tin nhắn khách (#6) | Giúp nhóm có thêm góc nhìn về các bài toán xử lý văn bản lặp lại để đối chiếu |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Đặt câu hỏi cho candidate #8 của Thịnh: "Vì sao cần giải bằng công nghệ khi một số thao tác có thể hướng dẫn bằng hình ảnh hoặc tài liệu đơn giản?" | Giúp nhóm nhận ra giải pháp cho bài #8 chủ yếu là No AI, củng cố thêm lý do chọn bài tủ lạnh (#3) |
| Nhận phản biện | Câu hỏi tôi nhận được: Nhận câu hỏi từ Thắng và Thịnh: "Nhà trường có cho phép đưa điểm và nhận xét của học sinh lên ChatGPT không?" | Tôi đã sửa gì: Thấy bài #5 có rủi ro Viability cao về bảo mật dữ liệu, đồng thuận không chọn làm candidate chính của nhóm |
| Gom cluster / cây OST | Tham gia phân loại candidate vào 4 cluster (A, B, C, D); hỗ trợ ghi chép biên bản thảo luận của nhóm | Giúp nhóm gom cụm D (quản lý đồ trong nhà & lãng phí) thành một nhánh rõ ràng |
| Chọn candidate problem | Tham gia chấm điểm shortlist, ủng hộ chọn candidate #3 vì đề tài gần gũi và đo lường được bằng tiền | Nhóm đạt được sự đồng thuận cao khi chốt candidate #3 |
| Kiểm chứng / research | Hỗ trợ khâu kiểm chứng giả định: tạo form poll ngắn gửi cho 6–8 người quen để khảo sát thói quen mở tủ lạnh và tần suất vứt bỏ đồ ăn hỏng | Thu thập thêm số liệu thực tế: đa số mọi người thừa nhận hay quên rau củ ở góc tủ dẫn đến bị hỏng |
| Quy trình nhóm | Đóng góp ý kiến cho quy trình To-Be: nhấn mạnh bước người nấu mở tủ kiểm tra thực tế (HITL) | Nhóm xác định boundary quan trọng: AI không thể biết đồ còn tươi hay đã hỏng, người nấu phải tự kiểm |
| Problem Statement | Góp ý cho phần Boundary: AI tuyệt đối không tự chốt món thay người nấu và cần lưu ý cảnh báo dị ứng | Giúp Problem Statement hoàn thiện hơn về mặt an toàn cho người dùng |
| Mức can thiệp AI | Tham gia thảo luận về tính khả thi: đồng ý với mức Workflow, không cần làm Agent tự động hóa quá mức | Giúp nhóm giữ phạm vi giải pháp vừa sức, tập trung vào bước gợi ý món ăn |
| Quyết định | Đồng ý với quyết định **Not Yet**: kiểm chứng bằng ghi chép sổ tay và No AI trước khi xây dựng AI | Tránh việc nhóm đầu tư công sức làm AI khi thói quen ghi chép danh sách đồ (bước A) chưa được chứng minh |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Dùng AI để gợi ý cách diễn đạt các vấn đề hàng ngày theo đúng cú pháp Job Story | Chuyển đổi các câu văn đời thường thành cấu trúc `Khi... tôi muốn... để...` chuẩn xác | Một số gợi ý bị lặp từ hoặc đưa công cụ giải pháp vào câu | Tự chỉnh sửa lại để câu văn thuần túy mô tả nỗi đau và bối cảnh thực tế |
| CP2 Problem Card | Dùng AI để hỗ trợ ước lượng sơ bộ các bước thực hiện trong quy trình nháp | Giúp hình dung nhanh các bước từ lúc nhận việc đến khi hoàn thành | AI đưa ra số phút quá chi tiết mà chưa có đo đạc thật | Ghi chú lại đây chỉ là ước lượng ban đầu, cần kiểm chứng thêm qua thực tế |
| CP4 Research | Nhờ AI giải thích khái niệm phương pháp phỏng vấn The Mom Test | Giúp hiểu nhanh nguyên lý: không hỏi ý kiến về tương lai, chỉ hỏi hành vi trong quá khứ | Đôi khi AI gợi ý các câu hỏi mang tính mớm cung ("Bạn có thích app...") | Lọc bỏ các câu hỏi mớm cung, giữ lại câu hỏi về lần gần nhất gặp sự cố |
| CP5 Quy trình | Tham khảo AI cách phân định giữa hành động của người dùng (User) và hệ thống (System) | Giúp định hình rõ ranh giới con người kiểm tra (HITL) và AI gợi ý | AI có xu hướng gán cho AI khả năng tự nhận diện độ tươi ngon của đồ ăn | Nhận ra AI không thể ngửi hay sờ được đồ ăn, giữ nguyên việc kiểm tra an toàn cho con người |
| CP5–6 Problem Statement | Dùng AI để kiểm tra lỗi chính tả và format bảng biểu Markdown | Trình bày bảng biểu ngay ngắn, chuẩn định dạng đề tài | Không có | Giữ nguyên nội dung đã thảo luận cùng nhóm |
| CP6 Mức can thiệp / quyết định | Nhờ AI tóm tắt ngắn gọn sự khác biệt giữa Rule và Workflow trong bài toán này | Giúp phân biệt rõ: Rule sắp xếp theo hạn, Workflow kết hợp AI để ghép món | AI đôi khi đề xuất giải pháp Agent phức tạp không cần thiết | Kiên định cùng nhóm chọn mức Workflow đơn giản, phù hợp với năng lực sinh viên |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
- Họ có chiều sâu trong các vấn đề hơn, và những vấn đề đó khá common
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
- Không, toàn bộ các vấn đề đều chưa nghĩ đến giải pháp
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
- Hơi đổi ý về vấn đề của giáo viên chủ nhiệm, vì số điểm có thể dùng lệnh của excel để gom điểm lại
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
- Không hẳn là có
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
- Bị tập trung vào 1 vấn đề quá mà không nghĩ tới các vấn đề khác (thời gian nấu ăn thay vì nghĩ tới cả thức ăn thừa)
**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
- Đổi xem các vấn đề nó thật sự có ý nghĩa hay không, hay dùng AI được không.
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
- problem chính là về việc không nghĩ ra nên nấu đồ ăn gì, và không nhớ hạn sử dụng lẫn đồ ăn còn gì dẫn đến đồ ăn thừa. Metric hiện tại là tiết kiệm được thời gian suy nghĩ đồ ăn, dùng được hết toàn bộ các nguyên liệu nấu ăn mà không bỏ phí. AI có thể can thiệp bằng cách scan hình ảnh trong tủ lạnh để biết số lượng và chất lượng (sắp hỏng hay chưa) của nguyên liệu rồi dùng cook book? có sẵn để nghĩ ra món ăn hộ con người (chỉ gợi ý không chốt món).
---

## 7. Tài liệu tham khảo

-Tạp chí Công Thương, 10/2025
- (FoodBank VN, 2024).
- (UNEP 2024).

