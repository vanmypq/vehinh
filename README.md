# GeoTHCS – Bản sửa lệnh dựng hình 2D

## Cập nhật lên GitHub Pages
1. Giải nén gói ZIP.
2. Mở kho `vanmypq/vehinh` trên GitHub.
3. Chọn **Add file → Upload files**.
4. Tải các tệp trong thư mục này lên thư mục gốc của kho và ghi đè tệp trùng tên.
5. Chọn **Commit changes**, chờ GitHub Pages hoàn tất triển khai.
6. Mở trang GeoTHCS và nhấn `Ctrl + F5`.

## Thay đổi
- Sửa mẫu trọng tâm tam giác: thay lệnh `Centroid(A,B,C)` không đúng số đối số bằng giao điểm hai đường trung tuyến dựng từ trung điểm hai cạnh.
- Sửa mẫu lục giác đều: dùng `RegularPolygon(A,B,6)` để bảo đảm các cạnh và góc bằng nhau khi thay đổi.
- Chuẩn hóa mẫu tam giác cân nhanh bằng phép quay quanh trung điểm đáy.
- Bộ chạy lệnh dừng ở lệnh đầu tiên bị GeoGebra từ chối, hiển thị chính xác lệnh gây lỗi; không báo thành công khi API không xác nhận lệnh.
- Sửa lựa chọn danh mục đường tròn cho lớp 9.

Lưu ý: GeoTHCS dùng GeoGebra trực tuyến, vì vậy cần kết nối Internet. Nên kiểm tra các mẫu trực tiếp trong trình duyệt sau khi cập nhật.
