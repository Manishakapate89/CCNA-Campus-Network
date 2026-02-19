# Enterprise Campus Network (CCNA Project)

## Project Overview
This project demonstrates the design and implementation of a complete enterprise-style campus network using Cisco Packet Tracer. The network follows a hierarchical architecture (Core, Distribution, Access) and includes VLAN segmentation, Inter-VLAN routing, dynamic routing (OSPF), DHCP, and NAT.

This project simulates a real-world organizational network and showcases practical CCNA-level networking skills.

---

## Network Architecture
The network is designed using the 3-layer hierarchical model:

- Core Layer → Backbone connectivity (R1)
- Distribution Layer → Routing and network control (R2, R3)
- Access Layer → End devices and VLAN segmentation (Switches)

---

## Key Features

- VLAN segmentation for department separation  
- Inter-VLAN Routing using Router-on-a-Stick  
- OSPF Dynamic Routing for automatic route learning  
- DHCP for automatic IP address assignment  
- NAT (PAT) for internet simulation  
- Hierarchical Campus Network Design  
- End-to-end connectivity testing and troubleshooting  

---

## VLAN & Network Plan

| VLAN | Department | Network | Gateway |
|------|------------|---------|---------|
| 10 | HR | 192.168.10.0/24 | 192.168.10.1 |
| 20 | IT | 192.168.20.0/24 | 192.168.20.1 |
| 30 | Sales | 192.168.30.0/24 | 192.168.30.1 |
| 40 | Admin | 192.168.40.0/24 | 192.168.40.1 |

---

## Routing Protocol
OSPF (Open Shortest Path First) was used to enable dynamic routing between core and distribution routers, ensuring automatic route learning and network convergence.

---

## Services Configured

### DHCP
Routers were configured as DHCP servers to automatically assign IP addresses, default gateways, and DNS to all VLAN users.

### NAT (PAT)
Network Address Translation was configured on the core router to simulate internet access for internal private networks.

---

## Testing & Verification

- Inter-VLAN communication successful  
- OSPF neighbors formed correctly  
- DHCP assigning IP addresses automatically  
- All VLANs able to communicate across network  
- NAT translation verified using show commands  

---

## Skills Demonstrated

Routing, Switching, VLAN, Inter-VLAN Routing, OSPF, DHCP, NAT, Network Design, Troubleshooting, Cisco IOS

---

## Files Included

- campus-network.pkt → Cisco Packet Tracer topology  
- configs.txt → Router and Switch configurations  
- topology.png → Network diagram  
- README.md → Project documentation  

---

## Author
Manisha Kapate
