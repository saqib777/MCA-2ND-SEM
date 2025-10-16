──────────────────────────────────────────────
             💻 OPERATING SYSTEM NOTES
──────────────────────────────────────────────

📘 SHORT ANSWERS (5 MARKS EACH)
──────────────────────────────

1️⃣ COMPONENTS OF COMPUTER SYSTEM  
A computer system has four main components:  
1. **Hardware:** Provides basic computing resources (CPU, Memory, I/O devices).  
2. **Operating System (OS):** Controls and coordinates the use of hardware among various applications and users.  
3. **Application Programs:** Define how system resources are used to solve user problems (e.g., browsers, compilers).  
4. **Users:** People or other machines interacting with the system.  

──────────────────────────────

2️⃣ SHORT-TERM SCHEDULER  
The Short-Term Scheduler (CPU Scheduler) selects a process from the Ready Queue in memory and allocates the CPU to it.  
It is invoked very frequently (in milliseconds) and must be extremely fast to ensure efficient CPU utilization and quick response times.  

──────────────────────────────

3️⃣ MEMORY HIERARCHY  
The memory hierarchy ranks storage based on speed, cost, and capacity:  
1. **Registers:** Inside CPU; fastest access.  
2. **Cache:** Small, fast SRAM; holds frequently accessed data from RAM.  
3. **Main Memory (RAM):** Large, volatile storage; running programs reside here.  
4. **Secondary Storage:** Non-volatile, permanent storage (HDD/SSD).  

──────────────────────────────

4️⃣ PAGING TECHNOLOGY  
Paging divides logical memory into fixed-size pages and physical memory (RAM) into same-sized frames.  
It uses a **Page Table** to map pages to frames, allowing a program’s physical address space to be non-contiguous and eliminating external fragmentation.  

──────────────────────────────

5️⃣ SPOOLING  
Spooling (Simultaneous Peripheral Operations On-Line) is a technique that temporarily holds data in a buffer (spool) on disk for slow devices like printers.  
It allows the CPU and applications to continue working without waiting for I/O devices to finish, improving system throughput.  

──────────────────────────────

6️⃣ MULTIPROGRAMMING & MULTITASKING  
• **Multiprogramming:** Keeps multiple jobs in memory at once to maximize CPU utilization.  
• **Multitasking (Time-Sharing):** CPU rapidly switches between jobs using small time slices to give users the feel of simultaneous execution.  

──────────────────────────────

7️⃣ TYPES OF OPERATING SYSTEM  
• **Batch:** Executes jobs sequentially in groups.  
• **Time-Sharing:** Multiple users share CPU for interactive use.  
• **RTOS:** Completes tasks within strict time deadlines.  
• **Distributed:** Manages multiple machines as a single system.  
• **Embedded:** Lightweight OS for devices like watches, routers.  

──────────────────────────────

8️⃣ RESOURCE ALLOCATION GRAPH (RAG)  
A RAG shows resource allocation using nodes and edges:  
• **Process Nodes (Circles)**  
• **Resource Nodes (Squares)**  
• **Request Edge (P→R):** Process requests resource.  
• **Assignment Edge (R→P):** Resource assigned to process.  
A cycle indicates the possibility of deadlock.  

──────────────────────────────

9️⃣ MEMORY HIERARCHY (SHORT NOTE)  
The memory hierarchy organizes storage by speed and cost: from Registers → Cache → RAM → Disk.  
Fastest and smallest at the top, slowest and largest at the bottom.  

──────────────────────────────

🔟 PAGING vs DEMAND PAGING  

| Feature | Paging | Demand Paging |
|----------|---------|----------------|
| Loading | All pages loaded before execution | Pages loaded only when needed |
| Page Fault | None after loading | Occurs when page not in memory |
| Memory Use | May waste space | Uses memory efficiently |
| Concept | Basic memory management | Virtual memory concept |

──────────────────────────────

11️⃣ CPU SCHEDULING CRITERIA  
• **CPU Utilization:** Keep CPU busy.  
• **Throughput:** No. of processes completed/time.  
• **Turnaround Time:** Time from submission to completion.  
• **Waiting Time:** Time spent in ready queue.  
• **Response Time:** Time until first response.  

──────────────────────────────

12️⃣ SAFE & UNSAFE STATES  
• **Safe State:** There exists a safe sequence of process execution ensuring no deadlock.  
• **Unsafe State:** No guarantee all processes will finish; potential deadlock.  

──────────────────────────────

15️⃣ LONG-TERM SCHEDULER & DEVICE QUEUE  
• **Long-Term Scheduler:** Loads jobs from disk to memory; controls degree of multiprogramming.  
• **Device Queue:** Queue of processes waiting for a specific I/O device.  

──────────────────────────────

16️⃣ FRAGMENTATION & SWAPPING  
• **External Fragmentation:** Free memory exists but is non-contiguous.  
• **Internal Fragmentation:** Allocated block larger than needed.  
• **Swapping:** Temporarily moves processes between RAM and disk to free space.  

──────────────────────────────

17️⃣ FUNCTIONS OF OPERATING SYSTEM  
• Process Management  
• Memory Management  
• File Management  
• Device Management  
• Security & Protection  
• Command Interpretation  
• Error Handling  

──────────────────────────────

18️⃣ PROCESS LIFE CYCLE  
States: **New → Ready → Running → Waiting → Terminated**  
Transitions depend on scheduling and I/O events.  

──────────────────────────────

