# CM32
MMURTL, a 32 Bit Computer Operating System by Richard A. Burgess, includes a C compiler, CM32, that compiles C code into Assembler which is then passed through DASM, a 32-Bit Intel-Based Assembler that is also include with MMURTL.

The code in this repository is all found in a single file CM32.c which has all the non-library header files 'in-lined'. This was done to make studying the code easier for me. Using Visual Studio 2022 Community Edition, CM32.c compiles successfully with addition of 3 #pragma statements. However it does not excute correctly, due to these definitions which are correctd in commit a991ced:

#define U32 unsigned long

#define S32 long

#define U16 unsigned int

#define S16 int