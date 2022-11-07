Các bạn [[Frontend Developer]] hay sử dụng gì để debug trong code [[JavaScript]] nhỉ?

Để hiển thị các thông tin lên trình duyệt thì có thể sử dụng:

-   [[alert()]]: hiện popup kèm nội dung
-   [[console.log()]]: hiển thị nội dung ở “[[Console]]" của trình duyệt
-   [[debugger;]] chỗ đặt bạn này sẽ là một breakpoint, khi code thực thi sẽ dừng lại để bắt đầu chế độ debug trên trình duyệt
-   [console.trace(](https://developer.mozilla.org/en-US/docs/Web/API/Console/trace)): hiện ra các dấu vết của nơi mình đặt bạn ấy vào và giúp mình kiểm tra đã đi qua những đâu, ở dòng bao nhiêu. Cái này gọi là [[`trace`]] ấy.   
![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/017c0419-7d41-45f9-a182-e63293cc6f93/trace-log.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221107%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221107T055220Z&X-Amz-Expires=86400&X-Amz-Signature=b54baa1ebdcfd6a46322d187ea368829a6ba8a8d176c2787d5f5d96d38369fa2&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22trace-log.png%22&x-id=GetObject)

Ngoài ra thì nên tìm hiểu về [Chrome DevTools](https://developer.chrome.com/docs/devtools/) , một công cụ vô cùng mạnh mẽ

Nếu làm app React thì có [React DevTools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)

[[Visual Studio Code]] cũng cung cấp công cụ debug rất mạnh mẽ ấy

Bạn ghé đọc thêm về [[Debug JavaScript Tools]] ở đây nhé

[](https://raygun.com/learn/javascript-debugging-tools)[https://raygun.com/learn/javascript-debugging-tools](https://raygun.com/learn/javascript-debugging-tools)