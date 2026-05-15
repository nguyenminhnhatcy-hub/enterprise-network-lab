# Enterprise Network Lab

## Overview
This project simulates a small enterprise network environment using Cisco Packet Tracer.  
The lab focuses on VLAN segmentation, inter-VLAN routing, dynamic routing, DHCP configuration, NAT, ACL, and SSH remote management.

---

## Network Topology

### Devices
- 3 Routers
- 3 Switches
- 1 DHCP Server
- Multiple PCs and Laptops

### Network Structure
- VLAN10 - HR Department
- VLAN20 - Sales Department
- VLAN30 - IT Department
- VLAN40 - Guest Network
- Server Network

---

## VLAN Configuration

| VLAN | Department | Subnet |
|------|------|------|
| VLAN10 | HR | 192.168.10.0/24 |
| VLAN20 | Sales | 192.168.20.0/24 |
| VLAN30 | IT | 192.168.30.0/24 |
| VLAN40 | Guest | 192.168.40.0/24 |

---

## Features Implemented
- VLAN segmentation
- Inter-VLAN routing
- DHCP configuration
- ACL filtering
- OSPF routing
- NAT configuration
- SSH remote access
- Basic network troubleshooting

---

## Device Naming

### Switches
- Access-SW1
- Core-SW
- Access-SW2

### Routers
- HQ-Router
- Branch-Router
- Server-Router

### End Devices
- HR-PC1
- HR-PC2
- Sales-Laptop1
- Sales-Laptop2
- IT-PC1
- IT-PC2
- Guest-Laptop1
- Guest-Laptop2

---

## Verification Commands

```bash
show vlan brief
show ip route
show ip ospf neighbor
show access-lists
ping
tracert
```

---

## Troubleshooting

### Issue 1
Devices in different VLANs could not communicate.

### Cause
Incorrect VLAN assignment on switch access ports.

### Solution
Reconfigured switchport VLAN settings and verified trunk links.

---

### Issue 2
OSPF neighbors failed to establish adjacency.

### Cause
Incorrect network configuration.

### Solution
Corrected OSPF network statements and verified interface IP addresses.

---

## Technologies Used
- Cisco Packet Tracer
- VLAN
- OSPF
- ACL
- DHCP
- NAT
- SSH

---

## Files
- Lab.pkt
- Topology.png

---

## What I Learned
- Basic enterprise network design
- VLAN segmentation and routing
- OSPF configuration
- Network troubleshooting workflow
- ACL implementation and traffic control
- Basic infrastructure management
