# Small_Enterprise_Network
# Enterprise LAN/WAN Network Simulation

A scalable enterprise network simulation built using Cisco Packet Tracer implementing VLANs, VLSM subnetting, DHCP, DNS, Static Routing, Supernetting, and Inter-VLAN Routing.

## 📌 Project Overview

This project demonstrates the design and implementation of a multi-site enterprise network consisting of:

- Headquarters (HQ)
- Branch Office 1
- Branch Office 2

The network supports:
- VLAN segmentation
- Dynamic IP allocation using DHCP
- Internal DNS services
- Inter-VLAN routing using Layer 3 Switch
- WAN connectivity between sites
- Route summarization using Supernetting
- Static Routing

The project simulates a real-world enterprise networking environment.

---

## 🛠 Technologies Used

- Cisco Packet Tracer
- VLAN
- VLSM Subnetting
- Supernetting
- DHCP
- DNS
- Layer 3 Switching
- Static Routing
- WAN Topology Design

---

## 🏗 Network Architecture

### Headquarters (HQ)
- VLAN 10 → Servers
- VLAN 20 → Admin
- VLAN 30 → Sales
- VLAN 40 → IoT

### Branch Offices
- Branch 1 connected through WAN
- Branch 2 connected through WAN

### Core Features
- DHCP Server for automatic IP assignment
- DNS Server for hostname resolution
- Inter-VLAN Routing using Multilayer Switch
- Route aggregation using Supernetting

---

## 🌐 IP Addressing Scheme

| Network | Subnet |
|---|---|
| VLAN 10 | 192.168.10.0/24 |
| VLAN 20 | 192.168.20.0/24 |
| VLAN 30 | 192.168.30.0/24 |
| VLAN 40 | 192.168.40.0/24 |
| Branch 1 | 192.168.50.0/24 |
| Branch 2 | 192.168.60.0/24 |
| WAN Links | 10.0.0.0/30 |

---

## ⚙ Features Implemented

✔ VLAN Segmentation  
✔ VLSM Subnetting  
✔ Supernetting  
✔ DHCP Configuration  
✔ DNS Configuration  
✔ Static Routing  
✔ Inter-VLAN Routing  
✔ WAN Connectivity  
✔ Route Summarization  
✔ DHCP Relay Agent  

---

## 🧪 Testing & Verification

The following tests were successfully performed:

- DHCP IP Allocation
- DNS Resolution
- Inter-VLAN Communication
- Branch-to-HQ Connectivity
- WAN Routing Verification
- Ping Tests
- Routing Table Verification

---

## 📷 Project Screenshots

Add screenshots here:

- Network Topology
- Router Configuration
- VLAN Configuration
- DHCP Verification
- Ping Test Results

Example:

![Topology](images/topology.png)

---

## 📚 Learning Outcomes

Through this project, we learned:

- Enterprise network design
- IP subnetting and route summarization
- VLAN implementation
- DHCP and DNS deployment
- Static routing configuration
- Inter-VLAN routing
- WAN communication setup

---

## 👨‍💻 Team Members

- Sajal Gupta
- Ashirwad Guru
- Ankit Hindwar
- Siddharth Jena

---

## 📖 References

- Cisco Networking Academy
- Cisco Packet Tracer Documentation
- Data Communications and Networking – Forouzan
- Cisco Official Documentation

---

## 🚀 Future Improvements

- Implement OSPF/EIGRP
- Add ACL security policies
- Configure NAT/PAT
- Add redundancy protocols
- Deploy firewall simulation
