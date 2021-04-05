# RISC-V processor 
32 bit RISC-V complete datapath present in the RISCV.circ file. 
Each circuit file holds an individual operational block.
The datapath works for R, I, S, B, auiPC, lui, lw, JAL and JALR instructions.
Different blocks used for immegiate generation, ALU, branch ALU, register file, controller, decoder, etc.
Operand A and B are used to represent two main inputs.
7 bit Opcode can be decoded completely to execute an operation.
Program counter would calculate the next address. 
A constant 4 is used in the prgram counter for memory allocation.
ROM and RAM used for memory 
ROM can clear and load different codes for testing.

