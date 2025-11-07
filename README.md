# 🐧 Linux and Bash for Data Engineers – IBM (Coursera)

This repository contains my work, notes, and final project submissions from the **"Linux and Bash for Data Engineers"** course offered by **IBM** on Coursera.  
The course focuses on mastering Linux commands, shell scripting, file management, and automation — essential tools for every Data Engineer.

---

## 📘 Course Overview

In this course, I learned how to:
- Navigate and manage the Linux file system
- Use core Linux commands for data and system management
- Write and debug Bash shell scripts
- Automate repetitive tasks with cron jobs
- Manage permissions, processes, and environment variables
- Apply Linux scripting in real-world data engineering workflows

---


---

## 🧠 Key Learning Concepts

- `ls`, `cd`, `cat`, `grep`, `awk`, `sed`, `chmod`, `ps`, `kill`, `df`, `du`
- Shell variables, loops (`for`, `while`), and conditionals (`if`, `elif`, `else`)
- I/O redirection (`>`, `<`, `|`, `>>`)
- Script arguments and automation (`$1`, `$2`, `$@`)
- Cron scheduling (`crontab -e`)
- File compression and backup using `tar` and `gzip`

---

## 🚀 Final Project: Automated Backup Script

### **Project Title:** `backup.sh`

The final project demonstrates real-world automation using Bash scripting.  
It automatically backs up any **encrypted password files** or other files **modified in the last 24 hours**.

### **Project Objectives**
- Automate daily file backup
- Remove human dependency and minimize errors
- Create compressed archives of updated files
- Schedule script to run daily using `cron`

---

### **How the Script Works**

1. Takes two input arguments:
   - Source directory (files to back up)
   - Destination directory (where to save the archive)
2. Finds files modified in the last 24 hours
3. Compresses them into `backup-[timestamp].tar.gz`
4. Moves the file to the destination folder
5. Can be scheduled to run automatically once a day

---

🧑‍💻 Author

Saad
Data Engineer | Student

📚 Course: IBM – Linux and Bash for Data Engineers (Coursera)
🌐 GitHub: [github.com/saad](https://github.com/Muhammad-Saad12345)

💬 Email: muhammadsaad97531@gmail.com
youtube: https://www.youtube.com/@DataEngineeringMastery786



