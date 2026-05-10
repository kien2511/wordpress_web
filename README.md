# wordpress_web
# Họ và tên : Nguyễn Trung Kiên 
# Lớp : K58KTPM
# Mssv : K225480106032
# đề bài: SỬ DỤNG DOCKER TRÊN UBUNTU ĐỂ TẠO docker ccompose chứa:
Mariadb: sử dụng image: mariadb:latest để làm hệ quản trị csdl cho wordpress
Phpmyadmin: sư dụng image: phpmyadmin:latest để đăng nhập vào mariadb rồi tạo csdl trống (chỉ để xem, ko cần tạo bảng từ đây, wordpress sẽ làm hết)
WordPress: Sử dụng image: wordpress:latest, truyền các tham số môi trường cho wordpress là các thông tin truy cập csdl mariadb, tạo bởi Phpmyadmin
Yêu cầu: sau khi có 3 service này trong file docker-compose.yml :
Cấu hình để hệ thống chạy
Sử dụng cloudflare tunnel để public web này lên 1 sub-domain
Tạo 1 bài viết trong wordpress giới thiệu về bản thân sinh viên: thông tin cá nhân, sở thích, ... bài viết có thể chứa hình ảnh, âm thanh, video, ...
Tạo 1 bài viết trong wordpress giới thiệu về ngành học mà em yêu thích trong trường TNUT. bài viết phải chứa hình ảnh, video, ...
Nhận xét việc sử dụng mã nguồn mở wordpress để tạo website (tốn công sức thế nào, dễ/khó dùng ra sao, tốn kém tài nguyên(ssh/ram) của máy chủ ra sao,....)

# bài Làm 

chạy ubuntu tạo thư mục 
<img width="1452" height="557" alt="image" src="https://github.com/user-attachments/assets/576f982f-62ee-49b6-ae07-70b8f0152063" />

cấu hình file docker-compose.yml

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cc78ca80-e925-472e-b339-bc68290886b2" />

chạy docker-compose

<img width="1917" height="941" alt="image" src="https://github.com/user-attachments/assets/80ea32d4-f5cd-4944-aae5-e43634cef483" />

cài cloudfare

<img width="1918" height="240" alt="image" src="https://github.com/user-attachments/assets/c41ea904-4177-4628-8706-ded098a64c50" />

chạy container

<img width="1918" height="740" alt="image" src="https://github.com/user-attachments/assets/3ce0131e-9d50-47eb-a8a6-a89c92cc2c09" />

cấu hình wordpress

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2cc0b575-1163-4590-a6da-8a93ef74fc66" />

cấu hình thành công 


trang giao diện 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/834e6f48-11e2-419b-80af-09f749258e42" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ec407686-455d-4c63-906b-a045f702a625" />

