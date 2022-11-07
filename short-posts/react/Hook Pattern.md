[[Hook Pattern]] giúp sử dụng function để tái sử dụng các trạng thái([[state]]) xuyên suốt nhiều components trong app.

[[React 16.8 ]]giới thiệu Hooks, một cách mới vẫn có thể sử dụng state và [[lifecycle methods]] mà không cần dùng cú pháp class của [[ES2015]].

**Vì sao lại thay thế [[class component]]?**

Để hiểu vì sao thì cần phải hiểu về class component. Trước đây, có hai cách để tạo một component là sử dụng [[function]] ([[stateless componet]]) và [[class]] ([[statefull component]]). Class sẽ sử dụng nếu component cần làm việc với các trạng thái (state).

Việc này dẫn tới một vấn đề vể code sẽ thay đổi nhiều lên rất nhiều khi một function component muốn chuyển sang class component vì syntax khác nhau. Class component cần có constructor để khởi tạo [[state]], hàm [[render]], các hàm khác, ...

Thêm vào đó, việc chia sẻ state qua nhiều component có thể sử dụng [[HOC]] hay [[Render Props pattern]], và khi có nhiều component lồng vào nhau sẽ sinh ra vấn đề [[component wrapper hell]] (có thể hiểu tương tự [[callback hell]])

Ngoài ra, việc kiểm soát một component ở lifecycle methods như [[componentDidMount]], ... sẽ càng làm cho code base của một component gia tăng, và lặp lại ở nhiều component.

**[[Hooks]] ra đời giúp giải quyết các vấn đề trên như thế nào**?

-   Hooks cho phép quản lý state trong một function component, nên không cần đổi code base nhiều khi sử dụng state nữa.
-   Hooks cho phép quản lý component lifecycles mà không cần viết các hàm như componentDidMount, ... như trước
-   Hook cho phép tái sử dụng state xuyên suốt app

Mời bạn đọc thêm ở bài này nhé, thú vị lắm ấy!

[](https://www.patterns.dev/posts/hooks-pattern/)[https://www.patterns.dev/posts/hooks-pattern/](https://www.patterns.dev/posts/hooks-pattern/)