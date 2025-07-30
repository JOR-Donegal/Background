# Operating Systems

The first computers of the 1940s were very primitive, operators entered programs directly by flipping switches. Keypads with similar functionality existed on mainframes and minicomputers, right into the 1970s.

As standardized computer hardware emerged in the 1950s, with each new generation of hardware, dedicated utilities were added to allow the hardware to be controlled by the software and applications. This is probably still the best definition of an Operating System (OS). These systems ran batch jobs, a range of tasks run one at a time in a single-tasking computer.

The earliest record of an operating system I can find is an implementation by General Motors for an IBM 701 \[1].

As computers became more powerful in the 1960s, operating systems were designed to allow multiple programs to run at the same time, using time slices. As one program became idle waiting for printing or disk access, another program would use the CPU. Resources are shared and the algorithms for this sharing have been developing since. This was an era of time-sharing operating systems.

One of the oldest technologies I have worked on was based on Multics, this introduced the concept of a process as an individual program running in an operating system. Process scheduling and management are still key topics in operating systems. At the time, Unix was a single process operating system.

One of the significant contributions of Multics was that it was the first operating system to be written in a high-level language, but it was eventually abandoned in favor of a multi-user version of Unix. When UNIX was being developed, the C programming language was specifically written to implement this operating system across hardware platforms. The original UNIX for the PDP11 was written c. 1973 in this way.

All software which runs on a modern computer (including the operating system) is organized into processes, a process is an instance of an executing program. Each process appears to have its own memory space, CPU, etc. Each system appears as if it has multiple processes running concurrently, the CPU switches from process to process. However, there is a cost to this context switching.

Threads are like lightweight processes. Many threads can run within the boundaries of a single process. Threads are the basic unit to which the operating system allocates processor time. A thread can execute any part of the process code, including parts currently being executed by another thread. Threads give the ability to have multiple things going on at the same time, without the performance cost of process switching.
