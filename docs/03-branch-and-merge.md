
```markdown
# Branch và Merge

## Xem danh sách branch

```bash
git branch

## Tạo branch mới
git switch -c feature/homepage

## Chuyển branch
git switch main

##Push branch lên GitHub
git push -u origin feature/homepage ##đẩy lên nhánh vừa tạo

##Merge branch
##Chuyển về nhánh chính:
git switch main

##Lấy code mới nhất:
git pull

##Merge branch:
git merge feature/homepage

##Xóa branch local
git branch -d feature/homepage

##Xóa branch trên GitHub
git push origin --delete feature/homepage