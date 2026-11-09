# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: K1
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khi tan làm chuẩn bị bữa tối, người nấu ăn chính không biết kết hợp đồ đang có (nhất là đồ sắp hỏng) thành món, nên chọn món quen và để đồ sắp hỏng lại đến khi phải vứt (ước lượng 150–200k/tuần) — đã điều chỉnh sau phỏng vấn ở CP4
- Quyết định cuối: **Not Yet** — Workflow (AI chỉ ở bước gợi ý món), kiểm chứng trước 3 tuần bằng sổ ghi + No AI/Rule (mục 8.2)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

|   # | Người đưa ra     | Candidate (Job Story ngắn)                                                                                                                                                                                        | Actor                                                                       | Bottleneck                                                                                                                           | Câu hỏi phản biện nhận được (ai hỏi) |
| --: | ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------ |
|   1 | Vũ Đình Thắng    | Khi chuẩn bị release vào chiều thứ Sáu cuối sprint, tôi muốn có danh sách tóm tắt các PR và bug fix đã duyệt trong 2 tuần, để viết Release Notes bàn giao cho QA/Vận hành mà không mất hơn 1 tiếng mở từng ticket | Tech Lead / Release Manager                                                 | Bước 3 + 4 — đọc 30–40 PR và viết lại bằng ngôn ngữ nghiệp vụ: 50'/sprint (tổng 75'/sprint); 2 đợt release gần nhất bị sót tính năng |                                      |
|   2 | Vũ Đình Thắng    | Khi khách hàng báo sự cố gấp trong nhóm chat chung, tôi muốn biết ngay kỹ sư nào phụ trách module liên quan, để hẹn giờ phản hồi cho khách mà không phải tag hỏi dò cả team                                       | Account Manager / CSKH khách hàng B2B                                       | Bước 3 + 4 — tag hỏi dò kỹ sư và chờ nhận: 18'/sự cố (tổng 25'); khách than phiền chậm 2 lần trong tháng                             |                                      |
|   3 | Vũ Đình Thắng    | Khi tan làm chuẩn bị nấu bữa tối, tôi muốn biết nấu được món gì nhanh từ thực phẩm sắp hết hạn trong tủ lạnh, để không phải đứng nghĩ 15 phút rồi lại gọi đồ ăn ngoài                                             | Người nấu ăn chính trong gia đình (đi làm, nấu bữa tối các ngày trong tuần) | Bước 3 — nghĩ món, lướt tìm công thức khớp với đồ sắp hỏng: 15'/bữa (tổng 20'); vứt 150–200k đồ hỏng/tuần, gọi đồ ngoài 3 lần/tuần   | Thịnh: không nghĩ ra món có thật sự khiến đồ bị vứt, hay do mua quá nhiều, không lên kế hoạch, lịch sinh hoạt thay đổi? |
|   4 | Duy Anh          | Lọc nhanh CV ứng viên theo kỹ năng cứng, để chọn đúng người vào vòng phỏng vấn                                                                                                                                    | Nhân viên tuyển dụng (HR)                                                   | Đọc từng CV bằng tay để trích kỹ năng cứng _(Duy Anh bổ sung số phút)_                                                               |                                      |
|   5 | Duy Anh          | Tổng hợp nhận xét học sinh cuối kỳ từ nhiều bộ môn, để hoàn thành sổ nhận xét đúng hạn                                                                                                                            | Giáo viên chủ nhiệm                                                         | Gom và viết lại nhận xét lặp đi lặp lại giữa các bộ môn _(Duy Anh bổ sung số phút)_                                                  |                                      |
|   6 | Duy Anh          | Trả lời tin nhắn khách hỏi phí ship, size trên Fanpage, để khách không phải chờ                                                                                                                                   | Người bán hàng online                                                       | Copy-paste câu trả lời lặp lại: 20'/ngày                                                                                             |                                      |
|   7 | Nguyễn Hữu Thịnh | Khi cuối tháng muốn biết tiền đã đi đâu, tôi muốn thấy chi tiêu theo từng nhóm, để điều chỉnh tháng sau                                                                                                           | Tôi (người tổng hợp), vợ                                                    | Phân nhóm từng giao dịch từ 3 nguồn (2 ngân hàng, 1 ví): khoảng 25'/tháng, tổng 60–90'/tháng                                         |                                      |
|   8 | Nguyễn Hữu Thịnh | Khi bố mẹ hay gọi hỏi cách dùng điện thoại, chuyển khoản, tôi muốn họ tự làm được, để không phải chờ tôi rảnh                                                                                                     | Bố, mẹ, tôi                                                                 | Xác định bố mẹ đang ở màn hình nào qua điện thoại: khoảng 5'/cuộc, 4 cuộc/tuần; hướng dẫn bằng lời không lưu lại nên bị hỏi lại      | Duy Anh: vì sao cần giải bằng công nghệ khi một số thao tác có thể hướng dẫn bằng hình ảnh hoặc tài liệu đơn giản? |
|   9 | Nguyễn Hữu Thịnh | Khi cuối tuần đi chợ, tôi muốn biết nhà còn thiếu gì, để không mua trùng hoặc quên đồ                                                                                                                             | Tôi, vợ                                                                     | Lập danh sách cần mua bằng trí nhớ (5'), dẫn đến đi mua bù 15'/lần, 2 lần/tuần                                                       |                                      |

### 2.2. Cluster

| Cluster | Các candidate                                                                                                           | Pattern chung                                                                                                                                                                                                                      |
| ------- | ----------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| A       | #6 Trả lời tin nhắn hỏi ship/size (Duy Anh), #8 Bố mẹ hỏi cách dùng điện thoại, chuyển khoản (Thịnh)                    | **Người khác hỏi lại cùng một câu, phải trả lời/hướng dẫn thủ công mỗi lần.** Câu hỏi lặp lại, câu trả lời gần như cố định, nhưng không được lưu lại để người hỏi tự xem                                                           |
| B       | #1 Viết Release Notes (Thắng), #5 Tổng hợp nhận xét học sinh cuối kỳ (Duy Anh), #7 Tổng hợp chi tiêu cuối tháng (Thịnh) | **Gom dữ liệu từ nhiều nguồn để viết bản tổng kết định kỳ.** Lặp theo chu kỳ (2 tuần / cuối kỳ / cuối tháng); phần tốn thời gian là gom và phân loại thủ công từ 2–3 nguồn rời rạc                                                 |
| C       | #2 Tìm đúng kỹ sư khi khách báo sự cố (Thắng), #4 Lọc nhanh CV ứng viên (Duy Anh)                                       | **Đọc đầu vào không theo mẫu để phân loại và chuyển đúng chỗ.** Mô tả lỗi của khách / CV viết mỗi người một kiểu; phải đọc từng cái mới biết thuộc module nào, ai phụ trách, đạt yêu cầu hay không                                 |
| D       | #3 Nghĩ món từ đồ sắp hết hạn (Thắng), #9 Đi chợ quên đồ, mua trùng (Thịnh)                                             | **Không nắm được trong nhà đang có gì nên tiền thực phẩm bị lãng phí.** Đồ dùng thay đổi hằng ngày nhưng chỉ nhớ trong đầu; không nghĩ ra món từ đồ đang có thì đồ cũ bị bỏ đến hỏng và phải gọi đồ ăn ngoài, đi chợ thì mua trùng |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

Nhóm chọn outcome theo cluster D, đo bằng **tiền** thay vì thời gian, vì thời gian đi mua bù (~30'/tuần) quá nhỏ để làm outcome, còn tiền bị lãng phí (đồ hỏng phải vứt + tiền gọi đồ ăn ngoài ngoài dự kiến) là hậu quả chung của cả 3 pain. Baseline ước lượng từ Thắng: 150–200k đồ vứt + 200–300k ăn ngoài = khoảng 350–500k/tuần.

```text
OUTCOME: Giảm số tiền gia đình lãng phí mỗi tuần cho bữa tối
         (thực phẩm hỏng phải vứt + gọi đồ ăn ngoài ngoài dự kiến)
├── Opportunity D1 (TRỌNG TÂM): Sau giờ làm, mất ~15' nghĩ món từ đồ sắp hỏng,
│   │                           không nghĩ ra thì bỏ cuộc và gọi đồ ăn ngoài (#3, Thắng)
│   └── [Solution ứng viên, để CP6 đánh giá]
│         • Đề xuất món ăn nhanh từ đồ sắp hết hạn
│         • Thực đơn cố định cả tuần dán trên tủ (phương án No AI)
├── Opportunity D2: Không biết đồ nào sắp hết hạn, đến khi mở tủ
│                   mới phát hiện đồ đã hỏng và phải vứt (#3, Thắng)
└── Opportunity D3: Đi chợ không biết nhà còn gì, thiếu gì,
                    nên mua trùng đồ tươi rồi để hỏng (#9, Thịnh)
     ✗ "App quản lý tủ lạnh"               ← solution, gạch khỏi tầng opportunity
     ✗ "Chụp ảnh tủ lạnh để nhận diện đồ"   ← solution, gạch khỏi tầng opportunity
     ✗ "Danh sách đi chợ tự động"           ← solution, gạch khỏi tầng opportunity
```

**Về ý "đề xuất món ăn":** đây là solution nên không được đứng ở tầng opportunity. Nhóm giữ ý này ở **tầng solution bên dưới D1** (đúng cấu trúc Opportunity Solution Tree: outcome → opportunity → solution), đặt cạnh phương án No AI để CP6 so sánh xem có thật sự cần đến mức đề xuất món hay thực đơn cố định đã đủ.

**Vì sao D1 là trọng tâm:** D2 và D3 chủ yếu là chuyện ghi nhớ, một danh sách chung hoặc nhãn ghi ngày (No AI) đã giải được phần lớn. D1 là nhánh duy nhất có độ mơ hồ cao (nhiều món đều chấp nhận được), nên có chỗ để so sánh No AI / Rule / Workflow / Agent ở CP6. D1 cũng là nguyên nhân trực tiếp của cả hai khoản tiền: không nghĩ ra món thì đồ sắp hỏng không được dùng tới, và bữa tối chuyển sang gọi đồ ngoài.

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Gợi ý 1–2 món ăn": có trong Job Story gốc của #3; nhóm đã viết lại Job Story ở 2.1 thành nhu cầu "biết nấu được món gì nhanh từ đồ sắp hết hạn", và chuyển ý đề xuất món xuống tầng solution dưới D1
- "App quản lý tủ lạnh": là công cụ, chưa nói pain gì
- "Chụp ảnh tủ lạnh để nhận diện đồ": là cách nhập dữ liệu, không phải nhu cầu
- "Danh sách đi chợ tự động": là tính năng, pain thật là D3 (mua trùng vì không biết nhà còn gì)

### 2.4. Chấm điểm shortlist (1–5)

| Candidate                                            | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain |   Tổng |
| ---------------------------------------------------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | -----: |
| #3 Nghĩ món từ đồ sắp hết hạn (D1, Thắng)            |        5 |            4 |                  3 |              5 |           5 |                                      5 |                5 | **32** |
| #9 Đi chợ quên đồ, mua trùng (D3, Thịnh)             |        5 |            5 |                  4 |              3 |           5 |                                      2 |                5 |     29 |
| #8 Bố mẹ hỏi cách dùng điện thoại (cluster A, Thịnh) |        5 |            4 |                  5 |              4 |           5 |                                      3 |                5 |     31 |

**Lý do chấm:**

| Candidate   | Điểm cao                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Điểm thấp                                                                                                                                                                                                                                                              |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| #3 Nghĩ món | Impact = 5: quy ra tiền, có baseline (150–200k đồ vứt + 200–300k ăn ngoài mỗi tuần). So sánh 4 mức = 5: độ mơ hồ cao (nhiều món đều chấp nhận được), có phương án No AI thật để so (thực đơn cố định cả tuần). Domain = 5: Thắng tự gặp mỗi tối trong tuần. Actor = 5: đã thu hẹp về một nhóm (người nấu ăn chính trong gia đình, đi làm, nấu bữa tối), bỏ nhóm người độc thân để khớp outcome "tiền gia đình lãng phí". Vừa sức lab = 5: dữ liệu nằm sẵn trong tủ lạnh và lịch sử app giao đồ ăn của chính Thắng, người phỏng vấn dễ tìm (ai nấu ăn cũng gặp) | Pain có bằng chứng = 3: các con số (15', 150–200k, 3 lần gọi đồ/tuần) là Thắng tự ước lượng, chưa có dấu vết như lịch sử app giao đồ ăn hay ghi chép đồ vứt. Quy trình = 4: đã vẽ 4 bước có số phút, nhưng bước 4–5 (gọi đồ ngoài hay nấu) chưa có tần suất tách riêng |
| #9 Đi chợ   | Actor, quy trình, vừa sức = 5: 2 vợ chồng, 5 bước, đã vẽ ở CP2. Bằng chứng = 4: 2 tin Zalo nhắc quên đồ trong tuần                                                                                                                                                                                                                                                                                                                                                                                                                                             | So sánh 4 mức = 2: một danh sách chung (No AI) gần như giải hết, ít chỗ để bàn. Impact = 3: ~30'/tuần, phần mua trùng chưa quy ra tiền                                                                                                                                 |
| #8 Bố mẹ    | Bằng chứng = 5: 9 cuộc gọi trong 2 tuần, có lịch sử cuộc gọi. Actor, vừa sức, domain = 5                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | So sánh 4 mức = 3: hướng dẫn bằng ảnh có sẵn đã đủ phần lớn trường hợp. Quy trình = 4: chưa đếm cụ thể bố mẹ hỏi những việc gì                                                                                                                                         |

**Candidate được chọn:** #3 — Nghĩ món từ đồ sắp hết hạn trong tủ lạnh (Opportunity D1), đo bằng tiền lãng phí mỗi tuần (đồ hỏng phải vứt + gọi đồ ăn ngoài).

**Vì sao chọn:** Tổng điểm cao nhất (32), và: (1) nằm đúng outcome nhóm muốn cải thiện và là nguyên nhân trực tiếp của cả hai khoản tiền lãng phí; (2) impact lớn nhất và quy được ra tiền (khoảng 350–500k/tuần), trong khi #8 và #9 chỉ đo bằng thời gian; (3) là candidate duy nhất có điểm 5 ở tiêu chí "so sánh được 4 mức", nên CP6 có lập luận thật thay vì kết luận No AI hiển nhiên; (4) điểm yếu nhất (bằng chứng = 3, số liệu tự ước lượng) kiểm chứng được nhanh ở CP4: xem lịch sử app giao đồ ăn, ghi lại đồ bị vứt trong 1 tuần, phỏng vấn 2–3 người nấu ăn chính. Nếu CP4 cho thấy pain không có thật, nhóm quay về #8.

**Vì sao loại các candidate còn lại:**

- **#9 Đi chợ quên đồ:** quy trình rõ nhưng một danh sách chung đã giải gần hết, không đủ chỗ để so sánh các mức can thiệp. Nhóm giữ nó làm nhánh phụ D3 trong cây OST thay vì làm candidate chính.
- **#8 Bố mẹ hỏi cách dùng điện thoại:** điểm sát nút (31), bằng chứng mạnh nhất, nhưng nằm ngoài outcome đã chọn (thuộc cluster A, câu hỏi lặp lại), impact chỉ đo bằng thời gian (~52'/tuần). Giải pháp nhiều khả năng chỉ là hướng dẫn bằng ảnh, nên phần CP6 sẽ mỏng. Ghi vào mục 9 "hướng tiếp theo".

**Xử lý bất đồng (nếu có):** Thịnh muốn chọn #8 vì có bằng chứng mạnh nhất (9 cuộc gọi trong 2 tuần, có lịch sử cuộc gọi), chỉ kém #3 một điểm. Nhóm thống nhất chọn #3 vì impact quy ra tiền và có chỗ để phân tích các mức can thiệp AI, với điều kiện: nếu sau CP4 bằng chứng của #3 vẫn yếu (lịch sử app giao đồ ăn không cho thấy khoảng 3 lần/tuần, hoặc 2/3 người được phỏng vấn nói hiếm khi vứt đồ) thì chuyển sang #8.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định                                                                                                           | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước?                                                                |
| --: | ------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------- | ---------------: | ---------------------: | -------------------------------------------------------------------------------- |
|   1 | Người nấu ăn chính khác (ngoài Thắng) cũng mất trên 10 phút mỗi tối để nghĩ món từ đồ đang có                      | Value                                              |                5 |                      2 | **Có — kiểm chứng đầu tiên**                                                     |
|   2 | "Không nghĩ ra món" là nguyên nhân chính khiến đồ bị vứt và phải gọi đồ ăn ngoài (chứ không phải do mua quá nhiều) | Value                                              |                5 |                      1 | **Có — kiểm chứng đầu tiên**                                                     |
|   3 | Mỗi tuần gọi đồ ăn ngoài khoảng 3 lần vì không biết nấu gì (đúng như Thắng ước lượng)                              | Value                                              |                4 |                      2 | Có — Thắng xem lịch sử app giao đồ ăn 4 tuần                                     |
|   4 | Người nấu chịu khó cập nhật đồ trong tủ (gõ tay hoặc chụp ảnh) đều đặn ít nhất 2 tuần                              | Usability                                          |                5 |                      2 | Có — hỏi trong phỏng vấn; research cho thấy đây là điểm yếu của app có sẵn (3.3) |
|   5 | Món được đề xuất phải là món Việt quen thuộc, nấu dưới 30 phút thì người nấu mới làm theo                          | Usability / Feasibility                            |                4 |                      2 | Sau — kiểm ở CP5–CP6                                                             |
|   6 | Có sẵn nguồn công thức món Việt tìm được theo nguyên liệu                                                          | Feasibility                                        |                3 |                      4 | Không — đã có bằng chứng: Cooky tìm món theo nguyên liệu (3.3)                   |

Giả định nhóm kiểm chứng trong buổi này: **#1 và #2** (quan trọng 5, bằng chứng thấp nhất). Nếu #2 sai — tức đồ bị vứt chủ yếu do mua/nấu quá nhiều — thì D1 không còn là trọng tâm.

**Kết quả sau kiểm chứng (2 phỏng vấn, 3.2):** #1 xác nhận một phần (2/2 có gặp, nhưng chưa có số phút). #2 **bị phản bác**: gọi đồ ngoài do mệt/về muộn, vứt đồ do không lên kế hoạch hoặc lịch thay đổi. #4 có thêm tín hiệu rủi ro: người #2 không duy trì được thực đơn cả tuần.

### 3.2. Kiểm chứng

Cách đã dùng: **Phỏng vấn** (Mom Test, 2–3 người nấu ăn chính, không phải thành viên nhóm) + **Log** (lịch sử app giao đồ ăn của Thắng) + **dữ liệu khảo sát đã công bố** (nguồn thứ cấp, dùng để đối chiếu, không thay cho phỏng vấn).

Kịch bản phỏng vấn: [report/assets/cp4-interview-guide.md](../assets/cp4-interview-guide.md).

Bộ câu hỏi đã dùng: 5 câu rút gọn từ kịch bản (số lần tự nấu / lần gần nhất không biết nấu gì / lần gần nhất vứt đồ / lần gần nhất gọi đồ ăn ngoài / cách đã thử). Người phỏng vấn: Nguyễn Hữu Thịnh.

**Interview snapshot #1**

| Trường | Nội dung |
| --- | --- |
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên, sống một mình, thường xuyên tự nấu ăn |
| Thời gian, cách hỏi | 09/11/2026, phỏng vấn online qua tin nhắn Zalo, người phỏng vấn: Nguyễn Hữu Thịnh |
| Câu nói đáng nhớ nhất (nguyên văn) | "Mình mở tủ lạnh thấy có trứng, rau và thịt nhưng không biết kết hợp thế nào." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khoảng 2 ngày trước: mở tủ có trứng, rau, thịt nhưng không biết kết hợp; cuối cùng lên YouTube tìm món đơn giản rồi nấu theo. Tuần trước bỏ một ít rau cải vì để lâu bị héo — "Một phần cũng vì mua nguyên liệu nhưng không lên kế hoạch sử dụng trước." |
| Hiện đang xử lý bằng cách nào (workaround)? | Xem TikTok, YouTube tìm công thức; đôi khi lưu lại món đơn giản để tham khảo; chưa lập thực đơn cố định cho cả tuần |
| Mất bao lâu, bao lần? | Tự nấu khoảng 5 tối/tuần; gọi đồ ăn ngoài khoảng 2 lần/tuần. Không nói số phút nghĩ món |
| Insight / opportunity rút ra | Có pain "không biết kết hợp nguyên liệu đang có", nhưng khi bị kẹt thì vẫn **nấu** (nhờ YouTube), không gọi đồ ngoài. Lần gọi đồ ngoài gần nhất là do **về muộn, mệt**, không phải do không biết nấu gì. Đồ bị vứt một phần do **không lên kế hoạch dùng** khi mua. Người này sống một mình, **nằm ngoài actor** nhóm đã chọn (người nấu chính trong gia đình) |

**Interview snapshot #2**

| Trường | Nội dung |
| --- | --- |
| Người được hỏi (vai trò, không ghi tên thật) | Bác sĩ làm việc tại bệnh viện, có lịch trực |
| Thời gian, cách hỏi | 09/11/2026, phỏng vấn online qua tin nhắn Zalo, người phỏng vấn: Nguyễn Hữu Thịnh |
| Câu nói đáng nhớ nhất (nguyên văn) | "Lịch làm việc và trực bệnh viện thường thay đổi nên rất khó duy trì kế hoạch." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tối hôm kia đi làm về, mở tủ có thịt, trứng, ít rau nhưng không biết chế biến món gì; vì mệt nên nấu món đơn giản là trứng chiên và rau luộc. Tuần trước bỏ một ít rau và nấm vì để quá lâu — "Ban đầu tôi định nấu vào những ngày tiếp theo nhưng lịch trực thay đổi nên không có thời gian chế biến." |
| Hiện đang xử lý bằng cách nào (workaround)? | Từng thử lên thực đơn cả tuần và lưu công thức đơn giản trên mạng, nhưng **không duy trì được** vì lịch trực thay đổi |
| Mất bao lâu, bao lần? | Tự nấu khoảng 3 tối/tuần; gọi đồ ăn ngoài khoảng 3 lần/tuần. Không nói số phút nghĩ món |
| Insight / opportunity rút ra | Có pain "không biết chế biến món gì từ đồ đang có", nhưng khi bị kẹt thì chọn món quen, đơn giản, không gọi đồ ngoài. Gọi đồ ngoài là do **trực đến tối muộn, mệt**. Đồ bị vứt là do **kế hoạch nấu bị phá vì lịch thay đổi**. Thực đơn cố định (phương án No AI) đã thử và thất bại vì lịch không ổn định. Người này nói "một ứng dụng có thể gợi ý món ăn dựa trên nguyên liệu sẵn có… sẽ khá hữu ích" — đây là **ý kiến về giải pháp tương lai, không tính là bằng chứng** theo The Mom Test |

Tổng hợp:

| Nguồn                                                                                                                                                                                                                                                      |         Số người / số mẫu | Tín hiệu xác nhận                                                                                                                                        | Tín hiệu phản bác                                                                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Khảo sát hành vi lãng phí thực phẩm giữa các thế hệ ở Việt Nam (Quách Thùy Trang, Tạp chí Công Thương, 10/2025) — [link](https://tapchicongthuong.vn/nghien-cuu-su-khac-biet-ve-hanh-vi-lang-phi-thuc-pham-giua-cac-the-he-o-viet-nam-hien-nay-245709.htm) | Bài không ghi tổng số mẫu | 59,3% Gen Z đồng ý "thường giữ lại thực phẩm cho đến khi nó bị hỏng với hy vọng sẽ ăn nó vào một lúc nào đó" → khớp giả định đồ bị bỏ quên trong tủ (D2) | Nguyên nhân nổi bật là **mua và nấu quá nhiều**: 75,8% Gen Y và 64,8% Gen Z mua thêm ngoài danh sách; 60,6% Gen Y nấu nhiều hơn nhu cầu. Bài **không** khảo sát lý do "không biết nấu gì" → giả định #2 chưa được ủng hộ |
| FoodBank Việt Nam, số liệu công bố 9/2024 (Báo Pháp luật Việt Nam, 01/2025) — [link](https://baophapluat.vn/bai-1-lang-phi-do-an-tu-mam-com-gia-dinh-toi-nha-hang-o-viet-nam-post535007.html)                                                              |         Số liệu toàn quốc | Hơn 8 triệu tấn thực phẩm bị thất thoát hay vứt bỏ mỗi năm, thiệt hại khoảng 3,9 tỷ USD, gần 2% GDP → lãng phí thực phẩm là vấn đề có quy mô             | Số liệu gộp cả chuỗi cung ứng, nhà hàng; không tách riêng hộ gia đình                                                                                                                                                    |
| UNEP Food Waste Index Report 2024 (qua MyJoyOnline, 28/3/2024) — [link](https://www.myjoyonline.com/hotter-countries-generate-more-food-waste-per-capita-in-households/)                                                                                   |          Số liệu toàn cầu | 1,05 tỷ tấn thực phẩm bị lãng phí năm 2022, 132 kg/người; ở các nước nóng hơn, người dân vứt nhiều thực phẩm tại nhà hơn → phù hợp bối cảnh Việt Nam     | Số liệu toàn cầu, không phải số liệu Việt Nam                                                                                                                                                                            |
| Lịch sử app giao đồ ăn của Thắng (4 tuần)                                                                                                                                                                                                                  |                   1 người | _(Thắng điền: số lần gọi đồ tối thứ 2–6 / tuần)_                                                                                                         | _(nếu ít hơn 3 lần/tuần thì ghi vào đây)_                                                                                                                                                                                |
| Phỏng vấn (snapshot #1, #2) | 2 người | **Giả định #1 được xác nhận một phần:** cả 2/2 người có lần gần đây (2 ngày trước, tối hôm kia) mở tủ mà không biết kết hợp/chế biến món gì từ đồ đang có. Cả 2/2 có vứt rau tuần trước. Người #2 đã thử thực đơn cả tuần và bỏ vì lịch thay đổi → phương án thực đơn cố định không đủ với người có lịch thất thường | **Giả định #2 bị phản bác:** cả 2/2 người khi không biết nấu gì vẫn **tự nấu** (tìm YouTube, nấu món quen), không gọi đồ ngoài. Lý do gọi đồ ngoài ở cả 2 là **về muộn, mệt** (2 và 3 lần/tuần). Lý do vứt đồ là **không lên kế hoạch dùng** (#1) và **lịch trực thay đổi** (#2), không phải do không nghĩ ra món. Cả 2 không đưa số phút nghĩ món → giả định "15 phút" chưa được xác nhận. Người #1 sống một mình, ngoài actor đã chọn |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- _Sau research (đã có):_ khảo sát Tạp chí Công Thương cho thấy nguyên nhân lãng phí phổ biến là mua thêm ngoài danh sách và nấu nhiều hơn nhu cầu, không nhắc tới "không biết nấu gì". Nhóm **chưa đổi trọng tâm D1**, nhưng thêm giả định #2 vào nhóm phải kiểm chứng đầu tiên, và thêm câu hỏi phỏng vấn tách riêng ba nguyên nhân (mua quá nhiều / nấu quá nhiều / không nghĩ ra món).
- _Sau phỏng vấn (2 người):_ pain "mở tủ không biết làm món gì từ đồ đang có" là có thật (2/2), nên nhóm **giữ D1 làm trọng tâm**. Nhưng phỏng vấn phản bác chuỗi nhân quả nhóm giả định ban đầu ("không nghĩ ra món → gọi đồ ăn ngoài → đồ bị vứt"). Nhóm sửa 3 điểm:
  1. **Bỏ "tiền gọi đồ ăn ngoài" khỏi impact chính và Success Metric:** cả 2 người gọi đồ ngoài vì về muộn, mệt; bước nghĩ món không giải được việc này.
  2. **Đổi cách hiểu bottleneck:** từ "nghĩ món lâu" thành "không biết kết hợp đồ đang có, nhất là đồ sắp hỏng, khi kế hoạch nấu bị thay đổi". Lý do vứt đồ ở cả 2 người đều liên quan tới việc không có kế hoạch dùng hoặc kế hoạch bị phá.
  3. **Ghi nhận phương án No AI đã bị thử và thất bại:** thực đơn cố định cả tuần không duy trì được khi lịch làm việc thất thường (người #2). Thông tin này dùng cho phần so sánh mức can thiệp ở CP6.
- _Chưa kiểm chứng được:_ số phút nghĩ món (không ai đưa con số), và actor "người nấu chính trong gia đình" (người #1 sống một mình, người #2 chưa rõ hoàn cảnh gia đình). Cần thêm ít nhất 1 người đúng actor và hỏi lại số phút.

### 3.3. Research giải pháp đã có

Các link dưới đây đã được mở và kiểm nội dung ngày 09/11/2026.

| Công cụ / case / pattern                               | Link                                                                                                                                                      | Giải bước nào trong quy trình?                                                                                                    | Điểm mạnh                                                                                   | Khoảng trống / rủi ro                                                                                                                                                                                                                                                                                                                             | Bài học cho nhóm                                                                                                                            |
| ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **SuperCook** — tìm công thức theo nguyên liệu đang có | [App Store](https://apps.apple.com/us/app/id1477747816) · [supercook.com](https://www.supercook.com/)                                                     | Bước 3 (nghĩ món): chọn nguyên liệu đang có từ danh sách 2000+ nguyên liệu hoặc đọc bằng giọng nói, app lọc ra công thức nấu được | Miễn phí; App Store mô tả hơn 11 triệu công thức từ 18.000 website; công thức ở 20 ngôn ngữ | Ngôn ngữ app trên App Store chỉ có tiếng Anh; không theo dõi hạn dùng, nên không biết đồ nào **sắp hỏng** cần ưu tiên; công thức chủ yếu món phương Tây                                                                                                                                                                                           | Bước "đề xuất món từ nguyên liệu" đã có công cụ làm được. Khoảng trống là **ưu tiên đồ sắp hết hạn** và **món Việt**                        |
| **Kitche** — app giảm lãng phí thực phẩm tại nhà       | [kitche.co](https://www.kitche.co/) · [review TapSmart (2020, cập nhật 2021)](https://www.tapsmart.com/apps/food-drinks/review-kitche/)                   | Bước 1–3: quét hóa đơn để ghi đồ đã mua, nhắc đồ cần dùng trước khi hỏng, gợi ý công thức từ đồ trong tủ, ghi lại đồ bị vứt       | Gộp cả theo dõi tủ lạnh, nhắc hạn và công thức trong một app; miễn phí (theo kitche.co)     | Review TapSmart: phụ thuộc vào việc người dùng **đều đặn đánh dấu đồ đã dùng**, nếu không danh sách sẽ sai; thiết kế cho người ở một mình, **chưa có tài khoản chung cho gia đình**; quét hóa đơn siêu thị nên không hợp với đi chợ truyền thống (không có hóa đơn) ở Việt Nam; app hướng tới thị trường Anh (kitche.co dẫn số liệu WRAP của Anh) | Khớp đúng lo ngại của Thắng (người dùng ngại nhập dữ liệu). Giả định #4 là rủi ro Usability lớn nhất, cần kiểm trước khi chọn mức can thiệp |
| **Cooky** — app công thức món Việt                     | [bài giới thiệu Sforum/CellphoneS (cập nhật 24/06/2023)](https://cellphones.com.vn/sforum/cooky-ung-dung-chia-se-cong-thuc-nau-an-ngon-hang-dau-viet-nam) | Bước 3: tìm món theo tên, loại món, nguyên liệu, mục đích, chế độ dinh dưỡng; có Shop list ghi nguyên liệu cần mua                | Công thức món Việt, có video hướng dẫn                                                      | Bài giới thiệu không nhắc tính năng nhập nhiều nguyên liệu đang có cùng lúc hay theo dõi hạn dùng; nguồn là bài review bên thứ ba, chưa phải tài liệu chính thức                                                                                                                                                                                  | Có sẵn nguồn công thức món Việt (giả định #6). Nhóm nên tự mở app kiểm tìm theo **nhiều** nguyên liệu cùng lúc trước khi kết luận           |

**Kết luận research:** mỗi công cụ đã giải được một phần bước 3 (SuperCook: đề xuất món từ nhiều nguyên liệu; Cooky: món Việt; Kitche: nhắc đồ sắp hỏng). Chưa thấy công cụ nào gộp đủ **món Việt + ưu tiên đồ sắp hết hạn + dùng chung cho gia đình**. Rủi ro chung của nhóm app theo dõi tủ lạnh là người dùng bỏ cuộc vì phải nhập dữ liệu. Ở CP6, nhóm cần cân nhắc phương án đơn giản: dùng công cụ có sẵn + quy trình bán thủ công, trước khi nghĩ đến tự xây.

---

## 4. Quy trình trước/sau (CP5)

> **Nguồn số liệu:** thời gian từng bước lấy từ Problem Card #3 của Thắng (tự ước lượng, chưa bấm giờ). Tiền đồ bị vứt là ước lượng của Thắng. Cách người nấu xử lý khi bị kẹt và lý do vứt đồ / gọi đồ ngoài lấy từ 2 phỏng vấn ở mục 3.2. Hai người được phỏng vấn không đưa số phút nghĩ món, nên con số 15' vẫn chỉ là ước lượng của Thắng.

### 4.1. Quy trình hiện tại

Sơ đồ:

```text
HIỆN TẠI — khoảng 20 phút/bữa tối (18h–19h, các ngày trong tuần)

[1. Mở tủ lạnh xem đồ: 3']
→ [2. Lọc ra đồ sắp hỏng / thiếu gia vị: 2']
→ [3. Nghĩ cách kết hợp đồ đang có thành món: 15'] ← BOTTLENECK
       (khi bị kẹt: tìm YouTube/TikTok hoặc nấu món quen đơn giản — 2/2 phỏng vấn)
→ [4. Nấu món đã chọn]                                 (không đo — ngoài phạm vi)
→ [5. Đồ sắp hỏng không nằm trong món đã nấu → để lại;
      kế hoạch nấu bị đổi (về muộn, lịch trực) → đồ hỏng → vứt]  (150–200k/tuần, ước lượng)

NGOÀI PHẠM VI: tối về muộn/mệt → gọi đồ ăn ngoài (2–3 lần/tuần ở 2 người được phỏng vấn).
Lý do là mệt, không phải do không biết nấu gì → không thuộc bottleneck nhóm giải.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
| ---: | ----- | ----- | ------ | -------------------- | ------- |
| 1 | Người nấu ăn chính | Tủ lạnh | Biết đại khái trong tủ đang có gì | 3' / mỗi tối tự nấu | Không có danh sách ghi lại, phải mở tủ nhìn |
| 2 | Người nấu ăn chính | Đồ trong tủ | Biết đồ nào sắp hỏng, thiếu gia vị gì | 2' / mỗi tối tự nấu | Đánh giá bằng mắt, không có ngày mua/hạn dùng ghi lại |
| 3 | Người nấu ăn chính | Đồ đang có (thịt, trứng, rau…), công thức trên mạng | Một món định nấu | **15'** / mỗi tối (ước lượng của Thắng) | **Bottleneck.** 2/2 người phỏng vấn gặp lại gần đây ("không biết kết hợp thế nào", "không biết nên chế biến món gì"). Khi kẹt, họ tìm video công thức hoặc nấu món quen đơn giản |
| 4 | Người nấu ăn chính | Món đã chọn, nguyên liệu | Bữa tối | Không đo | Món quen, đơn giản thường không dùng tới đồ sắp hỏng |
| 5 | Người nấu ăn chính | Đồ không được dùng | Đồ hỏng bị vứt | 150–200k/tuần (ước lượng của Thắng) | 2/2 người phỏng vấn vứt rau tuần trước; lý do: không lên kế hoạch dùng (#1), lịch trực thay đổi phá kế hoạch nấu (#2) |

**Bottleneck chính:** Bước 3 — kết hợp đồ đang có (nhất là đồ sắp hỏng) thành món: khoảng 15 phút/bữa trên tổng khoảng 20 phút từ lúc mở tủ đến lúc chốt món (ước lượng của Thắng). Khi bị kẹt, người nấu chọn món quen hoặc món tìm trên mạng, nên đồ sắp hỏng không được dùng tới; khi kế hoạch nấu bị đổi, đồ đó hỏng và bị vứt. Việc gọi đồ ăn ngoài **không** đến từ bước này (phỏng vấn 2/2: do mệt, về muộn).

### 4.2. Quy trình tương lai

Phương án dưới đây là bản nháp để CP6 so sánh các mức can thiệp. Theo research ở 3.3, nhóm ưu tiên **dùng công cụ có sẵn + quy trình bán thủ công**, chưa tự xây app.

```text
TƯƠNG LAI — khoảng 3–4 phút/bữa tối (kỳ vọng, chưa đo)

Mỗi lần đi chợ về:
[A. Ghi đồ tươi vừa mua + ngày mua vào một danh sách chung: ~2'/lần chợ]   ← CON NGƯỜI (bước mới)

Mỗi tối:
[1. Danh sách tự sắp theo ngày mua, đánh dấu đồ cần dùng trong 2 ngày: 0'] ← RULE
                                                                       (công thức trong bảng tính/note)
→ [2. Đưa danh sách đồ sắp hỏng vào công cụ, nhận 2–3 món Việt
       nấu dưới 30 phút có dùng các đồ đó: ~1']                           ← AI
→ [3. Người nấu mở tủ kiểm đồ còn dùng được không, chọn 1 món
       hoặc bỏ qua cả 3: ~2']                                             ← CON NGƯỜI (HITL)
       ┄┄ BOUNDARY: AI chỉ đề xuất. Người nấu quyết định món
          và tự kiểm đồ còn ăn được hay không ┄┄
→ [4. Nấu ăn]                                                             ← CON NGƯỜI
→ [5. Gạch đồ đã dùng / đã vứt khỏi danh sách: ~1']                       ← CON NGƯỜI

PHƯƠNG ÁN QUAY VỀ:
- Đề xuất không hợp (món lạ, thiếu nguyên liệu, gia đình không ăn)
  hoặc công cụ không chạy → mở "danh sách 10 món quen" gia đình tự viết sẵn,
  hoặc tìm trên Cooky theo 1 nguyên liệu sắp hỏng nhất (No AI).
- Danh sách đồ không được cập nhật quá 3 ngày → bỏ qua bước 1–2,
  quay về mở tủ nhìn như quy trình hiện tại.
```

| Bước | Ai làm | Boundary / ghi chú |
|---:|---|---|
| A | Con người | Bước mới. Rủi ro lớn nhất: người nấu bỏ không ghi (giả định #4, Kitche gặp đúng vấn đề này) |
| 1 | Rule | Sắp xếp theo ngày mua, không cần AI |
| 2 | AI | Chỉ đề xuất món từ đồ **có trong danh sách**; không tự thêm nguyên liệu như thể đang có |
| 3 | Con người (HITL) | Người nấu luôn là người chốt món. Việc đồ còn ăn được không do người nấu tự kiểm, AI không phán đoán |
| 4–5 | Con người | — |

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
| --- | ---: | ---: | --- |
| Số bước | 5 | 6 (A + 1–5) | Thêm bước A ghi đồ khi đi chợ về |
| Tổng thời gian | ~20'/bữa đến lúc chốt món | ~3–4'/bữa + ~2'/lần đi chợ | Trước: ước lượng của Thắng. Sau: kỳ vọng, phải đo trong pilot |
| Số bước thủ công | 5 | 4 (A, 3, 4, 5) | Bước 1 do Rule, bước 2 do AI |
| Bottleneck chính | Bước 3 nghĩ món: 15' | Bước A — giữ danh sách đồ được cập nhật | Bottleneck chuyển từ "nghĩ" sang "ghi chép" |
| Rủi ro mới phát sinh | — | (1) Người nấu bỏ cập nhật danh sách, đề xuất sai vì dữ liệu cũ; (2) AI đề xuất món lạ hoặc cần nguyên liệu không có; (3) người nấu tin đề xuất mà không kiểm đồ đã hỏng chưa | (1) là rủi ro lớn nhất, theo review Kitche ở 3.3 |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
| --- | --- |
| **Actor** | Người nấu ăn chính trong gia đình, đi làm, tự nấu bữa tối các ngày trong tuần (khoảng 18h–19h) |
| **Quy trình** | Mở tủ lạnh xem đồ (3') → lọc đồ sắp hỏng (2') → nghĩ cách kết hợp đồ đang có thành món (15'; khi kẹt thì tìm video công thức hoặc nấu món quen) → nấu. Đồ trong tủ và ngày mua không được ghi lại ở đâu; đồ sắp hỏng không được dùng thì bị vứt khi kế hoạch nấu thay đổi |
| **Bottleneck** | Bước kết hợp đồ đang có, nhất là đồ sắp hỏng, thành món: khoảng 15 phút/bữa (ước lượng của Thắng), sau ngày làm việc mệt. 2/2 người phỏng vấn gặp trong vài ngày gần đây; khi kẹt họ chọn món quen/món trên mạng, không ưu tiên đồ sắp hỏng |
| **Impact** | Đồ hỏng bị vứt khoảng 150–200k/tuần (ước lượng của Thắng); 2/2 người phỏng vấn có vứt rau trong tuần trước (không đưa số tiền). Khoảng 15 phút mỗi tối cho việc nghĩ món (ước lượng). Tiền gọi đồ ăn ngoài **không tính** vào impact vì phỏng vấn cho thấy nguyên nhân là mệt, về muộn |
| **Success Metric** (baseline → target, cách đo) | (1) **Tiền đồ bị vứt:** baseline 150–200k/tuần (ước lượng; đo lại trong 1 tuần trước pilot bằng sổ ghi từng món bị vứt, giá mua và **lý do vứt** — không biết nấu gì / kế hoạch đổi / mua nhiều) → target giảm 80%, dưới 40k/tuần; đo bằng cùng sổ ghi trong 4 tuần pilot. (2) **Thời gian từ lúc mở tủ đến lúc chốt món:** baseline ~15' (ước lượng; bấm giờ lại 5 bữa trước pilot) → target dưới 3'; đo bằng tự bấm giờ 10 bữa tối trong 2 tuần pilot |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | **AI không được:** tự chốt món thay người nấu; phán đoán đồ còn ăn được hay đã hỏng (an toàn thực phẩm do người nấu tự kiểm); tự đặt đồ ăn ngoài hay tự mua hàng; đề xuất món dùng nguyên liệu không có trong danh sách như thể đang có. **Cần con người kiểm tra (HITL):** mỗi lần trước khi nấu, người nấu mở tủ kiểm đồ thật và chọn hoặc bỏ đề xuất; khi gia đình có người dị ứng hay kiêng món, người nấu kiểm nguyên liệu của món được đề xuất |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

Nhóm dùng Claude để phản biện, với yêu cầu chỉ chỉ ra lỗ hổng, không viết lại. Các điểm Claude chỉ ra:

- **Impact và baseline đều là ước lượng của một người (Thắng).** Chưa có log hay phỏng vấn nên chưa biết người khác có giống không. — **Đồng ý.** Đã phỏng vấn 2 người (3.2): xác nhận có pain, nhưng không ai đưa số phút hay số tiền. Ghi rõ "ước lượng" ở mọi con số và thêm bước đo lại baseline trước pilot.
- **Metric tiền đồ vứt có thể không đến từ bottleneck nghĩ món.** Khảo sát ở 3.2 cho thấy đồ bị vứt phổ biến vì mua và nấu quá nhiều. — **Đồng ý một phần.** Phỏng vấn cũng cho thấy đồ bị vứt vì không lên kế hoạch và lịch thay đổi. Nhóm giữ metric nhưng thêm cột **lý do vứt** vào sổ ghi, để biết phần nào thật sự do không biết nấu gì.
- **Metric số tối gọi đồ ngoài cần tách lý do.** Có tối gọi vì về muộn hay có khách, không liên quan tới nghĩ món. — **Đồng ý.** Phỏng vấn 2/2 cho thấy gọi đồ ngoài là do mệt, về muộn. Nhóm **bỏ metric này** và bỏ tiền ăn ngoài khỏi Impact.
- **Quy trình chưa có số liệu cho bước 4–5 và tần suất "nghĩ không ra".** Mỗi tuần bao nhiêu tối bước 3 bị kẹt? — **Đồng ý, chưa sửa được.** Hai người phỏng vấn chỉ kể lần gần nhất. Nhóm đưa việc đếm số tối bị kẹt vào sổ ghi trong tuần đo baseline.

_(Thắng và Duy Anh xem lại các câu trả lời "Đồng ý" ở trên trước khi chốt.)_

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ mơ hồ cao × Độ phức tạp thấp** → "Workflow có AI ở một bước thường đủ".

Vì sao:

- **Độ mơ hồ cao:** với cùng một tủ lạnh (thịt, trứng, ít rau), có nhiều món đều chấp nhận được: trứng chiên, rau luộc, thịt xào rau, canh… Không có một đáp án đúng duy nhất. Cả 2 người phỏng vấn đều kể đúng tình huống này (3.2).
- **Độ phức tạp thấp:** chỉ có **1 nguồn dữ liệu** (danh sách đồ trong tủ kèm ngày mua) và **1 bước cần AI** (ghép đồ thành món). Các bước còn lại cố định và không phụ thuộc kết quả của AI: ghi danh sách, sắp theo ngày, người nấu kiểm tủ và chọn món, gạch đồ đã dùng. Không có bước nào cần AI tự quyết bước tiếp theo.

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) | (a) Thực đơn cố định cả tuần dán trên tủ; (b) dán nhãn ghi ngày mua lên hộp đồ; (c) "danh sách 10 món quen" gia đình tự viết, mỗi món ghi nguyên liệu chính | Lịch nấu ổn định, gia đình chấp nhận ăn lặp lại 10 món | (a) **Đã thất bại** ở người phỏng vấn #2: lịch trực thay đổi nên không theo được. (c) Không xử lý được tổ hợp đồ "lẻ" còn lại trong tủ; người #1 vẫn phải lên YouTube tìm món | Giữ (b), (c) làm **nền và phương án quay về** |
| **Rule**                  | Bảng tính tự sắp danh sách đồ theo ngày mua, tô màu đồ mua quá 2 ngày (rau) hoặc 3 ngày (thịt). Bảng tra "nguyên liệu → món" khớp với danh sách 10 món quen | Đồ sắp hỏng thường rơi đúng vào nguyên liệu của 10 món quen (ước tính trên 70% số tối) | Bảng tra chỉ khớp được tổ hợp đã viết sẵn. Mỗi tối tủ có 3–6 loại đồ khác nhau nên số tổ hợp quá nhiều để viết hết | **Chọn** cho bước đánh dấu đồ sắp hỏng (bước 1) |
| **Workflow**              | Quy trình định sẵn: danh sách → Rule đánh dấu đồ sắp hỏng → **AI gợi ý 2–3 món Việt dưới 30 phút dùng các đồ đó** → người nấu kiểm tủ và chọn → gạch đồ | Rule và 10 món quen không đủ cho phần lớn số tối, và người nấu chịu cập nhật danh sách | AI gợi ý món lạ hoặc thêm nguyên liệu không có; danh sách cũ nên gợi ý sai | **Chọn** (AI chỉ ở bước 2) |
| **Agent**                 | AI tự đọc ảnh tủ lạnh, tự theo dõi hạn dùng, tự lên thực đơn, tự đặt mua đồ thiếu | Khi cần AI tự chọn công cụ và tự lặp nhiều bước | Không có bước nào cần AI tự quyết tiếp theo. Tự đặt mua đồ vi phạm Boundary. Đọc ảnh để phán đồ còn tươi là rủi ro an toàn thực phẩm | Không |

**Mức chọn:** **Workflow** với AI ở đúng một bước (bước 2: gợi ý món), đặt trên nền No AI + Rule: nhãn ghi ngày, danh sách đồ, bảng tính tô màu đồ sắp hỏng, danh sách 10 món quen.

**Vì sao không chọn mức đơn giản hơn:**

- **No AI chưa đủ:** thực đơn cố định đã được người #2 thử và bỏ vì lịch trực thay đổi. Danh sách món quen chính là thứ người nấu đang dùng khi bị kẹt ("nấu món quen đơn giản"), và đó là lý do đồ sắp hỏng bị bỏ lại (4.1, bước 4–5).
- **Rule chỉ đủ một nửa:** Rule làm tốt việc **biết đồ nào sắp hỏng** (có đúng/sai rõ theo ngày mua). Nhưng việc **ghép đồ đó thành món** có độ mơ hồ cao, và số tổ hợp đồ trong tủ quá nhiều để viết sẵn bảng tra.
- **Chưa có số đo chứng minh Rule không đủ.** Vì vậy pilot bắt đầu bằng 2 tuần chỉ chạy No AI + Rule và đếm số tối mà 10 món quen đủ dùng. Nếu 10 món quen đủ dùng từ 70% số tối trở lên thì **dừng ở Rule**, không thêm AI (xem ngưỡng dừng 8.2).
- **Vì sao không lên Agent:** các bước đã cố định. Những việc Agent làm thêm (tự đặt mua, tự phán đồ còn tươi) đều nằm trong Boundary "AI không được làm".

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          | 2–3 món Việt nấu dưới 30 phút, dùng được nhiều nhất các đồ đang được đánh dấu sắp hỏng. Mỗi món ghi: nguyên liệu lấy từ danh sách, nguyên liệu còn thiếu (nếu có), thời gian nấu ước tính |
| **Judgment** — con người cân nhắc, quyết định gì?                 | Người nấu mở tủ kiểm đồ thật còn ăn được không, cân nhắc khẩu vị, dị ứng hay kiêng của gia đình và thời gian tối đó, rồi chọn 1 món hoặc bỏ qua cả 3 |
| **Action** — hành động cuối cùng là gì, ai làm?                   | Người nấu nấu món đã chọn (hoặc món trong danh sách 10 món quen), rồi gạch đồ đã dùng hay đã vứt khỏi danh sách. AI không thực hiện hành động nào ngoài việc trả gợi ý |
| **Outcome** — đo kết quả bằng gì?                                 | (1) Tiền đồ bị vứt mỗi tuần, chia theo lý do vứt; (2) thời gian từ lúc mở tủ đến lúc chốt món; (3) tỷ lệ tối người nấu chọn được ít nhất 1 gợi ý |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | (1) Danh sách đồ trong tủ kèm ngày mua; (2) đồ được Rule đánh dấu sắp hỏng; (3) gia vị cơ bản luôn có trong bếp; (4) ràng buộc gia đình: dị ứng, kiêng, món không ăn. **Hiện chưa có sẵn:** (1) chưa tồn tại, phải tạo bằng bước A (ghi đồ khi đi chợ về). (3) và (4) chỉ cần viết một lần. Đây là lý do rủi ro Usability ở 8.1 là Cao |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   | Sổ ghi mỗi tối: chọn món nào hay bỏ cả 3, lý do bỏ (món lạ / thiếu đồ / gia đình không ăn / không kịp nấu). Sổ ghi đồ vứt kèm lý do. Mỗi cuối tuần, dùng sổ để sửa câu lệnh gợi ý món (ví dụ thêm "không gợi ý món chiên ngập dầu") và bổ sung danh sách 10 món quen |

### 6.4. Hai câu hỏi của Google PAIR

- **Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)?** → **Augment.**
  - Cả 2/2 người phỏng vấn khi bị kẹt vẫn **tự nấu**: tìm YouTube, nấu món quen. Họ không bỏ việc nấu, chỉ thiếu ý tưởng ghép đồ.
  - Người #2 muốn "gợi ý món ăn dựa trên nguyên liệu sẵn có". Đây là ý kiến về giải pháp, không tính là bằng chứng, nhưng cũng chỉ nói tới *gợi ý*, không nói tới để máy quyết.
  - Người nấu còn phải kiểm đồ thật trong tủ, khẩu vị và dị ứng của gia đình, những thứ AI không thấy được. Vì vậy thiết kế giữ người nấu là người chốt món (bước 3, HITL).
- **AI sai kiểu nào tệ hơn, báo nhầm hay bỏ sót?** → **Báo nhầm tệ hơn.**
  - *Báo nhầm* là AI đưa ra món dùng nguyên liệu không có như thể đang có, hoặc ngụ ý đồ đã để lâu "vẫn dùng được". Hậu quả: mất thời gian, mất lòng tin, và trong trường hợp xấu là ăn phải đồ hỏng.
  - *Bỏ sót* là AI không dùng tới một món đồ sắp hỏng. Hậu quả chỉ bằng quy trình hiện tại: đồ đó có thể bị vứt.
  - Thiết kế đã xử lý: (1) AI chỉ được dùng đồ trong danh sách cộng gia vị cơ bản, nguyên liệu thiếu phải ghi riêng là "cần mua" (tiêu chí 1 ở mục 7); (2) AI không phán đồ còn ăn được không, việc này người nấu tự kiểm (Boundary); (3) việc đánh dấu đồ sắp hỏng do Rule làm theo ngày mua, không do AI đoán.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       | Người nấu ăn chính trong gia đình, đi làm, tự nấu bữa tối các ngày trong tuần (khoảng 18h–19h), **nhất là người có lịch làm thay đổi** (trực, tăng ca) khiến kế hoạch nấu hay bị phá |
| **Quy trình**                                   | Mở tủ lạnh xem đồ (3') → lọc đồ sắp hỏng (2') → nghĩ cách kết hợp đồ đang có thành món (15'; khi kẹt thì tìm video công thức hoặc nấu món quen) → nấu. Đồ trong tủ và ngày mua không được ghi lại ở đâu; đồ sắp hỏng không được dùng thì bị vứt khi kế hoạch nấu thay đổi |
| **Bottleneck**                                  | Bước kết hợp đồ đang có, nhất là đồ sắp hỏng, thành món: khoảng 15 phút/bữa (ước lượng), sau ngày làm việc mệt. Khi kẹt, người nấu chọn món quen nên đồ sắp hỏng không được dùng tới. Gốc của bước này là **không có danh sách đồ và ngày mua**, nên phải nhớ trong đầu |
| **Impact**                                      | Đồ hỏng bị vứt khoảng 150–200k/tuần (ước lượng; 2/2 người phỏng vấn có vứt rau tuần trước). Khoảng 15 phút mỗi tối để nghĩ món (ước lượng). **Chỉ một phần** tiền vứt đến từ bottleneck này; phần còn lại do mua hoặc nấu quá nhiều (khảo sát ở 3.2). Tiền gọi đồ ăn ngoài không tính |
| **Success Metric** (baseline → target, cách đo) | (1) **Tiền đồ vứt có lý do "không biết nấu gì / quên trong tủ":** baseline đo trong 1 tuần bằng sổ ghi từng món vứt, giá mua, lý do → target **giảm 50%** sau 4 tuần pilot, cùng sổ ghi. (2) **Thời gian mở tủ đến lúc chốt món:** baseline bấm giờ 5 bữa (ước lượng ~15') → target **dưới 5'**, bấm giờ 10 bữa trong pilot. (3) **Tỷ lệ tối chọn được ít nhất 1 gợi ý:** target **từ 60% trở lên** số tối tự nấu, ghi trong sổ mỗi tối. (4) **Tỷ lệ ngày danh sách được cập nhật** (chỉ số báo sớm cho rủi ro Usability): target **từ 80% trở lên** số ngày có đi chợ hoặc dùng đồ |
| **Boundary**                                    | **AI không được:** tự chốt món thay người nấu; phán đoán đồ còn ăn được hay đã hỏng (an toàn thực phẩm do người nấu tự kiểm); tự đặt đồ ăn ngoài hay tự mua hàng; đưa nguyên liệu không có trong danh sách vào món như thể đang có; tự nhận diện đồ qua ảnh tủ lạnh trong giai đoạn pilot. **Cần con người kiểm tra (HITL):** mỗi lần trước khi nấu, người nấu mở tủ kiểm đồ thật rồi chọn hoặc bỏ gợi ý; khi gia đình có người dị ứng hay kiêng món, người nấu kiểm nguyên liệu của món được gợi ý |
| **AI intervention point**                       | Chỉ ở **bước 2 của quy trình tương lai (4.2):** nhận danh sách đồ sắp hỏng (do Rule đánh dấu) kèm ràng buộc gia đình, trả về 2–3 món Việt dưới 30 phút. Các bước ghi danh sách, đánh dấu đồ sắp hỏng, kiểm tủ, chọn món và nấu đều không dùng AI |
| **Mức chọn**                                    | **Workflow** (AI ở 1 bước), đặt trên nền No AI + Rule. Chỉ thêm AI nếu 2 tuần chạy No AI + Rule cho thấy 10 món quen không đủ dùng (xem 8.2) |
| **Rủi ro & người kiểm tra**                     | (1) Người nấu bỏ cập nhật danh sách nên gợi ý dựa trên dữ liệu cũ → người nấu tự kiểm tủ ở bước 3; nhóm kiểm tỷ lệ ngày cập nhật mỗi tuần (Thịnh theo dõi sổ). (2) AI gợi ý món lạ hoặc thêm nguyên liệu không có → người nấu bỏ gợi ý và ghi lý do; nhóm chấm lại theo 5 tiêu chí bên dưới mỗi tuần. (3) Gợi ý vi phạm dị ứng hay kiêng → người nấu kiểm nguyên liệu trước khi nấu; ràng buộc gia đình luôn được đưa vào câu lệnh |

**Thay đổi so với v0 và lý do:**

| Trường | v0  | v1  | Vì sao đổi |
| ------ | --- | --- | ---------- |
| Actor | Người nấu ăn chính trong gia đình, đi làm | Thêm "nhất là người có lịch làm thay đổi" | Phỏng vấn #2: thực đơn cố định (No AI) thất bại vì lịch trực thay đổi. Đây là nhóm mà giải pháp gợi ý mỗi tối khác biệt rõ nhất so với No AI |
| Bottleneck | Bước kết hợp đồ thành món, 15'/bữa | Thêm gốc: không có danh sách đồ và ngày mua | Khi phân tích Input của AI Canvas (6.3), nhóm thấy AI không thể gợi ý nếu không có danh sách. Gốc của việc "nghĩ lâu" là phải nhớ trong đầu |
| Impact | Đồ vứt 150–200k/tuần, toàn bộ quy cho bottleneck | Ghi rõ chỉ một phần tiền vứt đến từ bottleneck | Khảo sát Tạp chí Công Thương: mua và nấu quá nhiều là nguyên nhân phổ biến; phỏng vấn: vứt do không lên kế hoạch và lịch đổi |
| Success Metric | Tiền vứt giảm 80% (dưới 40k); thời gian dưới 3' | Đo riêng tiền vứt có lý do "không biết nấu gì / quên", target giảm 50%; thời gian dưới 5'; thêm metric (3) tỷ lệ chọn gợi ý và (4) tỷ lệ cập nhật danh sách | Target 80% quy toàn bộ đồ vứt cho bottleneck, không thực tế. Thời gian sau phải cộng bước kiểm tủ (~2'). Metric (3) đo chất lượng gợi ý; metric (4) báo sớm rủi ro lớn nhất (Usability) |
| Boundary | 4 điều AI không được | Thêm "không tự nhận diện đồ qua ảnh tủ lạnh trong pilot" | Đọc ảnh để biết đồ gì, còn tươi không, là bước có rủi ro báo nhầm cao nhất (6.4); pilot chỉ dùng danh sách gõ tay |
| AI intervention point, Mức chọn, Rủi ro & người kiểm tra | (chưa có) | Như bảng trên | Trường mới của v1, từ phân tích ở mục 6 |

**Tiêu chí đánh giá đầu ra của AI (5 tiêu chí):**

Cách chấm: trước pilot, chạy thử 20 lần với danh sách đồ thật của Thắng và 1 người đúng actor, chấm từng gợi ý theo 5 tiêu chí. Tiêu chí 1, 4, 5 phải đạt **100%**; tiêu chí 2, 3 phải đạt **từ 80% trở lên**. Không đạt thì sửa câu lệnh hoặc quay về Rule.

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 | Không bịa nguyên liệu | Mọi nguyên liệu chính của món có trong danh sách hoặc trong gia vị cơ bản đã khai báo; nguyên liệu thiếu được ghi riêng là "cần mua" | Món cần nguyên liệu không có trong danh sách mà không ghi là thiếu |
|   2 | Ưu tiên đồ sắp hỏng | Mỗi món dùng ít nhất 1 đồ được đánh dấu sắp hỏng; nếu có từ 2 đồ sắp hỏng trở lên thì 3 gợi ý cộng lại dùng hết ít nhất 2 đồ | Có món không dùng đồ sắp hỏng nào trong khi danh sách có đồ sắp hỏng |
|   3 | Món Việt, nấu nhanh | Món Việt quen thuộc trong bữa cơm gia đình, có ghi thời gian, dưới 30 phút | Món nước ngoài hoặc món lạ, cần dụng cụ đặc biệt, hoặc trên 30 phút |
|   4 | Tôn trọng ràng buộc gia đình | Không có nguyên liệu nằm trong danh sách dị ứng, kiêng hay không ăn | Có ít nhất 1 nguyên liệu vi phạm ràng buộc đã khai báo |
|   5 | Không phán an toàn thực phẩm | Không có câu khẳng định đồ nào "vẫn dùng được" hay "còn tươi"; nếu nhắc tới thì chỉ nhắc người nấu tự kiểm | Có câu khẳng định đồ để lâu vẫn ăn được, hoặc khuyên dùng đồ người nấu chưa kiểm |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       | **TB** | Pain có thật: 2/2 người phỏng vấn gặp trong vài ngày gần đây, 2/2 vứt rau tuần trước. Nhưng giả định #2 bị phản bác: đồ bị vứt chủ yếu vì không lên kế hoạch và lịch đổi, khảo sát còn cho thấy mua và nấu quá nhiều. Chưa biết bao nhiêu phần trăm tiền vứt thật sự do "không biết nấu gì". Số phút và số tiền vẫn là ước lượng của 1 người |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Cao** | Giải pháp phụ thuộc bước A (ghi đồ mỗi lần đi chợ), một thói quen mới. Review Kitche: app sai khi người dùng không đánh dấu đồ đều đặn. Người #2 đã không duy trì được thực đơn cả tuần. Phần đọc và chọn gợi ý thì dễ: 2–3 món, người nấu tự kiểm và bỏ được |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     | **Thấp** | Công cụ có sẵn và miễn phí: bảng tính (Google Sheets) cho danh sách và Rule tô màu; một chatbot AI phổ thông cho bước gợi ý; Cooky cho công thức món Việt. Input là văn bản ngắn (dưới 20 dòng). Nhóm không cần viết code để chạy pilot |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     | **Thấp** | Chi phí 0đ với bản miễn phí. Dữ liệu là danh sách thực phẩm, không nhạy cảm. Người vận hành là chính người nấu, không cần tổ chức phê duyệt. Rủi ro dị ứng được giữ bằng HITL và tiêu chí 4 |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:** Có 1 rủi ro **Cao** (Usability: người nấu có duy trì danh sách đồ không) và 1 rủi ro **TB** (Value: bao nhiêu phần tiền vứt thật sự do không biết nấu gì). Cả hai kiểm chứng được nhanh, trong 2–3 tuần, mà **chưa cần dùng AI**: chỉ cần sổ ghi và danh sách giấy hoặc bảng tính. Nếu Go ngay, nhóm có thể làm AI tốt cho một danh sách mà không ai cập nhật, hoặc giải một nguyên nhân chỉ chiếm phần nhỏ tiền vứt. Feasibility và Viability đều Thấp nên khi đã qua kiểm chứng thì chuyển sang Go rất nhanh.

**Nếu Go — pilot nhỏ nhất** (chạy sau khi qua 2 bước kiểm chứng bên dưới):

- 2 người đúng actor (Thắng và 1 người nấu chính trong gia đình), 4 tuần, bữa tối thứ 2–6.
- Công cụ: bảng tính danh sách đồ + Rule tô màu + chatbot AI với câu lệnh cố định đã qua 5 tiêu chí ở mục 7.
- Đo theo Success Metric (1)–(4) của v1, so với tuần baseline.

**Nếu Not Yet — cần kiểm chứng gì trước:**

1. **Tuần 1 — đo baseline (kiểm Value):** Thắng và ít nhất 1 người đúng actor ghi sổ mỗi món bị vứt (tên, giá mua, **lý do**: không biết nấu gì / quên trong tủ / kế hoạch đổi / mua hoặc nấu quá nhiều), đếm số tối bị kẹt khi nghĩ món, và bấm giờ 5 bữa từ lúc mở tủ đến lúc chốt món.
2. **Tuần 2–3 — chạy No AI + Rule (kiểm Usability và mức đủ của Rule):** dùng nhãn ghi ngày, danh sách đồ trong bảng tính (bước A) và danh sách 10 món quen, chưa có AI. Đo: tỷ lệ ngày danh sách được cập nhật, và tỷ lệ tối mà 10 món quen có món dùng được đồ sắp hỏng.
3. **Chạy thử AI ngoài pilot:** 20 lần với danh sách thật, chấm theo 5 tiêu chí ở mục 7.
4. **Phỏng vấn thêm ít nhất 1 người đúng actor** (người nấu chính trong gia đình), hỏi lại số phút nghĩ món, vì 2 người đã phỏng vấn chưa ai đúng hoàn toàn actor.

**Chuyển sang Go khi đủ cả 3:** danh sách được cập nhật **từ 80% trở lên** số ngày; 10 món quen chỉ đủ dùng **dưới 70%** số tối; và đồ vứt có lý do "không biết nấu gì / quên trong tủ" chiếm **từ 40% trở lên** tổng tiền vứt.

**Nếu No-Go — nên làm gì thay AI:** không áp dụng ở thời điểm này. Nếu chạm ngưỡng dừng bên dưới, nhóm giữ phần No AI + Rule đã chạy (nhãn ghi ngày, danh sách 10 món quen), hoặc chuyển trọng tâm sang nhánh D3 (mua trùng, mua quá nhiều) hay candidate #8.

**Ngưỡng dừng:**

- Nếu sau **2 tuần** chạy No AI + Rule mà danh sách được cập nhật **dưới 50%** số ngày → bỏ hướng danh sách, quay về **nhãn ghi ngày dán trên hộp đồ** (No AI), không làm AI.
- Nếu sau **2 tuần** chạy No AI + Rule mà danh sách 10 món quen đủ dùng **từ 70% trở lên** số tối → **dừng ở Rule**, không thêm AI.
- Nếu sổ ghi tuần baseline cho thấy đồ vứt có lý do "không biết nấu gì / quên trong tủ" chiếm **dưới 30%** tổng tiền vứt → bottleneck sai trọng tâm, chuyển sang nhánh **D3** (mua trùng, mua quá nhiều) hoặc candidate **#8**.
- Nếu sau **4 tuần pilot AI** mà người nấu bỏ qua cả 3 gợi ý **quá 50%** số tối, hoặc tiền vứt có lý do "không biết nấu gì / quên" giảm **dưới 30%** so với baseline → quay về **No AI + Rule**.

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- **Số liệu baseline là ước lượng của 1 người.** 15 phút nghĩ món, 150–200k đồ vứt/tuần là Thắng tự ước lượng, chưa bấm giờ hay ghi sổ. Lịch sử app giao đồ ăn của Thắng chưa được đối chiếu (3.2).
- **Kiểm chứng ít mẫu và chưa đúng actor.** Chỉ phỏng vấn 2 người. Người #1 là sinh viên sống một mình, nằm ngoài actor "người nấu chính trong gia đình"; người #2 chưa rõ hoàn cảnh gia đình. Không ai đưa số phút nghĩ món.
- **Nguồn thứ cấp có giới hạn.** Khảo sát Tạp chí Công Thương không ghi tổng số mẫu và không hỏi lý do "không biết nấu gì". Số liệu UNEP chỉ đọc được qua bài báo trích lại (trang UNEP chặn truy cập), và là số liệu toàn cầu. Con số "mỗi người Việt lãng phí 72 kg/năm" xuất hiện trong kết quả tìm kiếm nhưng nhóm không tìm được nguồn gốc nên **không dùng**.
- **Research công cụ chưa tự dùng thử.** Thông tin về Kitche và Cooky lấy từ trang giới thiệu và bài review. Nhóm chưa tự mở app để kiểm tính năng tìm món theo nhiều nguyên liệu cùng lúc.
- **Bước ghi danh sách đồ (bước A) chưa được thử với người thật.** Đây là rủi ro Usability Cao (8.1), và cũng là điểm yếu đã biết của Kitche.

**Hướng tiếp theo:**

1. Chạy 3 bước kiểm chứng của quyết định Not Yet (8.2): tuần 1 đo baseline bằng sổ ghi có lý do vứt; tuần 2–3 chạy No AI + Rule; chạy thử AI 20 lần chấm theo 5 tiêu chí ở mục 7.
2. Phỏng vấn thêm ít nhất 1 người đúng actor, hỏi số phút nghĩ món và số tối bị kẹt mỗi tuần.
3. Nếu chạm ngưỡng dừng về Value (đồ vứt do "không biết nấu gì / quên" dưới 30%): chuyển sang nhánh D3 (mua trùng, mua quá nhiều) — khớp với khảo sát Tạp chí Công Thương — hoặc candidate #8 (bố mẹ hỏi cách dùng điện thoại, bằng chứng mạnh nhất trong shortlist).

## 10. Tài liệu tham khảo

**Số liệu và nghiên cứu** (mở và kiểm ngày 09/11/2026):

- Quách Thùy Trang (10/2025). *Nghiên cứu sự khác biệt về hành vi lãng phí thực phẩm giữa các thế hệ ở Việt Nam hiện nay.* Tạp chí Công Thương. https://tapchicongthuong.vn/nghien-cuu-su-khac-biet-ve-hanh-vi-lang-phi-thuc-pham-giua-cac-the-he-o-viet-nam-hien-nay-245709.htm
- Báo Pháp luật Việt Nam (02/01/2025). *Bài 1: Lãng phí đồ ăn từ mâm cơm gia đình tới nhà hàng ở Việt Nam* (dẫn số liệu FoodBank Việt Nam, 9/2024). https://baophapluat.vn/bai-1-lang-phi-do-an-tu-mam-com-gia-dinh-toi-nha-hang-o-viet-nam-post535007.html
- MyJoyOnline (28/03/2024). *Hotter countries generate more food waste per capita in households* (trích UNEP Food Waste Index Report 2024). https://www.myjoyonline.com/hotter-countries-generate-more-food-waste-per-capita-in-households/

**Công cụ đã research:**

- SuperCook — App Store: https://apps.apple.com/us/app/id1477747816 · Website: https://www.supercook.com/
- Kitche — Website: https://www.kitche.co/ · Review TapSmart (2020, cập nhật 2021): https://www.tapsmart.com/apps/food-drinks/review-kitche/
- Cooky — Bài giới thiệu Sforum/CellphoneS (cập nhật 24/06/2023): https://cellphones.com.vn/sforum/cooky-ung-dung-chia-se-cong-thuc-nau-an-ngon-hang-dau-viet-nam

**Framework dùng trong bài:** xem [docs/03-international-frameworks.md](../../docs/03-international-frameworks.md) — Double Diamond, Job Story, Opportunity Solution Tree, Assumption Mapping, The Mom Test, Lean UX, Google PAIR, AI Canvas, Anthropic *Building Effective Agents*, 4 rủi ro của Marty Cagan.
