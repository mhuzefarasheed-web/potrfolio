# PowerShell Endpoint Inventory & Audit Automation

![Status](https://img.shields.io/badge/Type-Personal%20Lab-blue)
![Owner](https://img.shields.io/badge/Owner-Muhammad%20Huzefa-purple)

## Overview

A reusable PowerShell toolkit for collecting endpoint inventory and basic IT audit information.

**Primary skills:** PowerShell, Windows, WMI/CIM, CSV, Networking, Hardware Inventory

## Automation Goals

Collect:
- Computer name
- Serial number
- Manufacturer/model
- CPU
- RAM
- RAM slot information
- Disk type and capacity
- Windows version
- Wi-Fi adapter/MAC
- IP configuration
- Logged-in user
- BitLocker status

## Example Output

CSV reports can be generated for helpdesk and asset-management use.

## Security Principles

- Read-only collection where possible
- No passwords or secrets
- Clear error handling
- Timestamped reports
- Test against lab devices first

## Deliverables

- `Get-EndpointInventory.ps1`
- `Export-EndpointAudit.ps1`
- Sample CSV output
- Troubleshooting notes

## Interview Talking Points

Discuss how automation reduces manual inventory work and how you would safely adapt a script before using it across a production fleet.


## Evidence Standard

Implementation evidence will be added as the lab is completed. Screenshots, diagrams, scripts and test results should represent actual work performed in the personal lab.

## Attribution

This project is independently authored by Muhammad Huzefa. Vendor documentation and public repositories may be consulted as learning references, but third-party code or documentation is not presented as original work.
