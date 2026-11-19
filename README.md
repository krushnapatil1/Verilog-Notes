# Verilog-Notes
# Verilog Learning Repository

Welcome to my **Verilog Learning Repository**! 🚀

This repository contains my learning journey in Verilog HDL, starting from the fundamentals of digital electronics to RTL design and simulation.

The main objective of this repository is to build a strong foundation in Verilog HDL through theoretical notes, practical coding examples, testbenches, and simulation waveforms.

## 📚 Repository Contents

### 1. Digital Electronics
- Number Systems and Number Conversions
- Logic Gates
- Boolean Algebra
- De Morgan's Theorems
- Karnaugh Maps (K-Maps)
- Combinational Circuits
- Sequential Circuits
- Multiplexers and Demultiplexers
- Encoders and Decoders
- Adders and Subtractors
- Flip-Flops and Registers
- Counters and Shift Registers

### 2. Verilog HDL Fundamentals
- Introduction to Verilog HDL
- Verilog Modules and Ports
- Data Types and Data Objects
- Verilog Operators
- Continuous Assignments
- Procedural Blocks (`always`, `initial`)
- Blocking and Non-blocking Assignments
- Conditional Statements
- Case Statements
- Loops in Verilog
- Tasks and Functions
- Parameters and Local Parameters
- Arrays and Memories
- Finite State Machines (FSM)

### 3. Verilog Coding Examples
- Basic Logic Gates
- Half Adder and Full Adder
- Half Subtractor and Full Subtractor
- Multiplexer and Demultiplexer
- Encoder and Decoder
- Comparator
- ALU Design
- Flip-Flops
- Counters
- Shift Registers
- RAM and ROM

### 4. Testbench Development
- Introduction to Testbenches
- Testbench Structure
- Clock Generation
- Reset Generation
- Stimulus Generation
- `$display` and `$monitor`
- `$dumpfile` and `$dumpvars`
- Functional Verification Basics

### 5. Simulation and Waveforms
Each practical design includes:
- Verilog RTL source code
- Testbench
- Simulation output
- Waveform screenshots

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Verilog HDL | Hardware Description Language |
| VS Code | Code Editor |
| Icarus Verilog | RTL Compilation and Simulation |
| GTKWave | Waveform Analysis |
| Questa / ModelSim | HDL Simulation |

## 📂 Repository Structure

```text
Verilog-Learning/
│
├── 01_Digital_Electronics/
│   ├── Notes/
│   └── Diagrams/
│
├── 02_Verilog_Fundamentals/
│   └── Notes/
│
├── 03_Verilog_Programs/
│   ├── Logic_Gates/
│   ├── Adders_Subtractors/
│   ├── MUX_DEMUX/
│   ├── Encoders_Decoders/
│   ├── Comparators/
│   ├── ALU/
│   ├── Flip_Flops/
│   ├── Counters/
│   └── Shift_Registers/
│
├── 04_Testbenches/
│
├── 05_Simulation_Waveforms/
│
└── README.md
```

## 💻 How to Run Verilog Programs

**Step 1:** Clone this repository.

```bash
git clone https://github.com/krushnapatil1/Verilog-Learning.git
```

**Step 2:** Open the project folder in VS Code.

**Step 3:** Compile the Verilog design and testbench.

```bash
iverilog -o output design.v testbench.v
```

**Step 4:** Run the simulation.

```bash
vvp output
```

**Step 5:** Generate and view waveforms using GTKWave.

```bash
gtkwave waveform.vcd
```

## 🎯 Learning Objectives

- Understand digital electronics fundamentals.
- Learn Verilog HDL from basic to intermediate level.
- Develop RTL design skills.
- Understand combinational and sequential logic.
- Gain practical experience in simulation and debugging.
- Develop a foundation for SystemVerilog and Design Verification.

## 📈 My Learning Approach

I believe in learning hardware description languages through practical implementation.

Every concept in this repository is supported by notes, coding examples, testbenches, and simulation results wherever applicable.

## 👨‍💻 Author

**Krushna Gopichand Patil**

- GitHub: [@krushnapatil1](https://github.com/krushnapatil1)
- LinkedIn: [Krushna Patil](https://www.linkedin.com/in/krushnapatil8936/)

**Career Interest:** RTL Design | Design Verification | VLSI Engineering

---

⭐ If you find this repository helpful, don't forget to give it a star!

*Learning Verilog, One Module at a Time!* 🚀
