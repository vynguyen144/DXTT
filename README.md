# Lumen Studio — Trình chỉnh sửa ảnh

Ứng dụng chỉnh sửa ảnh chạy trực tiếp trên trình duyệt, tập trung vào việc điều chỉnh ánh sáng và màu sắc theo từng vùng mà không làm thay đổi ảnh gốc trong bộ nhớ.

## Chức năng hiện có
- Mở ảnh từ thiết bị hoặc kéo thả ảnh vào vùng làm việc.
- Xử lý ngay trên trình duyệt; ảnh gốc không bị ghi đè và không được tải lên máy chủ.
- Nhiều lớp chỉnh sửa riêng biệt: bật/tắt, chỉnh độ mờ, đổi thứ tự, sao chép và xóa.
- Công cụ cọ tô, tẩy vùng chọn, dải chuyển sắc, chuyển sắc tròn, vùng chữ nhật, đảo vùng chọn và xem lớp phủ vùng tác động.
- Điều chỉnh theo vùng: phơi sáng, độ sáng, độ tương phản, vùng sáng, vùng tối, điểm trắng, điểm đen, nhiệt độ màu, sắc độ, độ bão hòa, độ rực màu, độ trong và độ sắc nét.
- Làm mềm rìa vùng chọn không phá hủy vùng chọn gốc.
- Tô đầy vùng chọn để áp dụng hiệu ứng lên toàn ảnh, hoặc xóa vùng chọn mà vẫn giữ nguyên thông số.
- Gợi ý cân sáng tự động cơ bản, so sánh trước/sau và xuất ảnh PNG.

## Cách chạy
Mở tệp `index.html` bằng trình duyệt hiện đại. Có thể triển khai bằng GitHub Pages sau khi nhánh này được đưa vào nhánh triển khai.

## Lưu ý
- Đây vẫn là phiên bản đầu tiên; tính năng tự động cân sáng dựa trên thống kê độ sáng của ảnh, chưa dùng AI để nhận diện chủ thể.
- Ảnh quá lớn được thu nhỏ để cạnh dài tối đa 2600 px nhằm hạn chế mức sử dụng bộ nhớ trình duyệt.
- Định dạng xuất hiện có là PNG.
- Ảnh gốc và các lớp chỉnh sửa hiện chỉ được giữ trong phiên làm việc; chưa có chức năng lưu dự án để mở lại ở phiên sau.
- Cú pháp JavaScript đã được kiểm tra, nhưng cần tiếp tục kiểm thử thao tác thực tế trên nhiều trình duyệt và kích thước ảnh.
