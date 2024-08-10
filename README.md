# RALU

## Overview

This project involved the design, simulation, and implementation of an Arithmetic Logic Unit (ALU) and a Registered Arithmetic Logic Unit (RALU) using Quartus. The project aimed to understand the operation of ALUs and RALUs, simulate their functions, and eventually implement them on a DE10-Lite FPGA board. 

### ALU Design

1. **Design and Simulation:**
   - The ALU was designed in Quartus using predefined components such as the 74’283 adder and MUXes.
   - Simulations were conducted to verify the correct operation of the ALU, testing key operations like addition, AND, and OR.

2. **ALU Functional Testing:**
   - Several test cases were simulated, focusing on addition with carry, logical AND, and OR operations.
   - The results confirmed that the ALU performed as expected.

### RALU Design

1. **Functional Block Diagram:**
   - A complete and detailed functional block diagram was created, labeling all inputs, outputs, and internal signals.

2. **RALU Circuit Design:**
   - The RALU was designed in Quartus with specific signals for REGA and REGB to make debugging easier.
   - After thorough testing, the design was modified to fit within the DE10-Lite’s PLD.

3. **Complex Functions Implementation:**
   - The project implemented complex functions such as loading registers, bitwise AND/OR operations, and performing arithmetic shifts.
   - Simulations were conducted for each complex function, and the results were annotated for clarity.

### Simulation and Implementation

1. **Simulation of Complex Functions:**
   - A sequence of steps was simulated to perform a complex arithmetic operation, combining addition, AND, OR, complement, and shifting operations.
   - The simulation results were documented and analyzed.

2. **Implementation on DE10-Lite:**
   - The RALU design was downloaded to the DE10-Lite FPGA board, with inputs provided by the Digilent Analog Discovery (DAD) tool and outputs displayed on HEX displays.

3. **Custom Pattern Generation:**
   - A custom pattern was created for testing the RALU on the DE10-Lite, ensuring that the circuit functioned as specified.

## Requirements

- **Hardware:** DE10-Lite FPGA Board
- **Software:** Quartus Prime Lite Edition, Digilent WaveForms (DAD tool)

## Video Demonstration

A video demonstration of the project can be found [here](https://www.dropbox.com/scl/fi/te0wkehv6n2iyrwo3ktuw/IMG_9981.MOV?rlkey=hkn05dxmo8hbemmodhytnkxc8&st=edz5jkj0&dl=0).

## Future Work

The ALU and RALU designed in this project lay the foundation for building a complete CPU in future projects. The knowledge gained from this project is crucial for understanding how arithmetic operations are implemented in hardware and how these operations can be controlled and modified.
