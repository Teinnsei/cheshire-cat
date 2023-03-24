# WinDbg

## Review

Debugging Tools for Windows

The Windows Debugger (WinDbg) can be used to debug kernel-mode and user-mode code, analyze crash dumps, and examine the CPU registers while the code executes.

## Download

[Download Stable](https://apps.microsoft.com/store/detail/windbg-preview/9PGJGD53TN86)

[Download Preview](https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/)

## Cheat sheet

[windbg.info](http://windbg.info/doc/1-common-cmds.html)

## Plugins

### [Narly](https://code.google.com/archive/p/narly/)

This windbg extension is intended to be able to:

- list /SafeSEH, /GS, DEP, and ASLR info about all loaded modules
- search for ROP gadgets
- other misc utils

```
.load narly
!nmod
```
