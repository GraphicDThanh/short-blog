[[Authorization]] là quá trình kiểm tra xem người dùng có quyền truy cập vào những phần nhất định nào của ứng dụng hay được thực hiện các thao tác cụ thể nào trên ứng dụng.

Bạn cũng có thể nghe về nó với tên "[[access control]]" hay "[[privilege control]]". Lưu ý authorization diễn ra sau quá trình authentication, và bao gồm cả cho phép ([[grant]]) và từ chối ([[deny]]) các quyền. 
Ví dụ như blog, người dùng sẽ được quyền comment, nhưng chỉ có người dùng đồng thời là tác giả mới có quyền đăng bài.

vậy kiểm tra bằng cách nào?

-   "[[role-based access control]]" - kiểm soát quyền truy cập dựa trên vai trò người dùng trong ứng dụng (viewer, editor, manager, admin, ...)

Mỗi role này sẽ có các quyền truy cập nhất định được định nghĩa tuỳ theo cách những loại kỹ thuật bạn dùng.

Ví dụ như trong Django sẽ có sẵn các quyền read, write, edit, view cho từng loại model và bạn có thể kiểm soát quyền truy cập của từng role dựa vào từng loại quyền của model đó.

-   "[[claims-based access control]]" - kiểm soát quyền truy cập dựa trên việc kiểm tra các quyền mà người dùng có.

Ví dụ bạn có một trường owner cho phép xác định chủ sở hữu của đối tượng cụ thể nào đó. Hoặc bạn có một trường account_type cho phép xác định phân loại người dùng.

Bạn đọc thêm ở bài viết này có thêm ví dụ và sơ đồ minh hoạ nhé.

[](https://www.freecodecamp.org/news/whats-the-difference-between-authentication-and-authorisation/)[https://www.freecodecamp.org/news/whats-the-difference-between-authentication-and-authorisation/](https://www.freecodecamp.org/news/whats-the-difference-between-authentication-and-authorisation/)