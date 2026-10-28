# GeoTHCS – Bản sửa lỗi hình lập phương và mở rộng thư viện hình học

## Cập nhật lên GitHub Pages
1. Tải ZIP và giải nén.
2. Mở kho GitHub `vanmypq/vehinh`, chọn **Add file → Upload files**.
3. Tải lên toàn bộ các tệp bên trong thư mục `GeoTHCS_GitHubPages` vào thư mục gốc của kho; ghi đè tệp trùng tên.
4. Chọn **Commit changes**, chờ GitHub Pages triển khai xong.
5. Mở trang và nhấn `Ctrl + F5`. Nếu đã cài PWA, đóng rồi mở lại ứng dụng; service worker được nâng lên phiên bản v3.

## Sửa lỗi chính
- Sửa lệnh hình lập phương sang `Cube(A,B)` trong không gian 3D; GeoGebra tạo khối lập phương dựa trên hai đỉnh của một cạnh.
- Sửa mẫu lăng trụ và hình chóp theo dạng lệnh nhận đa giác đáy và điểm/vec-tơ dựng khối.
- Khi dựng hình, ứng dụng báo cụ thể các lệnh không được GeoGebra chấp nhận thay vì chỉ báo thành công chung chung.

## Thư viện 2D mở rộng
Điểm, đoạn thẳng, đường thẳng, tia, trung điểm, đường trung trực, đường song song/vuông góc; tam giác thường/cân/đều/vuông, trọng tâm, đường cao, đường tròn ngoại tiếp; hình vuông, chữ nhật, bình hành, thoi, thang, diều, ngũ giác và lục giác; đường tròn qua ba điểm, nửa đường tròn, tiếp tuyến, góc, phân giác và giao điểm.

## Thư viện 3D mở rộng
Hình lập phương, hộp chữ nhật, lăng trụ tam giác/ngũ giác, chóp tứ giác/tam giác, tứ diện, trụ, nón, cầu và mặt phẳng. Một số lệnh 3D có thể khác biệt tùy phiên bản GeoGebra; nếu lệnh cụ thể không được hỗ trợ, thông báo sẽ nêu lệnh lỗi để dễ kiểm tra.

GeoTHCS dùng GeoGebra trực tuyến và cần Internet để tải bộ dựng hình. Các hình mẫu là điểm khởi đầu; có thể tiếp tục kéo điểm, xoay, đo đạc và chỉnh sửa bằng thanh công cụ GeoGebra.
