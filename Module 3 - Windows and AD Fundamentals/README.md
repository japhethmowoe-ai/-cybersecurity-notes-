# Module 3 – Windows and AD Fundamentals

**Status:** ✅ Completed

## 🧠 Things I Need to Remember

- Active Directory (AD) manages users, computers, and permissions in Windows networks.
- Domain Controllers authenticate users and enforce security policies.
- Event Viewer stores Windows security logs.
- Event ID **4624** = Successful logon.
- Event ID **4625** = Failed logon.

---

## Core Concepts

### Active Directory (AD)

Active Directory is Microsoft's directory service that centrally manages users, computers, groups, and permissions across a network.

### Domain Controller (DC)

A Domain Controller is the server that:

- Authenticates users
- Enforces Group Policy
- Stores Active Directory information

### Windows Event Viewer

Event Viewer is used to investigate Windows activity through logs.

| Event ID | Meaning |
|----------|---------|
| 4624 | Successful logon |
| 4625 | Failed logon |

### Useful Windows Commands

| Command | Purpose |
|---------|---------|
| `whoami` | Show current user |
| `hostname` | Show computer name |
| `ipconfig` | View network configuration |
| `netstat -ano` | View active connections |
| `tasklist` | List running processes |

---

## Quick Wins

- AD is the identity system used in many companies.
- Domain Controllers verify user logins.
- Event Viewer is one of the first places SOC analysts check.
- PowerShell is Windows' automation tool.

---

## 🎯 Interview Questions

**1. What is Active Directory?**

Active Directory is Microsoft's directory service that centrally manages users, computers, groups, and permissions across a network.

**2. What is a Domain Controller?**

A Domain Controller authenticates users, enforces security policies, and stores Active Directory information.

**3. What does Event ID 4625 mean?**

It indicates a failed logon attempt.

---

## ⚽ 30-Second Interview Drill

A company reports repeated failed logins on a user's account. How would you start?

> I'd check Event Viewer for Event ID 4625, identify which account was affected, look at when the attempts occurred, and determine whether there were successful logins (4624) afterward before escalating or responding.
