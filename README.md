# Linux Bash Scripting Project

This project contains a collection of essential Linux Bash scripts designed to perform various system administration, monitoring, and text processing tasks. It serves as a practical demonstration of shell scripting capabilities in a Unix-like environment.

## Scripts Overview

1. **System Identity Report (`script1.sh`)**: Displays essential system information including the kernel version, current user, system uptime, and the current date and time.
2. **Git Installation Checker (`script2.sh`)**: Checks whether the `git` version control system is installed via the `dpkg` package manager, and displays its version if available.
3. **Directory Information (`script3.sh`)**: Analyzes and reports the disk usage and directory permissions/ownership for key system directories: `/etc`, `/home`, and `/usr`.
4. **Error Counter (`script4.sh`)**: A text processing script that reads a user-specified file line by line and counts the total number of occurrences of the word "error" (case-insensitive).
5. **Simple Manifesto (`script5.sh`)**: An interactive script that prompts the user for inputs about their preferred tool, meaning of freedom, and building goals, and then generates a simple customized manifesto.

## Prerequisites

- A Linux/Unix-like operating system (or WSL on Windows).
- Bash shell (Bourne Again SHell).
- `dpkg` package manager (specifically for `script2.sh`).

## Usage

To run any of the scripts, you must first make them executable:

```bash
chmod +x script1.sh
./script1.sh
```
