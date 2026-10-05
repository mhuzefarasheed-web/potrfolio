# Microsoft 365 & Exchange Online Migration Lab

![Status](https://img.shields.io/badge/Type-Personal%20Lab-blue)
![Owner](https://img.shields.io/badge/Owner-Muhammad%20Huzefa-purple)

## Overview

A controlled lab for planning and documenting mailbox migration from hosted/cPanel mail to Microsoft 365, including DNS cutover, Outlook profile handling and PST validation.

**Primary skills:** Microsoft 365, Exchange Online, DNS, MX, SPF, DKIM, DMARC, Outlook, PST

## Scenario

Simulate a small organization moving selected executive mailboxes from a legacy hosted mail platform to Microsoft 365.

## Lab Scope

- Tenant/domain preparation
- Accepted domain and mailbox planning
- MX record cutover planning
- SPF, DKIM and DMARC validation concepts
- Exchange Online mailbox creation
- Outlook profile and autodiscover considerations
- PST export/import validation
- Shared mailbox and delegation concepts
- Rollback checklist
- Post-migration verification

## Test Cases

| Test | Expected Result |
|---|---|
| Send internal mail | Delivered |
| Send external mail | Delivered |
| Receive external mail | Delivered |
| Outlook profile reconnect | Successful |
| PST data visibility | Mail/folders visible after import |
| DNS verification | Records resolve correctly |
| Decommission legacy mailbox | Access removed after validation |

## Migration Runbook

1. Inventory legacy mailboxes
2. Identify critical users and aliases
3. Prepare Microsoft 365
4. Lower DNS TTL before cutover
5. Create/verify DNS records
6. Migrate pilot mailbox
7. Validate send/receive and Outlook
8. Migrate remaining mailboxes
9. Monitor delivery and authentication
10. Decommission legacy service after sign-off

## Interview Talking Points

- Why DNS planning matters before an email migration
- Difference between mailbox data migration and DNS cutover
- Why Outlook can retain stale account/profile information
- Why PST validation should confirm actual message visibility, not only successful file attachment


## Evidence Standard

Implementation evidence will be added as the lab is completed. Screenshots, diagrams, scripts and test results should represent actual work performed in the personal lab.

## Attribution

This project is independently authored by Muhammad Huzefa. Vendor documentation and public repositories may be consulted as learning references, but third-party code or documentation is not presented as original work.
