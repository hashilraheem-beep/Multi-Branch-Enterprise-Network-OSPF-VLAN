# TechNova – Multi-Branch Enterprise Network Infrastructure

## Project Overview
TechNova is a simulated enterprise network infrastructure designed using Cisco Packet Tracer. It connects three company branches located in Kochi, Kozhikode, and Trivandrum through a secure and scalable network architecture.

## Network Architecture
- Kochi – Head Office
- Kozhikode – Branch Office
- Trivandrum – Branch Office

Each branch contains three departments:
- HR
- IT
- Finance

## Technologies Implemented
- VLAN Configuration
- Inter-VLAN Routing (Router-on-a-Stick)
- OSPF Dynamic Routing
- DHCP Configuration
- Access Control Lists (ACL)
- SSH Remote Management
- Switch Port Security
- IP Addressing and Subnetting

## Network Design
The network uses a triangular WAN topology connecting all three branch routers. OSPF Area 0 enables dynamic routing and communication between branches.

## Security Features
- ACL rules restrict HR departments from accessing Finance networks.
- SSH provides secure remote device management.
- Port security limits each configured access port to one learned MAC address.

## Tools Used
- Cisco Packet Tracer
- Cisco IOS CLI
- CCNA Networking Concepts

## Project File
- `TechNova.pkt` – Complete Cisco Packet Tracer network simulation.

## Learning Outcomes
Gained practical experience in enterprise network design, VLAN segmentation, routing, IP addressing, network security, and remote device management.
