🤩 Redis basic ☕️

Redis là một cơ sở dữ liệu trong bộ nhớ ([[in memory database]]) 💿, dữ liệu được lưu trữ theo dạng [[key-value]] 🔑 🪟 tức là từ khóa và giá trị của nó.

👩‍🍳 [[Redis]] thường sử dụng như là một cơ sở dữ liệu [[caching]]📜, có tốc độ truy cập rất nhanh 💨.

💻 Để làm quen với Redis, cài đặt nhanh trên Mac với “brew install redis”, sau đó chạy server với “[[redis-server]]”.

Sau khi server được khởi chạy, bạn có thể bắt đầu làm quen với các câu lệnh cơ bản trong Redis bằng cách sử dụng [[CLI]], mở một cửa sổ mới và gõ lệnh “[[redis-cli]]”

🧐 Câu lệnh SET, GET, EXISTS, KEYS

Vì lưu trữ dạng key-value nên câu lệnh cơ bản nhất sẽ là:

-   gán trị vào từ khóa (set value to key): `SET <key> <value>`
-   lấy giá trị ra từ từ khóa (get value from key): `GET <key>`
-   kiểm tra xem từ khóa có trong bộ nhớ không: `EXIST <key>`
-   tìm kiếm từ khóa theo pattern: `KEYS <pattern>`

Một bộ key-value cũng có thể được set thời gian nó tồn tại với từ khóa `EXPIRE <key> <time>`

Ngoài ra, Redis cũng có nhiều kiểu dữ liệu khác được lưu cho value như: [[list]], [[sets]], [[hashes]] và các từ khóa tương ứng sử dụng cho từng kiểu dữ liệu trên.

Mời bạn ghé đọc [bài viết này](https://beautyoncode.com/basic-knowledges-about-redis/) để tìm hiểu thêm và có video hướng dẫn để bạn có thể thực hành nữa ấy.

Happy Coding!

BeautyOnCode.

([[Blog Posts]])