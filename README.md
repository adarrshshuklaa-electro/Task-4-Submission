# VLSI Task 4 – DFT & Basic Physical Verification

This repository contains the work completed for Task 4 of my VLSI internship.

## Part 1 – Design for Testability (DFT)

A 4-bit scan chain was implemented using Verilog HDL.

### Features
- 4-bit scan chain
- Functional mode
- Scan/test mode
- Scan enable control
- Serial scan input
- Serial scan output
- Reset
- Behavioral simulation using Xilinx Vivado

### Scan Chain Architecture

Scan In → FF0 → FF1 → FF2 → FF3 → Scan Out

### Files

- `scan_chain.v` – RTL implementation
- `scan_chain_tb.v` – Testbench
- `Simulation_Waveform.png` – Vivado simulation result
- `Task4_Part1_DFT_Report.pdf` – Detailed report

---

## Part 2 – Basic Physical Verification

A CMOS inverter was used as a sample circuit to study basic physical verification.

### Topics Covered

- Design Rule Check (DRC)
- Layout Versus Schematic (LVS)
- CMOS inverter layout
- Minimum width and spacing
- Layout connectivity
- LVS netlist comparison
- Stuck-at-0 and stuck-at-1 faults
- Open and short faults

Due to the unavailability of a complete physical-verification environment and technology PDK, DRC/LVS were documented at a conceptual and tool-driven level rather than claiming unexecuted tool results.

## Tools Used

- Verilog HDL
- Xilinx Vivado
- GitHub

## Learning Outcomes

This task provided practical understanding of:

- Scan-based DFT
- Controllability and observability
- RTL implementation of scan chains
- Behavioral simulation
- Basic DRC/LVS concepts
- Physical verification flow
- Common VLSI fault models
