# Module 01 — Active Directory & Windows Server

## Purpose

This module demonstrates the design and administration of a small enterprise Windows domain environment.

## Planned Environment

- Windows Server 2022
- Windows 11 client
- Active Directory Domain Services
- DNS
- Group Policy
- Organizational Units
- Security Groups
- PowerShell

## Logical Structure

```
Huzefa Enterprise Lab
|
+-- Domain Controllers
|   +-- DC01
|
+-- Organizational Units
|   +-- IT
|   +-- HR
|   +-- Finance
|   +-- Management
|   +-- Workstations
|
+-- Security Groups
|   +-- IT-Admins
|   +-- Helpdesk
|   +-- HR-Users
|   +-- Finance-Users
|   +-- Management-Users
|
+-- Windows 11 Clients
    +-- WIN11-01
```

## Implementation Checklist

- [ ] Create Windows Server virtual machine
- [ ] Configure static IP addressing
- [ ] Install AD DS role
- [ ] Promote server to Domain Controller
- [ ] Configure DNS
- [ ] Create organizational units
- [ ] Create users and security groups
- [ ] Join Windows 11 client to the domain
- [ ] Create baseline Group Policies
- [ ] Test policy application
- [ ] Document troubleshooting
- [ ] Add implementation screenshots

## Security Concepts

The lab will demonstrate:

- Least privilege
- Role-based group membership
- Controlled administrative access
- Password and account policies
- Workstation security policies
- Separation of administrative and standard accounts

## Evidence

Screenshots and configuration evidence will be added as the physical/virtual lab is implemented.
