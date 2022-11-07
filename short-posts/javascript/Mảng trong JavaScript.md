Có hai cách để tạo mảng trong JavaScript là tạo đối tượng của lớp [[Array]]: `let arr = new Array(1, 2)`hay sử dụng cú pháp mảng []: `let arr1 = [3, 4]`

Khi làm việc với một danh sách, sẽ có các thao tác cơ bản như: (các phương thức của mảng sẽ bắt đầu với dấu `.`)

-   thêm một phần tử vào danh sách `.[[push()`]], [[`.unshift()`]], [[`.splice()`]]
-   xóa một phần tử ra khỏi danh sách [[`.pop()`]], [[`.shift()`]], [[`.splice()`]]
-   thay thế phần tử trong mảng với [[`.splice()`]]
-   lặp qua từng phần tử của mảng để lấy dữ liệu hay xử lý logic [[`for`]], [[`.forEach()`]], [[`.map()`]] (lưu ý map trả về mảng mới)
-   kiểm tra index của một giá trị trong mảng với [[`.indexOf()`]]
-   kiểm tra giá trị nào với vị trí index đã biết [[`.at()`]]
-   nối hai mảng với nhau với [[`.concat()`]]
-   nối các phần tử trong mảng với một ký tự liên kết với [[`.join()`]]
-   chuyển đổi mảng về chuỗi với [[`.toString()`]] (lưu ý phương thức này của [[object]], và array cũng là object)
-   tìm kiếm phần tử đầu tiên thỏa điều kiện với [[`.find()`]]
-   tìm kiếm tất cả phần tử thỏa điều kiện với [[`.filter()`]]
-   lấy ra một mảng con từ mảng ban đầu
-   sắp xếp mảng theo một thứ tự nào đó với [[`.sort()`]], đảo ngược mảng với [[`.reverse()`]]
-   kiểm tra tất cả các phần tử trong mảng thỏa điều kiện với [[`.every()`]], kiểm tra một vài phần tử trong mảng thỏa điều kiện với [[`.some()`]]

**Khi sử dụng các phương thức này bạn cần chú ý một số điều sau:**

-   Hiểu rõ phương thức sử dụng làm gì
-   Nắm rõ cú pháp
-   Kiểm tra giá trị trả về
-   Kiểm tra xem phương thức có làm thay đổi mảng ban đầu hay không

Bạn có thể đọc thêm ví dụ ở bài viết sau [](https://dev.to/codewithtee/15-array-methods-in-javascript-1p1m)[https://dev.to/codewithtee/15-array-methods-in-javascript-1p1m](https://dev.to/codewithtee/15-array-methods-in-javascript-1p1m)