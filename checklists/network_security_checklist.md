# Network Security Checklist

This checklist summarises essential controls for securing networks, devices, and protocols.  
It is based on the MidTown IT case study and the requirements of VU23213 – Utilise basic network concepts and protocols required in cyber security.

---

## 1. Secure Protocols

| Requirement | Purpose | Notes |
|------------|----------|-------|
| Use HTTPS instead of HTTP | Encrypts data in transit | Prevents MitM attacks |
| Use SFTP/FTPS instead of FTP | Protects credentials & files | FTP sends data in plain text |
| Disable insecure protocols | Reduces attack surface | Telnet, SMBv1, HTTP, FTP |
| Enable TLS 1.2+ | Strong encryption | Avoid outdated SSL versions |

---

## 2. Network Devices & Configuration

| Requirement | Purpose | Notes |
|------------|----------|-------|
| Change default passwords | Prevents easy compromise | Applies to routers, switches, APs |
| Update firmware regularly | Fixes vulnerabilities | Schedule quarterly checks |
| Disable unused services | Minimises attack surface | e.g., guest Wi‑Fi, remote admin |
| Enable firewall filtering | Controls inbound/outbound traffic | Apply least‑privilege rules |
| Segment networks | Limits lateral movement | Separate guest, staff, servers |

---

## 3. Access Control & Authentication

| Requirement | Purpose | Notes |
|------------|----------|-------|
| Use MFA for sensitive systems | Prevents credential‑based attacks | Especially for admin accounts |
| Apply least‑privilege access | Reduces risk of misuse | Review permissions quarterly |
| Enforce strong passwords | Prevents brute‑force attacks | Use complexity + length |
| Log and audit access | Supports investigations | Enable object auditing |

---

## 4. Data Protection

| Requirement | Purpose | Notes |
|------------|----------|-------|
| Encrypt sensitive data | Protects confidentiality | Use XTS‑AES 128‑bit or higher |
| Classify data (e.g., Official‑Sensitive) | Ensures correct handling | Use labels and tracking |
| Secure backups | Prevents data loss | Encrypt + store offsite |
| Implement secure BYOD rules | Reduces personal device risks | Require registration + remote wipe |

---

## 5. Network Monitoring & Detection

| Requirement | Purpose | Notes |
|------------|----------|-------|
| Monitor network traffic | Detects anomalies | Use IDS/IPS or SIEM |
| Enable router/switch logs | Tracks events | Store logs securely |
| Review alerts regularly | Ensures timely response | Daily or weekly depending on risk |
| Detect insecure protocols | Identifies legacy systems | e.g., SMBv1, Telnet |

---

## 6. Testing & Validation

| Requirement | Purpose | Notes |
|------------|----------|-------|
| Perform regular vulnerability scans | Identifies weaknesses | Monthly or quarterly |
| Test incident response plan | Ensures readiness | Run tabletop exercises |
| Validate backups | Confirms recoverability | Test restore procedures |
| Conduct penetration testing | Identifies real‑world risks | Annual or after major changes |

---

## 7. Policy & Compliance

| Requirement | Purpose | Notes |
|------------|----------|-------|
| Review security policies annually | Keeps policies current | Include social media, BYOD, access |
| Train staff on cyber hygiene | Reduces human error | Phishing, passwords, device use |
| Maintain privacy impact assessments | Ensures compliance | Update when systems change |
| Document visitor/contractor access | Prevents unauthorised access | Track and audit all access |

---

## Summary

This checklist supports secure network design and operation by ensuring:

- Strong protocol usage  
- Secure device configuration  
- Controlled access  
- Proper data protection  
- Continuous monitoring  
- Regular testing  
- Policy compliance  

It can be used during audits, network reviews, or as part of ongoing cyber security maintenance.

