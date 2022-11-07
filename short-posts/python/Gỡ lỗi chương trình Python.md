Hôm nay mình muốn nói về “Gỡ lỗi” ([[Debugging]])🐞, một qui trình sửa lỗi trong chương trình phần mềm. Điều quan trọng đầu tiên cần nhớ là:

> **Đừng cảm thấy thất vọng khi bạn tạo ra một con bug.**

Khi viết một chương trình thì việc gặp [[bug]] 🐞 là việc đương nhiên 🥲. Mình sẽ giới thiệu một số **mẹo và kỹ thuật** để nhận dạng bug và sửa nó hiệu quả:

**✍️ Mô tả vấn đề ([[Describe the problem]])**

Để fix bug, đầu tiên bạn cần mô tả được vấn đề mà mình gặp phải.

🐞  **Tái tạo lại lỗi (r[[eproduce the bug]])**

Rất nhiều khi bug chỉ thỉnh thoảng xuất hiện. Để fix được những bug như vậy lập trình viên cần biết cách tái tạo lại con bug đó và tìm hiểu chính xác vấn đề mà trường hợp đó gặp phải là gì thì mới có thể sửa lỗi được.

💻 Thử thực hiện chương trình như máy tính ([[Play computer]])

Với một chương trình phức tạp như có logic với nhiều điều kiện rẽ nhánh, hay gọi nhiều hàm khác nhau, thì việc sửa lỗi sẽ càng khoai hơn. Lúc này bạn cần tưởng tượng mình là máy tính, và với đầu vào cụ thể nào đó, bạn tự kiểm tra từng dòng một của chương trình như cách máy tính chạy để tìm manh mối cho lỗi của mình.

🏹 Sửa lỗi ([[fix the errors]])

Viết chương trình mà editor báo lỗi hay chạy chương trình mà bị lỗi là lỗi có thể thấy và sửa ngay được. Còn nếu chương trình chạy không đúng thì cần kiểm tra lại từng đoạn code, từng dòng code, hiểu rõ từng thứ mình viết ra thì mới mong sẽ tìm ra manh mối 🧐

🛠 Dùng các công cụ hỗ trợ kiểm tra lỗi ([[print]], [[log]], [[debugger]])

In ra các dòng để hiển thị kết quả của biến, hay đơn giản là code có chạy vào đó không cũng là một cách debug. Thêm nữa hãy học cách dùng debugger là như hổ mọc thêm cánh luôn nhé 😎

Mời bạn ghé đọc thêm chi tiết ở bài này nhé.

[](https://beautyoncode.com/go-loi-chuong-trinh/)[https://beautyoncode.com/go-loi-chuong-trinh/](https://beautyoncode.com/go-loi-chuong-trinh/)