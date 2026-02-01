# Multi-Floor Software House Network Design (CCN Project)

##  Project Description
This project represents the design and implementation of a **multi-floor software house network** created using **Cisco Packet Tracer** as part of the **Computer Communication & Networks (CCN)** course.

The network spans **four floors**, each serving a distinct purpose such as administrative departments, working areas, and a cafeteria with wireless access. The design focuses on **logical segmentation, dynamic IP allocation, secure communication, and inter-floor connectivity**, following real-world enterprise networking practices.

---

##  Network Overview

### 🔹 First Floor – Admin Department
- Departments: CEO, Marketing, HR, Accountant
- Each department is placed in a **separate VLAN**
- Router-on-a-Stick used for inter-VLAN routing
- DHCP used for dynamic IP assignment
- ACLs applied to restrict inter-department access

---

### 🔹 Second Floor – Working Area 1
- Two offices segmented using VLANs
- Switch connected to router via trunk link
- DHCP enabled for IP assignment
- Controlled access between VLANs

---

### 🔹 Third Floor – Working Area 2
- Three offices connected through multiple switches
- VLAN configuration propagated using **VTP**
- RIP routing enabled for inter-floor communication
- DHCP used for IP allocation

---

### 🔹 Fourth Floor – Cafeteria
- Wireless router deployed
- PCs and employee devices connect wirelessly
- Simulates enterprise Wi-Fi environment

---

##  Technologies & Concepts Used
- Cisco Packet Tracer
- VLANs
- DHCP
- VTP
- ACLs
- 802.1Q Encapsulation
- RIP Routing
- Wired and Wireless Networking

---

##  Project Files
This repository contains a **single Cisco Packet Tracer file**:

