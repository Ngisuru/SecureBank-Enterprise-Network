# SecureBank Enterprise Network

## Project Overview
A Cisco Packet Tracer simulation of a secure banking network connecting a Head Office and two branch offices.

## Network Devices
- 4 Cisco 2911 Routers
- 4 Cisco 2960 Switches
- 9 PCs
- 3 Servers

## Network Technologies
- VLAN Segmentation
- Router-on-a-Stick Inter-VLAN Routing
- OSPF Area 0
- Extended Access Control Lists (ACLs)
- Switch Port Security
- SSH Version 2
- DHCP and DNS Services
- Banking Web Server

## IP Addressing Plan

| Network | Subnet |
|---|---|
| HQ Teller | 192.168.10.0/24 |
| HQ Admin | 192.168.20.0/24 |
| Servers | 192.168.30.0/24 |
| Branch 1 ATM | 192.168.40.0/24 |
| Untrusted | 192.168.50.0/24 |
| Branch 1 Teller | 192.168.60.0/24 |
| Branch 2 Teller | 192.168.70.0/24 |
| Branch 2 ATM | 192.168.41.0/24 |

## Security Features
- ACL rules restrict traffic from the untrusted network to the server subnet.
- Switch port security limits the number of secure MAC addresses on protected access ports.
- SSH provides encrypted remote router management.
- VLANs separate different types of network devices and users.

## Project File
`SecureBank_Enterprise_Network.pkt` — Cisco Packet Tracer simulation file.

## Testing
Connectivity, OSPF routing, ACL enforcement, port security, DNS resolution, HTTP access, and SSH login should be tested in Packet Tracer.

## Disclaimer
This project is an educational network simulation and is not intended for direct deployment in a production banking environment.
