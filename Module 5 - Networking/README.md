# Module 5 – Networking

**Status:** ✅ Completed

## 🧠 Things I Need to Remember

- OSI = **All People Seem To Need Data Processing**
- TCP/IP has **4 layers**.
- DNS translates names into IP addresses.
- TCP = reliable. UDP = faster.
- IP handles routing between networks.

---

## OSI Model

| Layer | Purpose |
|-------|---------|
| Application | Network services for applications |
| Presentation | Data formatting & encryption |
| Session | Manages communication sessions |
| Transport | End-to-end communication |
| Network | Routing using IP |
| Data Link | Communication on the local network |
| Physical | Cables, Wi-Fi, and signals |

**Memory Trick:** *All People Seem To Need Data Processing.*

---

## TCP/IP Model

| Layer | What it does | Examples |
|-------|--------------|----------|
| Application | Provides services to applications | HTTP, DNS, FTP |
| Transport | Controls communication between applications | TCP, UDP |
| Internet | Addressing and routing | IP, ICMP |
| Network Access | Moves data across the local network | Ethernet, Wi-Fi |

---

## TCP vs UDP

| TCP | UDP |
|-----|-----|
| Reliable | Faster |
| Connection-oriented | Connectionless |
| Guarantees delivery | No delivery guarantee |

---

## Quick Wins

- **DNS** = Converts names into IP addresses.
- **IP** = Finds the destination.
- **TCP** = Reliable communication.
- **UDP** = Speed over reliability.
- The OSI model explains networking; TCP/IP runs the internet.

---

## 🎯 Interview Questions

**1. What's the difference between the OSI model and TCP/IP?**

The OSI model is a 7-layer reference model for understanding networking, while TCP/IP is the practical 4-layer protocol suite used on the internet.

**2. When would you choose TCP instead of UDP?**

TCP when reliability matters (HTTPS, SSH, file transfers). UDP when speed matters (gaming, streaming, VoIP).

**3. What does DNS do?**

It translates human-readable domain names into IP addresses so devices can communicate.

---

## ⚽ 30-Second Interview Drill

**Explain what happens when you type `google.com` into your browser.**

> My computer asks a DNS server for Google's IP address, uses IP to route packets across networks, TCP establishes a reliable connection, and HTTP/HTTPS carries the webpage between my browser and Google's server.
