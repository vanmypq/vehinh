# GeoTHCS – bản chẩn đoán và sửa dựng hình 3D

## Cải tiến trong bản này
- Khởi tạo lại vùng chứa GeoGebra mỗi lần chuyển chế độ 2D/3D để tránh applet cũ ghi đè vùng vẽ mới.
- Mỗi lần khởi tạo có mã phiên riêng; callback tải trễ của phiên cũ bị bỏ qua.
- Có thông báo nếu GeoGebra 3D không tải trong 30 giây.
- Khi không gian 3D sẵn sàng, ứng dụng tự dựng một hình lập phương kiểm tra bằng `Cube(A,B)`. Điều này giúp xác nhận ngay trong trình duyệt người dùng rằng bộ dựng 3D hoạt động; chọn mẫu khác sẽ thay thế hình kiểm tra.
- Khi dựng mẫu, ứng dụng báo rõ các lệnh bị GeoGebra từ chối và tự yêu cầu khung nhìn hiển thị toàn bộ đối tượng.
- Đã tăng phiên bản cache Service Worker để tránh trình duyệt giữ bản cũ.

## Cập nhật GitHub Pages
1. Giải nén gói ZIP.
2. Tải tất cả tệp trong thư mục `GeoTHCS_GitHubPages` lên thư mục gốc của kho `vanmypq/vehinh`, ghi đè tệp trùng tên.
3. Commit changes, chờ GitHub Pages hoàn tất.
4. Mở `https://vanmypq.github.io/vehinh/` và nhấn `Ctrl+F5`. Nếu đã cài PWA, đóng hẳn ứng dụng rồi mở lại.
5. Chuyển sang 3D. Bản mới tự dựng khối lập phương kiểm tra. Sau đó chọn một mẫu khác để thử.

## Kiểm tra đã thực hiện
- Kiểm tra cú pháp JavaScript bằng Node.js: đạt.
- Kiểm tra cấu trúc tệp và đóng gói ZIP: thực hiện khi tạo gói.
- Môi trường tạo gói không có kết nối mạng đáng tin cậy tới máy chủ GeoGebra nên không thể giả nhận đã kiểm thử tương tác trực tiếp với máy chủ GeoGebra. Bản này có kiểm tra chạy thực tế ngay trong trình duyệt của người dùng và thông báo lỗi cụ thể nếu lệnh 3D bị từ chối.
