# 🌐 MIU Campus Area Network (CAN)

## 📌 Overview
This project implements a **Campus Area Network (CAN)** for Misr International University (MIU) using Cisco Packet Tracer.

It simulates a real-world enterprise network integrating routing, switching, security, and network services across multiple buildings and a branch network.

---

## 🧱 Network Architecture
- Multi-building campus network (Main, S, N, R)
- Branch network connected via WAN
- Central gateway (MIU-GW)
- Wireless home network integration

---

## 🚀 Features Implemented

### 🔹 Addressing & Design
- VLSM subnetting (10.0.0.0/8)
- VLAN-based segmentation
- Efficient IP allocation per department

### 🔹 Switching
- VLAN configuration
- Trunking (802.1Q)
- Inter-VLAN Routing (SVI)
- EtherChannel (LACP)

### 🔹 Routing
- OSPF (Main & S buildings)
- EIGRP (N & R buildings)
- Dynamic routing between all networks

### 🔹 Network Services
- DHCP (central server + router pools)
- DNS Server
- Web Server (HTTP)
- Email Server (SMTP/POP3)

### 🔹 Security & WAN
- Site-to-Site IPsec VPN
- NAT & PAT
- Static NAT for internal servers

### 🔹 Network Management
- NTP (time synchronization)
- Syslog logging
- SSH secure access

### 🔹 Wireless
- WPA2-secured wireless home network
- Multi-device connectivity

---

## 🛠️ Tools Used
- Cisco Packet Tracer
- Routing Protocols: OSPF, EIGRP
- Networking Services: DHCP, NAT, DNS, VPN

---

## 📸 Screenshots

### 🔹 Network Topology
![Topology](Screenshots/Topology.jpg)

---

### 🔹 VLAN Configuration
![VLAN](Screenshots/Vlan_Brief.jpg)

---

### 🔹 Trunk Configuration
![Trunk](Screenshots/Trunk_Brief.jpg)

---

### 🔹 EtherChannel
![EtherChannel](Screenshots/Etherchannel_Brief.jpg)

---

### 🔹 Routing Protocols (OSPF / EIGRP)
![Routing](Screenshots/IP_Protocols_Brief.jpg)

---

### 🔹 DHCP Configuration
![DHCP](Screenshots/DHCP_Configuration_Brief.jpg)

---

### 🔹 NTP Configuration
![NTP](Screenshots/NTP_Configuration_Brief.jpg)

---

### 🔹 Web Server Configuration
![Web Server](Screenshots/Web_Server_Configuration_Brief.jpg)

---

### 🔹 VPN Configuration
![VPN](Screenshots/VPN_Configuration_Brief.png)

---

### 🔹 Wireless Home Network
![Wireless](Screenshots/Wireless-HomeNetwork_Brief.jpg)


