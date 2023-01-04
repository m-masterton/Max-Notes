202301041627
Status: #Note
Tags: [[Computer Science]] [[Operating Systems]]

___

Modern computer systems are **multi-tasking** meaning that many different programs can be running simultaneously in memory.

Note that on a single core computers, only one task can be executed on the CPU at any given time. Therefore, to appear as if the computer is multi-tasking it must rapidly switch between different tasks. The piece of software used to allocate CPU time to make this possible is a **scheduler**.

>[!defi] Definition (Scheduler)
>The **scheduler** is an operating system module responsible for making sure that processor time is used as efficiently as possible
___
### References