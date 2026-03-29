# OSI Model - Notes

The OSI (Open Systems Interconnection) model explains how data moves through a network using **seven layers**, each with a specific job.

---

## OSI Model Overview

| Layer | Name | Purpose | Examples |
|-------|------|----------|----------|
| 7 | Application | Services for user applications | HTTP, HTTPS, FTP, DNS |
| 6 | Presentation | Encryption, compression, translation | SSL/TLS, JPEG, MPEG |
| 5 | Session | Starts, manages, ends sessions | NetBIOS, PPTP |
| 4 | Transport | Reliable delivery, error checking | TCP, UDP |
| 3 | Network | Routing and addressing | IP, ICMP, IGMP |
| 2 | Data Link | Frames, MAC addressing | Ethernet, PPP, ARP |
| 1 | Physical | Hardware transmission | Cables, Wi‑Fi, USB |

---

## Key Points

- Layers work **independently** but communicate with the layers above and below.
- Helps troubleshoot network issues by isolating problems.
- Used as a reference model in networking and cyber security.

---

## Why It Matters in Cyber Security

- Helps identify where attacks occur (e.g., ARP spoofing = Layer 2).
- Helps understand how protocols interact.
- Supports secure network design and troubleshooting.
