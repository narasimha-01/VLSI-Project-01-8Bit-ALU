# 🔥 8-Bit Arithmetic Logic Unit (ALU) using Verilog

## 📌 Project Overview

This project implements an **8-bit Arithmetic Logic Unit (ALU)** using Verilog HDL and verifies its functionality through simulation in Xilinx Vivado.

The ALU is one of the fundamental building blocks of a processor. It performs arithmetic and logical operations based on the control input (`sel`).

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

## 📂 Project Structure

```
ALU-8Bit-Verilog/
│
├── alu.sv
├── alu_tb.sv
│
├── screenshots/
│   ├── alu_code.png
│   ├── testbench_code.png
│   ├── waveform.png
│   └── rtl_schematic.png
│
└── README.md
```

---

## 🧪 Verification

A dedicated testbench was created to verify all ALU operations.

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
(Add RTL Screenshot Here)

### Testbench
(Add Testbench Screenshot Here)

### Simulation Waveform
(Add Waveform Screenshot Here)

### RTL Schematic
(Add RTL Schematic Screenshot Here)

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

- Verilog HDL Coding
- Combinational Logic Design
- Testbench Development
- Functional Verification
- Simulation Debugging
- Vivado Design Flow

---

## 👨‍💻 Author

**Narasimha Lakkimsetty**

B.Tech Electronics & Communication Engineering (ECE)

Interested in:
- VLSI Design
- Design Verification
- FPGA Development
- Embedded Systems

---

⭐ If you found this project useful, feel free to star the repository.
