# Các mạng CNN
* dữ liệu tại một thời điểm : đặc trừng về mặt không gian : 2D
1998 : LeNet

=> Dùng Convolutions thay cho full connected  + pooling để giảm số chiều => giảm số tham số => ít dữ liệu đầu vào => để tránh overfitting

2012 : AlexNet

* Dùng relu => activation function => hội tụ nhanh hơn(Do sigmoid dễ bão hòa)
* Dùng GPU để huấn luyện
* Dùng Data Augmentention => giải quyết vấn đề overfitting


2015 : 
* VGG
    
    * Bỏ hết filter 5x5,7x7
    * Chỉ dùng 3x3

* Iception
    * Nhiều nhánh bất biến tỉ lệ
* ResNet
    * Residual Network : x + f(x)
    * giải quyết vấn đề vanishing gradient
* DenseNet
    * Kết nối dày đặc
* MobileNet
    * dùng conv 1x1,3x3 -> deptwise conv -> giảm tham số -> tính nhanh
# ANN
* Tại nhiều thời điểm : Đặc trưng độc lập về mặt thời gian
# Recurrent Neural Network
### Input:
* chuỗi thông điệp đầu vào : đặc trưng về không gian 1D
many to one : classification

* many to many : 
    * chat bot
    * dự đoán
* giải quyết bài toán phân loại và tạo sinh
* không giải quyết các bài toán dữ liệu không có tính lặp đi lặp lại

Vấn đề: 

    văn bản,âm thanh không dùng với ANN đây là dữ liệu dạng chuỗi -> Trình tự tiếp nhận thông tin vai trò quan trọng
Giải pháp:
    ANN
RNN
    
    Dữ liệu dài độ chính xác không cao : Những từ ở đầu bị triệt tiêu thông tin sau nhiều biến đổi

LSTM:

Với những cổng:
* quên
* input

Sequence to Sequence 


Ôn tập
3 câu

câu 1:

Problem-Why-Solution

* Kể câu chuyện về nhứng cái đã học hoặc câu chuyện CNN và biến thể của nó. Câu chuyện ANN mô hình dạng chuỗi

câu 2:

Đầy đủ Số lượng tham số và kiến trúc.

Đúng kiến trúc thầy mô tả trong hình.

* Kiến trúc mạng Lenet hoặc AlexNet, RestNet,MobileNet,VGG. Cài đặt vài lớp. Cài đặt đặc trưng của vài lớp

Câu 3:

Có thực sự hiểu kiến trúc áp dụng giải quyết bài toán đó hay không.

Chấm dựa trên mả giả hoặc các bước.

Chấm về ý tưởng áp dụng.

* Dùng mạng CNN đi giải quyết bài toán nào đó
* Mạng ANN dùng cho bài toán Tranlastion
* Áp dụng Attention giải quyết phụ thuộc dài của RNN

