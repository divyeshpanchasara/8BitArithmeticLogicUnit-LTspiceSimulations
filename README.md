# 8-Bit Arithmetic Logic Unit (ALU) - LTspice Simulations

This repository contains LTspice simulation files for an 8-bit Arithmetic Logic Unit (ALU) designed as part of a major project. The ALU performs fundamental arithmetic and logical operations essential in computing systems. The project includes a detailed report on the design, implementation, and simulation results of the ALU using LTspice.

## Overview

An Arithmetic Logic Unit (ALU) is a key component of a microprocessor, responsible for performing arithmetic and logical operations. This 8-bit ALU is designed to execute a variety of operations such as addition, subtraction, AND, OR, XOR, XNOR, NOT A and CLEAR A.

The project focuses on:
- Designing the ALU with a modular approach.
- Simulating the ALU design using LTspice.
- Analyzing the simulation results to verify the functionality of the ALU.

## Features

The 8-bit ALU can perform the following operations:
- **Arithmetic Operations:**
  - Addition
  - Subtraction
- **Logical Operations:**
  - AND
  - OR
  - XOR
  - XNOR
  - NOT A
  - CLEAR A

Additional features include:
- Modular design for ease of understanding and simulation.
- Verification of results through extensive testing in LTspice.

## Components and Design

The ALU is built using basic logic gates and components that form the foundation of more complex digital circuits. The design is divided into several modules:
- **Adder/Subtractor**: A key module for arithmetic operations.
- **Logic Unit**: Handles logical operations such as AND, OR, XOR, XNOR, NOT A and CLEAR A
- **Control Unit**: Responsible for selecting the desired operation based on input signals.

The project also provides detailed schematics of each module, showing how the individual components are interconnected to form the complete ALU.

## LTspice Simulations

The simulations were conducted using **LTspice**, a powerful circuit simulation tool. The repository includes the following files:
- **Schematic files** for each module of the ALU.
- **Simulation files** to test the performance of the ALU for different inputs.
- **Results** that demonstrate the correctness of the ALU's operations.

## How to Run the Simulations

1. Download and install [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html).
2. Clone this repository:
   ```bash
   git clone https://github.com/divyeshpanchasara/8BitArithmeticLogicUnit-LTspiceSimulations.git
