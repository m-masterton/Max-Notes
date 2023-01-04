202301041320
Status: #Note 
Tags: [[Computer Science]] [[Architecture]]

___

A **register** is a special memory cell in the [[CPU (Central Processing Unit)|CPU]] which operates at a very high speed. Results of all arithmetic, logic or shift operations are temporarily stored in registers and generally there are up to 16 general purpose registers in the CPU. An 8-bit CPU has 8-bit registers, a 16-bit CPU has 16-bit registers and so on. It is much faster to shift data to and from registers rather than in out of Cache or RAM (Random Access Memory) and so this speeds up the processing time.

Whilst most registers in the CPU are general purpose registers, some have a specific purpose and so they have their own name (special-purpose registers):
1. The **accumulator** is where results of operations carried out in the [[ALU (Arithmetic Logic Unit)|ALU]] are stored.
2. The **PC (Program Counter)** holds the address of the next instruction to be executed. This may just be the next instruction in a series of instructions or this might be more complicated if there is a branch or jump instruction. If the current instruction is a branch or jump instruction, the address to jump to is copied from the current instruction register (CIR).
3. The **CIR (Current Instruction Register)** holds the current instruction being executed (dividing into operand and opcode).
4. The **MAR (Memory Address Register)** holds the **address** of the memory location from which data (or an instruction) is to be fetched or to which data is to be written.
5. The **MDR (Memory Data Register)** temporarily stores the data read from or written to memory. It is also sometimes called the **memory buffer register**.

___
### References

PG online computer science textbook (page 4)
[Teach-ICT - Architecture - Registers](https://teach-ict.com/2016/A_Level_Computing/OCR_H446/1_1_characteristics_components/111_architecture/parts_of_cpu/miniweb/pg5.php)