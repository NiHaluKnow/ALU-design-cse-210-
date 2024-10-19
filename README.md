# ALU-design-cse-210-
This repository contains my Level-2 Term-2 project for the sessional course CSE-210. The goal of this project is to design and implement an Arithmetic Logic Unit (ALU) that performs essential arithmetic and logic functions using a minimal number of integrated circuits (ICs).

Project Overview:
The ALU is a fundamental component of a computer's central processing unit (CPU). It performs arithmetic operations like addition and subtraction, as well as logic operations like AND, OR, and XOR. The objective of this project was to design an ALU that can perform these operations with the least number of ICs, while also implementing the design both in software and in a physical circuit.

Key Features
Arithmetic Operations:
Add
Add With Carry
Sub With Borrow
Increment A

Logic Operations:
XOR
Complement A (NOT)

Control Functions:
Select between arithmetic and logic operations
Carry-in and carry-out handling for arithmetic operations

Implementation Details
The project was implemented in two phases:

Software Implementation:
Simulated the ALU design using Logisim Version 2.7.1 (10.2) for hardware description and implemented test benches to verify functionality.
Software-based testing was conducted to ensure the ALU produces correct outputs for all supported operations.

The design was translated into a hardware implementation using minimal ICs.
Logical components like full adders, multiplexers, and logic gates were physically wired on a breadboard or PCB to create the ALU.
Testing of the physical circuit was done using standard inputs and outputs to verify correct operation.
Tools Used

Software Tools:
Logisim Version 2.7.1 (10.2) for ALU simulation
Digital design tools for circuit schematic generation

Hardware Components:
ICs (e.g., 7400 series logic chips)
Breadboard for prototyping
Power supply and voltmeter for testing

Conclusion
This project helped solidify my understanding of digital logic design and hardware implementation, specifically in the context of building a critical component like the ALU. The combination of software simulation and physical implementation provided a comprehensive learning experience in digital electronics.
