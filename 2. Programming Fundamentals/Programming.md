### 1. Fundamentals of Programming
1) A computer's Main part is CPU, it executes all tasks.
2) Processor uses binary to Understand instruction.
3) MLL -> Binary Code
4) ALL -> Mnemonics (ADD, SUB)
5) HLL -> English like Syntax
6) Compiler Converts HLL to MLL so the Processor can Understand it.

### 2. Memory Unit in a Computer
1) HDD stores data permanently but slow and mechanical.
2) RAM is faster (Semiconductor Based) but Volatile (data lost on power off).
3) Cache Memory sits between CPU and RAM to speed up tasks.
4) Memory Hierarchy : CPU > Cache > RAM > HDD

### 3. Platform and Platform Dependency
1) A Platform = hardware + software (OS like Windows, Linux, macOS).
2) A Programme compiled on one OS (Like Windows .exe ) won't run on another - it's platform-dependent.
3) Example: C Programs create platform-dependent execution.

### 4. How Java Made Platform Independent
1) Java Uses a Javac Compiler to convert code into bytecode (Intermediate Form).
2) JVM converts bytecode into Machine Code for each OS.
3) Every OS has its own JVM, Making Java Platform-Independent - Write Once and Run Anywhere (WORA).