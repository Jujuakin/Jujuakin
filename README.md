# Hi, I'm Emmanuel 👋

**EE grad student at the University of Ottawa (MEng '28) — Digital VLSI, RTL Design, and AI hardware.**

My work spans the full RTL-to-GDS stack: writing synthesizable SystemVerilog, running physical design flows through OpenLane2 and Cadence, and targeting open silicon shuttles. I'm particularly interested in AI accelerator architecture and the tooling that makes open-source silicon practical.

Currently targeting roles in **digital design, DV, and physical design** at AI chip companies.

**HDLs:** ![SystemVerilog](https://img.shields.io/badge/SystemVerilog-IEEE%201800-0057B7?style=flat-square) ![Verilog](https://img.shields.io/badge/Verilog-HDL-0057B7?style=flat-square)  
**EDA:** ![Cadence Genus](https://img.shields.io/badge/Cadence-Genus%20%26%20Innovus-DC143C?style=flat-square) ![OpenLane2](https://img.shields.io/badge/OpenLane2-Open%20PDK-2ECC40?style=flat-square) ![Yosys](https://img.shields.io/badge/Yosys-Synthesis-2ECC40?style=flat-square) ![ModelSim](https://img.shields.io/badge/ModelSim-Simulation-9B59B6?style=flat-square) ![Quartus](https://img.shields.io/badge/Quartus%20Prime-FPGA-0078D6?style=flat-square)  
**Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TCL](https://img.shields.io/badge/TCL-EDA%20Scripting-E86533?style=flat-square) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

## Projects

### 🔲 [32-Bit ALU — Full RTL-to-GDS on 45nm CMOS](https://github.com/Jujuakin/32-Bit-ALU)
Hierarchical 32-bit ALU supporting 14 operations, taken through a complete professional VLSI flow: RTL → synthesis (Cadence Genus) → place & route (Cadence Innovus) → DRC signoff → GDS tape-out. Two implementations benchmarked: structural (1,412 μm², 70.76 ns) vs. behavioral (1,524 μm², 60.96 ns). Clean DRC, zero connectivity errors.

`SystemVerilog` `Cadence Genus` `Cadence Innovus` `45nm CMOS` `VLSI`

---

### ⚡ [RISC-V RV32IM\_Zicsr Processor](https://github.com/Jujuakin/riscv-3stage)
3-stage pipelined RV32IM\_Zicsr core in SystemVerilog — full M-extension (MUL/DIV/REM), CSR file, WB→DE forwarding, custom assembler and reference ISS. Verified end-to-end with four self-checking programs; Yosys netlist generated.

`SystemVerilog` `Yosys` `RISC-V` `Icarus Verilog`

---

### 🔥 [EFDS — AI Wildfire Detection System](https://github.com/Jujuakin/EFDS)
Capstone project: custom CNN (98% accuracy, 97% fire recall) on NASA MODIS satellite imagery, deployed on Google Cloud with a Flask backend and real-time alert system. 7,336-image test set processed in 20 seconds (0.003 s/image).

`Python` `TensorFlow` `Keras` `Flask` `CNN` `Google Cloud`

---

### 🕹️ [FPGA Pong — Hardware Game on DE10-Lite](https://github.com/Jujuakin/Pong-Game)
Two-player Pong in pure RTL — no CPU. VGA rendering at 640×480@60Hz, ADXL345 accelerometer paddle control via SPI, 7-segment scoreboard. 1,789 LEs (4% of MAX10), Fmax 80.73 MHz.

`SystemVerilog` `FPGA` `Quartus` `VGA` `SPI` `DE10-Lite`

---

### 🏭 [TinyTapeout SKY130 Submission](https://github.com/Jujuakin/32-Bit-ALU) *(TTSKY26c — in progress)*
Adapting the 32-bit ALU for the TinyTapeout TTSKY26c shuttle (SKY130, deadline Sept 7 2026). Running OpenLane2 hardening flow and scoping the design to the TT tile I/O interface.

`OpenLane2` `SKY130` `TinyTapeout` `Open Silicon`

---

## Skills

| Domain | Tools & Technologies |
|---|---|
| RTL Design | SystemVerilog, Verilog (IEEE 1800-2012) |
| Synthesis | Cadence Genus, Yosys, OpenLane2 |
| Physical Design | Cadence Innovus, OpenROAD |
| Simulation | ModelSim, Icarus Verilog, GTKWave |
| FPGA | Intel Quartus Prime, DE10-Lite (MAX10) |
| Open Silicon | OpenLane2, SKY130 PDK, TinyTapeout |
| Timing Analysis | OpenSTA, Cadence Tempus |
| ML / Python | TensorFlow, Keras, NumPy, Flask |
| Processes | 45nm GPDK CMOS (Cadence) · SKY130 (open PDK) |

---

## Currently Working On

- **OpenLane2 setup** for RTL-to-GDS flows on SKY130 (RISC-V core + ALU TinyTapeout port)
- **TinyTapeout TTSKY26c** submission — adapting the 32-bit ALU to the SKY130 tile interface
- **RV32IM\_Zicsr pipeline** — extending toward a MAC instruction for neural network workloads and OpenLane2 GDS hardening
- **Open-source contribution** — scoping a good-first-issue in OpenLane2 or Yosys

---

## Education

**University of Ottawa** — MEng Electrical Engineering, expected 2028  
**York University (Lassonde)** — BEng Electrical Engineering

---

## Contact

📧 jujuakinsalami@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/emmanuel-akin-salami)  
🐙 [GitHub](https://github.com/Jujuakin)
