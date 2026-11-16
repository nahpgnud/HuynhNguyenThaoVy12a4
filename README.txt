WEBSITE LỚP HỌC 12A1
=====================

Cách xem:
1. Giải nén thư mục website_lop_hoc.zip.
2. Mở thư mục website_lop_hoc.
3. Mở file index.html bằng Chrome, Edge hoặc Firefox.

Cấu trúc:
- index.html: Trang chủ, giới thiệu lớp và 4 nhóm.
- groups/group1.html ... group4.html: Danh sách thành viên từng nhóm.
- students/student-*.html: Hồ sơ riêng của từng học sinh.
- style.css: Giao diện dùng chung.

Cách tùy chỉnh:
- Thay "12A1", phần tiểu sử và số liệu trong index.html.
- Mở từng file trong groups để sửa tên thành viên và đường dẫn.
- Mở từng file trong students để sửa thông tin cá nhân.
- Để dùng ảnh thật: tạo thư mục images, chép ảnh vào đó và thay khối
  <div class="profile-avatar">emoji</div> bằng:
  <img class="profile-avatar" src="../images/ten-anh.jpg" alt="Ảnh học sinh">
  (Nếu dùng ảnh, thêm object-fit:cover vào CSS cho ảnh.)
- Màu sắc, kích thước và bố cục chỉnh trong style.css.

Lưu ý: Đây là website tĩnh, chưa có chức năng đăng nhập hay quản trị dữ liệu.

TRANG MOI:
- leadership.html: Ban cán sự và giáo viên chủ nhiệm.
- class-map.html: Trang sơ đồ lớp; thay ảnh mẫu bằng sơ đồ thật trong thư mục assets.
- events.html: Danh sách sự kiện mẫu.

Thay ảnh: sửa đường dẫn src trong leadership.html hoặc class-map.html, rồi chép ảnh vào thư mục assets.
