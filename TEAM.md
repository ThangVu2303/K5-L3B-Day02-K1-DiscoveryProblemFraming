# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: K1
- Candidate problem nhóm chọn (1 câu): Người nấu ăn chính không biết kết hợp đồ đang có (nhất là đồ sắp hỏng) thành món, nên chọn món quen và để đồ sắp hỏng lại đến khi phải vứt (ước lượng 150–200k/tuần)
- Quyết định cuối (Go / Not Yet / No-Go): **Not Yet** — mức chọn Workflow (AI chỉ ở bước gợi ý món); kiểm chứng trước 3 tuần bằng sổ ghi đồ vứt + chạy No AI/Rule (xem `report/team/group_report.md` mục 8.2)

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Vũ Đình Thắng | 2A202603753 | Trưởng nhóm, điều phối thảo luận, phụ trách Problem Statement & Phân tích mức can thiệp AI | ThangVu2303 |
| 2 | Nguyễn Hữu Thịnh | 2A202603726 | Thành viên chính, phụ trách Research công cụ có sẵn & Tái thiết kế quy trình (As-Is / To-Be) | (Cập nhật sau) |
| 3 | Nguyễn Duy Anh | 2A202603796 | Thành viên hỗ trợ, phụ trách Khảo sát / Phỏng vấn kiểm chứng (CP4) & Ghi chép tài liệu | (Cập nhật sau) |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Vũ Đình Thắng | Nguyễn Hữu Thịnh, Nguyễn Duy Anh | Cluster, cây OST rút gọn, bảng chấm điểm chọn bài toán |
| CP4 — Kiểm chứng | Nguyễn Duy Anh | Nguyễn Hữu Thịnh, Vũ Đình Thắng | Tạo poll/khảo sát ngắn người quen, hỗ trợ tổng hợp số liệu kiểm chứng thói quen mở tủ & bỏ thừa thức ăn |
| CP4 — Research | Nguyễn Hữu Thịnh | Nguyễn Duy Anh | Bảng research các app/công cụ nấu ăn hiện có (SuperCook, Cookpad, Kitche...) và phỏng vấn The Mom Test |
| CP5 — Quy trình trước/sau | Nguyễn Hữu Thịnh | Vũ Đình Thắng | Sơ đồ quy trình As-Is vs To-Be + bảng so sánh before/after |
| CP5 — Problem Statement v0 | Vũ Đình Thắng | Nguyễn Hữu Thịnh | Problem Statement v0 (Actor, Quy trình, Bottleneck, Metric, Boundary) |
| CP6 — Mức can thiệp + Problem Statement v1 | Vũ Đình Thắng | Nguyễn Hữu Thịnh | Ma trận độ mơ hồ/phức tạp, AI Canvas, tiêu chí eval, Problem Statement v1 |
| CP6 — Quyết định | Vũ Đình Thắng | Nguyễn Hữu Thịnh, Nguyễn Duy Anh | Đánh giá 4 rủi ro, quyết định Not Yet & 4 ngưỡng dừng (Kill switch) |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### VuDinhThang-2A202603753

**Phần việc phụ trách:**

- Điều phối chung toàn bộ các buổi họp nhóm, chốt tiến độ hoàn thành các checkpoint.
- Chủ trì xây dựng cây Opportunity Solution Tree (OST) và chấm điểm shortlist ở CP3.
- Chịu trách nhiệm chính soạn thảo Problem Statement (v0, v1), AI Canvas rút gọn, xác định Boundary và 5 tiêu chí eval bản nháp.
- Đánh giá 4 khía cạnh rủi ro của Marty Cagan và xác lập quyết định Not Yet cùng 4 ngưỡng dừng (Kill switch).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch Problem Card #3 (Quản lý tủ lạnh & gợi ý bữa tối) và bảo vệ bài toán trước các câu hỏi phản biện của nhóm.
- Cung cấp số liệu baseline cá nhân (150–200k đồ vứt/tuần, 15 phút nghĩ món).
- Viết hoàn chỉnh bản Problem Statement v0 và nâng cấp lên v1 bổ sung điều kiện người nấu có lịch thay đổi.
- Hoàn thiện bảng phân tích 4 mức can thiệp (No AI / Rule / Workflow / Agent) và lựa chọn mức Workflow.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Mục 2.3 (Cây OST), Mục 5 (Problem Statement v0), Mục 6 (Mức can thiệp & AI Canvas), Mục 7 (Problem Statement v1), Mục 8 (Quyết định & 4 ngưỡng dừng) trong `group_report.md`.
- Báo cáo cá nhân `report/individual/2A202603753_VuDinhThang.md`.

**Điều mình học được từ phần nhóm:**

