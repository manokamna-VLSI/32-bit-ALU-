# 32-Bit Arithmetic Logic Unit (ALU)

## Overview
This project implements a 32-bit Arithmetic Logic Unit (ALU) using Verilog HDL. The ALU performs arithmetic and logical operations based on a 4-bit control signal.

## Features
- Addition (ADD)
- Subtraction (SUB)
- Bitwise AND
- Bitwise OR
- Bitwise NOT
- Multiplication (MUL)
- Division (DIV)
- Divide-by-zero protection

## Inputs
- A [31:0]
- B [31:0]
- ALU_sel [3:0]

## Output
- ALU_out [31:0]

## Operation Table

| ALU_sel | Operation |
|----------|-----------|
| 0000 | ADD |
| 0001 | SUB |
| 0010 | AND |
| 0011 | OR |
| 0100 | NOT |
| 0101 | MUL |
| 0110 | DIV |

## Tools Used
- Verilog HDL
- Xilinx Vivado

## Applications
- Processor Design
- FPGA Systems
- Digital Logic Design
- RISC Architectures

## Author
Muskan
