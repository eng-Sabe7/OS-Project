# Simple Shell & Mini-FAT File System (Python)

**Course:** Operating Systems (CS321)
**Instructor:** Prof. Khaled F. Hussain
**Faculty:** Computers and Information, Assiut University

## Overview

A simple shell interface with a Mini-FAT file system supporting subdirectories. The system simulates a virtual disk using a regular file and allows basic file and directory operations. It is designed to be stable and not crash during execution.

## Python Version

This project is a full rewrite of the original C# version using pure Python (standard library), including disk simulation, FAT structure, and shell commands.

## Supported Commands

`cd`, `cls`, `dir`, `quit`, `copy`, `del`, `help`, `md`, `rd`, `rename`, `type`, `import`, `export`

## Run

```bash
cd OS_Project
python main.py
```

## Directory Entry (32 bytes)

* Name (11 bytes): filename (8+3)
* Attribute (1 byte): file (0x0) / directory (0x10)
* Unused (12 bytes)
* First Cluster (4 bytes)
* File Size (4 bytes)

## Author

**Ahmad Sobeh**
📧 [ahmadaymansobeh@gmail.com]
