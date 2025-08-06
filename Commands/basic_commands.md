# 🖥️ Command Prompt (CMD) Commands - Windows

This file contains a list of commonly used **Command Prompt (CMD)** commands in **Windows**, along with their **descriptions**.

---

## 📁 Basic Commands

| Command           | Description                                     |
|-------------------|-------------------------------------------------|
| `dir`             | Lists files and directories in the current path |
| `cd`              | Changes the current directory                   |
| `cls`             | Clears the screen                               |
| `echo`            | Displays messages or turns command echoing on/off |
| `exit`            | Exits the command prompt                        |
| `help`            | Provides help information for commands          |

---

## 📂 File and Folder Management

| Command                   | Description                                          |
|---------------------------|------------------------------------------------------|
| `copy source dest`        | Copies files from source to destination              |
| `xcopy source dest /s /e` | Copies directories and subdirectories, including empty ones |
| `move source dest`        | Moves files or renames a file or directory           |
| `del filename`            | Deletes one or more files                            |
| `rmdir /s foldername`     | Deletes a folder and all its contents                |
| `mkdir foldername`        | Creates a new directory                              |

---

## 🌐 Network Commands

| Command             | Description                                       |
|---------------------|---------------------------------------------------|
| `ipconfig`          | Displays IP address and network configuration     |
| `ping hostname`     | Checks network connectivity                       |
| `tracert hostname`  | Traces the route taken to reach a host            |
| `netstat`           | Displays active connections and listening ports   |
| `nslookup domain`   | Queries DNS for domain name or IP address         |

---

## 💻 System Information

| Command             | Description                                 |
|---------------------|---------------------------------------------|
| `systeminfo`        | Shows detailed configuration info            |
| `tasklist`          | Lists all running tasks and their details    |
| `taskkill /PID id`  | Terminates task using its PID                |
| `set`               | Views or sets environment variables          |
| `ver`               | Displays the Windows OS version              |

---

## 💽 Disk Management

| Command          | Description                                |
|------------------|--------------------------------------------|
| `chkdsk`         | Checks disk for file system errors         |
| `diskpart`       | Opens disk partitioning utility            |
| `format`         | Formats a specified drive                  |
| `label`          | Changes or creates volume label            |
| `vol`            | Displays disk volume label and serial      |

---

## 👥 User Management

| Command                        | Description                                |
|--------------------------------|--------------------------------------------|
| `net user`                     | Lists all user accounts                    |
| `net user username *`          | Resets password for a user                 |
| `net localgroup`               | Lists all local groups                     |
| `net localgroup group user /add` | Adds user to a specified group            |

---

> ⚠️ **Note:** Run CMD as **Administrator** to use certain system-level commands like `taskkill`, `diskpart`, or `net user`.

---

📄 **Prepared by:** Priyanshu Pant  
📌 Perfect for quick reference, assignments, and practical exams.
