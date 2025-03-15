#  Linux Commands Cheat Sheet

## 📖 Introduction
This guide covers essential Linux commands for beginners. These commands will help you navigate directories, manage files, and perform administrative tasks efficiently.

---

## 📂 **File & Directory Management**
These commands will help you manage files and directories efficiently in Linux. Keep practicing, and you'll get comfortable navigating the terminal! 🚀


| Command | Description |
|---------|-------------|
| `ls` | Lists files and directories in the current location. |
| `ls -l` | Displays files with details like permissions, size, and date modified. |
| `ls -a` | Shows hidden files (files starting with `.`). |
| `pwd` | Prints the current working directory. |
| `cd <directory>` | Changes to a specified directory. Example: `cd Documents/` |
| `cd ..` | Moves up one directory level. |
| `mkdir <directory>` | Creates a new directory. |
| `rm <file>` | Deletes a file. |
| `rm -r <directory>` | Deletes a directory and its contents. |
| `cp <source> <destination>` | Copies a file or directory. |
| `mv <source> <destination>` | Moves or renames a file/directory. |
| `cat <file_name>` | Prints the contents of a file. |
| `touch <file_name>` | Creates a new empty file. |
| `find /path -name "file.txt"` | Searches for a file by name in a specified directory. |
| `du -sh <directory>` | Shows the total size of a directory in human-readable format. |
| `df -h` | Displays available and used disk space in human-readable format. |

---


## 📄 **File Viewing & Editing**

| Command | Description |
|---------|-------------|
| `cat <file>` | Displays the contents of a file. |
| `nano <file>` | Opens a file for editing in the Nano text editor. |
| `vim <file>` | Opens a file for editing in the Vim editor (advanced users). |
| `less <file>` | Allows scrolling through a file's content. |
| `head <file>` | Displays the first 10 lines of a file. |
| `tail <file>` | Displays the last 10 lines of a file. |
| `echo "text" > file.txt` | Writes text to a file, replacing existing content. |
| `echo "text" >> file.txt` | Adds text to the end of a file without removing existing content. |

---

## 🔍 **Searching & Finding Files**

| Command | Description |
|---------|-------------|
| `find /path -name "file.txt"` | Searches for a file by name. |
| `grep "word" file.txt` | Searches for a word inside a file. |
| `grep -r "word" /directory/` | Searches for a word in all files within a directory. |

---

## 🔄 **File Permissions & Ownership**

| Command | Description |
|---------|-------------|
| `ls -l` | Shows file permissions. |
| `chmod 777 file` | Changes file permissions (`777` = full access). |
| `chown user:group file` | Changes file owner and group. |

---

## ⚙️ **System Information**

| Command | Description |
|---------|-------------|
| `uname -a` | Displays system information. |
| `df -h` | Shows disk space usage. |
| `free -m` | Displays available memory (RAM). |
| `top` | Shows active processes and system performance. |
| `uptime` | Displays how long the system has been running. |
| `whoami` | Prints the current logged-in user. |

---

## 🛠️ **Process Management**

| Command | Description |
|---------|-------------|
| `ps aux` | Lists running processes. |
| `kill <PID>` | Kills a process using its Process ID (PID). |
| `killall <process_name>` | Kills all processes with a specific name. |
| `htop` | Interactive process monitoring tool (install if unavailable). |

---

## 🌐 **Networking Commands**

| Command | Description |
|---------|-------------|
| `ping <website>` | Tests connectivity to a website (e.g., `ping google.com`). |
| `ifconfig` | Displays network interface details (use `ip a` on newer systems). |
| `netstat -tulnp` | Shows active network connections. |
| `curl -I <website>` | Fetches HTTP headers of a website. |

---

## 🔑 **User Management**

| Command | Description |
|---------|-------------|
| `who` | Lists logged-in users. |
| `adduser <username>` | Adds a new user. |
| `passwd <username>` | Changes the password for a user. |
| `deluser <username>` | Deletes a user account. |
| `sudo <command>` | Runs a command with superuser privileges. |
| `su <username>` | Switches to another user account. |
| `id <username>` | Displays the user ID (UID) and group ID (GID) of a user. |

---

## 🔥 **Other Useful Commands**

| Command | Description |
|---------|-------------|
| `history` | Shows previously used commands. |
| `clear` | Clears the terminal screen. |
| `exit` | Logs out of the terminal session. |
| `reboot` | Restarts the system. |
| `shutdown -h now` | Shuts down the system immediately. |

---
