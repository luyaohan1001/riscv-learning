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

# Instructions
	- ADD rd, s1, s2
  s1, s2, rd are operands
	- 7 bits opcodes. 



