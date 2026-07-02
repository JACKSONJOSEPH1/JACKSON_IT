# Multi-VLAN Network with Router DHCP Configuration

## Project Overview

Designed and configured a multi-VLAN network where a Cisco router provides DHCP services, allowing PCs in different VLANs to automatically receive IP addresses and communicate across VLANs.

---

## Objectives

- Configure multiple VLANs on a Cisco switch.
- Assign switch ports to the correct VLANs.
- Configure Router-on-a-Stick (Inter-VLAN Routing).
- Configure DHCP pools on the router.
- Enable automatic IP address assignment to PCs.
- Verify end-to-end connectivity using ping.

---

## Technologies Used

- Cisco Packet Tracer
- Cisco Router
- Cisco Layer 2 Switch
- DHCP
- VLANs
- IEEE 802.1Q Trunking
- Inter-VLAN Routing

---

## Network Configuration

### VLANs

| VLAN ID | Department | Network |
|---------:|------------|----------------|
| 10 | Administration | 192.168.10.0/24 |
| 20 | Finance | 192.168.20.0/24 |
| 30 | ICT | 192.168.30.0/24 |

---

## Key Configurations

- Created multiple VLANs.
- Assigned switch access ports to the appropriate VLANs.
- Configured a trunk link between the switch and router.
- Created router subinterfaces using 802.1Q encapsulation.
- Configured DHCP pools for each VLAN.
- Set the default gateway for each VLAN.
- Configured DNS server addresses.
- Verified that all PCs automatically obtained IP addresses from the router.

---

## Skills Demonstrated

- VLAN Configuration
- Switch Port Configuration
- Trunk Configuration
- Router-on-a-Stick
- DHCP Configuration
- Inter-VLAN Routing
- Network Troubleshooting
- Connectivity Testing

---

## Results

- Successfully configured multiple VLANs.
- PCs automatically received IP addresses from the router.
- Devices within the same VLAN communicated successfully.
- Devices in different VLANs communicated through inter-VLAN routing.
- Connectivity was verified using the ping command.

---

## Tools

- Cisco Packet Tracer
- Cisco IOS CLI

---

## Screenshots

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4639e4f3-4366-4f6a-a744-47cc8b9f5a28" />
<img width="1856" height="755" alt="image" src="https://github.com/user-attachments/assets/ea44fc7f-9e4a-45e0-baf0-f555d1b6fa42" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42418652-fe21-449d-876a-edad6837489c" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/785b184f-9edc-497a-b5cb-6d266002ad08" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5a42e8ab-3b4f-4e02-bd14-869056fa78d1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5c8a193e-1331-4032-989d-4bd7818cdd22" />


