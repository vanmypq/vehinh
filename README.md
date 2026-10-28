# GeoTHCS – bản sửa lỗi dựng hình 3D

## Cập nhật lên GitHub Pages
1. Giải nén gói ZIP.
2. Tải toàn bộ tệp trong thư mục `GeoTHCS_GitHubPages` lên thư mục gốc của kho GitHub Pages, ghi đè tệp trùng tên.
3. Commit changes và đợi GitHub Pages triển khai.
4. Mở trang, nhấn `Ctrl + F5`, chọn **3D · Hình khối** và chờ trạng thái **GeoGebra 3D đã sẵn sàng**.
5. Chọn hình khối trong thanh công cụ rồi nhấn **Dựng hình**.

## Thay đổi chính
- Không ép chuyển về phối cảnh chung 2D sau khi chạy lệnh trong chế độ 3D.
- Bỏ thao tác đặt lưới theo chỉ số vùng 3D không phù hợp; lưới chỉ đặt qua API 2D.
- Bỏ qua callback tải trễ từ applet cũ khi người dùng chuyển nhanh giữa 2D và 3D.
- Giữ nguyên tích hợp GeoGebra; cần kết nối Internet để tải thư viện GeoGebra.
