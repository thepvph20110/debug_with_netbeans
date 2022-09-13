# Hướng dẫn Debug với Netbeans

## Debug là gì ?
- là quá trình tìm kiếm ra lỗi hay nguyên nhân gây ra lỗi (bug ở đâu) để có hướng sửa lỗi (fix bug). 
Việc kiểm soát lỗi của rất nhiều các dòng code là việc không hề đơn giản với những người lập trình viên chưa có nhiều kinh nghiệm. 
##	Mục đích 
- Debug không chỉ là để loại bỏ lỗi (error) khỏi chương trình mà quan trọng hơn còn để giúp lập trình viên hiểu rõ hơn sự thực thi của chương trình.
Một lập trình viên không có khả năng Debug hiệu quả thì cũng giống như bị mù vậy.

## Trong bài viết này mình sẽ hướng dẫn các bạn cách debug với netbeans thông qua 1 vidu đơn giản
- vidu: mình tạo ra 1 project ( java ) nhập từ bàn phím 2 số a và b . tính tổng 2 số a và b và in ra kết quả.

![Screenshot (57)](https://user-images.githubusercontent.com/109200115/189924464-6c140792-a2cb-42ba-b6ba-b1c04091566a.png)

### Bước 1: Breakpoint dòng muốn debug -> chạy chương trình debug

- **breakpoint** : là để kiểm tra cách chương trình hoạt động trong thời gian chạy, chúng ta cần tạm dừng việc thực thi của nó trước đoạn mã bị nghi ngờ. Điều này được thực hiện bằng cách thiết lập các điểm ngắt. Các điểm ngắt chỉ ra các dòng mã nơi chương trình sẽ bị tạm dừng để bạn kiểm tra trạng thái của nó.

- **Cách đặt breakpoint** : Click chuột vào lề trái của dòng đó. Lúc này breakpoint sẽ được toggle, click thêm lần nữa để xóa (như hình).

![Screenshot (58)](https://user-images.githubusercontent.com/109200115/189924515-a6b48e63-91e6-473b-bcd5-1e6d2b8fcf74.png)

### Bước 2: Bắt đầu nhập số a -> thực hiện chạy tiếp các dòng sau breakpoint -> thực hiện tương tự nhập số b 

![Screenshot (59)](https://user-images.githubusercontent.com/109200115/189924563-fd3f1663-690d-4190-81fe-b4edcb8c8ccf.png)

![Screenshot (61)](https://user-images.githubusercontent.com/109200115/189924574-dc4cf451-a5ac-451a-af20-a057b6274a60.png)

- **Lưu ý** : Dòng code được highlight sẽ chưa thực hiện, chỉ khi bạn đi tiếp qua dòng khác thì dòng trước đó mới được thực thi.

### Bước 3: khi nhập và chạy hết các dòng muốn debug thì giá trị của các biến sẽ hiển thị bên cạnh biến đó -> nếu trường hợp biến khác với giá trị  nhập vào thì dòng đó xảy ra lỗi -> tiến hành fix bug 

![Screenshot (62)](https://user-images.githubusercontent.com/109200115/189924604-62810404-24c4-4114-b5b6-b79f63e66e3c.png)

### Kết luận
- để quá trình fix bug diễn ra nhanh chóng , chúng ta cần biết debug để tìm ra dòng gặp lỗi 
