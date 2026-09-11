# Module 4 – Windows

**Status:** ✅ Completed

## 🧠 Things I Need to Remember

- Windows Event Viewer is where security events are investigated.
- Event ID **4625** = Failed logon.
- PowerShell is Windows' command-line automation tool.
- `ipconfig`, `whoami`, and `netstat` are commands I'll use often.

---

## Core Concepts

### Event Viewer

Used to investigate Windows security events, application logs, and system logs.

Important Security Event IDs:

| Event ID | Meaning |
|----------|---------|
| 4624 | Successful logon |
| 4625 | Failed logon |

### PowerShell

PowerShell is Windows' command-line and automation tool, similar to Bash in Linux.

### Useful Commands

| Command | Purpose |
|---------|---------|
| `ipconfig` | View IP configuration |
| `whoami` | Show current user |
| `hostname` | Show computer name |
| `netstat -ano` | View active network connections |
| `tasklist` | List running processes |

---

## Quick Wins

- Event Viewer helps investigate login activity.
- PowerShell is essential for Windows administration.
- `netstat` shows which connections are active.
- `whoami` quickly confirms the current user account.

---

## 🎯 Interview Questions

**1. What is Windows Event Viewer used for?**

It stores and displays security, system, and application logs used to investigate activity on a Windows machine.

**2. What does Event ID 4625 mean?**

A failed logon attempt.

**3. Why is PowerShell important in cybersecurity?**

It allows administrators and security analysts to automate tasks, gather system information, and investigate Windows systems efficiently.

---

## ⚽ 30-Second Interview Drill

A user reports they can't log in. How would you start investigating?

> I'd open Event Viewer, check the Security log for Event IDs like 4625 (failed logon) and 4624 (successful logon), confirm which account was affected, and use commands like `whoami`, `hostname`, and `netstat` if additional system information was needed.
