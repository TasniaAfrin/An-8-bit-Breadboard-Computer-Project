# Project-An-8-bit-Breadboard-Computer
An 8-bit computer designed and built entirely from discrete logic components on breadboards, inspired by Ben Eater’s “Build an 8-bit computer from scratch” series.
This project demonstrates the fundamental principles of computer architecture, digital logic, and low-level system design.

📌 Overview

This project implements a fully functional 8-bit CPU capable of executing simple programs using a custom instruction set.
All components—registers, ALU, control logic, and memory—were constructed using TTL logic ICs, without microcontrollers or programmable devices.

The primary goal was to gain hands-on understanding of:

How computers work at the hardware level

Data flow and control flow inside a CPU

Clocked digital systems and timing

Instruction decoding and micro-operations

🧱 System Architecture

The computer consists of the following major modules:

Clock Module – Provides adjustable clock pulses for manual and automatic execution

Registers – A, B, Instruction Register (IR), Output Register

Arithmetic Logic Unit (ALU) – Performs 8-bit addition and subtraction

Program Counter (PC) – Tracks the address of the next instruction

RAM Module – Stores program instructions and data

Control Unit – Generates control signals using combinational logic and a microcode ROM

Bus System – Shared 8-bit data bus connecting all modules

🧪 Testing & Verification

Individual modules were verified using manual clock pulses

LED indicators were used to visualize register values and bus states

Step-by-step instruction execution ensured correct micro-operations

📚 References

Ben Eater – Build an 8-bit computer from scratch
https://eater.net/8bit

Digital Design textbooks and lecture materials

Datasheets of 74xx series TTL ICs
