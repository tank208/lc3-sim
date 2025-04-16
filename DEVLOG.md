# DEVLOG.md – LC3-Sim

**Project:** LC3-Sim  
**Author:** Will Hall  
**Purpose:** A lightweight LC-3 simulator for Linux users in academic environments.  
**Status:** Planning and scaffolding complete. Development scheduled for Summer 2025.

---

## Development Log

### April 2025 – Initial Setup

- Created public GitHub repository with MIT license
- Designed initial Python module structure
- Configured Git and SSH key-based remote access
- Implemented `cpu.py` with register model, PC, and condition flags
- Created project README with project scope and usage
- Verified GitHub rendering and public visibility
- Added DEVLOG.md to document development progress

---

### Planned Milestones – Summer 2025

- Implement `memory.py`: RAM and I/O memory map
- Build `instructions.py`: instruction decoding and execution
- Implement `traps.py`: TRAP routines x21, x22, x23, x25
- Create `loader.py`: read `.obj` files and load into memory
- Write `cli.py`: basic command-line simulator loop (step, run, halt)
- Add unit tests in `test/`
- Test against known LC-3 `.obj` output files

---

## Project Notes

- This simulator is intended as a personal learning tool and a fallback LC-3 environment for Linux-based classrooms.
- It will prioritize portability, code clarity, and correctness over performance or UI complexity.
- This project is not affiliated with or intended to replace any official LC-3 tools.

---

## Development Timeline

Development will begin after the conclusion of the Spring 2025 semester.  
Target: functional CLI simulator by Fall 2025.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
