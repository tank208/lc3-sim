# LC3-Sim

A minimal LC-3 simulator written in Python for Linux.  
This project aims to provide a simple, offline-compatible LC-3 virtual machine to support CS students and instructors who use Linux-based systems and cannot run official LC-3 tools built for Windows.

## Purpose

This simulator was created to address the lack of LC-3 support for Linux users in academic environments. The goal is to:

- Simulate LC-3 core instructions and control flow
- Run `.obj` files generated from LC-3 assembly code
- Provide a clean command-line interface with step/run modes
- Support key TRAP routines: x21, x22, x23, x25

## Project Status

This project is under initial development and is not yet usable.  
Expected development will begin after Spring 2025 semester.

## Planned Features

- CPU model with 8 registers, PC, and condition flags
- Memory-mapped RAM and I/O registers
- Instruction decode/execute loop
- Basic TRAP routines (GETC, OUT, PUTS, HALT)
- Command-line interface (step, run, inspect)
- Unit tests

## Getting Started

```bash
git clone git@github.com:tank208/lc3-sim.git
cd lc3-sim
python3 -m venv venv
source venv/bin/activate
# requirements.txt will be added when dependencies are introduced
