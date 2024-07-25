# RISC-V-Single-Cycle
This repository contains the Verilog implementation of a single-cycle RISC-V processor. The processor includes key components such as the ALU, control unit, register file, and data memory.

## Components

- **ALU**: Performs arithmetic and logical operations.
- **ALU Decoder**: Decodes ALU operation signals.
- **Control Unit**: Generates control signals based on the opcode and function codes of the instruction.
- **Data Memory**: Stores data for the processor.
- **Instruction Memory**: Stores instructions for the processor.
- **Main Decoder**: Decodes the main control signals for the processor.
- **MUX**: Two-to-one multiplexer.
- **PC (Program Counter)**: Holds the address of the current instruction.
- **PC Adder**: Computes the next address of the instruction.
- **Register File**: Contains the processor's registers.
- **RISC V Top**: Top-level module that integrates all components to form the single-cycle processor.
