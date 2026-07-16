```markdown
# Quy trình làm việc với GitHub

## Bước 1: Cập nhật branch main

```bash
git switch main
git pull

## Bước 2: Tạo branch mới
git switch -c feature/add-documentation

## Bước 3: Thay đổi nội dung
##Chỉnh sửa hoặc thêm file cần thiết.

## Bước 4: Kiểm tra thay đổi
git status
git diff

## Bước 5: Tạo commit
git add .
git commit -m "docs: add GitHub workflow guide"

## Bước 6: Push branch
git push -u origin feature/add-documentation

## Bước 7: Tạo Pull Request
### Trên GitHub:
### Mở repository
### Chọn Pull Requests
### Chọn New Pull Request
### Chọn branch cần merge
### Điền tiêu đề và mô tả
### Chọn Create Pull Request

##Bước 8: Merge Pull Request
### Sau khi kiểm tra code, chọn Merge Pull Request.

##Bước 9: Cập nhật máy local
git switch main
git pull
git branch -d feature/add-documentation