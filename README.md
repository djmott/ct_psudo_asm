# ct_psudo_asm

This example is a demonstration of compile-time features and capabilities of the c++ language. C++ contains enough compile time semantic and syntactic creativity to embed other languages within it. In this respect, C++ can be considered a language defining language as demonstrated here.

The challenge here is to consume some arbitrary pseudo assembler code and convert it to c++. The assembler code adheres to a well-defined language spec and since it’s result is deterministic the compiler should optimize it all away. At run-time, the execution should produce zero processor instructions that perform the calculations.

