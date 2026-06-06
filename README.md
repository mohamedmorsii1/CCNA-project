<div align="center">

# 🏥 Hospital Branch Interconnectivity Network Infrastructure

**A high-availability enterprise network design for unified branch communication.**

![CCNA](https://img.shields.io/badge/Project-CCNA-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 📋 Project Overview
[cite_start]This project engineered a unified, high-availability (HA) network connecting two hospital branches to a shared Data Center[cite: 17]. [cite_start]The architecture provides centralized services such as AAA, DHCP, and FTP while ensuring continuous, uninterrupted service for the entire hospital system[cite: 17, 19].

## 🏗️ Technical Architecture
The design utilizes a sophisticated set of networking protocols to ensure redundancy, security, and optimal traffic flow.

| Feature | Implementation Details |
| :--- | :--- |
| **Addressing** | [cite_start]VLSM utilized for optimal IP allocation across segmented VLANs[cite: 18]. |
| **Routing** | OSPF deployed for dynamic routing; [cite_start]ROAS for Inter-VLAN communication[cite: 19, 288]. |
| **Redundancy** | HSRP for first-hop redundancy; [cite_start]EtherChannel for link aggregation[cite: 19, 193, 864]. |
| **Security** | [cite_start]AAA framework for access control and SSH for secure remote management[cite: 580, 938]. |

---

## 🚀 Key Features

* [cite_start]**Network Segmentation**: Logically divided physical networks into isolated segments using VLANs to improve security and reduce broadcast traffic[cite: 180, 181].
* [cite_start]**High Availability (HA)**: HSRP configured on internet-facing routers to prevent single points of failure at the default gateway[cite: 864].
* [cite_start]**Bandwidth Optimization**: EtherChannel bundled physical links to increase capacity and provide automatic link-level redundancy[cite: 194, 236].
* [cite_start]**Automated Services**: DHCP service implemented to dynamically assign IP addresses, simplifying network management and preventing IP conflicts[cite: 403, 405].

---

## 📊 Network Design Diagram
*The following diagram illustrates the branch connectivity and VLAN distribution.*



[Image of network topology diagram]


---

## 👥 Project Team

* [cite_start]**Mohamed Morsi Saad** [cite: 7]
* [cite_start]**Tarek Abdelrahman Elsayed** [cite: 8]

**Supervised by:** Eng. [cite_start]Ekram AbdelWahab Nour El-Din [cite: 10]

---

## 🛠️ Infrastructure Pillars

### VLSM & Addressing
[cite_start]The network employs Variable Length Subnet Masking (VLSM) to allocate address blocks based on specific host requirements, dividing the main 100.20.0.0/16 network into 18 efficient subnets[cite: 173, 174].

### Dynamic Routing (OSPF)
[cite_start]OSPF was strategically deployed to build a complete map of the network, choosing paths based on cost (bandwidth) and ensuring quick adaptation to network changes[cite: 327, 328].

### Secure Access (AAA & SSH)
* [cite_start]**AAA**: Security framework implemented to control and track user access via authentication, authorization, and accounting[cite: 580].
* [cite_start]**SSH**: Cryptographic protocol enabled to allow secure remote command-line login, replacing insecure protocols like Telnet[cite: 938, 940].

---

<div align="center">

[cite_start]*Engineered for the Information Technology Institute (ITI)* [cite: 3]

</div>
