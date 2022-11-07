Khi viết code HTML/CSS cho một trang web, sẽ có những tình huống không mong đợi xảy ra, ví dụ như: đoạn chữ dài quá kích thước của khung làm chữ tràn ra ngoài, hay kích thước ảnh thay đổi ngẫu nhiên, hay hình nền bị lặp lại khi kích thước hình ảnh nhỏ

Những tình huống như trên đôi khi bản thiết kế không có sẵn, thường sẽ dựa trên kinh nghiệm của Front Developer xử lý, hoặc cho đến khi gặp lỗi (bug) thì phải sửa.

Để chủ động trong những tình huống này, giới thiệu đến bạn một trang chuyên viết về Defensive CSS.

Vậy vì sao Defensive CSS? Hay vì sao viết HTML/CSS cần phải chuẩn bị trước (phòng thủ) có những tình huống như trên có thể xảy ra?

Vì:

-   Nội dung trong bản thiết kế có thể thay đổi, tức là nội dung có thể tràn (break) layout
-   Hình ảnh có thể có các tỉ lệ khác nhau
-   Sử dụng các CSS như flex, grid một cách hiệu quả có thể giảm bug/break layout
-   Bản thiết kể chỉ mang tính chất định hướng thiết kế, dữ liệu thật có thể thay đổi, cần học cách viết layout sao cho có thể dễ bảo trì (maintain) và extend (mở rộng)

Trong đây có nhiều tips như là `Flexbox Wrapping`, `Image Distortion`, `Long Content`, …

Mời bạn vào đọc và xem ví dụ ở đây [](https://defensivecss.dev/tips)[https://defensivecss.dev/tips](https://defensivecss.dev/tips)