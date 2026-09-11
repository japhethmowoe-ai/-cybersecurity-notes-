# Module 5 – Security Operations

**Status:** ✅ Completed

## 🧠 Things I Need to Remember

- A SOC (Security Operations Center) monitors, detects, and responds to threats.
- The SOC's goal is to identify suspicious activity before it becomes a major incident.
- SIEM = collects and analyzes logs from many systems.
- IOCs (Indicators of Compromise) are clues that an attack may have happened.

---

## Core Concepts

### What is a SOC?

A Security Operations Center (SOC) is a team that continuously monitors an organization's systems for suspicious activity and responds to security incidents.

### The SOC Workflow

| Step | Purpose |
|------|---------|
| Monitor | Watch alerts and logs |
| Detect | Identify suspicious activity |
| Investigate | Determine what happened |
| Respond | Contain and fix the issue |
| Document | Record findings and actions |

### SIEM

A **Security Information and Event Management (SIEM)** system collects logs from multiple devices and helps analysts detect threats in one place.

Examples:
- Splunk
- Microsoft Sentinel
- QRadar

### Indicators of Compromise (IOCs)

Examples of IOCs include:

- Suspicious IP addresses
- Unusual login attempts
- Malware file hashes
- Unexpected processes

---

## Quick Wins

- SOC analysts spend much of their time reading logs.
- SIEM tools help combine logs from many systems.
- IOCs are evidence that something suspicious may have happened.
- Every investigation should be documented.

---

## 🎯 Interview Questions

**1. What does a SOC analyst do?**

A SOC analyst monitors security alerts, investigates suspicious activity, responds to incidents, and documents findings.

**2. What is a SIEM?**

A SIEM collects and analyzes logs from multiple systems to help detect and investigate security threats.

**3. What is an Indicator of Compromise (IOC)?**

An IOC is evidence that suggests a system may have been compromised, such as a suspicious IP address, malicious file hash, or unusual login activity.

---

## ⚽ 30-Second Interview Drill

A SIEM alerts you about multiple failed logins from one IP address. What would you do?

> I'd review the login logs, identify the affected account, determine whether the attempts continued or succeeded, look for related activity from the same IP, and document the findings before escalating or responding according to procedure.
