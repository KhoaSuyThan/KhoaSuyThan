# Nhật Ký Thay Đổi (Changelog)

Toàn bộ các cập nhật và thay đổi mã nguồn của dự án sẽ được ghi nhận tại đây.

Định dạng dựa trên [Keep a Changelog](https://keepachangelog.com/vi/1.0.0/).

---
## [2026-09-10] - Tối Ưu Bảng Màu Con Rắn & Các Ô Contributions Arcade
### Đã thay đổi (Changed)
- **Đổi màu "trái táo" sang xanh lá contributions**: Cập nhật `color_dots` sang hệ màu xanh lá cây đặc trưng của GitHub (`#161b22,#0e4429,#006d32,#26a641,#39d353` cho Dark mode và `#ebedf0,#9be9a8,#40c463,#30a14e,#216e39` cho Light mode) giúp hiển thị chuẩn như graph contribution thực tế.
- **Tạo hiệu ứng gradient xanh dương nhạt dần cho con rắn**: Bổ sung bước xử lý tự động `Enhance Snake Color Gradient` trong GitHub Actions workflow `.github/workflows/snake.yml`, gán dải màu xanh dương chuyển sắc mượt mà từ đầu (`#0284c7` - xanh dương đậm rõ nét) nhạt dần qua thân (`#38bdf8`, `#7dd3fc`) đến đuôi (`#bae6fd`), giúp con rắn nổi bật hoàn toàn và không bị trùng màu với các ô xanh lá.
