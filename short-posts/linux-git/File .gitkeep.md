File **.gitkeep** thường được biết đến như là cách để có thể commit một thư mục trống lên trong quá trình thiết kế cấu trúc thư mục cho dự án của bạn.

Ví dụ cấu trúc một website đơn giản:

```jsx
src/
|-- assets/
  |-- images/
|-- styles/
  |-- main.css
index.html
[README.md](<http://readme.md/>)
```

Nếu không có .gitkeep trong thư mục “images” thì mình không thể commit cả hai thư mục “assets” và “images” lên repo được, kết quả là không giữ được cấu trúc thư mục như trên

![https://i0.wp.com/beautyoncode.com/wp-content/uploads/2022/06/gitkeep-0.png?w=597&ssl=1](https://i0.wp.com/beautyoncode.com/wp-content/uploads/2022/06/gitkeep-0.png?w=597&ssl=1)

![https://i1.wp.com/beautyoncode.com/wp-content/uploads/2022/06/gitkeep-1.png?resize=768%2C317&ssl=1](https://i1.wp.com/beautyoncode.com/wp-content/uploads/2022/06/gitkeep-1.png?resize=768%2C317&ssl=1)

Và đây là kết quả khi đặt .gitkeep trong thư mục “images”, cấu trúc thư mục sẽ được đảm bảo

![https://i0.wp.com/beautyoncode.com/wp-content/uploads/2022/06/gitkeep-2.png?resize=768%2C339&ssl=1](https://i0.wp.com/beautyoncode.com/wp-content/uploads/2022/06/gitkeep-2.png?resize=768%2C339&ssl=1)

**Câu hỏi đặt ra là: tại sao lại là .gitkeep? Có thể dùng file khác thay thế được không?**

Trả lời: **CÓ** thể dùng file khác thay thế! Ví dụ: text.txt hay thậm chí là .gitignore

Tuy nhiên vì mục đích của file này là giữ cho một thư mục có thể trống, theo nghĩa đen của nó, nên theo cách làm tiêu chuẩn sẽ là một file có đủ ý nghĩa trên:

-   .gitkeep là file ẩn
-   .gitkeep mang ý nghĩa đúng với vai trò của nó

Hi vọng bạn sẽ nhớ đến .gitkeep khi cần commit thư mục trống và hiểu thêm vì sao lại dùng bạn ấy nhé! Cơ mà nói chứ bạn sẽ ít xài lắm, vì thư mục có khi nào trống đâu haha.

Happy Coding! BeautyOnCode.

Bài viết gốc nằm trên blog của mình ở đây [](https://beautyoncode.com/gitkeep/)[https://beautyoncode.com/gitkeep/](https://beautyoncode.com/gitkeep/)

([[Blog Posts]])