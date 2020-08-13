# Reverse Shell TCP in NASM x86-64
![alt text](https://i.imgur.com/6273P8r.png)
# How to compile 64-bit ELF binary

```bash
nasm -f elf32 -o <filename>.o <filename>.asm
ld -m elf_i386 -o <filename> <filename>.o
```
