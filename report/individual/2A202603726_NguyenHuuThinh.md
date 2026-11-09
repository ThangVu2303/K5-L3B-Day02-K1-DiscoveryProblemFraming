# Báo cáo cá nhân — 2A202603726_NguyenHuuThinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Hữu Thịnh
- MSSV: 2A202603726
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: K1
- Link repo nhóm: https://github.com/ThangVu2303/K5-L3B-Day02-K1-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
| --: | --------- | ----------------------------- | ------------------ | --------------------------------------------------------- |
| 1 | Lặp lại | Khi cuối tuần đi chợ, tôi muốn biết nhà còn thiếu gì, để không mua trùng hoặc quên đồ | 2 người (tôi, vợ) | 15'/lần đi mua bù; 2 lần quên/tuần; tin Zalo vợ nhắn "anh quên mua trứng rồi" (2 tin tuần này) |
| 2 | Lặp lại | Khi mỗi sáng đi làm, tôi muốn biết đường nào đang tắc, để không đến muộn | 1 người (tôi) + team chờ họp | Trễ 10–20'/lần; 2 lần trễ/tuần; lịch sử chấm công: 7 lần trễ trong tháng 10 |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi cuối tháng muốn biết tiền đã đi đâu, tôi muốn thấy chi tiêu theo từng nhóm, để điều chỉnh tháng sau | 2 người (vợ chồng) | 60–90'/lần; 1 lần/tháng; phải xem 3 nguồn (2 tài khoản ngân hàng, 1 ví điện tử), file Excel tự cộng |
| 4 | Tốn thời gian | Khi làm thủ tục hành chính, tôi muốn biết chính xác cần mang gì, để không phải đi lại nhiều lần | 1–2 người | 90'/lần đi; 2–3 lần đi/thủ tục; giấy hẹn bổ sung hồ sơ, lịch sử Grab 3 chuyến cùng địa chỉ |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi thuê nhà, tôi muốn so sánh giá, vị trí, điều kiện giữa nhiều tin đăng, để chọn nhanh | 2 người | 30'/tin đăng; 15 tin/tuần trong 3 tuần; danh sách tin đã lưu trên app, lịch hẹn xem 8 phòng |
| 6 | Pain từ người khác | Khi bố mẹ hay gọi hỏi cách dùng điện thoại, chuyển khoản, tôi muốn họ tự làm được, để không phải chờ tôi rảnh | 3 người (bố, mẹ, tôi) | 10–15'/cuộc; 4 cuộc/tuần; lịch sử cuộc gọi: 9 cuộc trong 2 tuần, phần lớn hỏi cùng một việc |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Không dùng AI gợi ý thêm problem. 6 problem trên do tôi tự scan; AI chỉ trình bày vào bảng và gán lăng kính (xem mục 5, dòng CP1).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
| ---: | ------- | ----------- | ------------------ |
| 1 | Tổng hợp chi tiêu cuối tháng (#3) | Quy trình rõ và vẽ được (tải sao kê 3 nguồn → nhập Excel → phân nhóm → cộng tổng); tốn nhiều thời gian nhất (60–90'/lần); bottleneck cụ thể là bước phân nhóm từng giao dịch; có baseline đo được; so sánh được No AI / Rule / Workflow (app ngân hàng, quy tắc phân loại theo tên người nhận…) | Bước nào thật sự tốn nhất: lấy dữ liệu từ 3 nguồn hay phân nhóm giao dịch? Có xuất được sao kê dạng file từ cả 3 nguồn không? Vợ có cùng cách phân nhóm với mình không? |
| 2 | Bố mẹ hỏi cách dùng điện thoại, chuyển khoản (#6) | Tần suất cao (4 cuộc/tuần), có bằng chứng rõ (9 cuộc gọi trong 2 tuần, phần lớn hỏi cùng một việc); pain từ người khác nên impact không chỉ ở mình; câu hỏi lặp lại gợi ý có thể giải bằng hướng dẫn/checklist | Có đúng là "cùng một việc" không, hay mỗi lần một thao tác khác? Bố mẹ có muốn tự làm không, hay gọi điện còn vì muốn nói chuyện? Chuyển khoản liên quan tiền nên sai một bước là rủi ro |
| 3 | Đi chợ cuối tuần quên đồ (#1) | Lặp lại hằng tuần, actor rõ (2 vợ chồng), có bằng chứng (tin Zalo, 2 lần quên/tuần), quy trình ngắn và dễ vẽ, vừa sức một buổi lab | Impact nhỏ (15'/lần mua bù), có thể chỉ cần một danh sách chung là đủ, không cần đến AI; chưa rõ nguyên nhân quên là do không ghi lại hay ghi rồi nhưng không xem |

### Problem Card #1 — Tổng hợp chi tiêu cuối tháng

| Trường | Nội dung |
| --- | --- |
| Job Story | Khi cuối tháng muốn biết tiền đã đi đâu, tôi muốn thấy chi tiêu theo từng nhóm, để điều chỉnh tháng sau |
| Actor | Tôi (người tổng hợp); vợ (cùng xem và quyết định điều chỉnh) |
| Thời điểm / bối cảnh | Ngày cuối tháng hoặc đầu tháng mới, buổi tối ở nhà; tiền chi từ 3 nguồn: 2 tài khoản ngân hàng và 1 ví điện tử |
| Quy trình hiện tại (3–7 bước) | 1. Mở app ngân hàng A xem/tải lịch sử giao dịch (10') → 2. Làm tương tự với ngân hàng B (10') → 3. Làm tương tự với ví điện tử (10') → 4. Chép giao dịch vào file Excel (15') → 5. Phân nhóm từng giao dịch: ăn uống, đi lại, nhà cửa… (25') → 6. Cộng tổng theo nhóm, xem cùng vợ (5') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5 — phân nhóm từng giao dịch: khoảng 25'/lần, vì nội dung chuyển khoản ghi lộn xộn, phải nhớ lại từng khoản là gì |
| Impact (nếu không giải thì sao) | Mất 60–90'/tháng; nhiều tháng bỏ dở không tổng hợp, nên không biết tiền đi đâu để điều chỉnh; hai vợ chồng thiếu số liệu chung khi bàn chuyện chi tiêu |
| Success metric (baseline → target) | Thời gian tổng hợp: 60–90'/tháng → dưới 20'/tháng; đo bằng tự bấm giờ 2 tháng tiếp theo |
| Phương án không dùng AI | Gom chi tiêu về ít nguồn hơn; dùng tính năng thống kê chi tiêu có sẵn trong app ngân hàng; lập bảng Excel có sẵn danh mục và công thức cộng; ghi nhóm ngay lúc chuyển khoản |
| Giả thuyết về AI (nếu có) | AI có thể gợi ý nhóm cho các giao dịch mà nội dung chuyển khoản không rõ ràng; con người duyệt lại trước khi cộng tổng |
| Cảm nhận nhanh | Rule (quy tắc phân loại theo tên người nhận/từ khóa) hoặc Workflow |

Quy trình nháp hiện tại (tổng khoảng 75'/tháng):

```text
[Xem/tải giao dịch NH A: 10'] → [NH B: 10'] → [Ví điện tử: 10']
→ [Chép vào Excel: 15']
→ [Phân nhóm từng giao dịch: 25'] ← BOTTLENECK
→ [Cộng tổng, xem cùng vợ: 5']
```

### Problem Card #2 — Bố mẹ hỏi cách dùng điện thoại, chuyển khoản

| Trường | Nội dung |
| --- | --- |
| Job Story | Khi bố mẹ hay gọi hỏi cách dùng điện thoại, chuyển khoản, tôi muốn họ tự làm được, để không phải chờ tôi rảnh |
| Actor | Bố, mẹ (người cần làm thao tác); tôi (người hướng dẫn) |
| Thời điểm / bối cảnh | Bất kỳ lúc nào trong ngày, thường khi tôi đang làm việc; bố mẹ ở xa nên chỉ hướng dẫn được qua điện thoại |
| Quy trình hiện tại (3–7 bước) | 1. Bố/mẹ gặp thao tác không biết làm, gọi cho tôi (1') → 2. Tôi hỏi để hiểu bố mẹ đang ở màn hình nào, bị kẹt ở đâu (5') → 3. Hướng dẫn từng bước bằng lời (5') → 4. Kiểm tra lại đã làm xong chưa (2') → 5. Lần sau gặp lại cùng việc thì gọi lại từ đầu |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 — xác định bố mẹ đang ở màn hình nào: khoảng 5'/cuộc (ước lượng, chưa bấm giờ), vì không nhìn thấy màn hình và bố mẹ khó mô tả bằng lời. Nguyên nhân gốc khiến cả quy trình lặp lại là bước 3: hướng dẫn chỉ bằng lời, không lưu lại, nên lần sau bố mẹ quên và gọi lại (bước 5) |
| Impact (nếu không giải thì sao) | Khoảng 50'/tuần (4 cuộc × 10–15'); bị ngắt quãng khi đang làm việc; bố mẹ phải chờ đến lúc tôi rảnh, việc chuyển khoản có thể bị trễ |
| Success metric (baseline → target) | Số cuộc gọi hỏi lại việc **đã từng được hướng dẫn**: khoảng 4 cuộc/tuần → tối đa 1 cuộc/tuần; đo bằng lịch sử cuộc gọi, sau mỗi cuộc ghi 1 dòng "hỏi việc gì, việc cũ hay mới" trong 4 tuần (không tính cuộc gọi hỏi thăm) |
| Phương án không dùng AI | Viết hướng dẫn từng bước có ảnh chụp màn hình cho 3–5 việc hay hỏi nhất, in ra hoặc gửi Zalo để bố mẹ xem lại; gọi video hoặc chia sẻ màn hình khi cần. Riêng chuyển khoản: bố mẹ chụp màn hình xác nhận (tên người nhận, số tiền) gửi tôi kiểm trước khi bấm chuyển |
| Giả thuyết về AI (nếu có) | Chưa thấy cần AI: câu hỏi lặp lại cùng một việc nên hướng dẫn cố định có thể đủ |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại (khoảng 13'/cuộc, 4 cuộc/tuần):

```text
[Bố/mẹ gọi: 1']
→ [Hỏi xem đang ở màn hình nào, kẹt ở đâu: 5'] ← BOTTLENECK
→ [Hướng dẫn từng bước bằng lời: 5']
→ [Kiểm tra đã xong: 2']
→ (lần sau gặp lại việc cũ → gọi lại từ đầu)
```

### Problem Card #3 — Đi chợ cuối tuần quên đồ

| Trường | Nội dung |
| --- | --- |
| Job Story | Khi cuối tuần đi chợ, tôi muốn biết nhà còn thiếu gì, để không mua trùng hoặc quên đồ |
| Actor | Tôi (người đi chợ); vợ (người biết nhà đang thiếu gì) |
| Thời điểm / bối cảnh | Sáng cuối tuần, trước và trong lúc đi chợ; đồ dùng hết rải rác trong tuần nhưng không ai ghi lại |
| Quy trình hiện tại (3–7 bước) | 1. Trong tuần đồ hết dần, chỉ nhớ trong đầu (0') → 2. Trước khi đi, nhắn Zalo hỏi vợ hoặc tự nhớ lại cần mua gì (5') → 3. Đi chợ, mua theo trí nhớ (45', ước lượng, chưa bấm giờ) → 4. Về nhà, vợ phát hiện thiếu hoặc mua trùng, nhắn tin (1') → 5. Đi mua bù (15') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 — lập danh sách cần mua dựa vào trí nhớ (5'); bước này thiếu sót nên sinh ra bước 5 đi mua bù 15'/lần, 2 lần/tuần |
| Impact (nếu không giải thì sao) | Khoảng 30'/tuần đi mua bù; mua trùng gây lãng phí đồ tươi; hai vợ chồng khó chịu khi quên đồ |
| Success metric (baseline → target) | Số lần quên đồ phải mua bù: 2 lần/tuần → tối đa 2 lần/tháng; đo bằng đếm tin nhắn Zalo nhắc quên đồ trong 4 tuần |
| Phương án không dùng AI | Dùng một danh sách chung (ghi chú chia sẻ trên điện thoại hoặc tờ giấy dán tủ lạnh); ai thấy hết đồ thì ghi ngay; trước khi đi chợ mở danh sách ra đối chiếu |
| Giả thuyết về AI (nếu có) | Không cần AI: danh sách chung có thể giải phần lớn vấn đề |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại (khoảng 66'/tuần, trong đó 15'×2 mua bù):

```text
[Đồ hết trong tuần, chỉ nhớ trong đầu: 0']
→ [Hỏi vợ / tự nhớ cần mua gì: 5'] ← BOTTLENECK
→ [Đi chợ theo trí nhớ: 45']
→ [Về nhà phát hiện thiếu: 1']
→ [Đi mua bù: 15'/lần, 2 lần/tuần]
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: Tần suất cao nhất (4 cuộc/tuần), có bằng chứng rõ (9 cuộc gọi trong 2 tuần, phần lớn hỏi cùng một việc); pain nằm ở người khác (bố mẹ) nên impact không chỉ ở mình; nhiều người trong lớp có thể gặp cùng vấn đề với bố mẹ lớn tuổi nên dễ kiểm chứng
- Câu hỏi muốn nhóm phản biện: Bố mẹ gọi lại vì quên cách làm, hay vì sợ làm sai (nhất là chuyển khoản)? Nếu là sợ sai thì hướng dẫn bằng ảnh có đủ không?

### AI đã phản biện card thế nào

Phản biện card #2 (bố mẹ hỏi cách dùng điện thoại) bằng prompt "PM hoài nghi" trong worksheet.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
| ------------------ | ------- | --------- |
| Metric "số cuộc gọi" sai hướng: bố mẹ gọi còn để hỏi thăm, giảm số cuộc gọi không phải mục tiêu | Đồng ý | Đổi metric thành "số cuộc gọi hỏi lại việc đã từng được hướng dẫn", ghi nội dung mỗi cuộc để tách cuộc gọi hỏi thăm |
| "Phần lớn hỏi cùng một việc" chưa nói là việc gì, bao nhiêu cuộc; không biết nên viết hướng dẫn cho việc nào trước | Đồng ý | Chưa sửa card; trước buổi pitch sẽ xem lại 9 cuộc gọi trong 2 tuần và đếm theo từng việc để chọn 3–5 việc hay hỏi nhất |
| Bottleneck bước 2 chỉ là triệu chứng; nguyên nhân khiến quy trình lặp lại là hướng dẫn bằng lời không lưu lại | Đồng ý một phần | Giữ bước 2 là bước tốn nhất mỗi cuộc, bổ sung nguyên nhân gốc (bước 3 không lưu lại) vào ô Bottleneck |
| Để bố mẹ tự chuyển khoản có thể tăng rủi ro chuyển nhầm hoặc bị lừa đảo | Đồng ý | Thêm vào phương án không dùng AI: bố mẹ chụp màn hình xác nhận gửi tôi kiểm trước khi bấm chuyển |
| Actor nên là bố mẹ chứ không phải "tôi", vì bố mẹ mới là người cần làm được việc | Không đồng ý | Giữ cả hai actor: tôi là người mất thời gian và quan sát được quy trình; bố mẹ là người thực hiện thao tác |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?         | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------- | ---------------------- | -------------------------------- |
| Pitch Problem Card | Pitch 3 card: chi tiêu cuối tháng (#7), bố mẹ hỏi cách dùng điện thoại (#8), đi chợ quên đồ (#9). Card muốn pitch nhất: #8 | #8 vào shortlist 2.4 (31 điểm); #9 thành nhánh D3 trong cây OST |
| Phản biện bài của bạn khác | Hỏi Thắng về card #3 (không biết kết hợp đồ trong tủ lạnh thành món): việc không nghĩ ra món có thật sự khiến người dùng bỏ thực phẩm không, hay nguyên nhân còn đến từ mua quá nhiều, không lên kế hoạch hoặc lịch sinh hoạt thay đổi? | Card được xem lại về quan hệ nguyên nhân – tác động: không mặc định toàn bộ đồ bị vứt là do không nghĩ ra món. Nhóm bổ sung việc ghi lý do vứt để kiểm chứng chính xác hơn |
| Nhận phản biện | Duy Anh hỏi về card #8 (bố mẹ hay gọi hỏi cách dùng điện thoại): vì sao tôi xác định đây là vấn đề cần giải bằng công nghệ, trong khi một số thao tác có thể hướng dẫn bằng hình ảnh hoặc tài liệu đơn giản? | Card #8 vốn đã chọn No AI: phương án chính là hướng dẫn từng bước bằng ảnh cho 3–5 việc hay hỏi nhất, không cần công nghệ mới. Câu hỏi giúp tôi rõ hơn cách đo xem hướng dẫn bằng ảnh có hiệu quả không: tách số lần bố mẹ thật sự hỏi lại việc cũ khỏi các cuộc gọi chỉ để hỏi thăm, và dùng số lần hỏi lại làm metric |
| Gom cluster / cây OST | Tham gia gom 9 candidate thành 4 cluster; đề xuất đo outcome cluster D bằng **tiền** thay vì thời gian vì thời gian mua bù (~30'/tuần) quá nhỏ | Outcome 2.3: "Giảm số tiền gia đình lãng phí mỗi tuần cho bữa tối"; ý "đề xuất món ăn" chuyển xuống tầng solution dưới D1 |
| Chọn candidate problem | Muốn chọn #8 (bằng chứng mạnh nhất: 9 cuộc gọi trong 2 tuần); nhóm chọn #3 nghĩ món của Thắng | Ghi ở "Xử lý bất đồng" 2.4: đồng ý chọn #3 với điều kiện quay về #8 nếu bằng chứng của #3 yếu sau CP4 |
| Kiểm chứng / research | Phỏng vấn 2 người (sinh viên tự nấu ăn, bác sĩ có lịch trực) bằng 5 câu theo The Mom Test; tổng hợp research 3 công cụ (SuperCook, Kitche, Cooky) và 3 nguồn số liệu | Phỏng vấn **phản bác giả định #2**: gọi đồ ngoài do mệt/về muộn, vứt đồ do không lên kế hoạch và lịch đổi → nhóm bỏ tiền ăn ngoài khỏi Impact và Success Metric |
| Quy trình nhóm | Tham gia vẽ quy trình hiện tại và tương lai (mục 4) | Sau phỏng vấn, sửa bottleneck thành "không biết kết hợp đồ đang có thành món", tách việc gọi đồ ngoài ra ngoài phạm vi |
| Problem Statement | Tham gia viết v0; dùng AI phản biện 4 lỗ hổng | v0 bỏ metric "số tối gọi đồ ngoài", thêm cột "lý do vứt" vào sổ ghi |
| Mức can thiệp AI | Dùng Claude soạn bản nháp mục 6–8; tôi xem xét so sánh Rule / Workflow / Agent và đồng tình chọn Workflow có AI ở một bước, vì quy trình tương đối cố định, không cần AI tự quyết định toàn bộ | Nhóm chọn Workflow, AI chỉ ở bước gợi ý món |
| Quyết định | Chú ý các ngưỡng đánh giá để tránh triển khai AI khi phương án đơn giản đã đủ nhu cầu | Nhóm chọn **Not Yet**, kiểm chứng 3 tuần trước khi dùng AI; giữ các ngưỡng 70% / 80% / 50% làm cơ sở đánh giá, cần kiểm chứng qua thử nghiệm |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ------------------------------ | ---------------------- | ----------------- | -------------------------- | ----------------------------------- |
| CP1 Scan | Tự scan 6 problem trước, sau đó nhờ Claude trình bày vào bảng và gán lăng kính cho từng dòng | Kiểm được không dòng nào lẫn chữ "AI/chatbot", mỗi dòng có số liệu | Không gợi ý thêm problem; việc gán lăng kính là suy đoán của AI | Không phụ thuộc hoàn toàn vào cách phân loại của Claude, đối chiếu lại từng vấn đề với đối tượng và nhu cầu thực tế. Chú ý nhất dòng bố mẹ hỏi cách dùng điện thoại: đây là hỗ trợ người lớn tuổi dùng công nghệ, không đơn thuần là giao tiếp. Lăng kính cần chọn theo bản chất vấn đề, không theo cách diễn đạt |
| CP2 Problem Card | Nhờ Claude viết cột "Vì sao chọn / Điều còn chưa chắc", soạn 3 card và đóng vai "PM hoài nghi" phản biện card #2 | Phản biện chỉ ra metric "số cuộc gọi" sai hướng (bố mẹ còn gọi hỏi thăm) và rủi ro chuyển khoản | AI **tự ước lượng** các bước và số phút trong card (ví dụ đi chợ 45') khi tôi chưa đưa số liệu; AI đề xuất actor là bố mẹ — tôi không đồng ý | Coi số phút Claude đưa ra chỉ là dữ liệu tham khảo ban đầu, chưa bấm giờ. Tôi ghi rõ "ước lượng, chưa bấm giờ" ở bottleneck card #2 (khoảng 5 phút/cuộc) và quy trình card #3 (đi chợ 45 phút), để tách khỏi dữ liệu có dấu vết thật như 9 cuộc gọi trong 2 tuần hay 2 tin Zalo nhắc quên đồ |
| CP4 Research | Nhờ Claude tìm công cụ có sẵn và số liệu lãng phí thực phẩm, yêu cầu tự mở từng link | Tìm được 3 công cụ (SuperCook, Kitche, Cooky) và khảo sát Tạp chí Công Thương có tín hiệu phản bác | Kết quả tìm kiếm đưa ra con số "72 kg/người/năm" nhưng mở các bài báo thì không có — đã **bỏ** con số này; không mở được trang UNEP gốc. AI cũng từ chối bịa kết quả phỏng vấn khi tôi nhờ, nên tôi tự đi phỏng vấn 2 người | Xem lại phần tóm tắt từ nguồn Tạp chí Công Thương và Food Waste Index trong bảng research, đối chiếu với giả định của nhóm: lãng phí thực phẩm không chỉ do không biết nấu gì mà còn do mua quá nhiều hoặc nấu vượt nhu cầu. Nhóm dùng điểm này để xem lại giả định ban đầu |
| CP5 Quy trình | Nhờ Claude soạn quy trình hiện tại/tương lai từ card của Thắng | Tách rõ bước Rule / AI / con người, có boundary và phương án quay về | Bản đầu giả định chuỗi "không nghĩ ra món → gọi đồ ngoài → vứt đồ"; phỏng vấn của tôi cho thấy chuỗi này sai | Đổi cách xác định nguyên nhân: người được phỏng vấn vẫn tự nấu món quen hoặc tìm YouTube khi không nghĩ ra món; gọi đồ ngoài chủ yếu do mệt, về muộn. Nhóm loại chi phí ăn ngoài khỏi Impact, tập trung vào giảm lãng phí do không lên kế hoạch hoặc quên đồ trong tủ |
| CP5–6 Problem Statement | Nhờ Claude chỉ ra lỗ hổng của v0 (không viết lại) | Chỉ ra impact là ước lượng của 1 người, metric gọi đồ ngoài cần tách lý do | — | Đồng ý: số liệu chỉ là ước lượng của 1 người nên cần kiểm chứng; đồ vứt chưa chắc do không nghĩ ra món nên thêm cột lý do vứt; bỏ metric gọi đồ ngoài vì phỏng vấn cho thấy không liên quan trực tiếp. Riêng điểm thiếu tần suất "nghĩ không ra": dữ liệu quan trọng nhưng cần thêm thời gian ghi nhận thực tế trước khi kết luận |
| CP6 Mức can thiệp / quyết định | Nhờ Claude soạn bản nháp mục 6–8 báo cáo nhóm (ma trận, so sánh 4 mức, AI Canvas, PAIR, Problem Statement v1, 5 tiêu chí, 4 rủi ro, quyết định, ngưỡng dừng) từ dữ liệu CP4–CP5 đã có | Dùng lại đúng bằng chứng phỏng vấn (thực đơn cố định thất bại ở người #2, giả định #2 bị phản bác) để lập luận vì sao không dừng ở No AI; tách được phần Rule làm tốt (đánh dấu đồ sắp hỏng) và phần cần AI (ghép thành món) | Các ngưỡng 70% / 80% / 50% / 30% / 40% do AI **tự đặt**, chưa có căn cứ từ số liệu; AI tự giao việc theo dõi sổ ghi cho tôi; 5 tiêu chí đánh giá chưa được chạy thử lần nào. Theo RULES, phần này AI chỉ được phản biện, nên nhóm phải tự chốt lại | Nhóm giữ các ngưỡng trong bản CP6 hiện tại làm cơ sở đánh giá: 70% để xem các món quen đã đủ dùng chưa, 80% là tỷ lệ cập nhật danh sách, 50% là mục tiêu giảm tiền thực phẩm bị vứt. Các ngưỡng này cần kiểm chứng qua thử nghiệm thực tế, không xem là kết quả đã đạt |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi so sánh các candidate, tôi nhận ra mỗi vấn đề có cách đo impact khác nhau. Thắng ước lượng 150–200 nghìn đồng thực phẩm bị vứt mỗi tuần, trong khi card #8 của tôi có dấu vết thực tế là 9 cuộc gọi trong 2 tuần. Duy Anh cũng có hai card chưa bổ sung số phút xử lý. Điều này giúp tôi hiểu rằng số liệu ước lượng và bằng chứng thực tế có mức độ tin cậy khác nhau, cần được phân biệt khi chấm điểm.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có. Khi xây dựng Job Story cho card #3, nhóm đã đưa sẵn ý tưởng giải pháp vào vấn đề bằng cụm từ "gợi ý 1–2 món ăn". Trong quá trình xây dựng Opportunity Solution Tree, nhóm nhận ra cần tách nhu cầu thực tế khỏi giải pháp. Vì vậy, nhóm sửa thành nhu cầu "biết nấu được món gì nhanh từ thực phẩm sắp hết hạn". Những ý tưởng như app quản lý tủ lạnh và chụp ảnh tủ lạnh cũng được gạch khỏi tầng Opportunity. Ý tưởng gợi ý món được chuyển xuống tầng Solution để CP6 có thể so sánh với phương án No AI.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Ban đầu tôi muốn chọn card #8 vì có bằng chứng mạnh hơn với 9 cuộc gọi trong 2 tuần, trong khi card #3 có nhiều số liệu chỉ dựa trên ước lượng. Tuy nhiên, nhóm thuyết phục tôi chọn #3 vì impact có thể quy đổi thành tiền và có nhiều mức can thiệp để phân tích. Tôi đồng ý với điều kiện nếu sau CP4 bằng chứng của #3 vẫn yếu thì sẽ quay lại #8. Sau phỏng vấn, cả 2 người đều có vứt rau trong tuần trước nên nhóm giữ #3, dù vẫn cần kiểm chứng thêm vì số mẫu còn ít.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Có. Ban đầu tôi nghĩ không nghĩ ra món ăn sẽ khiến mọi người đặt đồ ăn bên ngoài và làm thực phẩm bị lãng phí. Tuy nhiên, người được phỏng vấn thứ nhất là sinh viên sống một mình và người thứ hai là bác sĩ có lịch trực đều cho biết họ vẫn tự nấu khi không biết kết hợp nguyên liệu. Người bác sĩ từng thử lên thực đơn cả tuần nhưng không duy trì được vì lịch trực thường xuyên thay đổi. Tôi cũng bất ngờ khi khảo sát Tạp chí Công Thương cho thấy mua và nấu quá nhiều mới là những nguyên nhân đáng chú ý của lãng phí thực phẩm. Qua đó, tôi hiểu rằng cần kiểm chứng hành vi thực tế thay vì chỉ dựa vào giả định hoặc ý kiến người dùng về một giải pháp.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất đối với tôi là xác định chính xác tác động nào thực sự xuất phát từ vấn đề nhóm đang nghiên cứu. Ban đầu, nhóm đưa cả chi phí gọi đồ ăn ngoài vào Impact, nhưng phỏng vấn cho thấy mọi người gọi đồ chủ yếu vì mệt hoặc về muộn. Vì vậy, nhóm phải loại khoản tiền này khỏi Impact và Success Metric. Tôi nhận ra rằng không thể quy tất cả hậu quả cho một vấn đề nếu chưa có bằng chứng chứng minh mối liên hệ.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu được làm lại, tôi sẽ phỏng vấn đúng đối tượng là người nấu ăn chính trong gia đình, đồng thời hỏi cụ thể thời gian suy nghĩ món và tần suất thực phẩm bị bỏ đi. Tôi cũng sẽ đề xuất ghi chép hoặc bấm giờ trước khi chấm điểm candidate để có baseline đáng tin cậy hơn. Ngoài ra, tôi muốn phản biện mạnh hơn về điểm bằng chứng của card #3 và ngưỡng 70% trong CP6, vì những con số này cần có cơ sở kiểm chứng thay vì chỉ dựa trên nhận định của nhóm.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

Vấn đề của nhóm tôi là người nấu ăn chính trong gia đình, đặc biệt là người có lịch làm việc thay đổi, gặp khó khăn khi kết hợp thực phẩm sẵn có, nhất là đồ sắp hết hạn, thành món ăn phù hợp. Quy trình hiện tại gồm mở tủ lạnh, lọc đồ sắp hỏng, suy nghĩ cách kết hợp nguyên liệu và nấu ăn, trong đó bước suy nghĩ món là điểm nghẽn khoảng 15 phút theo ước lượng ban đầu. Nhóm đặt ra các metric như giảm 50% tiền thực phẩm bị vứt do không biết nấu gì hoặc quên trong tủ, giảm thời gian chọn món xuống dưới 5 phút, tỷ lệ chọn được gợi ý từ 60% và tỷ lệ cập nhật danh sách từ 80%. Về Boundary, AI không được tự quyết định món ăn, đánh giá thực phẩm còn ăn được hay không, tự mua hàng hoặc đưa nguyên liệu không có trong danh sách vào món như thể đang có; người nấu phải tự kiểm tra thực phẩm thực tế, khẩu vị và dị ứng trước khi nấu. Rule có thể sắp xếp thực phẩm theo ngày mua và đánh dấu đồ sắp hết hạn, nhưng chưa đủ để kết hợp nhiều loại nguyên liệu thành những món ăn phù hợp vì có quá nhiều tổ hợp khác nhau. Vì vậy, nhóm chọn Workflow, chỉ sử dụng AI ở một bước để gợi ý 2–3 món Việt dưới 30 phút, còn các bước khác do con người và Rule thực hiện. Nhóm chưa chọn Agent vì quy trình đã có các bước cố định và không cần AI tự quyết định hay thực hiện nhiều hành động liên tiếp. Cuối cùng, nhóm quyết định Not Yet, thử nghiệm No AI kết hợp Rule trong 2 tuần trước; nếu danh sách 10 món quen đáp ứng được ít nhất 70% số bữa tối thì dừng ở Rule và không triển khai AI.

---

## 7. Tài liệu tham khảo

- Quách Thùy Trang (10/2025). *Nghiên cứu sự khác biệt về hành vi lãng phí thực phẩm giữa các thế hệ ở Việt Nam hiện nay.* Tạp chí Công Thương. https://tapchicongthuong.vn/nghien-cuu-su-khac-biet-ve-hanh-vi-lang-phi-thuc-pham-giua-cac-the-he-o-viet-nam-hien-nay-245709.htm
- Báo Pháp luật Việt Nam (02/01/2025). *Bài 1: Lãng phí đồ ăn từ mâm cơm gia đình tới nhà hàng ở Việt Nam.* https://baophapluat.vn/bai-1-lang-phi-do-an-tu-mam-com-gia-dinh-toi-nha-hang-o-viet-nam-post535007.html
- MyJoyOnline (28/03/2024). *Hotter countries generate more food waste per capita in households* (UNEP Food Waste Index Report 2024). https://www.myjoyonline.com/hotter-countries-generate-more-food-waste-per-capita-in-households/
- SuperCook — https://apps.apple.com/us/app/id1477747816
- Kitche — https://www.kitche.co/ · https://www.tapsmart.com/apps/food-drinks/review-kitche/
- Cooky — https://cellphones.com.vn/sforum/cooky-ung-dung-chia-se-cong-thuc-nau-an-ngon-hang-dau-viet-nam
- Rob Fitzpatrick, *The Mom Test* — https://www.momtestbook.com/
- Teresa Torres, *Opportunity Solution Trees* — https://www.producttalk.org/opportunity-solution-trees/
- Anthropic, *Building effective agents* — https://www.anthropic.com/research/building-effective-agents
- Marty Cagan, *The Four Big Risks* — https://www.svpg.com/four-big-risks/
