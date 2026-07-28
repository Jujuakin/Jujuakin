# Hi, I'm Juju 👋

**EE grad student at the University of Ottawa (MEng '28) — Digital VLSI, RTL Design, and AI hardware.**

My work spans the RTL-to-GDS stack: writing synthesizable SystemVerilog, running physical design flows through Cadence and OpenLane2, and verifying designs in simulation. I'm particularly interested in AI accelerator architecture and in the tooling that makes open-source silicon practical.

Currently targeting roles in **design verification, digital design, and physical design** at AI chip companies.

**HDLs:** ![SystemVerilog](https://img.shields.io/badge/SystemVerilog-IEEE%201800-0057B7?style=flat-square) ![Verilog](https://img.shields.io/badge/Verilog-HDL-0057B7?style=flat-square)  
**EDA:** ![Cadence Genus](https://img.shields.io/badge/Cadence-Genus%20%26%20Innovus-DC143C?style=flat-square) ![OpenLane2](https://img.shields.io/badge/OpenLane2-Open%20PDK-2ECC40?style=flat-square) ![Yosys](https://img.shields.io/badge/Yosys-Synthesis-2ECC40?style=flat-square) ![ModelSim](https://img.shields.io/badge/ModelSim-Simulation-9B59B6?style=flat-square) ![Quartus](https://img.shields.io/badge/Quartus%20Prime-FPGA-0078D4?style=flat-square)  
**Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TCL](https://img.shields.io/badge/TCL-EDA%20Scripting-E86533?style=flat-square) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

## Projects

### 🔲 [32-Bit ALU — Full RTL-to-GDS on 45nm CMOS](https://github.com/Jujuakin/32-Bit-ALU)
Hierarchical 32-bit ALU supporting 14 operations, taken through a complete VLSI flow: RTL → synthesis (Cadence Genus) → place & route (Cadence Innovus) → clock tree synthesis → static timing signoff → DRC/LVS-clean GDS-II with pad frame and I/O ring. Two implementations benchmarked: structural (1,412 μm², 70.76 ns) vs. behavioral (1,524 μm², 60.96 ns).

`SystemVerilog` `Cadence Genus` `Cadence Innovus` `45nm CMOS` `VLSI`

---

### ⚡ [RISC-V RV32IM\_Zicsr Processor](https://github.com/Jujuakin/riscv-3stage)
3-stage pipelined RISC-V core in SystemVerilog. Started as a base RV32I implementation with hazard detection, stalling, and operand forwarding, verified with 29 directed tests across 5 programs in ModelSim. Since extended with the M-extension (MUL/DIV/REM), a CSR file, a custom assembler, and a reference ISS, verified with four self-checking programs. Yosys netlist generated; OpenLane2 hardening on SKY130 in progress.

`SystemVerilog` `Yosys` `RISC-V` `Icarus Verilog` `ModelSim`

---

### 🔥 [EFDS — AI Wildfire Detection System](https://github.com/Jujuakin/EFDS)
Capstone project (ENG 4000, A+): CNN-based wildfire detection on NASA satellite imagery, with a Flask backend and a near-real-time alert system. Reached **88.74% classification accuracy** against an 85% project requirement, validated across 115,214 samples. My contribution was the CNN training pipeline and the preprocessing workflow.

`Python` `TensorFlow` `Keras` `Flask` `CNN`

---

### 🕹️ [FPGA Pong — Hardware Game on DE10-Lite](https://github.com/Jujuakin/Pong-Game)
Two-player Pong in pure RTL — no CPU. VGA rendering at 640×480@60Hz, ADXL345 accelerometer paddle control via SPI, 7-segment scoreboard. 1,789 LEs (4% of MAX10), Fmax 80.73 MHz.

`SystemVerilog` `FPGA` `Quartus` `VGA` `SPI` `DE10-Lite`

---

## Skills

| Domain | Tools & Technologies |
|---|---|
| RTL Design | SystemVerilog, Verilog (IEEE 1800) |
| Verification | SystemVerilog testbenches, directed & constrained-random testing, functional coverage, UVM (learning) |
| Synthesis | Cadence Genus, Yosys, OpenLane2 |
| Physical Design | Cadence Innovus, place & route, CTS, DRC/LVS, GDS-II |
| Simulation | ModelSim, Icarus Verilog, GTKWave |
| FPGA | Intel Quartus Prime, DE10-Lite (MAX10) |
| Open Silicon | OpenLane2, SKY130 PDK |
| ML / Python | TensorFlow, Keras, NumPy, Flask |
| Processes | 45nm GPDK CMOS (Cadence) · SKY130 (open PDK) |

---

## Currently Working On

- **UVM testbench** for the 32-bit ALU — building up driver, monitor, scoreboard, and functional coverage
- **OpenLane2 setup** for RTL-to-GDS flows on SKY130 (RISC-V core hardening)
- **RV32IM\_Zicsr pipeline** — extending toward a MAC instruction for neural network workloads
- **Open-source contribution** — scoping a good-first-issue in OpenLane2 or Yosys

---

## Education

**University of Ottawa** — MEng Electrical & Computer Engineering, VLSI & Digital Systems, expected 2028  
**York University (Lassonde)** — BEng (Honours) Electrical Engineering, 2025

---

## Contact

📧 jujuakinsalami@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/eyinojuoluwa-akin-salami)  
🐙 [GitHub](https://github.com/Jujuakin)
