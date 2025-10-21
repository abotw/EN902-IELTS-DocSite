---
parent: EN201-CE
title: "M03: Lang"
---
# 模块三：**编程语言与开发工具**（Programming Languages & Development Tools）

## ① 基础概念（Core Concepts）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|programming language|n.|编程语言|Python is a popular high-level programming language.|
|syntax|n.|语法|Syntax errors occur when code violates the language grammar.|
|semantics|n.|语义|Semantics define the meaning of syntactically correct statements.|
|source code|n.|源代码|Developers modify the source code and then build the program.|
|statement|n.|语句|A conditional statement controls program flow.|
|expression|n.|表达式|An expression evaluates to a value.|
|identifier|n.|标识符|Variable names and function names are identifiers.|
|literal|n.|字面量|`42` and `"hello"` are literals.|

---

## ② 编译与运行（Compilation & Execution）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|compiler|n.|编译器（将源代码翻译为可执行代码）|The compiler turns C code into machine code.|
|interpreter|n.|解释器（逐行执行源代码）|Python uses an interpreter to execute scripts.|
|bytecode|n.|字节码（中间代码）|Java compiles source code into bytecode for the JVM.|
|runtime|n.|运行期；运行时环境|The runtime provides services like memory allocation.|
|virtual machine (VM)|n.|虚拟机|The Java Virtual Machine executes Java bytecode.|
|JIT (Just-In-Time) compiler|n.|即时编译器|JIT improves performance by compiling hot code paths.|
|linking|n.|链接|The linker resolves references between object files.|
|static linking|n.|静态链接|Static linking includes libraries into the executable.|
|dynamic linking|n.|动态链接|Dynamic linking loads shared libraries at runtime.|
|ABI (Application Binary Interface)|n.|应用二进制接口|The ABI defines calling conventions and binary formats.|
|calling convention|n.|调用约定|The calling convention determines how arguments are passed.|

---

## ③ 语言特性（Language Features）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|static typing|n.|静态类型（编译时类型检查）|Static typing can catch many errors at compile time.|
|dynamic typing|n.|动态类型（运行时类型检查）|Dynamic typing makes development faster but may hide bugs.|
|strong typing|n.|强类型|A strongly typed language enforces type rules strictly.|
|weak typing|n.|弱类型|Weak typing allows implicit conversions that may be unsafe.|
|type system|n.|类型系统|The type system helps prevent illegal operations.|
|generics|n.|泛型（参数化类型）|Generics enable type-safe collections like `List<T>`.|
|polymorphism|n.|多态|Polymorphism allows a function to handle different types.|
|encapsulation|n.|封装|Encapsulation hides implementation details from users.|
|inheritance|n.|继承|Inheritance lets a class reuse behavior from a parent class.|
|interface|n.|接口|An interface defines a contract of methods.|
|lambda / anonymous function|n.|匿名函数|Lambdas make it easy to pass small functions as arguments.|
|closure|n.|闭包|A closure captures variables from its surrounding scope.|
|recursion|n.|递归|Recursive functions call themselves with smaller inputs.|
|mutable / immutable|adj.|可变 / 不可变|Strings are immutable in many languages like Java.|
|pointer|n.|指针|C uses pointers to reference memory addresses directly.|
|reference|n.|引用|References provide indirect access to variables.|
|garbage collection|n.|垃圾回收|Garbage collection automatically reclaims unused memory.|
|manual memory management|n.|手动内存管理|C requires manual memory allocation and freeing.|

---

## ④ 并发与异步（Concurrency & Asynchrony）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|concurrency|n.|并发|Concurrency allows multiple tasks to make progress simultaneously.|
|parallelism|n.|并行|Parallelism executes tasks simultaneously on multiple cores.|
|thread|n.|线程|Each thread can run a separate execution path.|
|process|n.|进程|Processes have separate memory spaces.|
|multi-threading|n.|多线程|Multi-threading can improve responsiveness.|
|synchronization|n.|同步|Synchronization prevents race conditions.|
|race condition|n.|竞态条件|Race conditions occur when access to shared data is unsynchronized.|
|lock / mutex|n.|锁 / 互斥量|Use a mutex to protect critical sections.|
|semaphore|n.|信号量|Semaphores control access to limited resources.|
|deadlock|n.|死锁|Deadlocks can freeze multiple threads forever.|
|thread pool|n.|线程池|A thread pool reuses threads to handle many tasks.|
|async / await|n./v.|异步 / 等待|Async/await simplifies asynchronous programming.|
|callback|n.|回调|Callbacks are invoked when an operation completes.|
|event loop|n.|事件循环|The event loop processes asynchronous callbacks in single-threaded environments.|

