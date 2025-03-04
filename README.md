Hammer & Sickle OS
==================

**Hammer & Sickle OS** is a parody operating system inspired by the themes of the Soviet Union This humorous and low-level operating system features a custom bootloader (`JosephStalin`), a kernel called `The KGB`, and a FAT32 (VERY WIP) filesystem. The project provides a deep dive into system programming with a lighthearted take on Soviet themes.

Features:
---------

*   **Bootloader (`JosephStalin`)**: A multi-stage bootloader that sets up the system and loads the kernel.
*   **Kernel (`The KGB`)**: The core of the OS responsible for managing system resources.
*   **Filesystem**: A FAT32 (VERY WIP) filesystem with a custom directory layout
*   **Soviet-Themed**: A playful reference to the USSR, with directories named `comrade_shared` and `red_bureau`.

Installation:
-------------

1.  Clone the repository:
    
        git clone https://github.com/yourusername/Hammer-And-Sickle-OS.git
        cd Hammer-And-Sickle-OS
    
2.  Install dependencies:
    *   **NASM**: You will need NASM (Netwide Assembler) to assemble the OS
    *   **python**: You need python version 3.X.X to run the build scripts
    *   **gcc**: For building higher level things because Assembly is physically painful to code in
    *   **A VM**: Not required but strongly recomended as it suports runing QEMU after building
3.  Build the project using `make` **NOTE**: on Windows you need to build ith with WSL (Windows Subsystem For Linux)

Project Structure:
------------------

    Hammer & Sickle OS
    ├── JosephStalin
    │   ├── stage1.asm
    │   └── stage2.asm
    ├── KGB
        ├── entry.asm
        └── kernel.c

Contributing:
-------------

Contributions are welcome! Feel free to fork the repository, make changes, and submit pull requests.
