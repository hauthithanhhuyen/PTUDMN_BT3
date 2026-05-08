HẦU THỊ THANH HUYỀN
K225480106027
# PTUDMN_BT3
SỬ DỤNG WORDPRESS ĐỂ TẠO WEB SITE
1.SỬ DỤNG DOCKER TRÊN UBUNTU ĐỂ TẠO docker ccompose chứa:
# 1. Cài Docker và Docker Compose trên Ubuntu
Cập nhật Ubuntu:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/816589c6-0941-438d-8862-feaa5f7cb87b" />
Cài docker
<img width="1694" height="263" alt="image" src="https://github.com/user-attachments/assets/f6f3ac0e-f7ce-4650-b4e1-2afd0d2592a1" />
Khởi động Docker
<img width="1178" height="159" alt="image" src="https://github.com/user-attachments/assets/acc39912-6410-4d19-8b79-0fd447cc636a" />
Cài Docker Compose:
<img width="1406" height="264" alt="image" src="https://github.com/user-attachments/assets/5c8db98e-6731-49ee-9bd8-d9eb506dab65" />
<img width="895" height="156" alt="image" src="https://github.com/user-attachments/assets/a9ec58b4-6eed-43f1-b7aa-68df8ac401a3" />
# 2. Tạo thư mục project
   <img width="1788" height="150" alt="image" src="https://github.com/user-attachments/assets/7debd353-5f71-422a-bd51-15231cd99eae" />
# 3. Chạy hệ thống Docker
   <img width="1916" height="417" alt="image" src="https://github.com/user-attachments/assets/3b6b08c3-88b0-495a-82e9-66cf3bf8875c" />
# 4. Truy cập hệ thống
 <img width="1842" height="968" alt="image" src="https://github.com/user-attachments/assets/056da7f0-816c-4ff1-80dc-38228826d7d6" />
<img width="1909" height="802" alt="image" src="https://github.com/user-attachments/assets/d36d5c52-0141-4ba2-8ed9-d80a85a22939" />
<img width="1715" height="704" alt="image" src="https://github.com/user-attachments/assets/dd0cdd41-a380-46ec-ad11-5b6fc2889408" />
 # 5 Tạo 1 bài viết trong wordpress giới thiệu về bản thân sinh viên: thông tin cá nhân, sở thích, ... bài viết có thể chứa hình ảnh, âm thanh, video, ...
<img width="1767" height="879" alt="image" src="https://github.com/user-attachments/assets/8bfd363b-13ea-498e-8d9a-7ccaf73de298" />
<img width="1857" height="938" alt="image" src="https://github.com/user-attachments/assets/3e4deed1-0ac5-43fe-84fd-cd5df648dd69" />
Tạo bài viết về trường
<img width="1814" height="872" alt="image" src="https://github.com/user-attachments/assets/4a3a5caa-c9bc-409f-96ed-9b0a2f7d18e6" />
# 6.Nhận xét việc sử dụng mã nguồn mở wordpress để tạo website (tốn công sức thế nào, dễ/khó dùng ra sao, tốn kém tài nguyên(ssh/ram) của máy chủ ra sao,....)
Nhận xét việc sử dụng WordPress & Docker để tạo website:
Về công sức: Khởi tạo cục bộ bằng Docker cực kỳ nhanh. Tuy nhiên, việc đưa web ra Internet (dùng Cloudflare) khá vất vả do hay gặp lỗi kẹt link cũ, bắt buộc phải can thiệp trực tiếp vào Database để sửa.
Độ dễ/khó dùng: Giao diện quản trị rất dễ dùng và trực quan. Việc tạo bài viết, chèn ảnh, nhúng video chỉ cần kéo thả hoặc copy-paste link, hoàn toàn không cần biết lập trình code.
Tốn kém tài nguyên:
RAM: Tiêu tốn khá nhiều RAM (khoảng 1GB) do phải chạy ngầm nhiều dịch vụ cùng lúc (Web, Database, phpMyAdmin).
Lưu trữ (Ổ cứng): Sẽ rất ngốn dung lượng nếu tải trực tiếp video/ảnh lên máy chủ. Giải pháp tối ưu là nhúng link nền tảng ngoài (YouTube, SoundCloud) để tiết kiệm tài nguyên.
