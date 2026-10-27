<div align="center">

# Ha Gia Bao (Bao Ha)

**Undergraduate in Integrated Circuit (IC) Design • FPT University**  
*Ho Chi Minh City, Vietnam*

[![Email](https://img.shields.io/badge/Email-weliuliu123%40gmail.com-0078D4?style=flat&logo=gmail&logoColor=white)](mailto:weliuliu123@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-weliuliu123--byte-181717?style=flat&logo=github&logoColor=white)](https://github.com/weliuliu123-byte)
[![Major](https://img.shields.io/badge/Major-Integrated%20Circuit%20Design-0052CC?style=flat)](https://hcmuni.fpt.edu.vn/)

---

</div>

## 📌 About Me

Hi there! I am **Gia Bao**, an undergraduate student majoring in **Integrated Circuit (IC) Design** at **FPT University**, Ho Chi Minh City.

- 🎯 **Academic Focus:** My coursework and self-study center around **Digital Logic & RTL Design** using Verilog HDL, digital computer architecture, and FPGA simulation.
- ⚙️ **Hardware-Software Bridge:** In addition to RTL design, I enjoy learning about embedded systems, specifically how low-level software interacts with hardware through Linux device drivers, POSIX real-time threads, and microcontroller firmware.
- 🤝 **Teamwork:** I regularly collaborate on digital design coursework and FPGA projects with my peer [@ntue2719-commits](https://github.com/ntue2719-commits).

---

## 🛠️ Technical Skills & Tools

| Area | Technologies & Tools |
| :--- | :--- |
| **HDL & RTL Design** | `Verilog HDL` • `SystemVerilog` basics • Datapath & Controller (FSM) modeling • Structural & Behavioral modeling • Pipelining concepts • Functional Testbenches |
| **EDA & Simulation** | `ModelSim / QuestaSim` • `Xilinx Vivado` • `GTKWave` • `Icarus Verilog` |
| **Programming Languages** | `C (C99/C11)` • `C++` • `Python` (data logging & scripts) • `Bash` |
| **Embedded & HW/SW Interfacing** | Linux character drivers (basic `file_operations`, `unlocked_ioctl`) • POSIX Real-Time APIs (`SCHED_FIFO`, `mlockall`, Mutexes) • ESP32 firmware • `KiCad` (Schematic capture & 2-layer PCB layout) |
| **Development Environment** | `Linux (Ubuntu)` • `Git / GitHub` • `QEMU` (ARMv7-A Cortex-A9 emulation) • `GDB` |

---

## 📂 Selected Coursework & Collaborative Projects

### 🖼️ [image-dsp-benchmark](https://github.com/ntue2719-commits/image-dsp-benchmark) *(Collaborative project with [@ntue2719-commits](https://github.com/ntue2719-commits))*
*RTL simulation of a 2D spatial image filtering accelerator in Verilog on FPGA.*
- Implemented a 3×3 sliding window architecture coupled with dual line buffers to handle streaming pixel data.
- Verified functional correctness and synthesis behavior across parameterized kernel sizes.

### ⚡ [secDED-bpsk-fpga](https://github.com/ntue2719-commits/secDED-bpsk-fpga) *(Collaborative project with [@ntue2719-commits](https://github.com/ntue2719-commits))*
*Digital communication and error-correction design for FPGA.*
- Designed the Datapath RTL module implementing Hamming (7,4) and extended (8,4) Single Error Correction, Double Error Detection (SEC-DED).
- Integrated with a baseband BPSK modulation/demodulation pipeline and verified using self-checking testbenches.

### 🧮 [fpu32-ieee754-lite](https://github.com/ntue2719-commits/fpu32-ieee754-lite) & [cnn-mnist-q44](https://github.com/ntue2719-commits/cnn-mnist-q44)
*Arithmetic and neural network hardware building blocks in Verilog.*
- **FPU-32:** Verilog implementation of an IEEE-754 32-bit single-precision floating-point adder/subtractor covering exponent alignment, normalization, rounding, and exception flag handling.
- **CNN-MNIST:** Coursework hardware model exploring fixed-point Q4.4 quantized arithmetic for digit classification logic on FPGA.

### 🐧 [Embedded Linux Systems (LOS)](https://github.com/weliuliu123-byte/LOS)
*Comprehensive coursework repository for Embedded Linux Systems (LOS201) on emulated ARM Cortex-A9 (QEMU `vexpress-a9`).*
- Practiced configuring Linux 5.10 LTS kernel, packaging BusyBox rootfs, and setting up U-Boot bootloader arguments.
- Wrote character device drivers implementing user/kernel memory safety (`copy_to_user`/`copy_from_user`) and `ioctl` control commands.
- Developed a multi-threaded POSIX sensor monitoring daemon with real-time scheduling (`SCHED_FIFO`) and clean heap memory management verified via Valgrind.

### 🌡️ Cold Chain Monitoring System *(Student Research Project)*
*Microcontroller-based environmental regulation system.*
- Designed a custom 2-layer PCB in KiCad incorporating an ESP32 microcontroller, power regulator, sensor headers, and MOSFET fan driver.
- Implemented feedback fan control with hysteresis debouncing to maintain stable temperature ranges.

---

<div align="center">
  <sub>Open to discussions, learning opportunities, and feedback • Feel free to connect via email!</sub>
</div>
