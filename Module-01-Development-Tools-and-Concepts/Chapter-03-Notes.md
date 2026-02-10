# Chapter 03 – Command Line & Basic Tooling (Week 1 – Session 3)

## 1. Purpose of This Chapter
This chapter introduces the **command-line interface (CLI)** and essential tools used in data science and software workflows.  
The goal is to make students **comfortable working in a terminal** instead of relying only on graphical interfaces.

---

## 2. What is a Command Line Interface (CLI)?
A **CLI** is a text-based interface that allows users to interact with the operating system using commands.

### Why CLI is Important:
- Faster than GUI for repetitive tasks
- Essential for servers and remote machines
- Used heavily in data science, DevOps, and backend work
- Enables automation using scripts

---

## 3. Shell and Terminal Basics

### Terminal
- A program that provides access to the shell
- Examples: Windows Terminal, GNOME Terminal, macOS Terminal

### Shell
- A command interpreter that executes user commands
- Common shells:
  - `bash`
  - `zsh`
  - `sh`

---

## 4. File System Basics

### Key Concepts:
- Everything in Linux is treated as a **file**
- Files are organized in a **tree structure**

### Important Directories:
| Directory | Purpose |
|---------|--------|
| `/` | Root directory |
| `/home` | User files |
| `/bin` | Essential binaries |
| `/etc` | Configuration files |
| `/var` | Logs and variable data |

---

## 5. Basic Navigation Commands

### `pwd`
Prints the current working directory
```bash
pwd
