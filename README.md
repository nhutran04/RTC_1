* Chủ đề: Sử dụng chức năng tạo số ngẫu nhiên RNG của phần cứng STM32.
* Chức năng: Tạo giá trị ngẫu nhiên dùng Hardware của STM32, hiển thị lên Hercules.
* Cách sử dụng: 
1. Mở file cấu hình (.ioc) để xem cấu hình nối các chân I2C (PB10 và PB11)
2. Mở file project trên STM32CubeIDE để compile và chạy chương trình.
3. Gắn module CP2102 vào cổng USB của máy tính, mở Device Manager kiểm tra trạng thái kết nối.
4. Mở Hercules, chọn Serial, chọn cổng COM đúng và bấm Open để thấy kết quả số random hiện trên màn hình.

