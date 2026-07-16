# Các lệnh Git cơ bản

## Kiểm tra phiên bản Git

```bash
git --version

## Thiết lập thông tin người dùng
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

## Khởi tạo repository
git init

## Kiểm tra trạng thái
git status

## Thêm file vào staging area
## Thêm một file:
git add README.md

## Thêm tất cả file:
git add .

## Tạo commit
git commit -m "docs: add Git command documentation"

## Xem lịch sử commit
git log

## Xem dạng ngắn:
git log --oneline

## Kết nối GitHub
git remote add origin https://github.com/USERNAME/REPOSITORY.git

## Đẩy code lên GitHub
git push -u origin main

## Lấy code mới về máy
git pull

## Clone repository
git clone https://github.com/USERNAME/REPOSITORY.git