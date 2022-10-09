
# Ultron OS
---------------------
An x86 operating system created in C++ is called Ultron OS. It can boot, initialise the GDT and IDT, and perform a few other tasks that operating systems are expected to perform.
  
**Author :** @aswinmohanme

------------------------
- [Ultron OS](#)
	- [Description](#)
	- [Installation](#)
		- [Requirements](#)
		- [Getting the Source](#)
		- [Compiling](#)
		- [Testing](#)

------------------------
## Description
OOP was a consideration when creating Ultron, and it has been fulfilled in every way conceivable..

---------------------------------------
## Installation
### Requirements
For Compiling the Operating System image it is required that these dependencies must be met.
> * Any ***nix** like system
> * The GNU **GCC** compiler Toolchain
> * Netwide Assembler **NASM**
> * GNU **Make**
> * GNU general linker **ld**
> * Astlye Formatter

For Testing the Operating System it is recommended to use
> **Qemu** the Emulator of our Choice  

-------------------------------
### Getting the Source
The most recent Source Code is hosted on *https://github.com/aswinmohanme/Ultron-OS*

> **How to get the most Recent Version **


```bash
# Get the Updated Source from github
git clone https://github.com/aswinmohanme/Ultron-OS
```

### Compiling
```
# Change the Directory into the Current One
cd Ultron-OS
# Run Make at the root of the project
make
```

### Testing
Make sure you have installed **qemu** on your system. From the project root run
```
# This Command Runs the OS on an Emulated Machine
make run
```

Thanks !! Enjoy
