# GeoTHCS – Cập nhật toàn bộ dựng hình nhanh 2D

## Cập nhật lên GitHub Pages
1. Giải nén gói ZIP.
2. Mở kho `vanmypq/vehinh` trên GitHub.
3. Chọn **Add file → Upload files**.
4. Tải các tệp trong thư mục này lên thư mục gốc của kho và ghi đè tệp trùng tên.
5. Chọn **Commit changes**, chờ GitHub Pages triển khai xong.
6. Mở trang GeoTHCS và nhấn `Ctrl + F5`. Nếu đã cài PWA, đóng cửa sổ ứng dụng rồi mở lại để cập nhật service worker.

## Cập nhật lần này
- Chuẩn hóa lệnh dựng nhanh 2D: điểm, đoạn thẳng, đường thẳng, tia, trung điểm, song song, vuông góc, tam giác, các tam giác có ràng buộc, hình vuông, chữ nhật, bình hành, thoi, thang, diều, đường tròn, đường tròn ngoại tiếp, góc, phân giác, ngũ giác đều và lục giác đều.
- Dùng phép dựng phụ thuộc cho tam giác cân; dùng `pi/2` và `pi/3` trong các phép quay để tránh phụ thuộc ký tự độ.
- Bổ sung các mục hình nhanh còn thiếu vào danh sách chọn trên thanh công cụ.
- Cập nhật kiểm tra kết quả lệnh để tránh coi giá trị trả về không xác định của API là lỗi ngay lập tức; nếu GeoGebra trả về `false`, thông báo lệnh bị từ chối.
- Tăng phiên bản cache PWA để trình duyệt tải mã nguồn mới.

## Lưu ý
GeoTHCS sử dụng GeoGebra trực tuyến nên cần Internet. JavaScript đã được kiểm tra cú pháp, nhưng các lệnh hình học cần được xác nhận thực tế trong trình duyệt với GeoGebra đang tải trên mạng.
