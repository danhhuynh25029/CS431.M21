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
