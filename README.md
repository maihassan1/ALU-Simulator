This project simulates a basic CPU architecture that includes components such as a Program Counter (PC), Memory, Registers, and an Arithmetic Logic Unit (ALU). The simulator processes a series of instructions from a text file, where each instruction is represented in hexadecimal format. The system performs operations like memory loading, register manipulation, arithmetic operations, and program jumps, mimicking the behavior of a simple CPU.

Features:
Program Counter (PC): Keeps track of the current instruction address, supports increment and jump operations.

Memory: Simulates a memory unit that stores data in hexadecimal format, allowing data loading and retrieval.

Registers: Simulates 16 registers, where data can be written and read.

ALU Operations: Supports various operations such as loading data into registers, storing data to memory, arithmetic addition of register values, and conditional jumps based on register values.

Instruction Set: The simulator reads instructions from a file and processes them accordingly, executing operations like:

Load data from memory to registers

Store data from registers to memory

Move data between registers

Perform arithmetic operations (e.g., addition)

Jump to specific addresses based on register values

End execution

Usage:
Load your memory and instructions from a text file containing hexadecimal data.

Run the program to execute the instructions.

View the state of the Program Counter, Registers, and Memory after execution.
