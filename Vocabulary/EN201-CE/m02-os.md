---
parent: EN201-CE
title: M02：操作系统与系统软件
---

# M02：操作系统与系统软件

（共约 90 词，分为 6 大类，附词性、中文释义与例句）

---

## ① 操作系统基础（OS Basics）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|operating system (OS)|n.|操作系统|The operating system manages hardware and software resources.|
|kernel|n.|内核|The kernel is the core part of the operating system.|
|system call|n.|系统调用|User programs interact with the OS through system calls.|
|shell|n.|外壳程序|The shell provides a command-line interface for the user.|
|user mode|n.|用户模式|User mode restricts access to critical resources.|
|kernel mode|n.|内核模式|Kernel mode allows execution of privileged instructions.|
|interface|n.|接口|The OS provides an interface between users and hardware.|
|boot|v./n.|启动|The computer boots from the system disk.|
|driver|n.|驱动程序|Device drivers translate OS commands into hardware actions.|
|firmware|n.|固件|Firmware provides low-level control for a device.|

---

## ② 进程与线程（Process and Thread）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|process|n.|进程|Each process has its own address space.|
|thread|n.|线程|Threads share the same memory within a process.|
|multitasking|n.|多任务处理|Multitasking allows multiple processes to run concurrently.|
|concurrency|n.|并发|Concurrency improves resource utilization.|
|parallelism|n.|并行性|Parallelism executes tasks simultaneously on multiple cores.|
|context|n.|上下文|The context includes the CPU state and registers.|
|context switch|n.|上下文切换|The OS performs a context switch between processes.|
|process control block (PCB)|n.|进程控制块|The PCB stores all the information about a process.|
|scheduling|n.|调度|The scheduler determines which process runs next.|
|ready queue|n.|就绪队列|The ready queue holds processes waiting for CPU time.|
|dispatch|v.|分派；调度|The scheduler dispatches the highest-priority process.|
|priority|n.|优先级|High-priority processes are executed first.|
|thread synchronization|n.|线程同步|Thread synchronization prevents data inconsistency.|

---

## ③ 同步与通信（Synchronization and Communication）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|synchronization|n.|同步|Synchronization ensures orderly execution of processes.|
|mutual exclusion|n.|互斥|Mutual exclusion allows only one process to access a resource.|
|semaphore|n.|信号量|A semaphore is used to control access to shared resources.|
|mutex|n.|互斥锁|Mutexes prevent concurrent access to critical sections.|
|critical section|n.|临界区|Only one thread can enter the critical section at a time.|
|deadlock|n.|死锁|A deadlock occurs when processes wait for each other indefinitely.|
|starvation|n.|饥饿|Starvation happens when a process never gets CPU time.|
|resource allocation|n.|资源分配|Proper resource allocation prevents deadlocks.|
|interprocess communication (IPC)|n.|进程间通信|IPC allows processes to exchange data.|
|pipe|n.|管道|Pipes provide a unidirectional communication channel.|
|message queue|n.|消息队列|Message queues are used to send structured messages between processes.|
|shared memory|n.|共享内存|Shared memory allows multiple processes to access the same region.|
|signal|n.|信号|Signals are software interrupts used for notification.|

---

## ④ 内存管理（Memory Management）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|memory management|n.|内存管理|Memory management allocates space for processes.|
|address space|n.|地址空间|Each process has its own virtual address space.|
|virtual memory|n.|虚拟内存|Virtual memory allows programs to use more memory than physically available.|
|paging|n.|分页|Paging divides memory into fixed-size blocks.|
|page table|n.|页表|The page table maps virtual addresses to physical addresses.|
|frame|n.|页框|Each frame stores one page of data in main memory.|
|page fault|n.|缺页中断|A page fault occurs when the required page is not in memory.|
|segmentation|n.|段式存储管理|Segmentation divides memory according to logical units.|
|swapping|n.|交换|Swapping moves processes in and out of main memory.|
|fragmentation|n.|碎片|Memory fragmentation reduces available space efficiency.|
|allocation|n.|分配|Dynamic allocation allows flexible memory usage.|

---

## ⑤ 文件系统（File System）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|file system|n.|文件系统|The file system organizes data on storage devices.|
|directory|n.|目录|A directory contains files and subdirectories.|
|path|n.|路径|Each file is identified by its path.|
|inode|n.|索引节点|In UNIX, each file is represented by an inode.|
|metadata|n.|元数据|File metadata includes creation date and permissions.|
|permission|n.|权限|File permissions determine who can read or modify a file.|
|read/write/execute|v.|读/写/执行|The OS controls read, write, and execute access.|
|mount|v.|挂载|The system mounts the file system at startup.|
|partition|n.|分区|The disk is divided into multiple partitions.|
|filesystem hierarchy|n.|文件系统层次结构|Linux uses a hierarchical file system starting from the root.|

---

## ⑥ 输入输出与系统软件（I/O and System Software）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|I/O device|n.|输入输出设备|The OS manages all I/O devices.|
|device controller|n.|设备控制器|Each device controller handles a specific hardware type.|
|buffer|n.|缓冲区|Buffers temporarily store data during I/O operations.|
|interrupt|n.|中断|An interrupt signals the CPU to handle an I/O event.|
|polling|n.|轮询|Polling repeatedly checks the device status.|
|DMA (Direct Memory Access)|n.|直接存储器访问|DMA allows devices to transfer data without CPU intervention.|
|spool|v./n.|假脱机|The system spools print jobs before sending them to the printer.|
|system utility|n.|系统工具|Utilities such as disk management and backup are part of the OS.|
|compiler|n.|编译器|The compiler translates source code into machine code.|
|linker|n.|连接器|The linker combines object files into an executable.|
|loader|n.|装载程序|The loader loads the executable into memory.|
|command interpreter|n.|命令解释器|The shell acts as a command interpreter.|

---

## ✅ 关键词组（常用搭配）

|表达|含义|
|---|---|
|process scheduling algorithm|进程调度算法|
|thread synchronization mechanism|线程同步机制|
|memory allocation strategy|内存分配策略|
|file access permission|文件访问权限|
|device driver interface|设备驱动接口|
|system performance optimization|系统性能优化|
