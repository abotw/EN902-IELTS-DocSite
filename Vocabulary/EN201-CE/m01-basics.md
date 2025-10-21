---
parent: EN201-CE
title: "M01: 计算机基础"
---

# M01: 计算机基础

（共约 80 词，按主题分类，含词性、中文释义与例句）

## ① 计算机组成（Computer Architecture）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|architecture|n.|架构；体系结构|The computer’s architecture determines how data flows between components.|
|component|n.|组件；部件|Each component of the computer has a specific function.|
|processor|n.|处理器|The processor executes instructions sequentially.|
|core|n.|核心；内核|A multi-core CPU can handle multiple tasks simultaneously.|
|register|n.|寄存器|Registers store intermediate data for faster access.|
|bus|n.|总线|The system bus connects the CPU, memory, and I/O devices.|
|address bus|n.|地址总线|The address bus carries memory addresses.|
|data bus|n.|数据总线|The data bus transfers binary data.|
|control unit|n.|控制器|The control unit manages the execution of instructions.|
|ALU (Arithmetic Logic Unit)|n.|算术逻辑单元|The ALU performs arithmetic and logic operations.|
|instruction|n.|指令|Each instruction tells the CPU what to do.|
|instruction set|n.|指令集|The instruction set defines the capabilities of a processor.|
|clock|n.|时钟|The system clock synchronizes all operations.|
|clock cycle|n.|时钟周期|Each instruction takes several clock cycles to execute.|
|frequency|n.|频率|CPU frequency is measured in hertz (Hz).|
|throughput|n.|吞吐量|High throughput indicates good system performance.|

---

## ② 数据表示（Data Representation）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|binary|adj./n.|二进制的；二进制数|Computers represent all data in binary form.|
|bit|n.|位（binary digit）|A bit is the smallest unit of information.|
|byte|n.|字节（8位）|One byte can store a single ASCII character.|
|word|n.|字（数据字）|A 32-bit word contains four bytes.|
|signed number|n.|有符号数|Signed numbers can represent negative values.|
|unsigned number|n.|无符号数|Unsigned integers cannot represent negative values.|
|overflow|n.|溢出|Overflow occurs when a result exceeds the available bits.|
|two’s complement|n.|二进制补码|Negative integers are represented in two’s complement form.|
|floating point|n.|浮点数|Floating point numbers can represent fractions.|
|exponent|n.|指数|The exponent determines the scale of the floating-point number.|
|mantissa|n.|尾数|The mantissa stores the significant digits.|
|ASCII|n.|美国信息交换标准码|ASCII encodes characters using 7 bits.|
|Unicode|n.|统一码|Unicode supports characters from multiple languages.|

---

## ③ 存储与层次结构（Memory Hierarchy）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|memory|n.|存储器|Memory stores data and instructions for processing.|
|cache|n.|高速缓存|Cache memory provides faster access than main memory.|
|main memory|n.|主存；内存|Main memory holds data temporarily while the CPU runs.|
|RAM (Random Access Memory)|n.|随机存取存储器|RAM is volatile and loses data when power is off.|
|ROM (Read Only Memory)|n.|只读存储器|ROM stores firmware permanently.|
|storage|n.|存储设备|Secondary storage includes SSDs and hard drives.|
|SSD (Solid State Drive)|n.|固态硬盘|SSDs are faster and more reliable than HDDs.|
|hierarchy|n.|层次结构|The memory hierarchy balances speed and cost.|
|latency|n.|延迟|Cache reduces memory access latency.|
|bandwidth|n.|带宽|Higher memory bandwidth improves data transfer speed.|

---

## ④ 输入输出系统（Input/Output System）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|input device|n.|输入设备|A keyboard is an example of an input device.|
|output device|n.|输出设备|A monitor is an output device.|
|interface|n.|接口|The USB interface connects external devices.|
|port|n.|端口|Each port allows communication between devices.|
|driver|n.|驱动程序|Device drivers control hardware components.|
|interrupt|n.|中断|Interrupts signal the CPU to handle urgent tasks.|
|DMA (Direct Memory Access)|n.|直接存储器访问|DMA allows peripherals to access memory directly.|

---

## ⑤ 逻辑电路与数据通路（Logic and Datapath）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|logic gate|n.|逻辑门|AND, OR, and NOT gates are basic logic gates.|
|combinational circuit|n.|组合电路|The output of a combinational circuit depends only on inputs.|
|sequential circuit|n.|时序电路|A flip-flop is a basic sequential circuit element.|
|flip-flop|n.|触发器|Flip-flops are used to store one bit of data.|
|latch|n.|锁存器|Latches are level-triggered storage elements.|
|multiplexer (MUX)|n.|多路选择器|A multiplexer selects one input from several signals.|
|decoder|n.|译码器|The decoder activates one output line based on binary input.|
|encoder|n.|编码器|The encoder converts active input lines into binary code.|
|counter|n.|计数器|A counter increases by one for each clock pulse.|
|register file|n.|寄存器组|The register file stores multiple temporary variables.|
|datapath|n.|数据通路|The datapath moves and processes data in the CPU.|

---

## ⑥ 性能与评估（Performance & Evaluation）

|词汇|词性|中文释义|英文例句|
|---|---|---|---|
|performance|n.|性能|Performance depends on clock speed and memory access time.|
|efficiency|n.|效率|The new design improves energy efficiency.|
|benchmark|n.|基准测试|Benchmarks are used to compare system performance.|
|instruction per cycle (IPC)|n.|每周期指令数|IPC measures how many instructions are executed per clock cycle.|
|MIPS (Million Instructions Per Second)|n.|每秒百万条指令|MIPS is a common measure of CPU performance.|
|pipeline|n.|流水线|Pipelining allows overlapping of instruction execution.|
|hazard|n.|冒险（流水线冲突）|Data hazards occur when instructions depend on previous results.|
