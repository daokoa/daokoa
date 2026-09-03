# Hi, I'm Dao

Third-year **Computer Engineering** student at **UC Irvine** (B.S., June 2028), focused on
**embedded systems and firmware** — the layer where software meets real hardware.

I learn by building real systems, breaking them, and then finding out *why* they broke.

---

## What I'm working on

**[SoleSense](https://github.com/daokoa/SoleSense2026)** — a 3D-printed smart running insole that
runs full gait analysis **on-device**, with no app, no cloud, and no internet. Primary firmware
and software contributor on an 11-person UCI capstone team.

- **500 Hz hardware-timer loop** in C++ scanning a six-FSR matrix across three ADC pins, with
  Schottky isolation to prevent cross-channel leakage
- **MPU-6050 IMU over I²C** with FSR-only fallback when the IMU is absent
- Streaming DSP: **incremental Goertzel DFT** (1024-sample window, 0.49 Hz bins), Welford running
  statistics, top-N outlier heap
- **CRC-protected flash storage** with a 10-slot ring buffer so runs survive Wi-Fi drops and
  power loss
- Serves its results over the device's **own Wi-Fi access point**

**Project Dynamo @ Handshake** *(contract)* — I author evaluation tasks for autonomous coding
agents, shipped as **digest-pinned Docker images** with reference solutions overlaid only at
verify time so ground truth stays unreachable by the agent under test.

- Built a **deterministic transaction-level DMA/UART simulator** that replays fixed completion and
  byte schedules to expose an ISR/shared-memory race under sustained load
- Repairs cover atomic DMA descriptor capture, interrupt-safe ring-buffer snapshots, and bounded
  interrupt masking against a hard timing budget
- I pre-register difficulty predictions, then measure them against solver panels — and I've killed
  my own task premise when running the code disagreed with the spec

**UCI Theta Tau, Pi Delta** — Director of Web Development. Built and shipped the chapter's 7-page
site in Astro, TypeScript and React, with content in typed data files so non-engineers can update
it without touching component code.

---

## Technical Skills

**Languages** — C++, C, Python, Verilog, TypeScript, JavaScript, SQL

**Embedded** — ESP32-C3, I²C, ADC, hardware timers, interrupts, DMA/UART, ISR-safe shared state,
sensor fusion, DSP, flash/NVS, deep sleep

**Tools & Verification** — Git, GitHub Actions, Docker, Linux, golden-file verification, unit
testing, RTL simulation

**Hands-on** — soldering and PCB rework, continuity testing, multimeter and POST-card diagnostics,
15+ custom mechanical keyboard builds, 10+ custom PC builds

---

## What I'm learning next

Bare-metal STM32 without the Arduino layer · RTOS scheduling and priority inversion ·
measuring what I've built with a logic analyzer instead of assuming it works

---

## Outside of engineering

Pokémon card collector (the market data is genuinely fun to model) · Valorant · anime and manga ·
dry sense of humor, and always down to collaborate.

---

## Let's connect

[![Email](https://img.shields.io/badge/Email-daogdoan%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daogdoan@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dao--doan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dao-doan)
