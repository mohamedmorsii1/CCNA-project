<div align="center">

# 🏥 Hospital Branch Interconnectivity Network Infrastructure

**A high-availability enterprise network design for unified branch communication.**

![CCNA](https://img.shields.io/badge/Project-CCNA-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 📋 Project Overview
* This project engineered a unified, high-availability (HA) network connecting two hospital branches to a shared Data Center. The architecture provides centralized services such as AAA, DHCP, and FTP while ensuring continuous, uninterrupted service for the entire hospital system.

## 🏗️ Technical Architecture
The design utilizes a sophisticated set of networking protocols to ensure redundancy, security, and optimal traffic flow.

| Feature | Implementation Details |
| :--- | :--- |
| **Addressing** | VLSM utilized for optimal IP allocation across segmented VLANs. |
| **Routing** | OSPF deployed for dynamic routing; ROAS for Inter-VLAN communication. |
| **Redundancy** | HSRP for first-hop redundancy; EtherChannel for link aggregation. |
| **Security** | AAA framework for access control and SSH for secure remote management. |

---

## 🚀 Key Features

* **Network Segmentation**: Logically divided physical networks into isolated segments using VLANs to improve security and reduce broadcast traffic.
* **High Availability (HA)**: HSRP configured on internet-facing routers to prevent single points of failure at the default gateway.
* **Bandwidth Optimization**: EtherChannel bundled physical links to increase capacity and provide automatic link-level redundancy.
* **Automated Services**: DHCP service implemented to dynamically assign IP addresses, simplifying network management and preventing IP conflicts.

---

## 📊 Network Design Diagram
*The following diagram illustrates the branch connectivity and VLAN distribution.*



<img width="836" height="657" alt="image" src="https://github.com/user-attachments/assets/c6af22c0-2503-46bc-8cee-0d597a8d8dd1" />

<img width="580" height="640" alt="image" src="https://github.com/user-attachments/assets/7299bb44-814e-4706-95d8-c86f91f54673" />




---

## 👥 Project Team

* **Mohamed Morsi Saad** 
* **Tarek Abdelrahman Elsayed** 

**Supervised by:** Eng. Ekram AbdelWahab Nour El-Din 

---

## 🛠️ Infrastructure Pillars

### VLSM & Addressing
The network employs Variable Length Subnet Masking (VLSM) to allocate address blocks based on specific host requirements, dividing the main 100.20.0.0/16 network into 18 efficient subnets.

### Dynamic Routing (OSPF)
OSPF was strategically deployed to build a complete map of the network, choosing paths based on cost (bandwidth) and ensuring quick adaptation to network changes.

### Secure Access (AAA & SSH)
* **AAA**: Security framework implemented to control and track user access via authentication, authorization, and accounting.
* **SSH**: Cryptographic protocol enabled to allow secure remote command-line login, replacing insecure protocols like Telnet.

---

<div align="center">

*Engineered for the Information Technology Institute (ITI)* 

</div>
