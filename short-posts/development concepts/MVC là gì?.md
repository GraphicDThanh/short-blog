Lập trình web ngày càng phát triển, từ ban đầu là các trang web tĩnh chỉ với HTML / CSS rồi phát triển lên trang web động và các hệ thống web ngày càng trở nên đồ sộ với sự làm việc chung của cả ngàn lập trình viên.

Để làm việc với hệ thống ngày càng phức tạp, có nhiều mô hình kiến trúc khác nhau để phân chia code sao cho đỡ phức tạp hơn và dễ dàng làm việc với nhiều người.

Mô hình được sử dụng phổ biến nhất là **[[MVC]]** ([[Model]] - [[View]] - [[Controller]]).

MVC giúp phân chia một ứng dụng lớn thành từng nhóm cụ thể khác nhau với mục đích và nhiệm vụ khác nhau.

Các thành phần:

-   Model: Là trung tâm của MVC, model là cấu trúc dữ liệu của ứng dụng, đứng độc lập với giao diện người dùng, chịu trách nhiệm quản lý dữ liệu, xử lý logic.
-   View: Là giao diện của ứng dụng
-   Controller: Là bộ điều khiển, nhận đầu vào là các yêu cầu và xử lý bằng cách gọi đến View, Model.

Trong mô hình này, Model và View sẽ không tương tác với nhau, chỉ có Controller là nói chuyện với cả Model và View.

![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8bbc907e-ac95-4dc4-9912-443e201c4821/Screen_Shot_2022-09-06_at_13.43.29.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221107%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221107T022655Z&X-Amz-Expires=86400&X-Amz-Signature=5150ea943004adab599b95862aecd2b96093abf72b63565c629bde574e65bad7&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Screen%2520Shot%25202022-09-06%2520at%252013.43.29.png%22&x-id=GetObject)

[https://en.wikipedia.org/wiki/Model–view–controller](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)