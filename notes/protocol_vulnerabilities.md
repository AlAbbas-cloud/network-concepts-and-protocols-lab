# Protocol Vulnerabilities - Notes

This file summarises common insecure protocols and how attackers exploit them.

---

## HTTP (Unsecure)

- Sends data in **plain text**.
- Vulnerable to **MitM attacks**.
- Attackers can steal login credentials or session cookies.

---

## FTP

- No encryption.
- Credentials and files can be intercepted.
- Vulnerable to brute‑force attacks.
- Anonymous login can be abused.

---

## SQL Injection

- Occurs when user input is not validated.
- Attackers inject malicious SQL commands.
- Can bypass login, read or delete data.

---

## Why This Matters

Understanding protocol weaknesses helps:

- Choose secure alternatives (HTTPS, SFTP).
- Harden systems.
- Detect suspicious traffic.

