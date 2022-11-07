[[ReactJS]] vẫn đang làm mưa làm gió trên cộng đồng lập trình web với mức lương khủng và nhu cầu thị trường rất nhiều. Một số điều thú vị về [[React]]:

Thuật toán áp dụng khi xử lý [[DOM]] ảo là [[diff algorithm]], nó sẽ so sánh các phiên trước và sau khi state hoặc props thay đổi. 
DOM ảo là một bản copy của DOM thật theo tỉ lệ 1-1, DOM ảo là một object với các thuộc tính như loại element, các node con. 
DOM ảo hoạt động và đồng bộ với DOM thật qua thư viện [[ReactDOM]], quá trình này gọi là [[Reconciliation]] 
[[DOM ảo]] cũng là một object, object được lưu trữ trong [[stack]], [[heap]], và các bạn này được lưu ở trên ram DOM ảo có thực sự nhanh hơn DOM thật? Vấn đề này vẫn đang được tranh cãi 
Có phải ReactJS là cha đẻ của DOM ảo? Không nha, ReactJS sử dụng DOM ảo nhưng không tạo ra khái niệm này, nó đã có từ trước. Vuejs hay Elm cũng có sử dụng DOM ảo, mỗi thư viện có cách áp dụng khác nhau. 
Tại sao lại chia ra hai thư viện [[react]] và [[reactDOM]]? 
Vì có sự xuất hiện React Native, lập trình app cho di động, nên react sẽ là phần lõi dùng chung của cả hai bên: web và di động, còn reactDOM thì chỉ sử dụng cho [[web app]].

Bạn có thể đọc thêm ở bài viết dưới đây [](https://viblo.asia/p/su-that-thu-vi-ve-react-co-the-ban-chua-biet-L4x5xAawKBM)[https://viblo.asia/p/su-that-thu-vi-ve-react-co-the-ban-chua-biet-L4x5xAawKBM](https://viblo.asia/p/su-that-thu-vi-ve-react-co-the-ban-chua-biet-L4x5xAawKBM)