19️⃣ RESOURCE ALLOCATION GRAPH (RAG) – DETAIL  
• **Process (Circle)**  
• **Resource (Square)**  
• **Edges:** Request or Assignment  
Cycle = possible deadlock.  

──────────────────────────────

20️⃣ INDEXED ALLOCATION  
All block pointers for a file are stored in one **Index Block**.  
• Direct access possible.  
• No external fragmentation.  
• Limited file size by index block size.  

──────────────────────────────

21️⃣ REMOTE PROCEDURE CALL (RPC)  
RPC allows a function on one machine to execute on another as if local.  
Uses **Client Stub** and **Server Stub** for communication.  
Hides network complexity and enables distributed systems.  

──────────────────────────────

23️⃣ PROCESS CONTROL BLOCK (PCB)  
Stores process info such as:  
• Process State  
• Program Counter  
• CPU Registers  
• Scheduling Info  
• Memory Info  
• Accounting Info  
• I/O Status  

──────────────────────────────

24️⃣ SEGMENTATION HARDWARE  
Logical address = (Segment No, Offset).  
Segment Table stores base and limit.  
Physical Address = Base + Offset.  

──────────────────────────────

25️⃣ REAL-TIME SCHEDULING  
• **Hard Real-Time:** Deadlines must never be missed.  
• **Soft Real-Time:** Occasional misses allowed.  
Algorithms: **EDF** and **RMS**.  
Used in robotics, medical, automotive systems.  

──────────────────────────────

26️⃣ DIRECT MEMORY ACCESS (DMA)  
DMA allows I/O devices to directly access memory without CPU involvement.  
• Steps: CPU sets DMA → DMA transfers data → Interrupt to CPU.  
Improves I/O speed and frees CPU.  

──────────────────────────────

27️⃣ TYPES OF OPERATING SYSTEM (DETAILED)  
• Batch OS  
• Time-Sharing OS  
• Distributed OS  
• Network OS  
• Real-Time OS  
• Embedded OS  

──────────────────────────────

29️⃣ PAGE REPLACEMENT ALGORITHMS  
1. **FIFO:** Replace oldest page (simple, may cause Belady’s anomaly).  
2. **OPTIMAL:** Replace page not needed for longest time (theoretical).  
3. **LRU:** Replace least recently used page.  

──────────────────────────────

30️⃣ CONTIGUOUS ALLOCATION  
Each file stored in one continuous set of blocks.  
• Fast sequential/direct access.  
• Suffers from external fragmentation.  

──────────────────────────────

31️⃣ INTERRUPT-DRIVEN I/O  
CPU issues I/O → device works → sends interrupt → CPU executes ISR → resumes task.  
Avoids CPU idle time; efficient I/O handling.  

──────────────────────────────

32️⃣ DEADLOCK & CONDITIONS  
Deadlock = processes waiting forever for resources held by each other.  
Necessary conditions:  
1. **Mutual Exclusion**  
2. **Hold & Wait**  
3. **No Preemption**  
4. **Circular Wait**  

──────────────────────────────

33️⃣ PRIORITY & ROUND-ROBIN SCHEDULING  
**Priority Scheduling:** Highest priority gets CPU first; may cause starvation → solved by aging.  
**Round Robin:** Fixed time quantum; fair and responsive; used in time-sharing.  

──────────────────────────────

34️⃣ PAGE REPLACEMENT ALGORITHMS (DETAIL)  
• FIFO – oldest page removed.  
• OPTIMAL – removes page not used soonest.  
• LRU – removes least recently used page.  

──────────────────────────────

35️⃣ FILE ALLOCATION METHODS  
1. **Contiguous:** Adjacent blocks.  
2. **Linked:** Blocks linked with pointers.  
3. **Indexed:** Uses index block.  

──────────────────────────────

36️⃣ DEVICE DRIVERS & INTERRUPTS  
• **Device Driver:** Software that connects OS and hardware.  
• **Interrupt Handling:** CPU stops current task → executes ISR → resumes.  

──────────────────────────────

37️⃣ ROUND-ROBIN & SRTF  
• **RR:** Fixed time slice, circular queue.  
• **SRTF:** Preemptive, shortest remaining time first.  

──────────────────────────────

38️⃣ DEADLOCK AVOIDANCE & PREVENTION  
• **Prevention:** Break one of the four necessary conditions.  
• **Avoidance:** Use Banker’s Algorithm to stay in safe state.  

──────────────────────────────

39️⃣ SYMMETRIC vs ASYMMETRIC ENCRYPTION  

| Type | Key | Speed | Example |
|-------|------|--------|----------|
| Symmetric | Same key for encrypt/decrypt | Fast | AES, DES |
| Asymmetric | Public & Private key pair | Slower | RSA, ECC |

──────────────────────────────

41️⃣ FCFS & SJF SCHEDULING  
• **FCFS:** First come first served; simple but causes convoy effect.  
• **SJF:** Shortest job first; minimizes waiting time but needs burst prediction.  

──────────────────────────────

42️⃣ THREAD SCHEDULING  
• **User-Level:** Managed by user libraries; fast but blocks entire process.  
• **Kernel-Level:** Managed by OS; slower but independent thread execution.  

──────────────────────────────

📘 END NOTES  
• OS manages hardware, memory, files, and processes.  
• Scheduling aims to maximize CPU efficiency.  
• Memory management prevents waste.  
• Deadlock prevention ensures smooth operation.  
• Encryption ensures data security in systems.

──────────────────────────────────────────────
