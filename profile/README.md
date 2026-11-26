# clang-retro
 
clang-retro adds 16-bit and 32-bit targets for retro systems to LLVM and clang.
With it, you can compile modern C and C++ for DOS, Windows 1.x to Windows 11, OS/2,
CP/M, classic Mac OS, AmigaOS, Atari TOS, 6502 systems and classic UNIX.
Each SDK gives a C library, system headers, examples and tests. Tests run
in emulators.
 
## Repositories
 
| Repository | Description |
| --- | --- |
| [llvm](https://github.com/clang-retro/llvm) | LLVM and clang with 16-bit and 32-bit targets for retro systems: DOS, 16-bit Windows, OS/2, CP/M, classic Mac OS (68k and PowerPC), AmigaOS, Atari TOS, Z80 and more. |
| [picolibc](https://github.com/clang-retro/picolibc) | Picolibc C library with system layers for retro targets: DOS, Windows, OS/2, CP/M, AmigaOS, Atari TOS, IRIX, Solaris and BSD. |
| [dos-sdk](https://github.com/clang-retro/dos-sdk) | SDK for DOS programs with clang: builds the 8086 DOS sysroot (picolibc and libc++) for all memory models, and the clang-retro toolchain packages. |
| [jwlink](https://github.com/clang-retro/jwlink) | JWlink linker for OMF, COFF and ELF objects. It makes DOS, Windows, OS/2 and VxD binaries. clang-retro uses it for its 16-bit targets. |
| [mac-sdk](https://github.com/clang-retro/mac-sdk) | SDK for classic Mac OS applications on 68k and PowerPC (System 0.1 to Mac OS 9): Toolbox headers, libraries and examples for clang. |
| [amiga-sdk](https://github.com/clang-retro/amiga-sdk) | SDK for AmigaOS programs (Kickstart 1.3 to 3.x, all 68k CPUs): C library, AmigaOS headers, libamiga and examples for clang. |
| [win16-sdk](https://github.com/clang-retro/win16-sdk) | SDK for 16-bit Windows programs (Windows 1.x to 3.x): Windows 3.1 API headers, import lists and library build scripts for clang. |
| [win32-sdk](https://github.com/clang-retro/win32-sdk) | SDK for 32-bit and 64-bit Windows programs with clang: mingw-w64 sysroots for Win32s, Windows 95 to ME and Windows NT 3.1 to 11, with C++ libraries and tests. |
| [atari-sdk](https://github.com/clang-retro/atari-sdk) | SDK for Atari ST, STe, TT and Falcon programs (TOS 1.0 to 4.x and EmuTOS): C library, GEMDOS, BIOS and XBIOS calls, and GEM AES and VDI for clang. |
| [mfc](https://github.com/clang-retro/mfc) | Independent implementation of the Microsoft Foundation Classes (MFC) API. It builds MFC programs with clang or MinGW-w64, without Visual C++. |
| [os2-sdk](https://github.com/clang-retro/os2-sdk) | SDK for OS/2 programs with clang: 16-bit OS/2 1.x (NE) and 32-bit OS/2 2.0 to ArcaOS (LX). Headers, Presentation Manager and DLL tools. |
| [clang-retro.github.io](https://github.com/clang-retro/clang-retro.github.io) | Source of the clang-retro website. |
| [opencow](https://github.com/clang-retro/opencow) | Archive of Opencow, an open-source Microsoft Layer for Unicode. clang-retro/unicows replaces it. |
| [unicows](https://github.com/clang-retro/unicows) | Free replacement for the Microsoft Layer for Unicode (unicows.dll). It lets Unicode programs run on Windows 95, 98 and ME. |
| [unix-sdk](https://github.com/clang-retro/unix-sdk) | Sysroots, examples and tests for classic UNIX systems with clang: SGI IRIX, Solaris (SPARC and x86), FreeBSD and NetBSD. |
| [cpm-sdk](https://github.com/clang-retro/cpm-sdk) | SDK for CP/M programs with clang: CP/M-86 on the 8086, and CP/M-80 on the Z80, 8080 and 8085. C library, BDOS calls and an emulator. |
| [mos-sdk](https://github.com/clang-retro/mos-sdk) | SDK for 6502 computers and consoles (Commodore, Apple II, Atari, NES and more). It is the llvm-mos SDK, built with clang-retro. |
| [softgl](https://github.com/clang-retro/softgl) | Software renderer for OpenGL 1.1 with GLU 1.3, on the design of the Windows NT opengl32.dll. It runs on a 68000 without a floating-point unit. |
 
For the full documentation, see the [clang-retro website](https://clang-retro.github.io/).
 
