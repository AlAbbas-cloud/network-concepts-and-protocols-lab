# LAB 1 — New Building Network Solution

This lab demonstrates the design and configuration of a functional network for a new building at MidTown IT.  
The goal was to create a working network using Cisco Packet Tracer, configure addressing, and verify connectivity.

---

## Objectives

- Design a new building network topology  
- Configure routers, switches, and end devices  
- Assign IPv4 addressing  
- Test connectivity using ping and simulation mode  
- Ensure all devices communicate successfully  

---

## Network Topology

The topology includes:

- 1 × Router  
- 2 × Switches  
- Multiple PCs  
- Server (optional depending on scenario)  
- Copper straight‑through and crossover cables  

A screenshot of the topology:

![Logical network diagram](https://raw.githubusercontent.com/AlAbbas-cloud/network-concepts-and-protocols-lab/refs/heads/main/images/lab-1/logical%20network%20diagram.png)

---

## Configuration Steps

### **1. Device Placement**
- Added router, switches, and PCs to the workspace  
- Connected devices using appropriate cables  

![East Building Layout](https://raw.githubusercontent.com/AlAbbas-cloud/network-concepts-and-protocols-lab/refs/heads/main/images/lab-1/East%20building%20layout.png)
**Figure 1: East building network layout used in LAB 1.**

![East Building Rack](https://raw.githubusercontent.com/AlAbbas-cloud/network-concepts-and-protocols-lab/refs/heads/main/images/lab-1/East%20Building%20rack.png)

**Figure 2: East building Rack used in LAB 1.**

---

![West Building layout](https://raw.githubusercontent.com/AlAbbas-cloud/network-concepts-and-protocols-lab/refs/heads/main/images/lab-1/West%20building%20%20layout.png)
**Figure 3: West building network layout used in LAB 1.**

![West Building Rack](https://raw.githubusercontent.com/AlAbbas-cloud/network-concepts-and-protocols-lab/refs/heads/main/images/lab-1/West%20building%20rack.png)

**Figure 4: West building Rack used in LAB 1.**

---

### **2. IP Addressing**
Each PC was assigned:

- IP address  
- Subnet mask  
- Default gateway  

Example:

| Device | IP Address | Subnet Mask | Gateway |
|--------|------------|-------------|---------|
| PC1 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| PC2 | 192.168.1.11 | 255.255.255.0 | 192.168.1.1 |

### **3. Router Configuration**
Basic router setup included:

- Enabling interfaces  
- Assigning IP addresses  
- Verifying interface status  

### **4. Switch Configuration**
- Enabled VLAN 1 (default)  
- Ensured ports were active  
- Connected PCs to switch ports  

---

## Testing & Verification

### **Ping Tests**
- PC1 → PC2  
- PC1 → Router  
- PC2 → Router  

All tests were successful.

### **Simulation Mode**
- Verified packet flow  
- Confirmed ARP resolution  
- Confirmed ICMP echo requests/replies  

---

## Results

The new building network was successfully designed and configured.  
All devices communicated correctly, and the topology met the MidTown IT requirements.

---

## 📁 Files

- `lab1_new_building_network.pkt` — Packet Tracer file  
- Screenshots available in `/packet-tracer/screenshots/`
