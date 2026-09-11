# Module 4 – Command Line

**Status:** ✅ Completed

## 🧠 Things I Need to Remember

- `pwd` = Where am I?
- `ls` = What's here?
- `cd` = Move between folders.
- `cat` reads files.
- `grep` searches inside files.
- `find` locates files.
- The command line is often faster than the GUI for investigations.

---

## Core Commands

| Command | Purpose |
|---------|---------|
| `pwd` | Show current directory |
| `ls` | List files and folders |
| `cd` | Change directory |
| `cat` | Display a file |
| `less` | Read long files |
| `head` | First lines of a file |
| `tail` | Last lines of a file |
| `grep` | Search inside files |
| `find` | Search for files |
| `mkdir` | Create a folder |
| `touch` | Create a file |

---

## Quick Wins

- `grep` is one of the most useful commands for searching logs.
- `tail` helps check the newest log entries.
- `find` locates files quickly.
- Combining simple commands is more powerful than memorizing dozens of commands.

---

## 🎯 Interview Questions

**1. What's the difference between `pwd` and `cd`?**

`pwd` shows my current directory, while `cd` changes my current directory.

**2. Why is `grep` valuable in cybersecurity?**

It quickly searches logs and files for usernames, IP addresses, error messages, or indicators of compromise.

**3. When would you use `tail` instead of `cat`?**

`tail` is better for viewing the most recent lines of a large log file.

---

## ⚽ 30-Second Interview Drill

You're asked to investigate a Linux log file. How do you start?

> I'd use `pwd` to confirm my location, `ls` to identify relevant files, `tail` to view the latest log entries, and `grep` to search for suspicious usernames, IP addresses, or error messages.
