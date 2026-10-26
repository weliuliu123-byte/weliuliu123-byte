<div align="center">

# Hà Gia Bảo
### **Digital IC Design Engineer • ASIC / FPGA • Hardware-Software Co-Design**

[![Major](https://img.shields.io/badge/Chuyên%20ngành-Thiết%20kế%20Vi%20mạch%20(IC%20Design)-blue?style=flat&logo=microchip&logoColor=white)](https://hcmuni.fpt.edu.vn/)
[![University](https://img.shields.io/badge/Trường-Đại%20học%20FPT-F37021?style=flat)](https://hcmuni.fpt.edu.vn/)
[![Email](https://img.shields.io/badge/Email-weliuliu123%40gmail.com-0078D4?style=flat&logo=gmail&logoColor=white)](mailto:weliuliu123@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-weliuliu123--byte-181717?style=flat&logo=github&logoColor=white)](https://github.com/weliuliu123-byte)
[![Location](https://img.shields.io/badge/Location-TP.%20Hồ%20Chí%20Minh%2C%20Việt%20Nam-555555?style=flat&logo=googlemaps&logoColor=white)](https://maps.google.com)

---

</div>

## 🎯 Giới thiệu chung (About Me)

Sinh viên chuyên ngành **Thiết kế Vi mạch (Integrated Circuit Design)** tại **Trường Đại học FPT**, định hướng nghiên cứu và phát triển chuyên sâu vào **Digital IC / RTL Design**, **FPGA Acceleration**, **Kiến trúc máy tính (Computer Architecture)** và **Hardware-Software Co-Design**.

- 🔬 **Trọng tâm kỹ thuật:** Thiết kế vi mạch số bằng Verilog/SystemVerilog, kiến trúc Datapath & FSM, thiết kế khối tính toán số học (FPU IEEE-754, bộ tăng tốc DSP, CNN Quantized), và kỹ thuật sửa lỗi SEC-DED Hamming.
- ⚙️ **Hardware-Software Co-Design:** Am hiểu sâu sắc về cầu nối giữa phần cứng vi mạch và phần mềm hệ thống: viết Linux Kernel Driver (`char`, `ioctl`) giao tiếp thiết bị, tối ưu hóa độ trễ thời gian thực và mô phỏng trên nền tảng vi xử lý ARM Cortex-A9 (QEMU).
- 🤝 **Hợp tác nghiên cứu & dự án:** Thường xuyên cộng tác nghiên cứu thiết kế vi mạch và bộ tăng tốc FPGA cùng [@ntue2719-commits](https://github.com/ntue2719-commits).

---

## 💻 Kỹ năng chuyên môn (Technical Skillset)

| Phân mảng | Công nghệ & Công cụ |
| :--- | :--- |
| **HDL & Thiết kế RTL** | `Verilog HDL` • `SystemVerilog` • Datapath & Controller (FSM) Design • Pipelining & Timing Optimization • Fixed-Point Arithmetic (Q4.4) • Line Buffers & Memory Interfacing |
| **Công cụ EDA & Mô phỏng** | `ModelSim / QuestaSim` • `Xilinx Vivado` • Icarus Verilog • GTKWave • Thiết kế Self-checking Testbenches |
| **Kiến trúc máy tính & Khối xử lý** | Khối số thực IEEE-754 (FPU 32-bit) • Bộ tăng tốc xử lý ảnh 2D Convolution DSP • Thuật toán mã hóa sửa lỗi SEC-DED Hamming • Bộ điều chế/giải điều chế số BPSK • Khối suy luận mạng nơ-ron CNN |
| **HW/SW Co-Design & Driver** | `C (C99/C11)` • `C++` • `ARM Assembly` • `Python` • Linux Device Drivers (`char`, `miscdevice`, `unlocked_ioctl`) • POSIX Real-Time (`SCHED_FIFO`, `mlockall`) • QEMU ARMv7 Cortex-A9 |
| **Thiết kế phần cứng PCB** | `KiCad` (Thiết kế PCB 2 lớp) • Tính toàn vẹn tín hiệu (Signal Integrity) & giảm nhiễu EMI • Mạch công suất điều khiển Actuator / MOSFET • Chuẩn giao tiếp phần cứng (I2C, SPI, UART, ADC) |

---

## 🏆 Dự án Thiết kế Vi mạch & Phần cứng tiêu biểu

### 🖼️ [image-dsp-benchmark](https://github.com/ntue2719-commits/image-dsp-benchmark) *(Cộng tác cùng [@ntue2719-commits](https://github.com/ntue2719-commits))*
*Bộ tăng tốc phần cứng (Hardware Accelerator) trên FPGA cho xử lý ảnh 2D Spatial Filtering & Convolution.*
- Thiết kế kiến trúc **Pipelined 3×3 Sliding Window** kết hợp hệ thống **Dual Line Buffers**, đảm bảo thông lượng tính toán đạt **1 pixel / 1 chu kỳ xung nhịp (clock cycle)**.
- Tối ưu hóa cấu trúc RTL có khả năng tùy biến linh hoạt theo kích thước ảnh (từ 256×256 đến 1024×1024) với chi phí tài nguyên phần cứng (LUTs/Registers) tối thiểu.

### ⚡ [secDED-bpsk-fpga](https://github.com/ntue2719-commits/secDED-bpsk-fpga) *(Cộng tác cùng [@ntue2719-commits](https://github.com/ntue2719-commits))*
*Thiết kế RTL trên FPGA cho hệ thống sửa lỗi Hamming SEC-DED và truyền thông số BPSK.*
- Trực tiếp thiết kế khối **Datapath RTL** và hệ thống testbench tự động kiểm chứng toàn diện.
- Hiện thực thuật toán mã hóa Hamming (7,4) và (8,4) mở rộng cho phép sửa 1 lỗi đơn (Single Error Correction) và phát hiện 2 lỗi kép (Double Error Detection), tích hợp pipeline điều chế/giải điều chế BPSK.

### 🧮 [fpu32-ieee754-lite](https://github.com/ntue2719-commits/fpu32-ieee754-lite) — Khối tính toán số thực FPU 32-bit
*Thiết kế vi mạch số cho bộ cộng/trừ số thực dấu chấm động chuẩn IEEE-754 Single-Precision.*
- Hiện thực pipeline giải mã các trường Sign, Exponent, Mantissa; căn chỉnh số mũ (Exponent alignment), chuẩn hóa (Normalization) và làm tròn (Rounding).
- Xử lý đầy đủ các trường hợp ngoại lệ phần cứng: Overflow, Underflow, NaN (Not a Number) và Zero.

### 🧠 [cnn-mnist-q44](https://github.com/ntue2719-commits/cnn-mnist-q44) — Bộ tăng tốc suy luận AI trên FPGA
*Hardware Accelerator suy luận mạng nơ-ron tích chập (CNN) cho bộ dữ liệu MNIST sử dụng số thực dấu phẩy tĩnh Q4.4.*
- Thiết kế các khối nhân tích chập (Convolution), hàm kích hoạt ReLU và Pooling bằng logic số nguyên/fixed-point, loại bỏ nhu cầu về phần cứng dấu chấm động đắt đỏ trên FPGA.

### 🐧 [Embedded Linux Systems (LOS)](https://github.com/weliuliu123-byte/LOS) — Tầng Giao tiếp HW/SW Co-Design
*Nền tảng kiểm chứng và phát triển Linux Kernel Driver điều khiển phần cứng trên kiến trúc ARMv7-A Cortex-A9 (QEMU).*
- Xây dựng driver giao tiếp vi mạch character device với giao diện điều khiển phần cứng `unlocked_ioctl`, bảo vệ tranh chấp tài nguyên bằng Mutex.
- Ứng dụng giám sát cảm biến thời gian thực đa luồng POSIX (`SCHED_FIFO`, `mlockall`), kiểm chứng đạt **jitter tối đa chỉ 45 µs** và **0 bytes rò rỉ bộ nhớ** trên Valgrind.

---

## 📑 Nghiên cứu khoa học & Ấn phẩm (Publications)

**Design and Experimental Evaluation of a Hybrid K-Means PID Controller for ESP32-Based Cold Chain Monitoring**  
*Nguyễn Trí Tuệ, Lê Nhật Nam, **Hà Gia Bảo**, ThS. Hồ Lê Minh Toàn (GVHD)* — Trường Đại học FPT  
- Nghiên cứu kiến trúc điều khiển hai tầng (Macro K-Means + Micro PID với cơ chế Hysteresis 0.5°C) chạy trực tiếp tại biên cảm biến (In-Sensor Computing / TinyML).
- Thiết kế bo mạch thực nghiệm PCB 2 lớp trên KiCad đáp ứng tính toàn vẹn tín hiệu. Hệ thống đạt thời gian ổn định nhanh hơn **18.13%** so với PID truyền thống, chu kỳ thực thi chỉ **23.6 µs** với bộ nhớ **226 kB SRAM**.

---

## 📊 Thống kê hoạt động (GitHub Metrics)

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=weliuliu123-byte&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" height="150" />
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=weliuliu123-byte&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" height="150" />

</div>

---

<div align="center">
  <sub>Thiết kế tinh gọn • Tập trung vào chất lượng kỹ thuật vi mạch & phần cứng số</sub>
</div>
