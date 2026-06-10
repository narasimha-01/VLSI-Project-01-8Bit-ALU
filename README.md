# 🔥 8-Bit Arithmetic Logic Unit (ALU) using Verilog

## 📌 Project Overview

This project implements an **8-Bit Arithmetic Logic Unit (ALU)** using Verilog HDL and verifies its functionality using a custom testbench in Xilinx Vivado.

The ALU is one of the core building blocks of a processor. It performs arithmetic and logical operations based on a control signal (`sel`).

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

```text
VLSI-Project-01-8Bit-ALU
│
├── alu.sv
├── alu_tb.sv
├── README.md
│
└── screenshots
    ├── alu_code.png
    ├── testbench_code.png
    ├── waveform.png
    └── rtl_schematic.png
```

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

![RTL Design](screenshots/alu_code.png)

### Testbench

![Testbench](screenshots/testbench_code.png)

### Simulation Waveform

![Waveform](screenshots/waveform.png)

### RTL Schematic

![RTL Schematic](screenshots/rtl_schematic.png)

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

- Add Carry-Out Flag
- Add Zero Flag
- Add Overflow Detection
- Parameterized ALU Design
- SystemVerilog Verification Environment

---

## 👨‍💻 Author

**Narasimha Lakkimsetty**

B.Tech Electronics and Communication Engineering (ECE)

Interested in:
- VLSI Design
- Design Verification
- FPGA Development
- Embedded Systems

### Connect with Me

- LinkedIn: www.linkedin.com/in/lakshminarasimhaswamy
- GitHub: https://github.com/narasimha-01

---

⭐ If you found this project useful, consider giving it a star.
