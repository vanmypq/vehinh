# GeoTHCS – Web app có thể cài đặt (PWA)

Bản này giữ giao diện GeoTHCS và bổ sung khả năng cài đặt như ứng dụng trên thiết bị tương thích.

## Cập nhật lên GitHub Pages
1. Giải nén ZIP.
2. Mở https://github.com/vanmypq/vehinh → **Add file → Upload files**.
3. Tải lên **toàn bộ các tệp bên trong thư mục** vào thư mục gốc của kho: `index.html`, `manifest.json`, `sw.js`, `icon.svg`, `.nojekyll`, `README.md`.
4. Commit changes và chờ GitHub Pages hoàn tất triển khai.
5. Mở https://vanmypq.github.io/vehinh/ bằng Chrome hoặc Edge.
6. Chọn **Cài đặt ứng dụng** nếu nút xuất hiện; hoặc mở menu trình duyệt và chọn **Install GeoTHCS / Cài đặt ứng dụng**.

## Lưu ý
- Không đổi `index.html` thành `.app`: web app được phân phối qua URL, còn PWA được cài từ trình duyệt.
- GeoTHCS cần Internet để tải thư viện GeoGebra 2D/3D. Service worker chỉ lưu bộ khung giao diện; không cam kết vẽ hình GeoGebra khi ngoại tuyến.
- Chưa thể cài đặt trực tiếp lên tài khoản GitHub của bạn từ đây; bạn cần tải các tệp đã cập nhật lên kho.
