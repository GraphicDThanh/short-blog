Một số công cụ làm việc với [[form]] mới có thể bạn chưa biết.

[[`.requestSubmit()`]] là lựa chọn tốt hơn giúp thay thế [[`.submit()`]] khi bạn muốn event `'submit'` được trigger đồng thời muốn form được validate. Ví dụ mỗi khi submit như các field có `required` sẽ là bắt buộc.

Thuộc tính`[[sumitter]]` của event, hay [[`event.submitter`]] cho phép xác định đâu là [[DOM]] thực hiện submit form khi form có nhiều nút có [[`type="submit"`]]

`[[formdata]]` [[event]] là một sự kiện khá mới được **trigger** khi một [[FormData]] được khởi tạo với new hoặc mặc định khi form được submit. `e.formData` là một FormData instance với các thuộc tính và phương thức cho phép truy cập vào các fields data ở dạng key / value. (đọc thêm về [APIs FormData](https://developer.mozilla.org/en-US/docs/Web/API/FormData) và ví dụ mình có thử ở [đây](https://replit.com/@graphicdthanh/FormData#script.js)). Vậy là bạn có thể truy cập tất cả data của form khi submit đồng thời có thể chỉnh sửa trước khi gọi trực tiếp API nếu cần.

[[`showPicker()`]] của thẻ input cho phép hiển thị UI của các lựa chọn của thẻ [[input]], đó có thể là màu sắc, ngày tháng, …

Thuộc tính `[[inert]]` cho phép hiển thị form như ở trạng thái không [[focus]], không click được, và thuộc tính này cũng không áp dụng các style mặc định vào các thành phần. `inert` tương tự như [[`aria-hidden="true"`]]

Bạn có thể xem các ví dụ minh họa ở bài viết:

[](https://css-tricks.com/whats-new-with-forms-in-2022/)[https://css-tricks.com/whats-new-with-forms-in-2022/](https://css-tricks.com/whats-new-with-forms-in-2022/)