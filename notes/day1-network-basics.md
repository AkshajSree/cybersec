# Day 1 – Networking Fundamentals for Cybersecurity
**Date:** 16-09-2025  

---

## 1️⃣ OSI Model – 7 Layers

| Layer | Purpose | Example Protocols |
|------|---------|--------------------|
| 7. **Application** | User‐level network services | HTTP, HTTPS, DNS, FTP |
| 6. **Presentation** | Data formatting, encryption, compression | TLS/SSL, JPEG |
| 5. **Session** | Manages sessions / connections | NetBIOS, RPC |
| 4. **Transport** | Reliable delivery of packets | TCP, UDP |
| 3. **Network** | Logical addressing & routing | IP, ICMP |
| 2. **Data Link** | Physical addressing (MAC) | Ethernet, Wi-Fi |
| 1. **Physical** | Hardware transmission of bits | Cables, radio |

---

## 2️⃣ TCP/IP Model – 4 Layers

| Layer | Purpose | Example Protocols |
|------|---------|--------------------|
| **Application** | All app-level protocols | HTTP, SMTP, DNS |
| **Transport** | End-to-end comms | TCP, UDP |
| **Internet** | Logical addressing & routing | IP, ICMP |
| **Network Access / Link** | Physical data transfer | Ethernet, Wi-Fi |

**Mapping:**  
- OSI App + Presentation + Session → **TCP/IP Application**  
- OSI Transport → **TCP/IP Transport**  
- OSI Network → **TCP/IP Internet**  
- OSI Data Link + Physical → **TCP/IP Network Access**

---

## 3️⃣ Key Concepts
- **Packet:** Smallest unit of data sent across a network.
- **Port:** Logical endpoint for network services (HTTP → 80, HTTPS → 443).
- **IP Address:** Unique identifier for a device.
- **Protocol:** Rules that define communication.

---

## 4️⃣ Hands-On Lab

Run these commands in Linux / WSL and observe the output:
```bash
ip addr show
netstat -tulnp
curl -I https://example.com
traceroute google.com
ping google.com

