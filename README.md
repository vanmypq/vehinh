# GeoTHCS – Bản dành cho GitHub Pages

## Vì sao trang cũ chỉ hiện tiêu đề?
GitHub Pages cần tệp `index.html` ở thư mục xuất bản. Bản cũ để mã trong thư mục con `GeoTHCS/` bên trong ZIP, vì vậy khi chỉ tải ZIP và README lên kho, trang gốc không tìm thấy trang ứng dụng.

## Cách cập nhật
1. Tải và giải nén gói `GeoTHCS_GitHubPages.zip` trên máy tính.
2. Mở kho https://github.com/vanmypq/vehinh và chọn **Add file → Upload files**.
3. Tải lên **các tệp bên trong thư mục đã giải nén** (`index.html`, `.nojekyll`, `README.md` nếu có), không tải riêng tệp ZIP. `index.html` phải nằm ngay thư mục gốc của kho, cạnh README.
4. Chọn **Commit changes**.
5. Mở **Settings → Pages**. Chọn **Deploy from a branch**, nhánh `main`, thư mục `/(root)`, rồi Save. Nếu đã cài đúng thì không cần đổi lại.
6. Chờ GitHub Pages triển khai xong rồi tải lại https://vanmypq.github.io/vehinh/ bằng `Ctrl+F5`.

## Kiểm tra
- Ứng dụng cần Internet để tải thư viện GeoGebra.
- Nếu thấy thông báo “Không tải được GeoGebra”, thử mở lại sau, cho phép kết nối tới `geogebra.org`, và kiểm tra mạng/trình chặn nội dung.
- Gói này đã được kiểm tra cú pháp JavaScript bằng Node.js; chưa thể xác nhận kết nối GeoGebra trong trình duyệt của người dùng từ môi trường đóng gói.
