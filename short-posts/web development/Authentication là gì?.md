[[Authentication]] là gì?
Là quá trình kiểm tra liệu người dùng có đúng danh tính mà hệ thống có về người ấy hay không. Nếu đúng thì sẽ cho phép người dùng truy cập vào hệ thống. Nếu không đúng thì từ chối truy cập vào hệ thống.

Vậy kiểm tra bằng cách nào?

[[single factor authentication]] - cách này hay sử dụng mật khẩu để đăng nhập, và sẽ có rủi ro là nếu bạn sử dụng cùng mật khẩu cho nhiều hệ thống thì nếu hacker hack được mật khẩu của một cái thì tất cả những tài khoản còn lại đều bị rủi ro về bảo mật.

[[2-factor authentication]] - cách này an toàn hơn và được sử dụng phổ biến hiện nay vì bên cạnh thông tin đăng nhập (username, password), bạn cần thêm một bên nữa như mã bảo mật gửi về email hay SMS.

[[multi-factor authentication]] - cách này còn xịn hơn cách ở trên với sự kết hợp giữa nhiều bên liên quan như thông tin đăng nhập, câu hỏi bảo mật, mã bảo mật ([[SMS]], [[authenticator app]]) hay nhận dạng vân tay, khuôn mặt.

Tuỳ vào loại ứng dụng mà chọn cách kiểm tra phù hợp vì không lý gì một ứng dụng giải trí lại yêu cầu quá nhiều thứ từ người dùng như tài khoản ngân hàng.