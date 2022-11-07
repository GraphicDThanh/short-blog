Như đã nói ở bài [“Điều gì xảy ra khi chạy một chương trình JavaScript ?”](https://beautyoncode.com/dieu-gi-xay-ra-khi-chay-mot-chuong-trinh-javascript/), mỗi khi một chương trình JS chạy sẽ có một `global execution context` được khởi tạo, mỗi hàm được thực thi sẽ có một `execution context` của hàm đó được khởi tạo.

[[`Execution context`]] chứa toàn bộ các biến, hàm và các đối số truyền vào ở global hoặc ở hàm được thực thi.

[`[Callstack]`] chứa toàn bộ các `execution contexts` này theo thứ tự chúng được khởi tạo, và hoạt động theo nguyên lý `[[LIFO]]` (last-in-first-out).

Vì thế, JavaScript hoạt động `[[synchronous]]`.

[[`Stack Overflow`]] là hiện tượng tràn `callstack` khi một hàm được gọi đệ quy vô tận. Trình duyệt có số lượng callstack nhất định do đó nếu gọi vô tận sẽ dẫn đến tràn stack, gây lỗi `“Maximum call stack size exceeded”`

Ví dụ chương trình này sẽ gây lỗi stack overflow:

```jsx
function callMySelf() {
  callMySelf()
}
callMySelf()
```