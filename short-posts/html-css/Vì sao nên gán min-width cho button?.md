Một vấn đề phổ biến khi tạo một nút bấm ([[button]]) là để chiều rộng của nút tùy vào nội dung của nút (text content) cộng với khoảng cách hai bên (padding).

Một vài lý do cho vấn đề này:

-   Nút bấm có nội dung hiển thị thay đổi trên UI tuỳ loại ngôn ngữ là rất phổ biến. Ví dụ nút `Done` trong tiếng Anh hiển thị qua tiếng Việt có thể là `Đã Xong`, và trong tiếng Arabic thì là [`تم`](https://defensivecss.dev/tip/button-min-width/#)thì khi đó button `Done` trong tiếng Anh có độ rộng là `72px` thì sẽ có độ rộng `95px` trong tiếng Việt và `43px` trong tiếng Ả Rập.
-   Việc hai nút bấm đứng cạnh nhau có cùng chiều rộng như `Done` và `Cancel` cũng thường xảy ra
-   Hoặc nội dung nút bấm ở phiên bản đầu là `Done` nhưng qua phiên bản sau đổi thành `Finished` cũng làm cho kích thước của nút bấm thay đổi theo

Vì thế, việc gán cho nút thuộc tính `min-width` sẽ giúp hạn chế những vấn đề ở trên. Nút `Done`

sẽ được gán [[min-width]] là 95px và sẽ hiển thị tốt cho cả ngôn ngữ là tiếng Việt hay tiếng Ả Rập.

```css
.button {
	min-width: 95px;
}
```

[](https://defensivecss.dev/tip/button-min-width/)[https://defensivecss.dev/tip/button-min-width/](https://defensivecss.dev/tip/button-min-width/)