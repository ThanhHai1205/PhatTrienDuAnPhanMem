Hướng dẫn sử dụng Git và GitHub đơn giản

1. Cài đặt Git

Tải Git từ trang chủ: https://git-scm.com/downloads
Cài đặt theo hướng dẫn mặc định

2. Tạo tài khoản GitHub

Truy cập: https://github.com
Đăng ký tài khoản mới với email của bạn

3. Thiết lập Git trên máy tính
Mở Terminal Command Prompt/Git Bash (Windows) và nhập:
git config --global user.name "Tên của bạn"
git config --global user.email "email@example.com"
4. Tạo repository mới trên GitHub

Đăng nhập vào GitHub
Nhấn nút "+" ở góc trên bên phải, chọn "New repository"
Đặt tên, mô tả (tùy chọn)
Chọn "Initialize with README" nếu muốn tạo file README
Nhấn "Create repository"

5. Clone repository về máy tính
git clone https://github.com/username/ten-repository.git
6. Làm việc với Git cơ bản
Di chuyển vào thư mục dự án:
cd ten-repository
Thêm file mới:
git add ten-file
Thêm tất cả file:
git add .
Commit thay đổi:
git commit -m "Mô tả thay đổi"
Đẩy lên GitHub:
git push
Cập nhật từ GitHub về máy:
git pull
7. Tạo nhánh mới
git branch ten-nhanh-moi
git checkout ten-nhanh-moi
Hoặc tạo và chuyển nhánh cùng lúc:
git checkout -b ten-nhanh-moi
