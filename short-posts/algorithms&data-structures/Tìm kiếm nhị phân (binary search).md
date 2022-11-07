Tìm [kiếm nhị phân](https://vi.wikipedia.org/wiki/T%C3%ACm_ki%E1%BA%BFm_nh%E1%BB%8B_ph%C3%A2n) ([[binary search]]) là một thuật toán tìm kiếm xác định vị trí của một giá trị cần tìm trong một mảng đã được sắp xếp.

Thuật toán sẽ tiến hành so sánh giá trị cần tìm với phần tử đứng giữa của mảng. Nếu hai giá trị không bằng nhau, thì một nửa mảng không chứa giá trị cần tìm sẽ được bỏ qua, và tiếp tục tìm kiếm trên nửa còn lại. Một lần nữa, lấy phần tử ở giữa so sánh với giá trị cần tìm, cứ thế lặp lại cho đến khi tìm thấy giá trị đó. Nếu phép tìm kiếm kết thúc mà vẫn chưa có giá trị cần tìm tức là nó không có trong mảng.

Binary search chạy theo giời gian logarit trong trường hợp tệ nhất, thực hiện O(logn) bước so sánh, với n là số phần tử của mảng. Thuật toán này sẽ nhanh hơn thuật toán tìm kiếm tuyến tính thông thường (lặp qua toàn mảng) với O(n)

Một số vấn đề thường gặp khi giải bài toán binary search:

-   Khi nào thì sẽ thoát ra khỏi vòng lặp?
-   Làm sao để khởi tạo và cập nhật biên bên trái (left), biên bên phải (right)?

[Bài viết sau](https://beautyoncode.com/tim-kiem-nhi-phanbinary-search/) giới thiệu một bản mẫu tổng quát về cách giải binary search sẽ giúp bạn hình dung về cách giải bài toán này dễ dàng hơn.

Note: [[beautyoncode blog posts]]