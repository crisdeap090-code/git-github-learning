```markdown
# Các lỗi Git thường gặp

## Lỗi remote origin already exists

```text
error: remote origin already exists

## Kiểm tra remote:

git remote -v

Xóa remote cũ:

git remote remove origin

Thêm lại:

git remote add origin REPOSITORY_URL
Lỗi rejected non-fast-forward
Updates were rejected because the remote contains work

Lấy code từ GitHub về:

git pull origin main --rebase

Sau đó:

git push
Lỡ thêm file không nên commit

Ví dụ đã thêm file .env:

git rm --cached .env

Thêm .env vào .gitignore, sau đó commit:

git add .
git commit -m "chore: remove environment file"
git push
Kiểm tra repository đang kết nối
git remote -v
Hủy thay đổi chưa commit
git restore ten-file