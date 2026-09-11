# Module 2 – Networking

**Status:** ✅ Completed

## 🧠 Things I Need to Remember

- OSI: **All People Seem To Need Data Processing**
- TCP/IP has **4 layers**.
- DNS translates names into IP addresses.
- TCP = reliable. UDP = faster.

---

## OSI Model

| Layer | Purpose |
|-------|---------|
| Application | User-facing network services |
| Presentation | Data formatting & encryption |
| Session | Manages communication sessions |
| Transport | End-to-end communication |
| Network | Routing (IP) |
| Data Link | Local network communication |
| Physical | Cables, Wi-Fi, signals |

**Mnemonic:** *All People Seem To Need Data Processing.*

---

## TCP/IP Model

| Layer | What it does | Examples |
|-------|--------------|----------|
| Application | Network services for applications | HTTP, DNS, FTP |
| Transport | Communication between applications | TCP, UDP |
| Internet | Addressing and routing | IP, ICMP |
| Network Access | Moves data across the local network | Ethernet, Wi-Fi |

---

## TCP vs UDP

| TCP | UDP |
|-----|-----|
| Reliable | Faster |
| Connection-oriented | Connectionless |
| Guarantees delivery | Doesn't guarantee delivery |

---

## Quick Wins

- **DNS** = Converts names into IP addresses.
- **IP** = Finds the destination.
- **TCP** = Reliable delivery.
- **UDP** = Speed over reliability.

---

## 🎯 Interview Questions

**1. What's the difference between the OSI model and TCP/IP?**

OSI is a 7-layer reference model for understanding networking, while TCP/IP is the practical 4-layer protocol suite used on the internet.

**2. When would you choose TCP over UDP?**

TCP when reliability matters (SSH, HTTPS, file transfers). UDP when speed matters (video streaming, gaming, VoIP).

**3. What does DNS do?**

It translates human-readable domain names into IP addresses so devices can find each other.

---

## ⚽ 30-Second Interview Drill

Explain how opening `google.com` works:

> My computer asks DNS for Google's IP address, uses IP to route traffic across networks, TCP establishes a reliable connection, and HTTP or HTTPS carries the web page between my browser and Google's server.
