# Networking Capstone Project - Technova Limited

Designed and configured in Cisco Packet Tracer.

## Overview
A small enterprise network for Technova Limited with three departments
(IT, Sales and HR) connected through one router. The network uses DHCP,
inter-department routing and an Access Control List (ACL) for security.

## Devices Used
- 1 x Cisco 2911 router
- 3 x Cisco 2960 switches
- 1 x server (IT department)
- 6 x PCs (2 per department)

## IP Plan
| Department | Subnet | Gateway |
|------------|------------------|--------------|
| IT | 192.168.10.0/24 | 192.168.10.1 |
| Sales | 192.168.20.0/24 | 192.168.20.1 |
| HR | 192.168.30.0/24 | 192.168.30.1 |

IT server (HTTP): 192.168.10.2

## What I Did
1. Built the topology with straight-through cables.
2. Configured DHCP so PCs get addresses automatically.
3. Confirmed routing: ping from an HR PC to an IT PC succeeded.
4. Wrote an extended ACL (Sales-ACL) to block ICMP from Sales to IT.
5. Confirmed the ACL: Sales to IT ping failed (100% loss).
6. Confirmed Sales could still open the IT web page over HTTP.

## Skills Demonstrated
IP addressing, subnetting, DHCP, routing, ACLs, network testing,
troubleshooting with ping, Cisco IOS CLI.

## Files
- Networking_Capstone_Project.pdf - full report with screenshots
- Technova Network Topology (Technova.pkt)
- Assets folder (screenshots)
  
## Author
Raphael Ndidi-Uboma
