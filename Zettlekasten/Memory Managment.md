202301041508
Status: #Note
Tags: [[Computer Science]] [[Operating Systems]]

___

Memory is one of the most important resources that an operating system needs to manage. Depending on the computer system, memory can be a limited resource and so efficient use of memory is extremely important to optimise performance.

>[!defi] Definition (Process)
>A **process** is an instance of an executable application loaded into memory on a computer system which has the ability to run several computer programs concurrently.

### Paging and Segmentation

**Paging** and **Segmentation** are two techniques for managing memory by splitting it into small sections.

Using a paging system, memory is divided into fixed size **pages** of 4kB each, and a process currently in memory may be assigned several non-contiguous pages. For example, consider a program which requires 15kB of consecutive memory addresses - these logical memory locations may be physically stored in four separate pages anywhere within RAM. A **page table** uses a mapping to store a link between the **physical** memory address and the **logical** address space of each process.

**Segmentation** is the logical division of the address space into varying length segments which depend on the program structure. As with paging, it is possible to load only a part of a program into memory initially

Similarities:
1. Both are a way of dividing up memory
2. Both are assigned by the memory manager as and when they are needed.
3. Both are a
### Virtual Memory

>[!defi] Definition (Virtual Memory)
>As more and more processes are loaded into memory, the operating system may swap pages of temporarily inactive processes out to a special space in secondary storage (**virtual memory**), thus using secondary storage as an extension of memory to make room for the next process.

Notice that if a large number of processes use up all the available memory (and more) there will be a significant drop in performance because the system will have to wait as the pages are swapped in and out of memory, which is very slow.

___
### References