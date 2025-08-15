<!-- Banner -->
<p align="center">
  <img src="assets/banner_vlsi_asic.png" alt="Suyash Ghadage | VLSI • ASIC • Embedded Systems" width="100%" />
</p>

<h1 align="center">Hi, I'm Suyash 👋</h1>
<p align="center">
  <b>Digital & Mixed-Signal Design</b> • <b>ASIC Design & Verification</b> • <b>Low-Power & Timing</b> • <b>Embedded Systems</b>
</p>

<p align="center">
  <a href="mailto:suyash.ghadage@example.com">Email</a> •
  <a href="https://www.linkedin.com/in/suyash-ghadage77/">LinkedIn</a> •
  <a href="https://github.com/suyash-ghadage77">GitHub</a>
</p>

---

## Spotlight: ASIC-Based Smart Digital Lock (Open-Source RTL→GDSII)
A silicon-to-system project implementing a secure FSM-based digital lock, designed with the open-source flow and SKY130 PDK, with FPGA/CPLD prototyping and custom PCB.

- Flow: Verilog/SystemVerilog → Icarus + GTKWave → Yosys (synth) → OpenROAD (P&R) → Magic/KLayout/Netgen (DRC/LVS) → GDSII
- Features: 4-digit keypad, secure FSM lock/unlock, alarm on incorrect attempts, RFID/IoT/biometric expansion
- Hardware: CPLD/FPGA (Xilinx/Altera), keypad, buzzer, relay, LEDs, debug headers
- Key wins: Timing closure, clean DRC/LVS, fabrication-ready GDSII, PCB bring-up

<p align="center">
  <img src="assets/asic_lock_flow.png" alt="ASIC Smart Lock Flow" width="85%"/>
</p>

> Repos: 
> - RTL & Verification: ./projects/asic-smart-lock/rtl  
> - Flow Scripts: ./projects/asic-smart-lock/flow  
> - PCB & Schematics: ./projects/asic-smart-lock/hardware

---

## What I Do
- VLSI/ASIC: RTL coding, SystemVerilog testbenches, synthesis, STA, floorplanning, P&R, DRC/LVS, ECOs
- Verification: Assertions, coverage-driven verification, ModelSim/Verilator, UART/FIFO/Protocol IP verification
- Embedded/IoT: ARM/ESP32/8051, UART/SPI/I2C/CAN, MQTT/HTTP, cloud dashboards (ThingSpeak/Azure/AWS IoT)
- PCB: Schematic → layout → routing → Gerbers in KiCad/EasyEDA/OrCAD/Eagle

---

## Highlights
- 100% functional coverage in UART verification with zero assertion failures
- Designed synchronous FIFO and validated timing + functionality on FPGA
- Built RFID-enabled IoT billing system reducing processing time by 70% 
- Silver Medalist (ENTC), 1st rank for six consecutive semesters; GPA: 9.21/10
- 1,600+ hours of GATE ECE preparation across core electronics

---

## Tech Stack
- Languages: Verilog, SystemVerilog, Embedded C, Python
- EDA: Yosys, OpenROAD, Magic, KLayout, OpenSTA, TritonRoute, FastRoute, Vivado, ModelSim
- Embedded/IoT: STM32, ESP32, 8051, FreeRTOS, MQTT/HTTP
- PCB: KiCad, EasyEDA, OrCAD, Eagle
- Tooling: Git/GitHub, Linux, CMake, Bash

<p align="left">
  <img src="assets/icons_verilog.svg" height="28" />
  <img src="assets/icons_systemverilog.svg" height="28" />
  <img src="assets/icons_yosys.svg" height="28" />
  <img src="assets/icons_openroad.svg" height="28" />
  <img src="assets/icons_magic.svg" height="28" />
  <img src="assets/icons_klayout.svg" height="28" />
  <img src="assets/icons_vivado.svg" height="28" />
  <img src="assets/icons_models im.svg" height="28" />
  <img src="assets/icons_kicad.svg" height="28" />
  <img src="assets/icons_esp32.svg" height="28" />
</p>

---

## Selected Projects
- ASIC-Based Smart Digital Lock (SKY130, OpenROAD, Magic, KLayout, Netgen)  
  RTL, verification, synthesis, P&R, DRC/LVS, GDSII handoff; PCB for prototyping.  
  Path: projects/asic-smart-lock/
- UART VIP + Coverage  
  SystemVerilog assertions and covergroups; achieved 100% functional coverage.  
  Path: projects/verification/uart_vip/
- Sync FIFO (RTL + FPGA bring-up)  
  FPGA timing closure and on-board validation.  
  Path: projects/rtl/fifo_sync/
- RFID IoT Billing System  
  ESP32 + MQTT + Cloud dashboards; 70% faster processing.  
  Path: projects/iot/rfid_billing/

---

## Metrics & Proof
- Coverage reports: ./reports/coverage/  
- STA summaries: ./reports/sta/  
- DRC/LVS logs: ./reports/signoff/  
- PCB fabrication files: ./hardware/gerbers/  

> Hiring managers: Please see logs and artifacts in the reports/ directory for verification evidence.

---

## Publications, Courses, and Certifications
- VLSI Design Flow: RTL to GDS (NPTEL)
- CMOS Circuit Design & SPICE (SKY130)
- ChatGPT & AI Tools – From Beginner to Expert (Udemy)
- SystemVerilog, Static Timing Analysis, DFT, Python AI

---

## Current Focus
- GATE 2026 prep (Digital, CMOS VLSI, Signals, STA)
- AI-assisted hardware design, open-source silicon, Industry 4.0 systems
- Low-power design, clock-domain crossing, DFT readiness

---

## How I Work
- I maintain clean, reproducible flows with Makefiles and Docker where possible
- I publish reports (coverage/STA/DRC/LVS) for transparency
- I prefer open-source EDA and public documentation to support learning and verifiability

---

## Let’s Collaborate
- Roles: ASIC/Digital Design, Verification Engineer, Physical Design, Embedded/VLSI R&D
- Location: Pune, Maharashtra, India (Open to remote/hybrid/on-site)
- Contact: Email or LinkedIn (links above)

<p align="center">
  <img src="assets/footer_trace.png" alt="VLSI • ASIC • Embedded" width="70%"/>
</p>
