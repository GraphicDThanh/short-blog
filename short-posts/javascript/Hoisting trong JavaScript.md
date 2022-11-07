Điều khiến [[JavaScript]] khó hiểu với những người mới hay chuyển từ ngôn ngữ khác qua chính là JavaScript cho phép sử dụng biến và hàm ngay cả trước cả khi bạn khai báo chúng.

**Vậy điều gì đã khiến mình có thể truy cập vào các biến và hàm ngay cả khi chúng chưa được khai báo?** Đó chính là cơ chế **[[Hoisting]] trong JavaScript.**

Bạn có nhớ hai giai đoạn của một “[[Execution Context]]" là [[Memory Creation]] và [[Code Execution]](đọc thêm ở [bài viết này](https://beautyoncode.com/dieu-gi-xay-ra-khi-chay-mot-chuong-trinh-javascript/)).

**Hoisting** trong JavaScript chính là sau giai đoạn Memory Creation, các biến và hàm sẽ được cấp bộ nhớ trước khi code được thực thi, biến được cấp bộ nhớ với giá trị `undefined` , còn hàm thì sẽ được cấp bộ nhớ cho toàn bộ nội dung bên trong hàm `f nameFunction()`. Vì thế, bước vào giai đoạn thực thi Code Execution, thì các giá trị này đã có sẵn để sử dụng.

**Hoisting** trong JS sẽ dễ gây hiểu nhầm nếu bạn không hiểu về JavaScript Engine nên bạn cần tìm hiểu cơ chế này để dễ debug chương trình của mình nhé.

Mời bạn đọc thêm chi tiết ở bài blog này

[](https://beautyoncode.com/hoisting-trong-javascript/)[https://beautyoncode.com/hoisting-trong-javascript/](https://beautyoncode.com/hoisting-trong-javascript/)

([[Blog Posts]])