# 📁 LAB 2 — File Sharing Testing (SMB)

This lab demonstrates how to configure and test file sharing using SMB in a controlled Packet Tracer environment.

---

## 🎯 Objectives

- Configure a server for SMB file sharing  
- Create shared folders  
- Configure user permissions  
- Connect clients to the shared folder  
- Test access and verify security controls  

---

## 🧱 Network Topology

The topology includes:

- 1 × Server  
- 1 × Switch  
- 2 × PCs  
- Copper straight‑through cables  

A screenshot of the topology is available in `/packet-tracer/screenshots/`.

---

## 🔧 Configuration Steps

### **1. Server Setup**
- Enabled SMB service  
- Created shared folder (e.g., `SharedDocs`)  
- Added user accounts  
- Assigned read/write permissions  

### **2. PC Configuration**
Each PC was configured with:

- IP address  
- Subnet mask  
- Default gateway  
- DNS (if required)

### **3. Mapping the Network Drive**
On each PC:

1. Opened the file sharing client  
2. Entered server IP (e.g., `\\192.168.1.5`)  
3. Logged in with assigned credentials  
4. Verified access to shared folder  

---

## 🧪 Testing & Verification

### **Access Tests**
- PC1 successfully accessed shared folder  
- PC2 successfully accessed shared folder  

### **Permission Tests**
- Verified read/write access  
- Confirmed unauthorised users were blocked  

### **Connectivity Tests**
- Ping from PCs → Server  
- Ping between PCs  

All tests were successful.

---

## ✔ Results

The SMB file sharing environment was successfully configured.  
Users were able to access shared resources securely, and permissions worked as expected.

---

## 📁 Files

- `lab2_file_sharing.pkt` — Packet Tracer file  
- Screenshots available in `/packet-tracer/screenshots/`
