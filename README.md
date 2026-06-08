<div align="center">

![banner](banner.svg)

# Jawad Saied Ahmed

**Electrical Engineering Graduate · Tel Aviv University**
*Digital Hardware Design · VLSI · Analog Circuit Design*

[![Portfolio](https://img.shields.io/badge/Portfolio-jawad--saied--ahmed.netlify.app-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://jawad-saied-ahmed.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jawadsaidahmed-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jawadsaidahmed)
[![Email](https://img.shields.io/badge/Email-jawadsa02%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jawadsa02@gmail.com)

</div>

---

## 🎯 About Me

B.Sc. Electrical Engineering at **Tel Aviv University**, specializing in the **full VLSI design flow** — from RTL and logic design through schematic capture, full-custom layout, and silicon-aware verification.

- 🔬 Hands-on with **RTL design & FPGA bring-up** (Verilog, Vivado, Artix-7)
- 🧩 **Full-custom VLSI** in Cadence Virtuoso (schematic → floorplan → layout → DRC/LVS)
- 📈 **Analog design** meeting 7 simultaneous specs — *100/100 in Analog Electronic Circuits*
- 💼 Available immediately for **chip design / design verification / chip bring-up** roles

## 🚀 Featured Projects

| Project | Domain | Stack | Highlights |
|---|---|---|---|
| **[DLX Microprocessor on FPGA](https://github.com/jawadsa02/dlx-fpga-resa-bringup)** | RTL · Bring-up | Verilog, Vivado 2024.2, Artix-7 (Cmod A7) | Led bring-up on a new FPGA platform; migrated ISE 14.x → Vivado; designed I/O & bus control; validated with ACSL Labs 1–7 |
| **[ALU — Full-Custom VLSI](https://github.com/jawadsa02/alu-vlsi-gpdk45)** | VLSI · Layout | Cadence Virtuoso, gpdk45 | Knowles adder, registers & subtractor from gate-level schematic to layout; clean **DRC + LVS** |
| **[OTA Analog Amplifier](https://github.com/jawadsa02/ota-analog-design)** | Analog | Cadence Virtuoso, SPICE | Met **7 simultaneous specs** (gain, BW, GBW, phase margin, power, settling) via transistor-sizing iteration |
| **[Triple-Verified FIFO](https://github.com/jawadsa02/sync-fifo-verified)** | RTL · Formal DV | SymbiYosys, z3, Yosys, Icarus | Simulated (994 checks), **formally proven** (data integrity, no overflow), synthesis-gated — 4-job CI |
| **[Buffered UART Subsystem](https://github.com/jawadsa02/uart-buffered-subsystem)** | System Integration | Verilog, Yosys, Icarus | **Composes** uart_tx + uart_rx + 2× sync_fifo into one subsystem; end-to-end verified (12 bytes through the full pipeline) |

## 🛠️ Technical Skills — every skill links to public proof

![skills](skills.svg)

| Domain | Stack | Proven in |
|---|---|---|
| **RTL Design** | ![Verilog](https://img.shields.io/badge/Verilog-RTL-1ABC9C?style=flat-square) ![FSM](https://img.shields.io/badge/FSM-design-1ABC9C?style=flat-square) ![Lint](https://img.shields.io/badge/Verilator-lint--clean-2ECC71?style=flat-square) | [UART TX/RX](https://github.com/jawadsa02/dlx-fpga-resa-bringup), [FIFO](https://github.com/jawadsa02/sync-fifo-verified) — lint-clean, synthesizable |
| **Verification (DV)** | ![SVA](https://img.shields.io/badge/Self--checking-testbenches-8957e5?style=flat-square) ![Formal](https://img.shields.io/badge/SymbiYosys-formal%20proofs-8957e5?style=flat-square) ![z3](https://img.shields.io/badge/z3-SMT-8957e5?style=flat-square) | [FIFO formal proofs](https://github.com/jawadsa02/sync-fifo-verified) — data integrity *proven*, scoreboards, 1000+ checks |
| **FPGA & Bring-up** | ![Vivado](https://img.shields.io/badge/AMD%20Vivado-2024.2-E74C3C?style=flat-square) ![Artix7](https://img.shields.io/badge/Artix--7-Cmod%20A7-9B59B6?style=flat-square) ![UART](https://img.shields.io/badge/USB--UART-host%20link-9B59B6?style=flat-square) | [DLX bring-up](https://github.com/jawadsa02/dlx-fpga-resa-bringup) — ISE→Vivado migration, validated on hardware (ACSL Labs 1–7) |
| **VLSI / Physical** | ![Virtuoso](https://img.shields.io/badge/Cadence-Virtuoso-DA1710?style=flat-square) ![DRC](https://img.shields.io/badge/DRC%2FLVS-clean-2ECC71?style=flat-square) ![Synth](https://img.shields.io/badge/Yosys-synthesis-3498DB?style=flat-square) | [ALU full-custom flow](https://github.com/jawadsa02/alu-vlsi-gpdk45) — schematic→layout→signoff, 33 documented figures |
| **Analog** | ![OTA](https://img.shields.io/badge/OTA%2FOp--amp-design-F39C12?style=flat-square) ![SPICE](https://img.shields.io/badge/SPICE-simulation-F39C12?style=flat-square) ![gmid](https://img.shields.io/badge/Transistor-sizing-F39C12?style=flat-square) | [7-spec OTA](https://github.com/jawadsa02/ota-analog-design) — 100/100 course grade |
| **Engineering Infra** | ![CI](https://img.shields.io/badge/GitHub%20Actions-4--stage%20CI-2088FF?style=flat-square) ![Git](https://img.shields.io/badge/Git-workflow-F05032?style=flat-square) ![Python](https://img.shields.io/badge/Python-tooling-3776AB?style=flat-square) ![C](https://img.shields.io/badge/C-embedded-555?style=flat-square) | Every repo: lint → sim → synthesis → formal on each push |

> The difference from a typical skills list: each row is **verifiable** — click through and read the code, the testbench, or the proof.

## 🎓 Education

**Tel Aviv University** — B.Sc. Electrical Engineering *(2026)*
Top coursework: Analog Electronic Circuits **(100)** · Electronic Devices **(92)** · Physics 2 **(91)** · Computer Architecture **(88)** · Digital Electronic Circuits **(86)** · Intro to VLSI **(83)**

## 🌐 Languages

Arabic (native) · Hebrew (fluent) · English (fluent)

---

<div align="center">

*“From transistor sizing to processor bring-up — I design across the full stack of silicon.”*

</div>
