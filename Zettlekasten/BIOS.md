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

The fundamental purpose of the BIOS in modern computers is to initialise and te


___
### References