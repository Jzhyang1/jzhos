# JzhOS
A basic implementation x86-64 of a modular OS that supports most Linux syscalls. Prioritizes performance above all else

## Components
* Boot
* Kernel
* User system
* Drivers

## System Information

### File System
* EXT4 file system
* Bootstraper at `/k/b` (only runs with the custom JzhOS bootloader)
* Kernel at `/k/k`
* Init program at `/k/i`

### Program Memory Layout
* Kernel space: 0x00000000 - 0x10000000

