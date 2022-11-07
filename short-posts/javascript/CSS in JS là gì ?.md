`CSS-in-JS` là một thuật ngữ mô tả việc viết code style `CSS` trong code `JS`, tức viết vào file `.js` , `.jsx` thay vì viết code `CSS` vào file `.css` như thông thường.

`CSS-in-JS` ra đời khi mà trang web ngày càng phức tạp và việc maintain tất cả các `CSS` của toàn bộ trang web trong một `scope global document` (hay global scope selectors) duy nhất của của file css gây nhiều xung đột khi trùng tên class, id hay việc ghi đè `CSS` trở nên khó khăn hơn.

Thêm vào đó xu hướng `component-based development` (hay component driven development) ngày càng phát triển với React khiến việc style từng component càng trở nên cấp thiết.

**CSS-in-JS đã giúp giải quyết vấn đề này như thế nào?**

**CSS-in-JS sẽ trích xuất CSS theo từng component thay vì theo document như CSS.**

Những ưu và nhược điểm khi sử dụng CSS-in-JS

Ưu điểm

-   Code ngắn gọn hơn
-   Giảm xung đột CSS
-   CSS dynamic với props
-   Kế thừa style
-   Cú pháp SASS giúp style dễ dàng với pseudo element và pseudo class
-   Tự động tạo prefix cho class CSS, không sợ bị trùng nhau
-   Có thể viết unit test cho CSS
-   Dễ dàng đổi theme với ThemeContext

Nhược điểm

-   Không phù hợp với người chưa biết JS
-   Tốn thời gian làm quen với thư viện, code base gây khó khăn cho người mới
-   Sẽ khó khăn khi muốn debug bằng tên class
-   Hiệu suất không tốt bằng CSS bình thường do tăng code base

Bạn tìm hiểu thêm ở link bên dưới nhé [](https://beautyoncode.com/css-trong-js-la-gi/)[https://beautyoncode.com/css-trong-js-la-gi/](https://beautyoncode.com/css-trong-js-la-gi/)

([[Blog Posts]])