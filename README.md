# windowsapp1

This repository contains a minimal Windows application that pops up a
**Hello world** message.

## Building on Windows

From a Visual Studio Developer Command Prompt, compile the program with:

```cmd
cl main.c user32.lib
```

Alternatively, using MinGW's gcc:

```bash
gcc main.c -luser32 -o main.exe
```

Run `main.exe` to see the message box.
