## Compile and Run Assembly

Compile using elf64:
- nasm -f elf64 hello.asm -o hello

Compile as 32 bits: 
- nasm -f elf hello.asm -o hello

Prepare execution file:
- ld -s -o hello hello.o

Run:
./hello

Source: http://www.tutorialspoint.com/assembly_programming/assembly_basic_syntax.htm
