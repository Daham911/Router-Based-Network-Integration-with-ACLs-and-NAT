# Cisco Packet Tracer Project: LAN-to-LAN Network Simulation with Static and Dynamic Routing

## 📘 Overview

This project is a Cisco Packet Tracer simulation that connects two Local Area Networks (LANs) via a WAN using routers and demonstrates both **static** and **dynamic routing** configurations. It is designed to simulate real-world inter-network communication between separate LANs across a WAN.

- **Tool Used**: Cisco Packet Tracer
- **LANs**:  
  - LAN1 → `192.168.10.0/24`  
  - LAN2 → `192.168.30.0/24`
- **WAN Network (Between Routers)**: `192.168.20.0/24`
- **Routing Types**: Static Routing (first file), Dynamic Routing (second file)
- **Connection Medium**: Ethernet (straight-through cables), Serial (WHC-1H port)

---

## 🧱 Network Topology

- **LAN1**
  - 5 PCs connected to 2 switches via straight-through cables
  - Connected to Router1 using straight-through cable

- **LAN2**
  - 5 PCs connected to 2 switches via straight-through cables
  - Connected to Router2 using straight-through cable

- **WAN**
  - Routers connected via serial cable (WHC-1H port)
  - IP addresses assigned from `192.168.20.0/24`

---

## 📂 Files Included

| File Name             | Description                                      |
|----------------------|--------------------------------------------------|
| `static-routing.pkt` | Static routing configured between LAN1 and LAN2 |
| `dynamic-routing.pkt`| Dynamic routing (e.g., RIP or OSPF) configured  |

---

## ⚙️ Features Implemented

- Static routing across LAN1 and LAN2 via WAN
- Dynamic routing protocol configuration (RIP or OSPF)
- IP addressing for WAN (router-to-router link: `192.168.20.0/24`)
- End-to-end communication between all LAN PCs
- Use of serial cable and WHC-1H ports for router interconnection

---

## 🚀 How to Use

1. Open `.pkt` file(s) in **Cisco Packet Tracer** (v8.2 or higher).
2. Review the topology and router configurations.
3. Use the **ping** tool to test communication between LAN1 and LAN2 PCs.
4. Explore how static and dynamic routing differs by inspecting the routing tables.

---

## 🧠 Learning Outcomes

- Understand inter-network routing across LANs and WAN
- Learn the difference between static and dynamic routing
- Practice interface configuration and subnet planning
- Understand serial and Ethernet cabling standards

---

## 📌 Notes

- WAN IP configuration between routers is based on `192.168.20.0/24`.
- Static and dynamic routing files are configured separately to show routing behavior.
- Project can be extended to include ACLs, NAT, or VLANs for advanced simulation.

---

## 🧑‍💻 Author

> This project was developed as a hands-on simulation to demonstrate how two LANs can communicate over a WAN using Cisco Packet Tracer.

---
