
# Git and GitHub Learning

Repository này lưu lại kiến thức và bài thực hành của tôi trong quá trình học Git và GitHub.

## Mục tiêu

- Hiểu sự khác nhau giữa Git và GitHub
- Biết cách quản lý phiên bản mã nguồn
- Biết tạo commit rõ ràng
- Biết sử dụng branch và merge
- Biết làm việc với GitHub Repository
- Biết tạo Pull Request
- Biết xử lý một số lỗi Git cơ bản

## Nội dung

### Tài liệu

- [Tổng quan về Git](docs/01-git-overview.md)
- [Các lệnh Git cơ bản](docs/02-basic-commands.md)
- [Branch và Merge](docs/03-branch-and-merge.md)
- [Quy trình làm việc với GitHub](docs/04-github-workflow.md)
- [Các lỗi Git thường gặp](docs/05-common-errors.md)

### Bài thực hành

- [HTML và CSS cơ bản](examples/basic-html)
- [Thực hành Git Command](examples/command-demo)

## Công nghệ và công cụ

- Git
- GitHub
- Git Bash
- PowerShell
- Visual Studio Code
- HTML
- CSS

## Quy trình Git cơ bản

```bash
git status
git add .
git commit -m "feat: add new feature"
git push
## Quy trình sử dụng branch
git switch main
git pull
git switch -c feature/new-feature

## Sau khi hoàn thành chức năng:

git add .
git commit -m "feat: implement new feature"
git push -u origin feature/new-feature

## Quy ước commit
| Loại       | Ý nghĩa                           |
| ---------- | --------------------------------- |
| `feat`     | Thêm chức năng                    |
| `fix`      | Sửa lỗi                           |
| `docs`     | Thay đổi tài liệu                 |
| `style`    | Thay đổi giao diện hoặc định dạng |
| `refactor` | Cải tiến cấu trúc code            |
| `test`     | Thêm hoặc sửa kiểm thử            |
| `chore`    | Cấu hình và công việc phụ         |
