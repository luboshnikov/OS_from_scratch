# OS_from_scratch

## Description

A small 32-bit operating system created from scratch using assembler and Clang. It can write lines on the screen.

## Screenshot
![os_from_scratch](https://user-images.githubusercontent.com/62390397/175969520-facf0cd3-c43c-48a4-a500-c1674c96eabc.png)

## Requirements:

* qemu emulator
* Linux OS

## Run 

To run this operating system, you need to install the required packages: 

* gmp
* mpfr
* libmpc
* gcc

Then build binutils and cross-compiler, you can use [this link](https://wiki.osdev.org/GCC_Cross-Compiler)

Change the path to gcc and gdb in the Makefile if your cross compiler is not in `/usr/local/`

## References:
[os-tutorial](https://github.com/cfenollosa/os-tutorial)

[OSDev.org](https://wiki.osdev.org/Main_Page)
