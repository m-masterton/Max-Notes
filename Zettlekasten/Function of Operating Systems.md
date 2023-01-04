202301041440
Status: #Note
Tags: [[Computer Science]] [[Operating Systems]]

___

### Purpose of an Operating System

>[!defi] Definition (Operating System)
>An **operating system** is a piece of software that lets people interact with a computer and manages computer hardware and software resources. It also provides services for computer programs. Common examples include Microsoft Windows, macOS, Linux, iOS and Android.

Operating systems need to:
+ Control the hardware of a computer system
+ Manage software
+ Provide some security features
+ Provide an interface to allow a person to interact with the computer

### Components of an Operating System

The operating system has four main parts:
+ The **Kernel**
+ The **Device Drivers**
+ The **User Interface**
+ The **System Utilities**

### The Kernel

>[!defi] Definition (Kernel)
>The **kernel** is the core of the operating system that manages and controls the operations of the computer and the hardware, most importantly the CPU and memory. Kernels also provide facilities which programs can use through system calls.

The kernel has the task of:
+ [[Memory Management]]
+ Scheduling
+ File Storage and File Management

### Device Drivers

>[!defi] Definition (Device Driver)
>A **device driver** is a computer program that provides a software interface to hardware devices, enabling operating systems to access hardware functions and communicate with the device.

Usually, the company who made the hardware creates the associated driver and hands it to the operating system proprietor to bundle with their operating system.

Every piece of hardware that communicates with the operating system will require a device driver. For example printers, hard drives, sound cards, monitors and so on. Note that drivers aren't the same across operating systems. A driver for Microsoft Windows will not work for Linux or macOS.

### User Interface

>[!defi] Definition (User Interface)
>A **user interface** is a piece of software that allows a person to interact with the computer.

There are different types of user interfaces, all have their own use case. Here we will discuss 3 types:
+ A **Graphical User Interface (GUI)** is the most commonly used today. It is very friendly and easy to use but can require more computer resources. It is better for an inexperienced user as they will not have to memorize commands or have much specialist knowledge to interact with the computer.
+ A **Command Line Interface (CLI)** or **Text User Interface (TUI)** allows the user to interact directly with the computer system by typing in commands into a screen. This is better for an advanced user as they can instantly do things and there is little room for ambiguity. However this is bad for an inexperienced user as they will have to memorize lots of commands to interface with the computer. Some tasks, such as photo editing cannot be done using a CLI.
+ A **Natural Language Interface (NLI)** allow the user to interact with the computer with speech. Common examples include a bank's telephone line "You have selected option 2, is this correct?" or Amazon Alexa "Alexa, add paper to the shopping list."

### Utilities

An operating system will also contain a number of utilities which have a specific task to carry out. Examples include
+ Anti-Virus utility
+ Disk Defragmentation utility
+ File Compression utility

___
### References

[Teach-ICT - Operating System - Purpose of an Operating System](https://teach-ict.com/2016/A_Level_Computing/OCR_H446/1_2_software/121_operating_systems/purpose_of_os/miniweb/index.php)