---

## ⑤ 编程范式（Programming Paradigms）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|imperative programming|n.|命令式编程|Imperative code describes _how_ to perform tasks step by step.|
|declarative programming|n.|声明式编程|Declarative code describes _what_ the outcome should be.|
|object-oriented programming (OOP)|n.|面向对象编程|OOP organizes code using objects and classes.|
|functional programming|n.|函数式编程|Functional programming treats functions as first-class citizens.|
|procedural programming|n.|过程式编程|Procedural code groups instructions into procedures or functions.|
|reactive programming|n.|响应式编程|Reactive programming handles data streams and propagation of change.|

---

## ⑥ 开发工具（Development Tools）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|IDE (Integrated Development Environment)|n.|集成开发环境|Many developers use an IDE like VS Code or IntelliJ.|
|text editor|n.|文本编辑器|Lightweight editors like Vim are popular for quick edits.|
|debugger|n.|调试器|The debugger lets you step through code and inspect variables.|
|profiler|n.|性能分析器|Use a profiler to find bottlenecks in your program.|
|linter|n.|代码风格检查工具|Linters catch style issues and potential bugs early.|
|formatter|n.|代码格式化工具|A formatter enforces consistent code style.|
|REPL (Read-Eval-Print Loop)|n.|交互式解释器|The Python REPL is helpful for quick experiments.|

---

## ⑦ 构建 / 包管理 / 部署（Build, Package & Deployment）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|build system|n.|构建系统（如 Make, CMake, Gradle）|A build system compiles and links the project automatically.|
|makefile|n.|Make 构建脚本|The makefile defines build targets and dependencies.|
|CI/CD|n.|持续集成 / 持续部署|CI/CD pipelines run tests and deploy code automatically.|
|package manager|n.|包管理器（npm, pip, Maven）|Use a package manager to install third-party libraries.|
|dependency|n.|依赖|Keep dependencies up to date to avoid vulnerabilities.|
|versioning|n.|版本管理|Semantic versioning (MAJOR.MINOR.PATCH) is widely used.|
|container|n.|容器（如 Docker）|Containers package applications with their environment.|
|image|n.|镜像（容器镜像）|Pull the Docker image before running the container.|
|orchestration|n.|编排（如 Kubernetes）|Kubernetes handles container orchestration in production.|

---

## ⑧ 调试与测试工具（Debugging & Testing Tools）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|unit test|n.|单元测试|Write unit tests to verify individual functions.|
|integration test|n.|集成测试|Integration tests check interactions between components.|
|test runner|n.|测试运行器|The test runner executes your test suite and reports failures.|
|mocking|n.|模拟（测试替身）|Use mocking to isolate components during tests.|
|breakpoint|n.|断点|Set a breakpoint to pause execution at a specific line.|
|stack trace|n.|堆栈跟踪|A stack trace shows the call sequence leading to an error.|
|core dump|n.|核心转储|A core dump helps analyze a program crash post-mortem.|

---

## ⑨ 性能与内存（Performance & Memory）

|词汇|词性|中文释义|英文例句|
|---|--:|---|---|
|time complexity|n.|时间复杂度|Big O notation describes an algorithm's time complexity.|
|space complexity|n.|空间复杂度|Space complexity measures memory usage.|
|profiling|n.|性能剖析|Profiling reveals hotspots in the code.|
|memory leak|n.|内存泄漏|Memory leaks cause increasing memory usage over time.|
|stack|n.|栈（调用栈、栈内存）|Local variables are usually stored on the stack.|
|heap|n.|堆（动态分配）|Objects allocated at runtime usually live on the heap.|
|optimization|n.|优化|Optimize only after profiling identifies bottlenecks.|

---

## 常用短语 & 写作表达（Helpful Phrases）

- "The program crashes with a segmentation fault when ..."
    
- "This function returns `null` if the input is invalid."
    
- "Use a profiler to identify performance bottlenecks."
    
- "Refactor the module to reduce coupling and improve cohesion."
    
- "The CI pipeline runs unit tests on each commit."
    
