# Linux Commands List - Ultimate Linux Course 🐧

![Go Programming Banner](https://miro.medium.com/v2/resize:fit:1400/0*Qqqd7UsfFDPL7WXh.jpeg)

## Introduction

This document compiles essential commands covered in the "Ultimate Linux" course by Hola Mundo. The course takes students from basics to advanced Linux system administration, including:

- Linux OS fundamentals
- File navigation and management
- User and permission management
- Process administration
- Basic networking

## Table of Contents
- [Navigation](#navigation)
- [File Manipulation](#file-manipulation)
- [Permissions](#permissions)

## Navigation

| Command | Description | Example |
|---------|-------------|---------|
| `pwd` | Print working directory | `pwd` <br> Output: /home/user |
| `cd` | Change directory | `cd Documents` <br> `cd ..` <br> `cd ~` |
| `ls` | List directory contents | `ls -la` <br> `ls Documents` <br> `ls -R` |

## File Manipulation

| Command | Description | Example |
|---------|-------------|---------|
| `cp` | Copy files and directories | `cp file.txt ~/Documents` <br> `cp -r folder destination` <br> `cp *.txt destination` |
| `mv` | Move or rename files | `mv file.txt newfile.txt` <br> `mv file.txt ~/Documents` <br> `mv folder newfolder` |
| `rm` | Remove files or directories | `rm file.txt` <br> `rm -r folder` <br> `rm -f file.txt` |

## Permissions

| Command | Description | Example |
|---------|-------------|---------|
| `chmod` | Modify file permissions | `chmod 755 script.sh` <br> `chmod +x file` <br> `chmod -R 644 folder` |
| `chown` | Change file owner | `chown user file.txt` <br> `chown -R user:group folder` <br> `chown :group file` |

---
**Note**: This document will be updated as we progress through the Ultimate Linux course by Hola Mundo.
