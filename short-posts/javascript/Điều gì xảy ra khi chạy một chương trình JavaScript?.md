Mọi thứ trong JavaScript diễn ra bên trong một ngữ cảnh thực thi, hay “Execution Context”. Có hai giai đoạn trong “Execution Context” là “Memory Creation” và ”Code Execution

Khi chương trình JS khởi chạy, một execution context ở global sẽ được tạo. Ở giai đoạn **“Memory Creation Phase”**, bộ nhớ được cấp cho tất cả các biến và các hàm.

Ở giai đoạn **“Code Execution"**, code sẽ được thực thi từng dòng một theo thứ tự trên xuống dưới.

Nếu có một hàm được gọi, một Execution Context giành riêng cho hàm đó sẽ được tạo và thực hiện tương tự với hai giai đoạn trong Execution Context mới này. Khi một hàm kết thúc thực thi, thì Execution Context này sẽ được xóa đi.

Và cứ thế, chạy cho đến hết chương trình.

Quá trình ở trên thường được gọi là **call stack**

Mỗi execution context được tạo sẽ được bỏ vào(push) vào ngăn xếp(stack)

Mỗi execution context bị xóa sẽ được lấy ra khỏi(pop) ngăn xếp(stack)

Đây chính là cách JS Engine thực thi code.

Mời bạn đọc chi tiết về quá trình này kèm ví dụ và hình ảnh minh họa ở blog post này nhé

[](https://beautyoncode.com/dieu-gi-xay-ra-khi-chay-mot-chuong-trinh-javascript/)[https://beautyoncode.com/dieu-gi-xay-ra-khi-chay-mot-chuong-trinh-javascript/](https://beautyoncode.com/dieu-gi-xay-ra-khi-chay-mot-chuong-trinh-javascript/)

([[Blog Posts]])