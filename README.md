![image](https://github.com/user-attachments/assets/f8305cb1-5824-491f-bddc-5b7fc60d9875)# My Django Blong
This is my Django blog.


## Notes on Memory Management in OS

Summary of Memory Management in Operating Systems:

Memory management in an operating system (OS) involves managing the system’s memory to allow efficient execution of processes. The primary purpose is to ensure that memory is allocated and deallocated efficiently, minimizing fragmentation, and ensuring the CPU can quickly access the data it needs.

Key Concepts:
Main Memory: Also known as RAM, it stores the data and instructions that the CPU needs to access quickly. It is volatile and loses data when power is lost.

Memory Management: Involves dividing memory among multiple processes and managing the transfer of data between main memory and secondary storage. It is crucial for multiprogramming and efficient memory utilization.

Logical vs. Physical Address Space:

Logical Address: Generated by the CPU during execution (virtual address).
Physical Address: The actual location in memory, used by the memory unit (real address).
The Memory Management Unit (MMU) maps logical addresses to physical addresses.
Static vs. Dynamic Loading:

Static Loading: Entire program loaded into memory at once.
Dynamic Loading: Parts of a program (routines) are loaded only when required, saving memory.
Static vs. Dynamic Linking:

Static Linking: Combines all modules into a single executable at compile time.
Dynamic Linking: Libraries are linked at runtime, with routines loaded only when needed.
Swapping: The process of moving data between main memory and secondary storage to allow more processes to run simultaneously. It is commonly used when the system has limited memory.

Memory Allocation Methods:

First Fit: Allocates the first available block of memory.
Best Fit: Allocates the smallest block that fits the process.
Worst Fit: Allocates the largest available block.
Fragmentation:

Internal Fragmentation: Wasted space within allocated memory blocks.
External Fragmentation: Wasted space between allocated blocks of memory.
Compaction can reduce external fragmentation by rearranging memory.
Paging: A technique that divides physical memory into fixed-size blocks called frames and divides logical memory into pages. This allows non-contiguous memory allocation, eliminating the need for large contiguous blocks of memory. The Memory Management Unit (MMU) handles the mapping between pages and frames.

Translation Lookaside Buffer (TLB): A cache used to speed up the mapping between logical and physical addresses. It reduces the number of memory accesses required for address translation.

Advantages of Effective Memory Management:
Efficient utilization of memory.
Reduction of fragmentation.
Enables multiprogramming, allowing multiple processes to run concurrently.

Challenges:
Memory fragmentation (both internal and external).
Managing the allocation and deallocation of memory effectively.
The trade-off between memory allocation strategies (e.g., First Fit, Best Fit, Worst Fit).
Effective memory management ensures that a system runs smoothly by allocating memory resources to processes in an optimized way, thereby enhancing the performance and reliability of the system.

![image](https://github.com/user-attachments/assets/38f84b8b-3789-41e6-a18d-97c55910449f)
