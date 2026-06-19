<div align="center">

# Jawad Saied Ahmed

**B.Sc. Electrical Engineering · Tel Aviv University**  
RTL design · FPGA bring-up · full-custom VLSI · analog circuits

[![Portfolio](https://img.shields.io/badge/Portfolio-jawad--saied--ahmed.netlify.app-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://jawad-saied-ahmed.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jawadsaidahmed-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jawadsaidahmed)
[![GitHub](https://img.shields.io/badge/GitHub-jawadsa02-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jawadsa02)

![banner](assets/banner.svg)

</div>

---

## About

I work across the full silicon stack — from transistor-level analog sizing and custom layout, through RTL and formal verification, to FPGA bring-up on real hardware.

Most of my digital work follows the same habit: write synthesizable RTL, prove it with self-checking testbenches, gate it with CI, and only then integrate it into a larger block. The repos below are split by project so each one tells a clear story on its own.

```mermaid
flowchart LR
    A[Analog sizing<br/>OTA · 7 specs] --> B[Custom layout<br/>ALU · DRC/LVS]
    B --> C[RTL + formal DV<br/>FIFO · UART]
    C --> D[Subsystem integration<br/>Buffered UART]
    D --> E[FPGA bring-up<br/>DLX on Cmod A7]
```

## Projects

| | Repository | What you'll find | CI |
|:---:|---|---|:---:|
| 1 | [**uart-buffered-subsystem**](https://github.com/jawadsa02/uart-buffered-subsystem) | Three verified blocks wired into one UART with FIFO buffering | ![CI](https://github.com/jawadsa02/uart-buffered-subsystem/actions/workflows/ci.yml/badge.svg) |
| 2 | [**sync-fifo-verified**](https://github.com/jawadsa02/sync-fifo-verified) | Synchronous FIFO — simulated, formally proven, synthesis-gated | ![CI](https://github.com/jawadsa02/sync-fifo-verified/actions/workflows/ci.yml/badge.svg) |
| 3 | [**dlx-fpga-resa-bringup**](https://github.com/jawadsa02/dlx-fpga-resa-bringup) | DLX processor migration to Artix-7, UART RTL, hardware validation | ![CI](https://github.com/jawadsa02/dlx-fpga-resa-bringup/actions/workflows/ci.yml/badge.svg) |
| 4 | [**alu-vlsi-gpdk45**](https://github.com/jawadsa02/alu-vlsi-gpdk45) | Full-custom ALU in Virtuoso — Knowles adder, layout, clean signoff | — |
| 5 | [**ota-analog-design**](https://github.com/jawadsa02/ota-analog-design) | OTA meeting seven simultaneous specs (100/100 course grade) | — |
| 6 | [**ai-verification-copilot**](https://github.com/jawadsa02/ai-verification-copilot) | AI-assisted RTL verification — golden model, scoreboard, coverage, fault injection | ![CI](https://github.com/jawadsa02/ai-verification-copilot/actions/workflows/ci.yml/badge.svg) |

## Skills

![skills](assets/skills.svg)

| Area | Tools | Backed by |
|---|---|---|
| RTL | Verilog, FSM design, Verilator lint | [UART](https://github.com/jawadsa02/dlx-fpga-resa-bringup), [FIFO](https://github.com/jawadsa02/sync-fifo-verified) |
| Verification | Self-checking TBs, scoreboards, SymbiYosys, z3 | [FIFO proofs](https://github.com/jawadsa02/sync-fifo-verified), [AI co-pilot](https://github.com/jawadsa02/ai-verification-copilot) |
| FPGA | Vivado 2024.2, Artix-7, USB-UART host link | [DLX bring-up](https://github.com/jawadsa02/dlx-fpga-resa-bringup) |
| Physical design | Virtuoso, DRC/LVS, Yosys synthesis | [ALU flow](https://github.com/jawadsa02/alu-vlsi-gpdk45) |
| Analog | OTA/op-amp, gm/ID sizing, SPICE | [OTA design](https://github.com/jawadsa02/ota-analog-design) |
| Infra | GitHub Actions, Make, Python/C host tools | Lint → sim → synth → formal on every RTL push |

## Education

**Tel Aviv University** — B.Sc. Electrical Engineering (2026)

Analog Electronic Circuits **100** · Electronic Devices **92** · Physics 2 **91** · Computer Architecture **88** · Digital Electronic Circuits **86** · Intro to VLSI **83**

## Languages

Arabic (native) · Hebrew (fluent) · English (fluent)

---

<div align="center">

*Open an issue or reach out on LinkedIn if you'd like to walk through any of the designs.*

</div>
