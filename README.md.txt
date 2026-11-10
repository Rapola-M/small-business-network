
# Small Business Network

## 1. Project Overview

This project involves designing and implementing a small business network using Cisco Packet Tracer.

The network connects two departments: IT and Finance. Each department has its own VLAN and IP network.

## 2. Project Objectives

- Create and configure VLANs.
- Assign switch ports to the correct VLANs.
- Configure 802.1Q trunk links.
- Implement Router-on-a-Stick.
- Configure DHCP for automatic IP addressing.
- Enable communication between different VLANs.
- Test network connectivity.

## 3. Technologies Used

- Cisco Packet Tracer
- VLANs
- 802.1Q Trunking
- Router-on-a-Stick
- DHCP
- IPv4 Addressing
- Inter-VLAN Routing

## 4. Network Addressing

| Department | VLAN | Network |
|---|---|---|
| IT | 10 | 192.168.10.0/24 |
| Finance | 20 | 192.168.20.0/24 |

## 5. DHCP Address Allocation

| Computer | Assigned IP |
|---|---|
| IT-PC1 | 192.168.10.11 |
| IT-PC2 | 192.168.10.12 |
| IT-PC3 | 192.168.10.13 |
| FIN-PC1 | 192.168.20.11 |
| FIN-PC2 | 192.168.20.12 |
| FIN-PC3 | 192.168.20.13 |

## 6. Implementation

The network was configured using VLAN segmentation, trunk links and Router-on-a-Stick.

DHCP was configured to automatically assign IP addresses to the six computers.

## 7. Testing and Results

The following tests were performed:

- DHCP address allocation was successful.
- All six computers received IP addresses.
- Gateway connectivity was tested.
- Inter-VLAN connectivity was tested.
- Ping tests showed 0% packet loss.

## 8. Project Outcome

The network successfully demonstrated communication between the IT and Finance departments.

All six computers received DHCP addresses and connectivity tests were successful.

## 9. Evidence

Screenshots of the network topology, VLAN configuration, trunk configuration, DHCP bindings and ping tests are available in the screenshots folder.

## 10. Author

Networking Portfolio Project