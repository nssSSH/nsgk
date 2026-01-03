# NSGK: Not So Good Kernel


This is a kernel made only for learning purposes (I dont claim this kernel as mine because of the number of tutorials I followed). Made from Youtube and a bit of googling. All rights to their respective owners. 

## Installation

1. Git clone this repo and cd into the repo
```shell

https://github.com/nssSSH/nsgk.git && cd nsgk
```

2. Run make command (no need to configure anything, as Makefile is already here.)

```shell
make
```

3. Run the image with qemu.

```shell
qemu-system-i386 -fda build/main_floppy.img
```

That's it. 


------------ 

## Requirements


You need a Linux machine as certain commands such as Truncate are in the Makefile. Or just install them in your system. Your choice. 

- Make (for building)
- nasm (netwide assembler)
- qemu (or any other VM software. I used qemu.)

That's about it. I'll add some more things as I learn.



## What it currently does and what it doesn't 

- Boots 
- Prints text to the screen

What it doesn't doesn't do 

- No memory management
- No multitasking
- No filesystem
- No user input

Very bare bones. I will slowly add these.
