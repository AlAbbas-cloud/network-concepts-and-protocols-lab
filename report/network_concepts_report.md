# 🛡️ Network Concepts & Protocols Report  
*VU23213 – Utilise basic network concepts and protocols required in cyber security*

This report documents my work for the MidTown IT case study, covering network communication models, protocol vulnerabilities, security policy review, addressing schemes, and Packet Tracer lab activities.

All work was completed as part of my TAFE Queensland cybersecurity training.

---

## 1. Network Security & Communication Models

### 🔓 Unsecure HTTP
HTTP sends data in **plain text**, making it vulnerable to interception.

**Example:**  
An attacker can perform a **Man‑in‑the‑Middle (MitM)** attack and read login credentials sent over HTTP.

---

### 📁 FTP Vulnerabilities
FTP does not encrypt data, making it easy for attackers to capture:

- usernames  
- passwords  
- transferred files  

It is also vulnerable to:

- brute‑force attacks  
- anonymous login abuse  

---

### 💉 SQL Injection
SQL injection occurs when attackers insert malicious SQL into input fields.

**Example:**  
Entering `' OR '1'='1` in a login form can bypass authentication and access the database.

---

### 🔐 Network Security vs Cyber Security

| Network Security | Cyber Security |
|------------------|----------------|
| Protects data **in transit** across networks | Protects **all digital assets** |
| Focuses on routers, switches, firewalls | Includes software, hardware, data, identity |
| Prevents network‑based attacks | Covers broader threats like malware, phishing |

---

### 🏢 Business Implications of Cyber Breaches

#### **1. Financial Loss**
Breaches lead to legal costs, fines, and recovery expenses.  
*Example: Equifax breach cost over $1.4 billion.*

#### **2. Reputational Damage**
Loss of customer trust and long‑term brand damage.  
*Example: Facebook–Cambridge Analytica scandal.*

#### **3. Operational Disruption**
Downtime, cancelled services, and productivity loss.  
*Example: WannaCry ransomware disrupted the NHS.*

---

## 2. OSI Data Communication Model

The OSI model explains how data moves through a network in **seven layers**.

### 📘 OSI Model Table

| Layer | Function | Protocols |
|-------|----------|-----------|
| 7. Application | Provides services to applications | HTTP, HTTPS, FTP, SMTP, DNS |
| 6. Presentation | Translates, encrypts, compresses data | SSL/TLS, JPEG, MPEG |
| 5. Session | Manages sessions between devices | NetBIOS, PPTP |
| 4. Transport | Reliable delivery, error checking | TCP, UDP |
| 3. Network | Routing and addressing | IP, ICMP, IGMP |
| 2. Data Link | Reliable transfer over physical layer | Ethernet, PPP, ARP |
| 1. Physical | Hardware transmission | Ethernet, USB, Bluetooth |

---

## 3. Security Policy Review

### 📝 Visitor & External Personnel Access
The current policy **does not mention** visitor or contractor access.

**Why this matters:**

- Prevents unauthorised access  
- Supports auditing and accountability  
- Required for compliance  
- Helps incident response  

---

### 📱 Social Media Usage Policy Improvements

- Define “professional and responsible use”  
- Provide training and awareness  
- Add incident reporting steps  
- Clarify personal vs professional use  
- Outline consequences of misuse  
- Review policy regularly  
- Encourage strong privacy settings  
- Provide examples of acceptable use  

---

### 🔒 Access to Official‑Sensitive Data

**People with access:**

- Authorised employees  
- IT administrators  
- Backup personnel  

**Controls in place:**

- Red label classification  
- XTS‑AES 128‑bit encryption  
- Object auditing  
- Encrypted backups  

**Suggested improvements:**

- Multi‑factor authentication  
- Regular access reviews  
- Detailed incident response plan  
- Employee training  
- Zero‑trust model adoption  

---

### 🔐 Privacy Impact Statement Review

**Suggested improvements:**

- Add step‑by‑step process  
- Define roles and responsibilities  
- Provide templates  
- Schedule regular reviews  
- Add training requirements  
- Integrate with other policies  

---

### 📱 BYOD (Bring Your Own Device) Review

**Risks:**

- Malware and weak security  
- Data leakage  
- Compliance issues  
- Device diversity challenges  
- Loss or theft  

**Consequences:**

- Data breaches  
- Legal penalties  
- Operational disruption  
- Loss of trust  

**Recommended changes:**

- Minimum security requirements  
- Device registration  
- Remote wipe capability  
- Access controls  
- Employee training  
- Incident response plan  
- Regular audits  

---

## 4. TCP/IP, Addressing & Conversions

### 🌐 TCP/IP Model

| Layer | Description | Protocols |
|-------|-------------|-----------|
| Application | Services for applications | HTTP, FTP, SMTP |
| Transport | Reliable delivery | TCP, UDP |
| Internet | Routing & addressing | IP, ICMP, IGMP |
| Network Access | Physical transmission | Ethernet, Wi‑Fi, ARP |

---

### 🔐 How TLS/HTTPS Provide Security

**Confidentiality:**  
Encrypts data so attackers cannot read it.

**Integrity:**  
Detects tampering using cryptographic hashes.

**Availability:**  
Protects against MitM and DoS attacks.

---

### 🔄 OSI vs TCP/IP

**Differences:**

- OSI has **7 layers**, TCP/IP has **4**  
- OSI separates Presentation & Session; TCP/IP merges them  

**Commonalities:**

- Both use layered architecture  
- Both include Transport & Network layers  

---

### 🌍 IPv4 vs IPv6 Addressing

**IPv4:**  
- 32‑bit  
- Example: `192.168.1.1`

**IPv6:**  
- 128‑bit  
- Example: `2001:0db8:85a3::8a2e:0370:7334`

---

### 🔢 Binary & Hexadecimal

**Binary:** Base‑2  
**Hex:** Base‑16  

**Examples:**

- 129 → `1000 0001`  
- 78 → `0100 1110`  
- 54 → `0011 0110`  

**Hex conversions:**

- 8193 → `2001`  
- 3512 → `DB8`  
- 61697 → `F101`  

---

## 5. Security Services, Standards & Protocols

*(Continue adding from your assignment — I can help you finish this section once you upload the remaining pages.)*

---

## 6. Packet Tracer Labs

### 🏗 LAB 1 — New Building Network
- Designed a functional network  
- Configured addressing, routing, switching  
- Verified connectivity  

### 📁 LAB 2 — File Sharing Testing
- Implemented SMB file sharing  
- Tested permissions  
- Validated communication  

Screenshots and `.pkt` files are in the `/packet-tracer` folder.

---

## ✔ Summary & Recommendations

- Use secure protocols (HTTPS, SFTP, SSH)  
- Apply strong access controls  
- Encrypt sensitive data  
- Review policies regularly  
- Train staff on cyber hygiene  
- Use MFA and zero‑trust principles  
- Keep firmware and systems updated  

---

## 📚 References

- TAFE Queensland MidTown IT Scenario  
- TAFE Security Policy Documentation  
- Cisco Networking Academy  
- OWASP Secure Coding Guidelines  

