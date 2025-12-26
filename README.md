# EE3067 - Embedded Control Systems Exam Solutions

![University](https://img.shields.io/badge/University-HCMUT-blue) ![Language](https://img.shields.io/badge/Language-C%20%7C%20Verilog-orange) ![Platform](https://img.shields.io/badge/Platform-STM32F4%20%7C%20FPGA-green)

This repository contains my solutions for the final exams of the **Embedded Control Systems (EE3067)** course at **Ho Chi Minh City University of Technology (HCMUT)**.

## Repository Structure

The solutions are organized by academic years and specific exam questions, focusing on:
* **Verilog:** Designing digital logic circuits, counters, and measuring engine speed based on Encoder signals.
* **STM32F4 (C Language):** Memory-mapped I/O, Peripheral configurations (UART, PWM, ADC, Timer), and DMA handling.

## Tech Stack

* **Microcontroller:** STM32F4 Series (ARM Cortex-M4).
* **Hardware Description Language:** Verilog HDL.
* **Protocols:** UART, SPI, I2C, Memory Mapped Interface.
* **Tools:** Keil C / STM32CubeIDE, Quartus II / ModelSim.

## Key Implementations

### 1. Memory Mapped Peripherals (STM32)
Implementation of driver logic to interact with custom hardware peripherals mapped to specific memory addresses (e.g., `0x60000000`).
* Techniques: Pointer arithmetic, `volatile` keyword usage, Bitwise operations.
* *Example:* Handling 32-bit Encoder data splitting into 16-bit bus transfers.

### 2. Digital Design (Verilog)
Verilog modules for processing sensor signals.
* *Example:* Speed measurement logic using Encoder pulses over 4 cycles.

## Disclaimer
This code is for educational reference only. Please use it to understand the logic and logic flow, do not copy-paste directly for your exams.

---
*Author: LvDaengineer*
