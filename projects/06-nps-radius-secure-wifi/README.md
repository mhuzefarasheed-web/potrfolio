# NPS/RADIUS Secure Wi-Fi Authentication Lab

![Status](https://img.shields.io/badge/Type-Personal%20Lab-blue)
![Owner](https://img.shields.io/badge/Owner-Muhammad%20Huzefa-purple)

## Overview

A secure wireless access lab using Active Directory-backed authentication and RADIUS concepts.

**Primary skills:** NPS, RADIUS, Active Directory, WPA2/WPA3-Enterprise, UDM Pro

## Scenario

Design enterprise Wi-Fi authentication where staff access is authenticated centrally rather than through a shared password.

## Architecture

```
Windows Client
     |
Access Point / UDM
     |
   RADIUS
     |
 Windows NPS
     |
Active Directory
```

## Lab Scope

- NPS role
- RADIUS client configuration
- AD security-group based access
- Authentication policy
- Authorization policy
- Staff vs guest wireless design
- Logging and troubleshooting

## Security Goals

- Avoid shared staff credentials
- Separate guest traffic
- Centralize access decisions
- Log authentication attempts
- Apply least privilege

## Troubleshooting

Document checks for certificate issues, shared-secret mismatch, rejected credentials, firewall blocks and incorrect NPS policies.


## Evidence Standard

Implementation evidence will be added as the lab is completed. Screenshots, diagrams, scripts and test results should represent actual work performed in the personal lab.

## Attribution

This project is independently authored by Muhammad Huzefa. Vendor documentation and public repositories may be consulted as learning references, but third-party code or documentation is not presented as original work.
