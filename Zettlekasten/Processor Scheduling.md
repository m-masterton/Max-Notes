202301041627
Status: #Note
Tags: [[Computer Science]] [[Operating Systems]]

___

Modern computer systems are **multi-tasking** meaning that many different programs can be running simultaneously in memory.

Note that on a single core computers, only one task can be executed on the CPU at any given time. Therefore, to appear as if the computer is multi-tasking it must rapidly switch between different tasks. The piece of software used to allocate CPU time to make this possible is a **scheduler**.

>[!defi] Definition (Scheduler)
>The **scheduler** is an [[Function of Operating Systems|operating system]] module responsible for making sure that processor time is used as efficiently as possible.

The scheduler has a few main goals:
+ maximise throughput
+ be fair to all users on a multi-user system
+ provide acceptable response time to users
+ ensure hardware resources are kept as busy as possible

The ideal scheduler would be one that is making 100% use of the CPU, no jobs are left hanging around and the user is never aware of a time delay. There are a few algorithms that try to accomplish this:

### Round Robin

With the **Round Robin** scheduling algorithm, a queue is made holding all jobs that are ready to run. When the first job is loaded into memory, it is given a set amount of CPU time to use. If the job is completed during the allocated time then the next job is loaded immediately. If the process is not finished when the time expired, it is put at the back of the queue.

In order to do this, the [[Function of Operating Systems|operating system]] sets an **interrupting clock / interval timer** to generate interrupts at specific times. This method of scheduling helps to guarantee a reasonable response time.

Note that in round robin scheduling, processes are dispatched on a first in first out (FIFO) basis.

Advantages:
1. It is fairly simple to implement
2. Helps to guarantee a reasonable response time, effective if all job s are of similar priority and size

Disadvantages:
1. It does not take into account how important a job is. An important, high priority job will have to wait just as long as an unimportant, low priority job
2. If an job is long, it will take forever to finish

### First Come First Served

Fairly self explanatory, each process is lined up in a first in first out (FIFO) queue and the processes are allowed to run until they are completed.

Advantages:
1. Very simple to implement
2. Once a job starts, it will run to competition in minimal time

Disadvantages:
1. Once a job starts it prevents other jobs from being processed until it is completed
2. A job that needs access to a slow resource (for example a printer) wastes processor time whilst it is waiting for that resource
3. It does not take into account the priority of a process.
4. A long job will delay all the processes in the queue behind it

### Shortest Job First

Each job's length is measured (in number of Fetch-Decode-Execute cycles) and lined up in a queue or increasing order or job length. The shortest job is executed first and so on.

Advantages:
1. It ensures that the maximum number of jobs are completed
2. It ensures that short jobs aren't kept waiting


___
### References