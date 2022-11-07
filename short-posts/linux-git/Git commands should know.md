[[Git]] sẽ đi cùng bạn suốt thời gian làm dev, vì cứ hễ code là phải commit lên [[repository]] của [[github]], [[gitlab]] cá nhân hay của dự án, công ty.

Làm chủ Git [[CLI]] với 30 câu lệnh mà lập trình viên nên biết với bài viết ở link bên dưới.

Mình sẽ tóm tắt một số câu lệnh hay sử dụng và quan trọng theo cách mình nhìn nhé.

-   Setup usernane và email với [[`git config`]]. Câu lệnh này quan trọng khi bạn có nhiều repository khác nhau cần [[commit]] với tên và email khác nhau, ví dụ như repo cá nhân và công ty, dự án.
-   Clone một dự án về với [[`git clone`]], chuyển branch với [[`git checkout <tên branch>`]]
-   Tạo branch mới với [[`git branch`]], tạo mới và checkout qua luôn với [[`git checkout -b <tên branch>`]]
-   Xem các branch với `[[git branch`]], xem cả cho remote thì thêm option `-a`
-   Kiểm tra code changes với [[`git status`]]
-   Thêm file thay đổi lên staged với [[`git add`]]
-   Commit một dòng với `[[git commit -m <message>]]`
-   View commit history với [`[git log]`], thêm option `-3` sẽ xem 3 commits gần nhất, thêm `-p` sẽ xem thay đổi trên commit. Xem log đẹp dạng graph thì sử dụng [[`git log --graph --oneline --decorator`]]
-   Xem một commit với `[[git show <id>]]`, với id có thể là 6 số đầu của một commit id
-   Bỏ thay đổi của file chưa lên staged với [[`git checkout`]], nếu lên staged rồi thì dùng `git reset`
-   Rollback commit gần nhất với [[`git revert`]]
-   Xoá branch đã merge với [[`git branch -d`]], nếu có lỗi tức là branch này chưa được merge vào main branch, lúc nãy vẫn muốn xoá cần dùng option `-D`
-   Xoá branch ở remote với [[`git push origin --delete <branch-name>`]]
-   Merge hai branch với[[ `git merge`]], nếu cần commit merge thì thêm option `--no-ff`

[link](https://levelup.gitconnected.com/top-30-git-commands-you-should-know-to-master-git-cli-f04e041779bc)