- Nhận ra rằng bài toán càng đời thường thì rào cản hành vi người dùng (nhập liệu đầu vào) càng lớn; vai trò của người làm discovery là đặt ra boundary chuẩn để tránh biến giải pháp thành một hệ thống cồng kềnh không ai duy trì được.

---

### NguyenHuuThinh-2A202603726

**Phần việc phụ trách:**

- CP4: phỏng vấn người dùng (2 người, qua tin nhắn Zalo) và research giải pháp đã có.
- Tham gia CP3 (cluster, cây OST), CP5 (quy trình As-Is / To-Be, Problem Statement v0), CP6 (mức can thiệp, quyết định).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 candidate (#7 chi tiêu cuối tháng, #8 bố mẹ hỏi cách dùng điện thoại, #9 đi chợ quên đồ); #9 thành nhánh D3 trong cây OST, #8 vào shortlist (31 điểm).
- Phản biện card #3 của Thắng: không nghĩ ra món có thật sự khiến đồ bị vứt, hay do mua quá nhiều, không lên kế hoạch, lịch thay đổi → nhóm thêm việc ghi lý do vứt.
- Đề xuất đo outcome cluster D bằng tiền thay vì thời gian.
- Phỏng vấn 2 người (sinh viên tự nấu ăn, bác sĩ có lịch trực) theo The Mom Test; kết quả phản bác giả định #2, làm nhóm bỏ tiền gọi đồ ăn ngoài khỏi Impact và Success Metric.
- Tổng hợp research 3 công cụ (SuperCook, Kitche, Cooky) và 3 nguồn số liệu (Tạp chí Công Thương, FoodBank Việt Nam, UNEP).
- Cùng Thắng vẽ sơ đồ quy trình As-Is và To-Be (mục 4); dùng AI phản biện Problem Statement v0 và góp ý chọn Workflow có AI ở một bước.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (card #7, #8, #9 và cột phản biện), 2.4 (xử lý bất đồng), 3.2 (interview snapshot #1, #2 và bảng tổng hợp), 3.3 (bảng research), mục 4 (quy trình As-Is / To-Be), mục 5 (phản biện v0).
- `report/assets/cp4-interview-guide.md` (kịch bản phỏng vấn).
- Báo cáo cá nhân `report/individual/2A202603726_NguyenHuuThinh.md`, mục 4–5.

**Điều mình học được từ phần nhóm:**

- Cần kiểm chứng hành vi thực tế thay vì chỉ dựa vào giả định hoặc ý kiến người dùng về một giải pháp: phỏng vấn cho thấy người ta gọi đồ ăn ngoài vì mệt, về muộn, không phải vì không nghĩ ra món.
- Không thể quy tất cả hậu quả cho một vấn đề nếu chưa có bằng chứng chứng minh mối liên hệ.

---

### NguyenDuyAnh-2A202603796

**Phần việc phụ trách:**

- Phụ trách khâu kiểm chứng giả định thực tế: tạo khảo sát (poll) ngắn và thu thập ý kiến người quen về thói quen nấu ăn/quản lý tủ lạnh.
- Hỗ trợ ghi chép biên bản thảo luận nhóm và đóng góp ý kiến về an toàn dữ liệu, ranh giới AI (Boundary/HITL).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 candidate đơn giản: Lọc CV ứng viên (#4), Nhận xét học sinh (#5), Trả lời tin nhắn khách (#6).
- Đặt câu hỏi phản biện cho candidate #8 của Thịnh về việc tài liệu ảnh đơn giản đã đủ giải quyết mà không cần công nghệ phức tạp.
- Soạn câu hỏi khảo sát ngắn (poll) gửi cho bạn bè để thu thập số liệu thực tế về thói quen mở tủ lạnh và tần suất vứt bỏ đồ ăn hỏng.
- Đóng góp cho phần Boundary: AI tuyệt đối không tự chốt món thay người nấu và không thể phán đoán an toàn thực phẩm, bắt buộc con người tự kiểm tra (HITL).
- Đồng thuận với quyết định Not Yet để thử nghiệm No AI / Rule trước.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (card #4, #5, #6), 2.2 (cluster A, B, C), 3.1 (hỗ trợ kiểm chứng giả định), mục 5 & 7 (ranh giới Boundary và HITL).
- Báo cáo cá nhân `report/individual/2A202603796_NguyenDuyAnh.md`, mục 4–5.

**Điều mình học được từ phần nhóm:**

- Hiểu cách phỏng vấn không mớm câu trả lời (The Mom Test): thay vì hỏi "Bạn có thích một ứng dụng AI gợi ý nấu ăn không?", hãy hỏi về lần gần nhất họ phải vứt bỏ đồ ăn thừa trong tủ lạnh để nắm bắt đúng hành vi thật.
