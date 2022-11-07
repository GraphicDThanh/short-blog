>[[ Inner function]] là hàm được định nghĩa bên trong một hàm khác.

Ví dụ:

```python
def outer_func(name):
	def inner_func():
		print(f"hello {name}")
	
	inner_func()

outer_func("Anna") # hello Anna
```

## **Inner function thường được được sử dụng:**

**Sử dụng đóng gói hàm ([[encapsulation]])**

Ở ví dụ trên, `inner_func` chỉ được truy cập bên trong hàm `outer_func` , bên ngoài không thể truy cập được. Đây gọi là **[encapsulation](https://en.wikipedia.org/wiki/Encapsulation_(computer_programming))**.

**Sử dụng để chia logic trong một hàm lớn thành các hàm logic nhỏ và có thể tái sử dụng**

Sử dụng viết các các hàm helper để sử dụng chỉ trong hàm nhất định. Có thể dùng prefix _ để mô tả hàm này là [[private]] với hàm, module hay class.

**Sử dụng để tạo closures** Closures là hàm được tự động tạo bằng cách trả về một hàm khác.

Tạo closures với 3 bước:

1.  Tạo một inner function
2.  Tham chiếu biến từ hàm bên ngoài để xử lý trong hàm inner function
3.  Trả về inner function

**Ví dụ:** tạo closures "generate_power" để tạo ra các hàm tính luỹ thừa.

```python
def generate_power(exponent):
	def power(base):
		return base ** exponent

	return power
```

sử dụng tạo hàm luỹ thừa hai

```python
raise_two = generate_power(2)
# tính lũy thừa hai của 5

raise_two(5) # 25
```

**Sử dụng để tạo [[decorators]]** 
Decorators là một [[HOC]] hay [[higher-order function]] nhận đầu vào một hàm, class, object và trả về hàm khác. 
Decorators thưởng được sử dụng trong [[debug]], [[caching]], [[logging]], [[timing]].

Ví dụ tạo một decorator thêm một số log trước và sau khi gọi hàm:

```python
# tạo decorator
def add_messages(func):
	def _add_messages():
		print("Start call function")
		func()
		print("Finish call function")

# sử dụng với @
@add_messages
def greet():
	print("Hi")

# gọi hàm greet
greet()

# kết quả:
Start call function
Hi
Finish call function
```

Inner function là một công cụ vô cùng mạnh mẽ đúng không nào !

---

Bạn đọc thêm ở bài viết sau nhé

[](https://realpython.com/inner-functions-what-are-they-good-for/)[https://realpython.com/inner-functions-what-are-they-good-for/](https://realpython.com/inner-functions-what-are-they-good-for/)