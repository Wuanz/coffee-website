Cài đặt XAMPP và mở - Apache cổng 3344, 8088 - MySQL cổng 3306 - server.port=8080

Import database vào trang phpmyadmin

Thông tin tài khoản haminhquan@gmail.com 
- 123456 minhquanha@gmail.com 
- 123456 alolo@gmail.com
- 123456 tdt2023@gmail.com 

Phân quyền tại trang web chưa hoàn thiện, chỉ có thể phân quyền trên http://localhost:8088/phpmyadmin 
Link video demo bài : https://drive.google.com/file/d/1IzvUkY9HdHcKa-34BvB4dWmmZsIrLq45/view?usp=sharing 

USER:
- Được quyền vào trang home, menu, shop, cart, login, sign up 
- Không được vào trang xem thông tin tài khoản, nhân viên
ADMIN:
- Có đặc quyền cao nhất
- Ngoài ra được vào trang quản lý tài khoản và sản phẩm 
- Được thêm, xem và sửa thông tin sản phẩm
- Ngoài ra được quyền xóa thông tin nhân viên và sản phẩm
- Được vào mọi trang mà không bị chặn

1. Thực hiện đăng ký tài khoản
2. Chuyển hướng đăng nhập theo role của tài khoản
3. Tự động gán role mặc định cho tài khoản mới đăng ký
4. Đăng xuất
5. Thực hiện tạo, xem, sửa thông tin sản phẩm (admin)
6. Thực hiện chọn sản phẩm tại shop
7. Thực hiện thao tác thêm sản phẩm vào giỏ hàng
8. Thực hiện thanh toán bao gồm các thông tin cần nhập
9. Thanh toán thành công và trở về trang chủ
