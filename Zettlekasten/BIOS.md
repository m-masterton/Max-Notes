202301041857
Status: #Note
Tags: [[Computer Science]] [[Operating Systems]]

___

### Booting a Computer

When a computer is first turned on, the RAM is empty and the memory is empty and the CPU has no instructions to follow. So how does a computer get from this sate of doing nothing to a state of doing something?

This is the role of **booting** a computer.

Booting has to happen in small steps because at the point of switch-on the machine is effectively dumb. It does not know anything about hard disks, or peripherals - absolutely nothing. There is a way of booting up a computer and the piece of software involved in this is called the **BIOS**

>[!defi] Definition (BIOS)
>The **BIOS (Basic Input Output System)** is a small program that is responsible for booting up the computer after you turn it on. It is not part of the operating system as it has to work before the operating system is even loaded into memory.

The BIOS is normally flashed on a BIOS chip on the motherboard. The chip contains non-volatile memory.

The fundamental purpose of the BIOS in modern computers is to initialise and test the system hardware components and load the operating system (or key parts of it) from the hard disk into RAM. This test is called **POST**:

>[!defi] Definition (POST)
>**POST (Power On Self-Test)** is a set of hardware and system health checks conducted by the BIOS. The POST checks include:
>+ BIOS is not corrupted (not really an issue on modern computers)
>+ System chips are OK (for example the interrupt controller)
>+ Processor is OK
>+ Memory is OK
>+ Keyboard is present
>+ Video Display Memory is OK

After POST the BIOS looks for a bootable drive and the [[Function of Operating Systems|operating system]] is loaded from the drive by the boot loader.

In older computers the BIOS was used to provide an abstraction layer which allowed for a consistent way for application programs and the operating system to interact with I/O devices (hence the name). However, more modern computers do not use the BIOS after loading the operating system.

___
### References

PG Online - A-Level OCR Computer Science Textbook - Page 38
[Teach-ICT - Operating System - BIOS](https://teach-ict.com/2016/A_Level_Computing/OCR_H446/1_2_software/121_operating_systems/bios/miniweb/index.php)