Đầu tiên chúng ta sẽ xây dựng URL_API để có thể request dữ liệu đến máy chủ cung cấp nội dung thông qua giao thức HTTPS 
Sau đó chúng ta dùng fetch() để tạo yêu cầu gửi đến server và nhận về một dữ liệu từ URL_API
Các dữ liệu sẽ được trả về theo định dạng JSON
Các product sẽ xuất ra tên và giá
Function deleteProduct sẽ xóa product theo id của chúng 
Khi click vào product chúng ta sẽ lấy được id của sản phẩm và gọi lại hàm deleteProduct để xóa product chúng ta vừa chọn.
Để chạy được file test.html
Lưu file ở wamp64/www
Chạy wamp lên
Vào đường dẫn localhost/test
Giao diện sẽ là các product(thông tin tên và giá product) lấy được URL_API
Để xóa product chúng ta chỉ cần click vào product cần xóa.
