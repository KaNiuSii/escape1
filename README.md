## Instructions:

# NOP: 
instruction that stands for "No Operation". It does nothing and is often used for timing or waiting.
# LDB: 
instruction that could stand for "Load Byte". It loads a byte from memory into a register.
# LDH: 
Similar to LDB, but it might load a half-word (two bytes).
# STB/STW: 
instructions for "Store Byte/Word". They store a byte or word from a register to memory.
# ADD/SUB/DIV/MUL: 
arithmetic instructions that perform addition, subtraction, division, and multiplication, respectively.
# AND/OR/XOR: 
logical instructions that perform bitwise AND, OR, and XOR operations.
# SLL/SRA: 
shift instructions that perform shift left logical and shift right arithmetic operations.
# BRZ/BRNZ/BRGT/BRGE/BRLE: 
branch instructions that perform jumps based on zero, non-zero, greater than, greater or equal, less or equal conditions.

*Each mnemonic is followed by its operand specification in brackets. For instance, r1, r2, r3 for an ADD operation means that the instruction will add the contents of registers r2 and r3, and store the result in register r1.*

## Instruction Encoding:

# Number of Opcodes: 
This indicates how many different operation codes (opcodes) are available in the instruction set. In this case, there are 64 different opcodes that the architecture can execute.
# Number of Registers: 
This specifies the number of registers available in the machine. Registers are small, fast storage locations within the CPU used to hold temporary data and instructions.
# Immediate 1 Size: 
The size, in bits, of the first immediate value that can be encoded in an instruction. Immediate values are constants encoded directly in the instruction.
# Immediate 2 Size: 
The size, in bits, of the second immediate value that can be encoded in an instruction.
# Number of Formals: 
Likely refers to the number of formal parameters that can be passed to an instruction.
## Types of Instructions
# R-type: 
Register type instructions that perform operations on registers directly (e.g., r1, r2, r3 means the operation takes three register operands).
# I-type: 
Immediate type instructions that perform operations using an immediate value and typically one or two registers (e.g., r1, r2, imm1 means the operation takes two register operands and one immediate value).
# J-type: 

*Jump type instructions that are used for jumping to a certain address in the code (e.g., imm2 is likely an address or offset for the jump).
Opcode Table*

