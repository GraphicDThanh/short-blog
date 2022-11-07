Làm tròn số thực trong Python là chuyện thường ngày, và tụi mình sẽ sử dụng rất nhiều trong khi học Python cùng toán cũng như trong hiển thị các số thực với một số lượng các chữ số thập phân bất kỳ.

Có một số cách để làm tròn số thập phân:

-   Dùng hàm round() Cách này sẽ làm tròn số 3.333333 thành 3.33 và số 3.5 sẽ giữ nguyên là 3.5. round(3.33333) kết quả 3.33 round(3.5) kết quả 3.5 Nếu bạn muốn bắt buộc có hai chữ số thập phân thì cách này chưa triệt để, kết quả cần là 3.50
-   Chuyển về định dạng chuỗi và cắt số ký tự đứng sau dấu . rồi chuyển về lại dạng số với ép kiểu qua float

"{:.2f}".format(3.5) kết quả "3.50"

Lưu ý đây là chuỗi, muốn chuyển qua số bạn cần thực hiện ép kiểu từ string về số với float()

Nội dung này được tóm tắt từ bài viết chia sẻ tips trên blog cá nhân của mình.

[](https://beautyoncode.com/lam-tron-dung-hai-chu-so-thap-phan-trong-python/)[https://beautyoncode.com/lam-tron-dung-hai-chu-so-thap-phan-trong-python/](https://beautyoncode.com/lam-tron-dung-hai-chu-so-thap-phan-trong-python/)