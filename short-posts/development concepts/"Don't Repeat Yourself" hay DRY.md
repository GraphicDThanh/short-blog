Nói cho dễ hiểu hơn, thì khi bạn bắt gặp mình lặp lại một thao tác giống nhau, như việc copy / paste một đoạn code thì đã đến lúc bạn nên tạo cho nó một hàm để sử dụng lại.

Lợi ích dễ thấy của nguyên tắc này là giúp tái sử dụng code, hay "[[code resuse]]".

Nhưng [[copy / paste]] code thì code thì có gì sai cơ chứ ?

Thực ra copy / paste code thì cũng không có gì sai trái, nhưng DRY bên cạnh giúp code reuse ra thì còn giúp lập trình viên ẩn đi những đoạn logic quá chi tiết cho từng phần công việc nhỏ giúp giảm tải khối lượng logic lại, nếu cần truy cập thì sẽ tìm đến nơi viết đọc sau.

Vì thế [[DRY]] không chỉ là giảm code lặp. Mà bạn đang chia nhỏ một quá trình phức tạp ra thành từng đoạn công việc nhỏ có tên và nhiệm vụ riêng. Từ đó, việc định nghĩa tên hàm, các biến, giá trị trả về, viết document cho hàm cũng trở nên quan trọng, giúp bạn self-document code base của mình.

[](https://benwilhelm.com/articles/beyond-dry.html)[https://benwilhelm.com/articles/beyond-dry.html](https://benwilhelm.com/articles/beyond-dry.html)