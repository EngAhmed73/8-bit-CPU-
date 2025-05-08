# 8-bit CPU Design using Logisim

## Overview
This project is an 8-bit CPU designed and built using **Logisim** as part of a course project for *CMPE263 - Computer Architecture and Organization I* at Qatar University.

The CPU includes the following components:
- ALU (Arithmetic Logic Unit)
- Register File
- ROM (for instructions)
- RAM (for data storage)
- Control Unit
- Multiplexers and other supporting logic

## Features
- Executes a custom instruction set architecture (ISA)
- Supports arithmetic operations like ADD, SUB, AND, OR, XOR, etc.
- Includes register-to-register and memory-based instructions
- Basic control logic for instruction fetching, decoding, and execution

## How to Run
1. Open the project `.circ` file in **Logisim**.
2. Uploade the date files to the ROM (that depends in your program whether your program includes JMP operation or not )
3. **Click on the clock** component to simulate instruction execution.
   - Each click represents one clock cycle.
   - You can observe the CPU execution in steps through the datapath.

## Instruction Set
The CPU supports a custom 8-bit instruction set with the following format:
- **Opcode (3 bits)** | **Reg A (2 bits)** | **Reg B (2 bits)** | **Unused (1 bit)**

Example Instructions:
- `000` – ADD
- `001` – SUB
- `010` – AND
- `011` – OR
- `100` – XOR
- `101` – LOADI
- `110` – STORE
- `111` – LOAD

- #sample programs to run using this CPU 
- ![image](https://github.com/user-attachments/assets/dcb762e5-ab0e-4aed-8b98-21512f10aaf8)


## File Structure
- `CPU.circ` – Main Logisim circuit file
- `README.md` – This file
- `report.pdf` – Full documentation and architecture description

- #

## Author
This project was developed by students of Qatar University  incuding me as part of the CMPE263 course.

---

