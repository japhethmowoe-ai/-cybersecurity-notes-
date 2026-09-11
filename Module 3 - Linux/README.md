# Module 3 – Linux

**Status:** ✅ Completed

## 🧠 Things I Need to Remember

- Everything in Linux is treated like a file.
- `pwd` tells me where I am.
- `ls` shows what's there.
- `cd` moves between directories.
- `cat`, `less`, and `head` help me read files.
- `chmod` changes permissions.

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

Makes a script executable.

---

## Quick Wins

- `find` locates files.
- `grep` searches for keywords inside files.
- `sudo` gives temporary administrator privileges.
- `tail` is useful for checking the newest log entries.

---

## 🎯 Interview Questions

**1. What's the difference between `ls` and `pwd`?**

`ls` lists the contents of a directory, while `pwd` shows the current directory path.

**2. What does `sudo` do?**

It temporarily runs a command with administrator (root) privileges.

**3. Why is `grep` useful in cybersecurity?**

It quickly searches logs and files for specific keywords, usernames, IP addresses, or indicators of compromise.

---

## ⚽ 30-Second Interview Drill

A Linux server is acting strangely. How would you start investigating?

> I'd identify my location with `pwd`, list files using `ls`, inspect relevant files with `cat` or `less`, search for suspicious entries with `grep`, and use `tail` to check the latest log activity before making changes.
