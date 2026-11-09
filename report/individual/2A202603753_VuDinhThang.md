# Báo cáo cá nhân — 2A202603753_VuDinhThang

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Đình Thắng
- MSSV: 2A202603753
- Email trường (không bắt buộc, repo có thể để public): 26ai.thangvd2@vinuni.edu.vn
- Tên nhóm: K1
- Link repo nhóm: https://github.com/ThangVu2303/K5-L3B-Day02-K1-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi chuẩn bị release phiên bản ứng dụng mới vào chiều thứ Sáu, tôi muốn có danh sách tóm tắt tất cả các Pull Request và bug fix đã được duyệt trong 2 tuần qua, để viết bản Release Notes bàn giao cho team QA/Vận hành mà không mất hơn 1 tiếng mở từng ticket kiểm tra. | Tech Lead, QA Lead, CS (khoảng 3–5 người) | Tốn 60–90 phút mỗi 2 tuần; phải mở lội qua 30–40 commit và ticket Jira; 2 đợt release gần nhất bị sót tính năng khiến CS bị động khi khách hỏi. |
| 2 | Lặp lại | Khi tới giờ tan làm chuẩn bị nấu bữa tối, tôi muốn biết trong tủ lạnh còn những thực phẩm gì sắp hết hạn kèm 1–2 gợi ý món ăn phù hợp, để nấu xong bữa cơm nhanh chóng mà không phải đứng mở tủ suy nghĩ 15 phút rồi lại tặc lưỡi gọi đồ ăn ngoài. | Người nấu ăn chính, các thành viên gia đình (2–4 người) | 15–20 phút mỗi ngày (7 ngày/tuần); 2–3 lần/tuần phải đặt đồ ăn ngoài vì lười nghĩ món; vứt bỏ rau củ/thịt hết hạn khoảng 150k–200k mỗi tuần. |
| 3 | Lặp lại | Khi có khách hàng mới đăng ký dùng thử phần mềm, tôi muốn có ngay bộ tài liệu hướng dẫn thiết lập phù hợp đúng với quy mô và ngành nghề của họ, để gửi đi nhanh chóng mà không phải gõ lại cùng một nội dung tư vấn và tìm link hướng dẫn từ đầu mỗi ngày. | CS/Onboarding, khách hàng mới (5–7 khách/ngày) | 15 phút/khách × 5–7 khách = 75–105 phút/ngày; lịch sử tin nhắn cho thấy 80% câu trả lời là copy-paste và chỉnh lại tên công ty/ngành nghề. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi mở một đợt tuyển dụng nhận về hơn 50 hồ sơ từ nhiều nguồn (LinkedIn, TopCV, email giới thiệu), tôi muốn nắm nhanh các ứng viên đáp ứng đủ số năm kinh nghiệm và bộ kỹ năng bắt buộc, để chọn ra danh sách phỏng vấn kịp hạn mà không phải mở đọc lướt từng file PDF dài 2–3 trang. | HR Recruiter, Hiring Manager | Mất trọn vẹn 12–16 tiếng (2 ngày làm việc) cho mỗi đợt tuyển; mở ~50 file PDF; tỷ lệ sót ứng viên tiềm năng do đọc lướt mệt mỏi ước tính 10–15%. |
| 5 | Pain từ người khác | Khi khách hàng nhắn tin báo sự cố gấp trong nhóm chat chung, tôi muốn biết ngay đầu mối kỹ thuật nào đang phụ trách module liên quan, để hẹn giờ phản hồi cho khách mà không phải liên tục tag hỏi dò và làm ngắt quãng công việc của cả team kỹ thuật. | Account Manager, Khách hàng, Team Kỹ thuật | 3–5 sự cố/tuần; trung bình mất 20–30 phút chờ kỹ thuật trả lời trong nhóm; khách than phiền vì phản hồi chậm trễ 2 lần trong tháng gần nhất. |


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Ý giữ lại (#6, #7, #8):** Sau khi tự scan 5 ý đầu, tôi nhận thấy còn thiếu lăng kính "Pain từ người khác" và muốn mở rộng thêm góc nhìn ma trận. Tôi đã nhờ AI gợi ý thêm các tình huống friction giữa các team (briefing design, support sự cố khách hàng, recap họp) và giữ lại vì có dấu hiệu đo lường thực tế rõ ràng.
- **Ý loại bỏ:** AI có gợi ý ý tưởng *"Trợ lý ảo tự động quản lý toàn bộ công việc cá nhân"* — Tôi loại bỏ vì bài toán này quá rộng, không có quy trình cụ thể và thiếu baseline đo lường thực tế.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Viết Release Notes (Vấn đề 3) | Quy trình cố định 2 tuần/lần, input rõ ràng (PR GitHub, Jira ticket), baseline đo lường chuẩn xác, impact trực tiếp tới chất lượng release. | AI có hiểu đúng các breaking change kỹ thuật phức tạp từ PR diff hay không. |
| 2 | Điều phối sự cố khách hàng (Vấn đề 2) | Pain từ người khác rất rõ (khách sốt ruột, dev bị ngắt quãng), tần suất 3–5 lần/tuần, cải thiện thời gian phản hồi tức thì. | Mô tả lỗi của khách thường dùng ngôn ngữ phi kỹ thuật, khó map chính xác 100% với module hệ thống. |
| 3 | Quản lý tủ lạnh & gợi ý bữa tối (Vấn đề 1) | Tần suất lặp lại hàng ngày (7 ngày/tuần), pain đời sống ai cũng gặp, giảm lãng phí tài chính và decision fatigue. | Khâu cập nhật nguyên liệu đầu vào (phải chụp ảnh hoặc gõ tay) có thể làm người dùng nản và bỏ cuộc giữa chừng. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị release phiên bản ứng dụng mới vào chiều thứ Sáu, tôi muốn có danh sách tóm tắt tất cả các Pull Request và bug fix đã được duyệt trong 2 tuần qua, để viết bản Release Notes bàn giao cho team QA/Vận hành mà không mất hơn 1 tiếng mở từng ticket kiểm tra. |
| Actor | Tech Lead / Release Manager phụ trách bàn giao phiên bản |
| Thời điểm / bối cảnh | Chiều thứ Sáu mỗi 2 tuần (cuối sprint), trước giờ deploy production |
| Quy trình hiện tại (3–7 bước) | 1. Lọc 30–40 commit & PR đã merge trên GitHub · 2. Đối chiếu danh sách ticket trạng thái "Done" trên Jira · 3. Mở đọc từng PR/ticket để hiểu logic thay đổi · 4. Viết tổng hợp Release Notes (Tính năng mới, Bug fix, Breaking change) · 5. Rà soát lại với QA Lead · 6. Đăng lên Confluence/Slack |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & 4 (Đọc hiểu 30–40 PR kỹ thuật và viết lại thành ngôn ngữ nghiệp vụ cho QA/Vận hành): mất khoảng 50–60 phút |
| Impact (nếu không giải thì sao) | Tốn 60–90 phút/sprint của Tech Lead; 2 đợt release gần nhất bị sót tính năng lên production khiến CS và Vận hành bị động khi khách hàng hỏi |
| Success metric (baseline → target) | Tổng thời gian soạn Release Notes từ 75' xuống dưới 20'; 0 trường hợp bỏ sót tính năng hoặc breaking change |
| Phương án không dùng AI | Dùng script gom git log tự động theo tag. Nhược điểm: commit message của dev viết tắt/thiếu ngữ cảnh, không tự phân loại theo ngôn ngữ nghiệp vụ cho QA hiểu được |
| Giả thuyết về AI (nếu có) | AI đọc nội dung tóm tắt PR + Jira ticket, tự động phân nhóm và soạn nháp Release Notes chuẩn format; Tech Lead chỉ cần review và duyệt |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 75 phút

[1 Lấy PR GitHub: 10'] → [2 Đối chiếu Jira: 10'] → [3 Đọc từng PR: 30'] 
→ [4 Soạn Release Notes: 20'] ← BOTTLENECK (Bước 3 + 4)
→ [5 Rà soát với QA: 5'] → [6 Đăng Slack/Confluence: 0']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi khách hàng nhắn tin báo sự cố gấp trong nhóm chat chung, tôi muốn biết ngay đầu mối kỹ thuật nào đang phụ trách module liên quan, để hẹn giờ phản hồi cho khách mà không phải liên tục tag hỏi dò và làm ngắt quãng công việc của cả team kỹ thuật. |
| Actor | Account Manager (AM) / Chuyên viên CSKH quản lý nhóm hỗ trợ khách hàng B2B |
| Thời điểm / bối cảnh | Giờ làm việc, khi khách hàng gặp lỗi hệ thống, downtime hoặc sai dữ liệu và báo gấp vào nhóm chat chung |
| Quy trình hiện tại (3–7 bước) | 1. Đọc tin nhắn và ảnh chụp lỗi từ khách · 2. Tự suy đoán module bị lỗi và mở bảng phân công (RACI) tra cứu · 3. Nhắn tin riêng hoặc tag 1–2 kỹ sư nghi vấn để hỏi · 4. Chờ kỹ sư kiểm tra và xác nhận nhận ticket · 5. Trả lời cam kết thời gian cho khách |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & 4 (Xác định đúng người và chờ phản hồi): mất 15–25 phút; AM bị kẹt ở giữa không dám hứa thời gian xử lý với khách |
| Impact (nếu không giải thì sao) | Khách hàng than phiền dịch vụ chậm (2 lần trong tháng gần nhất); làm ngắt quãng sự tập trung của nhiều kỹ sư bị tag nhầm |
| Success metric (baseline → target) | Thời gian xác định đúng kỹ sư phụ trách giảm từ 20' xuống dưới 2'; tỷ lệ phản hồi trấn an khách hàng lần đầu đạt 100% trong vòng 5 phút |
| Phương án không dùng AI | Bảng Excel/Notion tra cứu theo từ khóa lỗi. Nhược điểm: khách hàng mô tả bằng lời văn tự nhiên/cảm tính, AM không biết dùng từ khóa kỹ thuật nào để tra cứu |
| Giả thuyết về AI (nếu có) | AI phân tích đoạn chat báo lỗi của khách, trích xuất triệu chứng, đối chiếu với danh mục module và gợi ý chính xác kỹ sư on-call phụ trách kèm mẫu câu phản hồi |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 25 phút

[1 Đọc tin nhắn lỗi: 2'] → [2 Tra cứu phân công: 3'] 
→ [3 Tag hỏi dò kỹ sư: 10'] → [4 Chờ kỹ sư nhận: 8'] ← BOTTLENECK (Bước 3 + 4)
→ [5 Hẹn giờ phản hồi khách: 2']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tới giờ tan làm chuẩn bị nấu bữa tối, tôi muốn biết trong tủ lạnh còn những thực phẩm gì sắp hết hạn kèm 1–2 gợi ý món ăn phù hợp, để nấu xong bữa cơm nhanh chóng mà không phải đứng mở tủ suy nghĩ 15 phút rồi lại tặc lưỡi gọi đồ ăn ngoài. |
| Actor | Người nấu ăn chính trong gia đình / người độc thân tự nấu ăn |
| Thời điểm / bối cảnh | Khoảng 18h–19h các ngày trong tuần sau giờ làm việc |
| Quy trình hiện tại (3–7 bước) | 1. Mở tủ lạnh xem nguyên liệu còn lại · 2. Phát hiện đồ sắp hỏng hoặc thiếu gia vị · 3. Đứng suy nghĩ hoặc lướt mạng tìm công thức khớp với đồ sẵn có · 4. Bỏ cuộc vì không nghĩ ra món -> đặt đồ ăn ngoài · 5. Nấu ăn hoặc chờ đồ ship |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 (Suy nghĩ món ăn khớp với thực phẩm thừa sắp hỏng): mất 15 phút, gây quá tải suy nghĩ (decision fatigue) sau ngày làm việc mệt mỏi |
| Impact (nếu không giải thì sao) | Vứt bỏ thực phẩm hỏng trị giá 150k–200k/tuần; tốn thêm 200k–300k/tuần tiền ăn ngoài kém lành mạnh; tâm lý căng thẳng mỗi bữa tối |
| Success metric (baseline → target) | Thời gian từ lúc mở tủ đến khi chốt món giảm từ 15' xuống dưới 3'; số lần gọi đồ ngoài giảm từ 3 lần xuống 1 lần/tuần; lượng đồ ăn phải vứt bỏ giảm 80% |
| Phương án không dùng AI | Bảng thực đơn cố định cả tuần dán trên tủ (meal prep sheet). Nhược điểm: thiếu linh hoạt khi có ngày bận đột xuất hoặc mua sắm phát sinh nguyên liệu ngoài kế hoạch |
| Giả thuyết về AI (nếu có) | AI nhận danh sách nguyên liệu hiện có trong tủ (qua text hoặc ảnh chụp), gợi ý ngay 2 món chế biến nhanh dưới 25 phút tận dụng tối đa đồ sắp hết hạn |
| Cảm nhận nhanh | Rule kết hợp AI (Workflow) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 20 phút

[1 Mở tủ kiểm tra đồ: 3'] → [2 Lọc đồ sắp hỏng: 2'] 
→ [3 Nghĩ món / lướt tìm công thức: 15'] ← BOTTLENECK
→ [4 Quyết định nấu hoặc gọi đồ ngoài: 0']
```

### Card muốn pitch nhất

- Card số: Card #3 (Quản lý tủ lạnh & Gợi ý thực đơn bữa tối)
- Vì sao:
  - Tần suất lặp lại hàng ngày (7 ngày/tuần), nỗi đau phổ biến và nhức nhối (decision fatigue sau ngày dài làm việc).
  - Có baseline định lượng rõ ràng: mất 15–20 phút đứng nghĩ món, 2–3 lần/tuần phải gọi đồ ăn ngoài vì lười nghĩ, lãng phí khoảng 150k–200k tiền thực phẩm hỏng mỗi tuần.
  - Đề tài gần gũi, vừa sức trong phạm vi lab, rất dễ phỏng vấn kiểm chứng thực tế với người dùng mà không bị rào cản bảo mật dữ liệu công ty.
- Câu hỏi muốn nhóm phản biện: "Rào cản lớn nhất là khâu nhập liệu đầu vào (người dùng lười chụp ảnh hoặc gõ tay danh sách thực phẩm trong tủ). Liệu có nguy cơ người dùng bỏ dở sau 2-3 ngày không, và làm thế nào để quy trình thu thập dữ liệu nguyên liệu đạt mức tối giản nhất?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Người dùng gọi đồ ăn ngoài vì mệt mỏi sau giờ làm, chứ không hẳn vì thiếu ý tưởng món ăn. | Đồng ý một phần | Bổ sung tiêu chí cho gợi ý: chỉ đề xuất các món chế biến siêu tốc (dưới 20 phút) và sử dụng tối đa đồ sẵn có, không bắt đi mua thêm gia vị cầu kỳ. |
| Nhận diện thực phẩm qua ảnh chụp tủ lạnh dễ bị sót đồ ở ngăn sâu hoặc nhận diện sai hạn sử dụng. | Đồng ý | Đặt boundary rõ ràng: AI chỉ gợi ý ý tưởng món từ những gì thấy được, không cố xây hệ thống quản lý tồn kho chính xác 100%. |
| Gợi ý xây agent tự động kết nối app đi chợ để mua thêm nguyên liệu còn thiếu. | Không đồng ý | Giữ phạm vi tối giản: chỉ tập trung giải quyết đồ thừa/sắp hỏng trong tủ, không mở rộng sang tích hợp đặt hàng bên ngoài. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Problem Card #3: "Nghĩ món từ đồ sắp hết hạn trong tủ lạnh để giảm tiền lãng phí" | Lọt vào shortlist và được nhóm chọn làm candidate chính vì impact đo được bằng tiền (khoảng 350–500k/tuần) và có nhiều cấp độ để so sánh mức can thiệp AI |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Phản biện candidate #8 của Thịnh (Bố mẹ hỏi cách dùng điện thoại): đặt câu hỏi về việc tác động chủ yếu là thời gian và giải pháp chỉ dừng ở ảnh chụp tài liệu | Giúp nhóm thấy candidate #8 ít đất diễn cho AI ở CP6, chuyển sang làm hướng tiếp theo |
| Nhận phản biện | Câu hỏi tôi nhận được: Nhận câu hỏi từ Thịnh: "Không nghĩ ra món có thật sự khiến đồ bị vứt hay do mua quá nhiều, không lên kế hoạch?" | Tôi đã sửa gì: Nhóm đưa giả định này vào kiểm chứng ở CP4, sau đó phát hiện chuỗi nhân quả ban đầu bị sai lệch một phần |
| Gom cluster / cây OST | Dẫn dắt xây dựng cây Opportunity Solution Tree (OST) với outcome là "Giảm tiền lãng phí mỗi tuần", xác định D1 làm trọng tâm, loại bỏ các solution đội lốt | Nhóm có một cây OST chuẩn xác, không bị lẫn giải pháp vào tầng cơ hội |
| Chọn candidate problem | Trình bày bảng chấm điểm 7 tiêu chí (tổng 32 điểm cho #3), bảo vệ tính khả thi và phạm vi đề tài | Nhóm thống nhất chọn #3, đồng thời cam kết sẽ đổi hướng nếu CP4 phản bác giả định |
| Kiểm chứng / research | Cung cấp số liệu baseline cá nhân (150–200k đồ vứt/tuần, 3 lần gọi đồ ngoài); cùng Thịnh rà soát số liệu Tạp chí Công Thương và FoodBank | Nhận ra nguyên nhân mua/nấu quá nhiều là rủi ro lớn, quyết định bỏ tiền gọi đồ ngoài khỏi impact chính |
| Quy trình nhóm | Tham gia định hình quy trình As-Is (5 bước) và To-Be (6 bước); nhấn mạnh bước A (ghi đồ khi đi chợ về) là điểm then chốt | Xác định rõ bước A là bottleneck mới về mặt Usability cần kiểm chứng kỹ |
| Problem Statement | Viết bản Problem Statement v0 và nâng cấp lên v1 (bổ sung điều kiện người nấu có lịch thay đổi, 4 metric và tiêu chí eval) | Problem Statement chặt chẽ, có boundary rõ ràng và tiêu chí đánh giá bản nháp cụ thể |
| Mức can thiệp AI | Phân tích ma trận độ mơ hồ cao x độ phức tạp thấp; lập bảng so sánh 4 mức (No AI / Rule / Workflow / Agent); điền AI Canvas và trả lời câu hỏi PAIR | Nhóm chốt mức Workflow (Rule sắp xếp theo hạn, AI chỉ gợi ý 2–3 món, HITL duyệt) |
| Quyết định | Phân tích 4 rủi ro của Marty Cagan (Usability Cao, Value TB); đề xuất quyết định **Not Yet** và thiết lập 4 ngưỡng dừng (Kill switch) | Nhóm thống nhất không vội vàng làm AI mà chạy kiểm chứng No AI + Rule trong 3 tuần trước |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý thêm các bài toán theo các lăng kính đa dạng | Gợi ý thêm các vấn đề về friction giữa các phòng ban (briefing, sự cố) | Gợi ý một số ý quá rộng như "Trợ lý ảo toàn năng" | Loại bỏ các ý không có quy trình cụ thể, giữ lại các bài toán có baseline đo lường được |
| CP2 Problem Card | Đóng vai phản biện sắc sảo để tìm lỗ hổng trong Problem Card #3 | Chỉ ra điểm yếu về việc người dùng lười nhập liệu đầu vào (Usability risk) | Gợi ý làm Agent tự động kết nối app đi chợ mua đồ thừa | Giữ boundary tối giản: chỉ gợi ý món từ đồ có sẵn, không tự mua sắm bên ngoài |
| CP4 Research | Hỗ trợ phân tích đối chiếu các nguồn dữ liệu lãng phí thực phẩm | Tóm tắt nhanh các luận điểm từ báo chí và báo cáo | Đưa số liệu 72kg/người/năm không có nguồn xác thực | Loại bỏ con số này, chỉ giữ lại số liệu có thể verify từ Tạp chí Công Thương và FoodBank |
| CP5 Quy trình | Chuyển đổi mô tả quy trình sang dạng sơ đồ text/Mermaid | Dựng luồng nhanh, phân định rõ ràng giữa các bước | AI ban đầu tự động gộp bước kiểm tra an toàn thực phẩm vào AI | Tách riêng bước kiểm tra cho con người (HITL), AI tuyệt đối không phán đoán an toàn |
| CP5–6 Problem Statement | Nhờ AI đóng vai chuyên gia sản phẩm phản biện v0 | Chỉ ra metric ban đầu chỉ đo thời gian và lẫn tiền ăn ngoài | Đề xuất thêm các metric phức tạp khó đo trong lab | Đơn giản hóa metric: đo tiền đồ vứt có lý do cụ thể và thời gian chọn món |
| CP6 Mức can thiệp / quyết định | Dùng AI để rà soát ma trận rủi ro và các ngưỡng dừng | Gợi ý khung 4 rủi ro của Marty Cagan và cấu trúc ngưỡng dừng logic | Các ngưỡng phần trăm (70%, 80%) do AI đưa ra còn mang tính định tính | Xác lập lại các ngưỡng dừng kèm phương án quay về cụ thể cho từng kịch bản thử nghiệm |

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
