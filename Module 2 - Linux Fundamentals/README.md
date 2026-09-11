# Module 2 – Linux Fundamentals

**Status:** ✅ Completed

## 🧠 Things I Need to Remember

- Everything in Linux is treated like a file.
- `pwd` = Where am I?
- `ls` = What's here?
- `cd` = Move between folders.
- `grep` searches inside files.
- `sudo` gives temporary admin privileges.

---

## Core Commands

| Command | Purpose |
|---------|---------|
| `pwd` | Show current directory |
| `ls` | List files and folders |
| `cd` | Change directory |
| `mkdir` | Create a folder |
| `touch` | Create a file |
| `cp` | Copy files |
| `mv` | Move or rename files |
| `rm` | Delete files |
| `cat` | Display a file |
| `less` | Read long files |
| `head` | First lines of a file |
| `tail` | Last lines of a file |
| `find` | Search for files |
| `grep` | Search inside files |
| `chmod` | Change permissions |
| `sudo` | Run as administrator |

---

## File Permissions

| Symbol | Meaning |
|--------|---------|
| `r` | Read |
| `w` | Write |
| `x` | Execute |

Example:

```bash
chmod +x script.sh
```

This makes `script.sh` executable.

---

## Quick Wins

- `pwd` tells me where I am.
- `ls` shows what's inside a folder.
- `grep` is one of the fastest ways to search logs.
- `tail` is useful for checking the newest log entries.
- `chmod` controls who can access or execute a file.

---

## 🎯 Interview Questions

**1. What's the difference between `pwd` and `ls`?**

`pwd` shows my current directory, while `ls` lists the files and folders inside it.

**2. Why is `grep` useful for a SOC analyst?**

It quickly searches logs and files for usernames, IP addresses, error messages, or indicators of compromise.

**3. What does `sudo` do?**

It temporarily runs a command with administrator (root) privileges.

---

## ⚽ 30-Second Interview Drill

A Linux server is acting strangely. How would you start investigating?

> I'd identify my current location with `pwd`, list the directory contents using `ls`, inspect important files with `cat` or `less`, search for suspicious entries using `grep`, and check the latest log activity with `tail` before making any changes.
