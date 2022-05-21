https://www.youtube.com/watch?v=v0ssX-JiV-s

# RISCV has a smaller ISA than ARM and x86
  - x86 being CISC has 1300+ instructions
	- arm 32 bit has 500+ instructions
	- RISCV has 60+

# For low-memory chips
	- RISCV can be used to make small cores that saves money. 
	- If size of core double, cost quadruple.

# RISC-V Extensions
	- RV32G means general such as general purpose os such as Linux. 

# CSR command and status register.

# ISA vs microarchitecture
	- ISA is like the interface to the microarchitecture.
	Intel and AMD can both run x86 but they have different microarchitecture.

# RISC-V boards.
	- Personal Computer
	- Raspberry Pi Crowd
	- Arduino Uno R3 form, SparkFun RED-V.

# RISCV Pseudo Instructions
	- Some instructions are too simple to the point where it hurt readability
	- So pseudo instructions are composed to say doing Load-Immediate with the actual instructions. 

# Registers
	- 32 registers, R0 is always zero. 
	- Register Alias Names
	  - zero
		- ra - return regiser
		- sp - stack pointer 
		- gp 
		- tp 
		- t0 - t6 temporary registers
		- a0 - a7 function arguments
	- Why #registers are limited?
	  Because the number of bits available to encode is limited. 

# Execution 
	- Each clock cycle the most basic operation is performned
	- Each instruction in a program takes typically 4-clocks - the concept of pipelining.  Fetch - Decode - Execution - Writeback 

# Instructions
	- ADD rd, s1, s2
  s1, s2, rd are operands
	- 7 bits opcodes. 

	- Immediate type 
	  -> when you code the data inside of the instruction itself. 
	- Load and Store type
    -> LW / SW 
		SW x1, 4(x0) -> stores [x0+4] into x1. 

# RISC vs CISC
	- RISC = 1 instruction 1 micro operation
	- CISC = 1 instruction multiple micro operations. 
  Even it's micro, it doesn't mean the instruction is small.

# Superscalar Microprocessor on CISCS
	- Multiple Decoder multiple instructions in parallel
	- Checking instructions coming after each other - hazard 

# Superscalar vs Multi-core 
  - Multi-core, from programmer perspective you see multiple thread.
	- Superscalar, from programmer perspective, you see ONE thread. 


