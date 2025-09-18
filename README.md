# ARP-Based LAN Simulation using Cisco Packet Tracer  
*Industrial IoT Project – L&T EduTech*
 by Srajit Srivastava
---

##  Problem Statement

In a Local Area Network (LAN), devices communicate using MAC addresses, but applications reference devices using IP addresses. This gap is bridged using the Address Resolution Protocol (ARP), which resolves IP addresses to MAC addresses. This project simulates the behavior of ARP using Cisco Packet Tracer.

---

##  Objective

To simulate a LAN using Cisco Packet Tracer and demonstrate how ARP enables communication by resolving IP addresses to MAC addresses dynamically.

---

##  Scope of the Project

- Simulate a LAN with 4 PCs connected to a switch  
- Assign IP addresses to each PC manually  
- Test device-to-device communication using `ping`  
- Show ARP resolution using `arp -a`  
- Document architecture, components, execution, and output  
- Record a demo video showing the ARP process in action  

---

##  Architecture of the System

A simple LAN is created in Cisco Packet Tracer with the following structure:

- 4 End Devices (PC0 to PC3)  
- 1 Switch (Cisco 2960)  
- Straight-through Ethernet cables connecting all PCs to the switch  
- All PCs assigned static IPs from the 192.168.1.x subnet

---

##  Simulated Circuit

![Simulated Network Topology](./Simulated%20_circuit.png)

---

##  Components Used

| Component              | Quantity |
|------------------------|----------|
| Cisco 2960 Switch      | 1        |
| End Devices (PCs)      | 4        |
| Copper Straight Cables| 4        |

### IP Configuration:

| Device | IP Address     | Subnet Mask        |
|--------|----------------|--------------------|
| PC0    | 192.168.1.1    | 255.255.255.0      |
| PC1    | 192.168.1.2    | 255.255.255.0      |
| PC2    | 192.168.1.3    | 255.255.255.0      |
| PC3    | 192.168.1.4    | 255.255.255.0      |

---

##  Execution



🎬 **Demo Video:**  


https://github.com/user-attachments/assets/4dba3d40-703c-4612-bc4a-85e0634ecac7

//github.com/sraj-git-it/Simple-LAN/blob/main/Simple_LAN.mp4" width="300" />



**What’s shown in the video:**
- PC connections and IP configuration  
- Ping from PC0 to PC1, PC2, PC3  
- Use of `arp -a` to show IP-to-MAC mapping  
- Live ARP table updates after each ping  

---

##  Output Screenshots

###  IP Configuration (PC0)

Shows manually assigned IP address and subnet:

![PC0 IP Configuration](./IP%20Configuration%20.png)

---

###  Successful Ping Replies and ARP Table Output (PC0)

Shows dynamically populated MAC addresses after communication:

![ARP Table](./ARP%20Table.png)

---

##  Result

The simulation successfully demonstrated ARP working in a LAN setup. The devices were able to:
- Discover each other using IP addresses
- Resolve those IPs into MAC addresses via ARP
- Communicate using MAC at Layer 2, verified via ping and ARP table

This forms a fundamental use-case in Industrial IoT systems where seamless communication within local networks is required.

---

##  Made By

**Srajit Srivastava**  
B.Tech – Electronics & Instrumentation  
VIT Vellore  
For: *L&T EduTech – Industrial IoT Certification Program*

---

