# GeoTHCS – Bản dựng hình bảo toàn tính chất khi kéo điểm

## Cải tiến cốt lõi
- Các mẫu tam giác đều, tam giác vuông, hình vuông, ngũ giác đều và lục giác đều được tạo bằng lệnh dựng phụ thuộc (`RegularPolygon`, `Rotate`, `Midpoint`) thay vì đặt toàn bộ đỉnh độc lập.
- Khi người dùng kéo các điểm tự do, các điểm phụ thuộc sẽ được GeoGebra tính lại, giúp giữ tính chất hình học được xác định bởi phép dựng.
- Bổ sung lời nhắc trong giao diện về sự khác nhau giữa điểm tự do và điểm phụ thuộc.
- Hình lập phương và các khối được tạo bằng lệnh hình học 3D của GeoGebra; không chỉ vẽ các cạnh như hình tĩnh.

## Cập nhật GitHub Pages
1. Giải nén ZIP.
2. Tải tất cả tệp trong thư mục `GeoTHCS_GitHubPages` lên thư mục gốc kho `vanmypq/vehinh`, ghi đè tệp trùng tên.
3. Commit changes và chờ GitHub Pages triển khai.
4. Mở `https://vanmypq.github.io/vehinh/`, nhấn `Ctrl+F5`. Nếu cài PWA, đóng hẳn ứng dụng rồi mở lại.
5. Thử dựng tam giác đều/hình vuông/đa giác đều, sau đó kéo đỉnh để quan sát tính chất được bảo toàn.

## Kiểm thử
- Đã kiểm tra cú pháp JavaScript bằng Node.js.
- Các mẫu được đổi sang cách dựng phụ thuộc để GeoGebra duy trì quan hệ hình học. Chưa thể kiểm thử tương tác trực tiếp trên máy chủ GeoGebra trong môi trường đóng gói này; nên xác minh sau khi triển khai.

## Lưu ý sư phạm
Không thể bảo đảm mọi hình giữ tính chất nếu dựng bằng các điểm độc lập hoặc lệnh nhập tùy ý. Với hình mẫu chuẩn, hãy dùng các lệnh dựng phụ thuộc. Khi người dùng nhập lệnh riêng, tính chất phụ thuộc vào cách họ xây dựng đối tượng trong GeoGebra.
