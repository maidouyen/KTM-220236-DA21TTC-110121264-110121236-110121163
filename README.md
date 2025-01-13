# KTM-220236-DA21TTC-110121264-110121236-110121163
Thành viên nhóm:
1 Tải Trọng Nghĩa
2 Mai Đỗ Uyên
3 Thạch Minh Thắng
Đề tài: Xây dựng website bán phụ kiện điện thoại
Mục tiêu của hệ thống
Hệ thống được xây dựng nhằm cung cấp giải pháp quản lý bán phụ kiện điện thoại một cách toàn diện, từ việc quản lý danh mục, sản phẩm, đơn hàng đến quản lý người dùng và hiển thị giao diện chính cho khách hàng. Hệ thống bao gồm hai phần chính:

Công nghệ sử dụng
Ngôn ngữ lập trình:
PHP: Sử dụng cho phát triển backend, quản lý dữ liệu, xử lý các chức năng liên quan đến quản lý và giao diện người dùng.
JavaScript: Xử lý tương tác giao diện người dùng.
Cơ sở dữ liệu:
MySQL: Lưu trữ dữ liệu về sản phẩm, người dùng, đơn hàng và các danh mục liên quan.
Giao diện:
HTML, CSS, Bootstrap 5: Xây dựng giao diện website thân thiện với người dùng.
Thư viện hỗ trợ:
Carbon: Xử lý các thao tác liên quan đến thời gian.
Session: Quản lý phiên làm việc của người dùng.
Công cụ phát triển:
Visual Studio Code: Môi trường phát triển tích hợp (IDE).
Composer: Quản lý các thư viện và phụ thuộc PHP.

Kiến trúc hệ thống
Hệ thống được thiết kế theo kiến trúc module hóa, chia thành các phần chính như sau:
1. Phần quản trị (Admin)
Thư mục admin:
Modules:
quanlydanhmuc: Quản lý danh mục sản phẩm.
quanlysp: Quản lý sản phẩm.
quanlydonhang: Quản lý đơn hàng.
quanlytaikhoan: Quản lý tài khoản người dùng.
thongke: Cung cấp các báo cáo thống kê về doanh thu.......
Giao diện admin:
main.php: Trang chính của quản trị.
header.php và footer.php: Các thành phần chung của giao diện.
Cấu hình:
Thư mục config: Lưu trữ các file cấu hình hệ thống.

 Phần giao diện người dùng (Frontend)
Thư mục pages/main:
Trang chức năng chính:
index.php: Trang chủ hiển thị danh sách sản phẩm.
search.php: Trang tìm kiếm sản phẩm.
detail.php: Hiển thị thông tin chi tiết về sản phẩm.
cart.php: Giỏ hàng của người dùng.
pay-registered.php và pay-unregistered.php: Trang thanh toán cho khách hàng đã đăng ký và chưa đăng ký.
contact.php: Trang liên hệ.
shop.php: Hiển thị các sản phẩm theo danh mục hoặc cửa hàng.
Giao diện điều hướng:
navtop.php và navmenu.php: Thành phần điều hướng chung.

Cấu hình hệ thống
Cơ sở dữ liệu:
Thư mục database: Chứa file kết nối và quản lý cơ sở dữ liệu.
Công cụ và thư viện:
Composer.json: Định nghĩa các thư viện sử dụng.
Carbon: Xử lý thời gian và ngày tháng.
Tính năng chính

Admin:
Quản lý danh mục, sản phẩm, đơn hàng, khách hàng, và phản hồi.
Xem thống kê doanh thu và số liệu sản phẩm.
Dễ dàng thêm, sửa, xóa dữ liệu thông qua giao diện quản trị.
Người dùng:
Duyệt và tìm kiếm sản phẩm theo danh mục, tên.....
Quản lý giỏ hàng và đặt hàng.
Xem thông tin chi tiết sản phẩm và phản hồi.