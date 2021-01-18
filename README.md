Async - khai báo một hàm bất đồng bộ (async function someName(){...}).

Tự động biến đổi một hàm thông thường thành một Promise.
Khi gọi tới hàm async nó sẽ xử lý mọi thứ và được trả về kết quả trong hàm của nó.
Async cho phép sử dụng Await.



Await - tạm dừng việc thực hiện các hàm async. (Var result = await someAsyncCall ).

Khi được đặt trước một Promise, nó sẽ đợi cho đến khi Promise kết thúc và trả về kết quả.
Await chỉ làm việc với Promises, nó không hoạt động với callbacks.
Await chỉ có thể được sử dụng bên trong các function async.


Promise và async/await không hoàn toàn thay thế mà hỗ trợ lẫn nhau. Mặc dù chúng ta có thể dùng async/await ở đa số các trường hợp, Promise vẫn là nền tảng cần thiết khi thực thi các tác vụ bất đồng bộ trong JavaScript