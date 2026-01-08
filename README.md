## 📌 Giới Thiệu Dự Án
Đây là repository chứa báo cáo bài tập lớn (BTL) của nhóm sinh viên Khoa Điện - Điện Tử, Trường Đại học Giao thông Vận tải. Báo cáo tập trung vào việc ứng dụng các phương pháp kiểm tra không phá hủy (Non-Destructive Testing - NDT) hiện đại với chi phí thấp, sử dụng phần cứng đơn giản và phần mềm mã nguồn mở.
Báo cáo bao gồm ba đề tài chính:
- Sử dụng công nghệ sóng siêu âm khảo sát vết nứt bề mặt (sử dụng cảm biến HC-SR04 + ESP32 + Python để tạo A-scan và B-scan).
- Hiển thị dữ liệu GPR bằng phần mềm gprMax (mô phỏng sóng điện từ với FDTD).
- Thiết kế mạch dùng công nghệ GPR phát hiện khuyết tật và vật thể bên trong bê tông (sử dụng cảm biến HB100 + Arduino Mega + GPRPy).
Mục tiêu: Xây dựng các hệ thống mô phỏng đơn giản, chi phí thấp nhưng vẫn thể hiện bản chất của công nghệ NDT hiện đại, kết hợp lý thuyết, mô phỏng và thực nghiệm.

## 📊 Mục Tiêu Chính
- Tìm hiểu nguyên lý siêu âm (UT) và radar xuyên đất (GPR).
- Xây dựng hệ thống thu thập và xử lý tín hiệu chi phí thấp.
- Mô phỏng và trực quan hóa dữ liệu (A-scan, B-scan, FFT).
- Thực nghiệm trên mẫu vật liệu thực tế (bê tông, gỗ, nhựa, kim loại).
- Đánh giá khả năng phát hiện khuyết tật/vết nứt/vật thể ẩn.

## ⚙️ Công Nghệ & Linh Kiện Sử Dụng
### Phần cứng:
- Cảm biến siêu âm: HC-SR04
- Cảm biến vi ba: HB100 (Doppler radar 10.525 GHz)
- Vi điều khiển: ESP32, Arduino Mega 2560
- Op-amp: LM324
### Phần mềm:
- Arduino IDE
- Python (NumPy, Pandas, Matplotlib, SciPy cho FFT và xử lý tín hiệu)
- gprMax (mô phỏng FDTD GPR)
- gprPy (xử lý và hiển thị dữ liệu GPR)
