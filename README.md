# S-MIPSv2 Processor
The project consists of designing a processor in LogiSim that implements the S-MIPSv2 (Simplified-MIPS Version 2) instruction set architecture.

S-MIPSv2 is a 32-bit architecture. The processor has 32 general purpose 32-bit registers, named `R0` to `R31`, of which `R0` always has a constant value of 0 regardless of the operations performed on it, and `R31` (`SP`), which acts as a stack pointer. pointers). It has two additional registers `Hi` and `Lo` where the result of the division and multiplication is stored.

The processor must be implemented on the S-MIPS module of the supplied S-MIPS Board. You must not modify the RAM circuit or the S-MIPS Board circuit. These will be used during the evaluation of the circuits.

More information about S-MIPSv2 instructions can be found in [instruciones.xlsx](https://github.com/lorainemg/s-mipsv2-processor/blob/main/doc/instruciones.xlsx), a more detailed document is available at [s-mipsv2.pdf](https://github.com/lorainemg/s-mipsv2-processor/blob/main/doc/s-mipsv2.pdf).