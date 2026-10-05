# Enterprise Network Segmentation, DHCP & DNS Lab

![Status](https://img.shields.io/badge/Type-Personal%20Lab-blue)
![Owner](https://img.shields.io/badge/Owner-Muhammad%20Huzefa-purple)

## Overview

A practical enterprise network design covering logical segmentation, addressing, DHCP, DNS and secure client connectivity.

**Primary skills:** LAN/WAN, VLANs, TCP/IP, DHCP, DNS, Routing, UDM Pro

## Proposed Network

| VLAN | Purpose | Example Subnet |
|---|---|---|
| 10 | IT/Admin | 10.10.10.0/24 |
| 20 | Staff | 10.10.20.0/24 |
| 30 | Voice | 10.10.30.0/24 |
| 40 | Guest | 10.10.40.0/24 |
| 50 | Servers | 10.10.50.0/24 |
| 60 | CCTV/IoT | 10.10.60.0/24 |

All addresses are fictional lab values.

## Lab Scope

- VLAN planning
- IP addressing and subnetting
- DHCP scopes
- DNS resolution
- Inter-VLAN routing
- Guest isolation
- Server/client network separation
- Firewall rule design
- UDM Pro concepts
- Troubleshooting with ping, nslookup and tracert

## Troubleshooting Matrix

Document checks for:
- No IP address
- Duplicate IP
- DNS failure
- Gateway unreachable
- Inter-VLAN access blocked
- Internet unavailable

## Evidence

Create a topology diagram and screenshots of VLAN/DHCP/DNS configuration in the lab environment.


## Evidence Standard

Implementation evidence will be added as the lab is completed. Screenshots, diagrams, scripts and test results should represent actual work performed in the personal lab.

## Attribution

This project is independently authored by Muhammad Huzefa. Vendor documentation and public repositories may be consulted as learning references, but third-party code or documentation is not presented as original work.
