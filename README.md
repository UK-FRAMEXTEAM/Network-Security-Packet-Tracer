# Network-Security-Packet-Tracer
Secure enterprise network design with VLANs, ASA firewall, NAT, DMZ, and segmentation (Cisco Packet Tracer)
## 🖥 Network Topology
![Topology](Network-Diagram/Network-Topology.png)

## 📌 Project Overview

This project was developed for **Pearson BTEC HND in Computing – Unit 29 (Network Security)**.

The objective was to design and implement a secure enterprise network using:

* VLAN segmentation
* Layer 3 routing
* ASA Firewall
* NAT configuration
* DMZ implementation
* Internal server isolation
* Access control policies

The network was implemented and tested using **Cisco Packet Tracer**.

---

# 🏢 Network Architecture

The design follows a **Layered Enterprise Model** with:

* Core Layer (Multilayer Switch – Inter-VLAN Routing)
* Access Layer (Access Switches for End Devices)
* Perimeter Security Layer (ASA Firewall)
* ISP Edge Connectivity
* DMZ Zone for public services

---

# 🌐 VLAN & IP Addressing Scheme

| VLAN | Name            | Network       | Purpose             |
| ---- | --------------- | ------------- | ------------------- |
| 10   | ITS_TRAINER     | 10.10.10.0/24 | Staff / Trainers    |
| 20   | ITS_GUEST       | 10.10.20.0/24 | Guest Wi-Fi         |
| 30   | ITS_BUSINESS    | 10.10.30.0/24 | Business Users      |
| 40   | ITS_TECH        | 10.10.40.0/24 | Technical Team      |
| 50   | DMZ             | 10.10.50.0/24 | Public Servers      |
| 60   | DEV             | 10.10.60.0/24 | Development Servers |
| 70   | INTERNAL_SERVER | 10.10.70.0/24 | Internal Servers    |

Full IP allocation table available in:

📂 `/IP-Addressing/`

---

# 🔐 Security Implementation

## 🛡 ASA Firewall Configuration

* Inside / Outside Interface Configuration
* Static & Dynamic NAT
* Access Control Lists (ACL)
* Default Route to ISP
* Controlled DMZ access

## 🌍 NAT Implementation

* Inside private networks translated to public IP
* DMZ servers accessible from outside
* Internal servers protected from direct internet access

## 🚫 Network Segmentation

* VLAN isolation between departments
* Guest network separated from internal network
* DMZ separated from internal VLANs
* Internal server network restricted

---

# 🔄 Routing & Connectivity

* Inter-VLAN Routing via Multilayer Switch
* Static Default Route to ASA Firewall
* ASA default route to ISP Router
* End-to-End Connectivity Tested (Ping & Traceroute)

---

# 🧪 Testing & Verification

The following tests were performed:

* VLAN-to-VLAN communication testing
* Guest network internet access testing
* DMZ external accessibility testing
* Internal server isolation validation
* NAT translation verification
* Firewall policy testing

---

# 📁 Project Files

| Folder              | Description                        |
| ------------------- | ---------------------------------- |
| Network-Diagram     | Network topology image             |
| Packet-Tracer-Files | Cisco Packet Tracer file           |
| IP-Addressing       | VLAN & Device IP allocation tables |
| Assignment-Document | Official Unit 29 assignment        |

---

# 🎯 Key Technologies Used

* Cisco 3560 Multilayer Switch
* Cisco 2960 Access Switches
* Cisco ASA Firewall
* VLAN & Trunking (802.1Q)
* Static Routing
* NAT
* ACL
* Network Segmentation

---

# 👨‍💻 Author

**Pasindu Nilupul**
BEng (Hons) Computer Networking & Cloud Security (Top-Up)
London Metropolitan University (UK)

Aspiring Network Engineer | Cloud & Security Enthusiast
