# Bash Command Cheat Sheet

Here’s a practical **Bash Command Cheat Sheet** 🖥️🐚 — perfect for quick reference while scripting, navigating the terminal, or automating tasks.

---

## 📁 File & Directory Management

| Command           | Description                     |
| ----------------- | ------------------------------- |
| `ls`              | List files in current directory |
| `ls -l`           | Long listing format             |
| `cd dir_name`     | Change directory                |
| `pwd`             | Show current directory path     |
| `mkdir dir_name`  | Create a new directory          |
| `touch file_name` | Create a new empty file         |
| `rm file_name`    | Delete a file                   |
| `rm -r dir_name`  | Delete a directory recursively  |
| `cp source dest`  | Copy file or directory          |
| `mv source dest`  | Move or rename file/directory   |

---

## 🧮 File Viewing & Editing

| Command               | Description            |
| --------------------- | ---------------------- |
| `cat file`            | View file contents     |
| `less file`           | Scroll through file    |
| `head file`           | Show first 10 lines    |
| `tail file`           | Show last 10 lines     |
| `nano file`           | Edit file with nano    |
| `vim file`            | Edit file with vim     |
| `echo "text"`         | Print text to terminal |
| `echo "text" > file`  | Write text to file     |
| `echo "text" >> file` | Append text to file    |

---

## 🔍 Searching & Filtering

| Command               | Description                |
| --------------------- | -------------------------- |
| `grep "pattern" file` | Search for pattern in file |
| `find . -name "file"` | Find file by name          |
| `wc -l file`          | Count lines in file        |
| `sort file`           | Sort file contents         |
| `uniq file`           | Remove duplicate lines     |
| `cut -d':' -f1 file`  | Extract fields from file   |

---

## 🧰 System Info & Utilities

| Command      | Description            |
| ------------ | ---------------------- |
| `whoami`     | Show current user      |
| `uname -a`   | System info            |
| `top`        | Live process monitor   |
| `ps aux`     | List running processes |
| `df -h`      | Disk usage             |
| `du -sh dir` | Directory size         |
| `free -h`    | Memory usage           |
| `date`       | Show current date/time |
| `uptime`     | System uptime          |

---

## 🧪 Permissions & Execution

| Command                 | Description              |
| ----------------------- | ------------------------ |
| `chmod +x file.sh`      | Make script executable   |
| `./file.sh`             | Run script               |
| `sudo command`          | Run command as superuser |
| `chown user:group file` | Change file ownership    |

---

## 🔄 Redirection & Pipes

| Command    | Description                         |
| ---------- | ----------------------------------- |
| `>`        | Redirect output to file (overwrite) |
| `>>`       | Redirect output to file (append)    |
| `<`        | Read input from file                |
| `\|`       | Pipe output to another command      |
| `tee file` | Redirect and display output         |

---

## 🔁 Loops & Conditionals (Script Snippets)

```bash
# For loop
for file in *.txt; do
  echo "$file"
done

# If statement
if [ -f "file.txt" ]; then
  echo "File exists"
fi
```

---
