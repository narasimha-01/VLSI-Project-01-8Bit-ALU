# 🔥 8-Bit Arithmetic Logic Unit (ALU) using Verilog

## 📌 Project Overview

This project implements an 8-Bit Arithmetic Logic Unit (ALU) using Verilog HDL and verifies its functionality using a custom testbench in Xilinx Vivado.

The ALU is a fundamental component of digital processors, responsible for performing arithmetic and logical operations based on a control signal (`sel`).

This project was developed as part of my VLSI Design & Verification learning journey.

---

## 🚀 Features

The ALU supports the following operations:

| Select (sel) | Operation |
|-------------|-----------|
| 000 | Addition (A + B) |
| 001 | Subtraction (A - B) |
| 010 | Bitwise AND |
| 011 | Bitwise OR |
| 100 | Bitwise XOR |
| 101 | Bitwise NOT (~A) |
| 110 | Left Shift (A << 1) |
| 111 | Right Shift (A >> 1) |

---

## 🛠️ Tools Used

- Verilog HDL
- Xilinx Vivado 2020.1
- Behavioral Simulation

---

## 📂 Project Files

- `alu.sv` → ALU Design Module
- `alu_tb.sv` → Testbench for Verification

---

## 🧪 Verification

### Test Inputs

```text
A = 20
B = 10
```

### Simulation Results

| Operation | Result |
|------------|---------|
| 20 + 10 | 30 |
| 20 - 10 | 10 |
| 20 AND 10 | 0 |
| 20 OR 10 | 30 |
| 20 XOR 10 | 30 |
| NOT 20 | 235 |
| 20 << 1 | 40 |
| 20 >> 1 | 10 |

All operations were successfully verified through behavioral simulation.

---

## 📸 Screenshots

### RTL Design

![RTL Design](alu_code.png.png)

### Testbench

![Testbench](testbench_code.png.png)

### Simulation Waveform

![Waveform](waveform.png.png)

### RTL Schematic

![RTL Schematic](rtl_schematic.png.png)

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

- Verilog HDL Coding
- Combinational Logic Design
- RTL Development
- Testbench Writing
- Functional Verification
- Simulation and Debugging
- Vivado Design Flow

---

## 🔮 Future Improvements

- Carry-Out Flag
- Zero Flag Detection
- Overflow Detection
- Parameterized ALU Design
- SystemVerilog Testbench

---

## 👨‍💻 Author

**Narasimha Lakkimsetty**

B.Tech Electronics and Communication Engineering (ECE)

### Areas of Interest

- VLSI Design
- Design Verification
- FPGA Development
- Embedded Systems

### Connect with Me

- GitHub: https://github.com/narasimha-01
- LinkedIn: www.linkedin.com/in/lakshminarasimhaswamy

---

⭐ If you found this project useful, consider giving it a star.
