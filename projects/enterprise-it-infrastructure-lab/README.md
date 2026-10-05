# Muhammad Huzefa — Enterprise IT Infrastructure & System Administration Lab

![Project Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Focus](https://img.shields.io/badge/Focus-IT%20Infrastructure-blue)
![Lab](https://img.shields.io/badge/Type-Hands--On%20Lab-purple)

## Overview

This is an original personal learning and portfolio project by **Muhammad Huzefa**, designed to demonstrate practical IT infrastructure, system administration, endpoint management, service desk, asset management, identity, networking, and security skills.

The lab is designed around realistic enterprise scenarios and is documented as an implementation project rather than a copy of another repository.

## Objectives

- Build and document a Windows enterprise identity environment
- Practice Active Directory, DNS and Group Policy administration
- Simulate Windows endpoint onboarding and support
- Document Microsoft 365 / Entra ID identity workflows
- Demonstrate IT service desk incident and request handling
- Demonstrate IT asset lifecycle management with Snipe-IT
- Practice PowerShell automation and operational documentation
- Develop enterprise infrastructure diagrams and troubleshooting runbooks
- Apply practical security and least-privilege concepts

## Lab Architecture

```
                         Internet / Cloud
                                |
                     +----------+----------+
                     | Microsoft 365 /     |
                     | Entra ID / Intune   |
                     +----------+----------+
                                |
                           Enterprise LAN
                                |
                 +--------------+--------------+
                 |                             |
           Windows Server                  Client VLAN
                 |                             |
        +--------+--------+              +-----+------+
        |                 |              |            |
      AD DS             DNS           Windows 11   Support
        |                 |              Endpoint    Tools
        +--------+--------+                  |
                 |                         Snipe-IT
             Group Policy                 Service Desk
                 |
          PowerShell / Security
```

## Project Modules

| Module | Technologies | Status |
|---|---|---|
| Active Directory & Windows Server | AD DS, DNS, GPO | In Progress |
| Network Infrastructure | TCP/IP, VLAN, DHCP, DNS | Planned |
| Microsoft 365 & Entra ID | M365, Entra ID, IAM, RBAC | Planned |
| Endpoint Management | Intune, Windows 11 | Planned |
| IT Service Desk | Incident, Request, ITIL | Planned |
| IT Asset Management | Snipe-IT | Planned |
| Security Hardening | GPO, least privilege, BitLocker concepts | Planned |
| PowerShell Automation | PowerShell | Planned |

## Professional Relevance

This lab supports my professional focus as an **IT Infrastructure Engineer / System Administrator** and complements my enterprise IT support experience.

Key areas demonstrated:

- Active Directory and identity administration
- Microsoft 365 and cloud administration
- Endpoint and workplace support
- Incident and request management
- Hardware and software lifecycle management
- Network troubleshooting
- PowerShell
- IT documentation
- Security fundamentals

## How This Project Was Created

The implementation, documentation, diagrams and scenarios in this repository are being developed independently by Muhammad Huzefa.

Public GitHub projects and vendor documentation were reviewed as learning references where appropriate. No third-party repository was simply copied, renamed, or presented as original work.

## References

- Snipe-IT: https://github.com/grokability/snipe-it
- SysAdmin Portfolio / AD reference: https://github.com/nate-guru/sysadmin-portfolio
- HomeLab reference: https://github.com/JuanmaFranco/HomeLab
- IT Support & System Admin Labs: https://github.com/SusamTmg/IT-SUPPORT-AND-SYSTEM-ADMIN-LABS
- Enterprise IT Lab reference: https://github.com/ayitemoses/it-entreprise-lab

## Author

**Muhammad Huzefa**  
IT Infrastructure Engineer  
Karachi, Pakistan

Portfolio: https://mhuzefarasheed-web.github.io/potrfolio/

---

> This is a personal hands-on lab and portfolio project. Production environments require additional security controls, change management, monitoring, backup and governance.
