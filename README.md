# hello-assembly
Hello World Assembly

nasm -f elf64 -o hello.o hello.asm

ld -s -o hello hello.o

(bash) ./hello