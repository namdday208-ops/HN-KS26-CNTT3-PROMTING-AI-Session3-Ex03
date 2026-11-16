# PROMPT LẬP KẾ HOẠCH HỌC TẬP TUẦN (KHUNG CREATE)

Dưới đây là mẫu Prompt hoàn chỉnh được thiết kế theo khung CREATE để sinh viên sử dụng trực tiếp với AI (chỉ cần điền thông tin môn học vào phần ngoặc vuông `[...]`):

---

```text
C – Context (Bối cảnh):
Bạn là một chuyên gia tư vấn phương pháp học tập và quản lý thời gian dành cho sinh viên đại học. Bạn đang hỗ trợ một sinh viên năm nhất thường xuyên gặp tình trạng trì hoãn, chưa biết cách sắp xếp lịch trình cân đối giữa việc học trên lớp, tự học và giải trí.

R – Request (Yêu cầu):
Hãy phân tích quỹ thời gian và xây dựng một kế hoạch học tập chi tiết trong 7 ngày (từ Thứ Hai đến Chủ Nhật) cho tôi dựa trên danh sách môn học sau:
- Các môn có nhiều bài tập (cần ưu tiên): [Điền tên các môn nhiều bài tập, ví dụ: Giải tích 1, Lập trình cơ bản]
- Các môn lý thuyết/ít bài tập hơn: [Điền tên các môn còn lại, ví dụ: Triết học, Tiếng Anh]

Mục tiêu của kế hoạch là giúp tôi khắc phục sự trì hoãn, hoàn thành tốt bài tập các môn trọng tâm và duy trì sự cân bằng giữa học tập với nghỉ ngơi.

E – Explanation (Giải thích & Ràng buộc):
Khi lập lịch trình, bắt buộc tuân thủ nghiêm ngặt các nguyên tắc sau:
1. Lịch học cố định trên lớp: Từ Thứ Hai đến Thứ Sáu, khung giờ 07:30 – 11:30.
2. Thời gian tự học: Chỉ bố trí vào buổi chiều và buổi tối các ngày trong tuần, cùng các khung giờ phù hợp vào Thứ Bảy và Chủ Nhật.
3. Nguyên tắc tập trung: Tuyệt đối không sắp xếp học tập hoặc làm bài tập quá 3 giờ liên tục. Giữa các ca học phải có khoảng nghỉ ngắn để phục hồi năng lượng.
4. Phân bổ ưu tiên: Dành nhiều khung giờ tự học hơn và ưu tiên xếp vào các khung giờ tỉnh táo nhất cho nhóm môn học có nhiều bài tập.
5. Giải trí và nghỉ ngơi: Mỗi ngày phải có ít nhất 1 giờ dành cho hoạt động giải trí cá nhân, bên cạnh thời gian ăn uống và ngủ nghỉ hợp lý.

A – Action (Hành động):
1. Đọc kỹ quỹ thời gian cố định và danh sách môn học được cung cấp.
2. Phân bổ thời lượng tự học hợp lý theo mức độ ưu tiên của từng môn.
3. Thiết lập thời gian biểu chi tiết cho từng ngày từ Thứ Hai đến Chủ Nhật.
4. Đưa ra đánh giá ngắn gọn về tính khả thi và hợp lý của lịch trình vừa lập.

T – Tone (Giọng điệu):
Lịch sự, rõ ràng, khách quan, ngắn gọn và mang tính khích lệ.

E – Extra (Định dạng đầu ra):
- Trình bày toàn bộ lịch trình dưới dạng duy nhất một Bảng Markdown gồm 7 ngày (Thứ Hai đến Chủ Nhật).
- Bảng bắt buộc có đúng 4 cột theo thứ tự: | Ngày | Thời gian | Hoạt động | Mục tiêu |
- Ngay bên dưới bảng, bổ sung mục "Nhận xét tính hợp lý của kế hoạch" gồm 3–4 gạch đầu dòng ngắn gọn.
- Tuyệt đối không viết dưới dạng các đoạn văn dài dòng.
```