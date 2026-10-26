<div align="center">

# Hà Gia Bảo
**Embedded Linux Systems • Digital IC & FPGA Design • Edge AI / TinyML**

[![Email](https://img.shields.io/badge/Email-weliuliu123%40gmail.com-0078D4?style=flat&logo=gmail&logoColor=white)](mailto:weliuliu123@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-weliuliu123--byte-181717?style=flat&logo=github&logoColor=white)](https://github.com/weliuliu123-byte)
[![Location](https://img.shields.io/badge/Location-Ho%20Chi%20Minh%2C%20Vietnam-555555?style=flat&logo=googlemaps&logoColor=white)](https://maps.google.com)
[![University](https://img.shields.io/badge/University-FPT%20University-F37021?style=flat)](https://hcmuni.fpt.edu.vn/)

---

</div>

## 📌 Executive Summary

Final-year Computer Engineering / Embedded Systems student at **FPT University**, passionate about **Hardware-Software Co-Design**, **Linux Kernel Internals**, and **FPGA Digital Signal Processing**. Experienced in developing custom Linux device drivers, POSIX real-time multithreaded systems, hardware RTL synthesis (Verilog/SystemVerilog), and TinyML algorithms for resource-constrained edge devices.

- 🔭 **Specialization:** Embedded Linux Drivers, POSIX Real-Time Systems (`SCHED_FIFO`), FPGA RTL Design (Datapath/FSM), and TinyML / Edge Computing.
- 🛠️ **Methodology:** Test-Driven Development (TDD), zero-leak memory management (Valgrind), deterministic latency profiling (`cyclictest`), and comprehensive hardware testbenches.
- 🤝 **Collaboration:** Actively collaborating on digital IC design and hardware acceleration with [@ntue2719-commits](https://github.com/ntue2719-commits).

---

## 🛠️ Technical Stack & Toolchain

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | `C (C99/C11)` • `C++` • `Verilog` • `SystemVerilog` • `Python` • `Bash / Shell` • `ARM Assembly` |
| **Kernel & Embedded OS** | Linux Kernel 5.10+ LTS (Character Drivers, `miscdevice`, `unlocked_ioctl`, `sysfs`, `procfs`) • POSIX Real-Time Threads (`SCHED_FIFO`, `mlockall`, Mutexes, POSIX Message Queues) • BusyBox Initramfs • Das U-Boot • QEMU ARMv7 Cortex-A9 (`vexpress-a9`) • FreeRTOS • ESP32 |
| **Digital Design & FPGA** | RTL Architecture • Datapath & FSM Synthesis • SEC-DED Hamming Code • BPSK Modulation/Demodulation • 2D Convolution DSP Accelerators • IEEE-754 FPU • ModelSim • Vivado |
| **Hardware & PCB** | KiCad (Multi-layer PCB Design) • Signal Integrity & EMI Reduction • PWM Power Stages (MOSFET Gate Drivers) • Sensor Interfaces (I2C, SPI, UART, ADC) |
| **Diagnostics & Profiling** | GDB Multiarch • gdbserver • Valgrind Memcheck • `perf` CPU Profiling • `strace` • `cyclictest` (PREEMPT_RT Latency) • Git |

---

## 🚀 Featured Engineering Projects

### 🐧 [Embedded Linux Systems (LOS)](https://github.com/weliuliu123-byte/LOS)
*Comprehensive Embedded Linux coursework & research implementation on ARMv7-A Cortex-A9 (QEMU `vexpress-a9`).*
- **Kernel Bring-Up & Storage:** Built Linux 5.10 LTS kernel with custom U-Boot bootargs, packaged BusyBox rootfs, and integrated MTD NAND Flash emulation with JFFS2.
- **Custom Drivers:** Developed character device drivers with memory safety (`copy_to_user`/`copy_from_user`), mutex synchronization, `unlocked_ioctl` hardware control, and atomic counter devices (`miscdevice` Major 10, `atomic_t`).
- **Real-Time Sensor Monitoring Daemon (Capstone):** Multi-threaded userspace application running 4 POSIX threads (`SCHED_FIFO`, `mlockall`, lockless circular buffer). Achieved **45 µs maximum jitter** (99th percentile) and **0 bytes memory leak** verified via Valgrind.

### ⚡ [secDED-bpsk-fpga](https://github.com/ntue2719-commits/secDED-bpsk-fpga) *(Collaborator: [@ntue2719-commits](https://github.com/ntue2719-commits))*
*FPGA RTL implementation of Single Error Correction Double Error Detection (SEC-DED) and BPSK digital communication.*
- Engineered the complete **Datapath RTL module** and comprehensive verification testbenches.
- Implemented real-time Hamming parity syndrome generation, single-bit error correction, double-bit error flagging, and BPSK baseband modulation/demodulation pipeline.

### 🖼️ [image-dsp-benchmark](https://github.com/ntue2719-commits/image-dsp-benchmark) *(Collaborator: [@ntue2719-commits](https://github.com/ntue2719-commits))*
*Hardware accelerator for 2D spatial image filtering and convolution on FPGA.*
- Designed pipelined 3×3 sliding window architecture with dual line-buffers to sustain single-cycle-per-pixel throughput.
- Optimized for parameterized image dimensions (from 256×256 to 1024×1024) with low resource utilization.

### 🧮 [fpu32-ieee754-lite](https://github.com/ntue2719-commits/fpu32-ieee754-lite) & [cnn-mnist-q44](https://github.com/ntue2719-commits/cnn-mnist-q44)
*Digital IC design blocks in Verilog/SystemVerilog.*
- **FPU-32:** Pipelined IEEE-754 single-precision 32-bit Floating Point Adder/Subtractor handling normalization, rounding, and exception flags.
- **CNN-MNIST:** Fixed-point Q4.4 quantized inference engine for handwritten digit classification directly on hardware.

---

## 📄 Research & Publications

**Design and Experimental Evaluation of a Hybrid K-Means PID Controller for ESP32-Based Cold Chain Monitoring**  
*Nguyen Tri Tue, Le Nhat Nam, **Ha Gia Bao**, Ho Le Minh Toan* — FPT University  
- Proposed **Feedforward Hybrid Layers Control (FHLC)** on the ESP32 platform combining a Macro layer (K-Means Clustering) and Micro layer (PID Controller with 0.5°C hysteresis debouncing).
- **Results:** Achieved **560 s settling time** (18.13% faster than pure PID and 19.77% faster than If-Else), with an average execution time of **23.6 µs** and stable **226 kB SRAM** footprint for In-Sensor TinyML computing.

---

## 📊 GitHub Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=weliuliu123-byte&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" height="150" />
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=weliuliu123-byte&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" height="150" />

</div>

---

<div align="center">
  <sub>Crafted with precision • Open for Embedded Systems & IC Design opportunities</sub>
</div>
