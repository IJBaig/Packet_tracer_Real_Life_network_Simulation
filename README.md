# Packet_tracer_Real_Life_network_Simulation
A real-world enterprise network simulation using Cisco Packet Tracer. The project includes OSPF dynamic routing, DHCP, DNS, NAT, VLANs, ACLs, and IoT devices with CIDR-based subnetting. Developed by IJ Baig.
# 🌐 Real-Life Network Simulation using Cisco Packet Tracer

### 🧑‍💻 Created By: IJ Baig  
### 🗓️ Submission Date: 20 May 2025  

---

## 📘 Overview

This project simulates a real-world medium-to-large scale enterprise network in Cisco Packet Tracer. It uses **Class C private IP addressing (192.168.x.x)** with **CIDR-based subnetting**, and includes:

- 🔁 **Dynamic Routing (OSPF)**
- 🖥️ Multiple **PCs, Routers, Switches, Servers, and IoT Devices**
- 🌍 **DNS, DHCP, Web Services, VLANs, NAT, and ACLs**
- 🔒 Security Measures using **ACLs and NAT**
- 📡 Realistic Subnetting using **/26, /28, /30**, and **/29** for public access

---

## 🧱 Network Architecture

### 📡 Subnetting
- CIDR-based subnetting with /30 for router links, /26 and /28 for LANs
- Public-facing subnet: `192.168.2.0/29`

### 🔄 Routing
- OSPF (Area 0) is used for dynamic routing
- Static routes are added for NAT paths

### 🧰 Services
| Service | Location | Function |
|--------|----------|----------|
| **DHCP** | R6 | Assigns IPs to clients |
| **DNS** | R6 | Resolves internal domains |
| **Web Servers** | R5, Public | Hosts websites |
| **NAT** | R7 | Maps internal IPs to public |
| **ACLs** | R7 | Filters incoming external traffic |
| **IoT** | R6 | Webcam, Thermostat connected |

---

## 🖼️ Screenshots
![Screenshot_2025-06-28_02-58-44](https://github.com/user-attachments/assets/d8e2c782-d035-4cd5-81a1-f26cbc89c084)

---

## 🚀 How to Use

1. Open the `.pkt` file using **Cisco Packet Tracer 8.0 or above**.
2. Review the configurations on routers (OSPF, interfaces).
3. Test connectivity using:
   - `ping`
   - `tracert`
   - Web browser simulation
4. Verify DHCP leases and DNS resolutions.
5. Test public access to internal web server via NAT using `192.168.2.4`.

---

## 🛡️ Security & Limitations

- 🔐 ACLs allow only HTTP traffic to internal server
- 🔒 NAT hides internal IPs
- ⚠️ Future improvements:
  - Add VPN for remote access
  - Use Layer 3 Switches
  - Add secondary DHCP/DNS for redundancy

---

## 🧪 Learning Outcomes

- Gained practical experience in enterprise-level network design
- Learned to configure OSPF, NAT, ACLs, DHCP, and DNS
- Understood subnetting using CIDR
- Improved troubleshooting and simulation skills

---

## 📫 Contact

For queries or suggestions:  
📧 **ijbaig53@gmail.com**

---
