# GAS Hello, World!
Hello, World! but wrote in assembly with AT&amp;T Syntax

Assemble:
```
as --32 -o hello.o hello.S
ld -m elf_i386 -o hello hello.o
```
Run:
```
./hello
```
