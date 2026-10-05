# Module 02 — IT Service Desk & Troubleshooting

## Purpose

This module simulates an enterprise IT service desk workflow for incidents and service requests.

## Ticket Categories

### Incidents

- Windows login failure
- Account lockout
- Outlook synchronization issue
- VPN connection failure
- DNS resolution failure
- Network connectivity issue
- Software failure
- Hardware failure

### Service Requests

- New user account
- Laptop provisioning
- Software installation
- Access request
- Peripheral request
- Employee offboarding

## Ticket Workflow

```
New
  |
  v
Categorize
  |
  v
Prioritize
  |
  v
Investigate
  |
  v
Resolve
  |
  v
User Confirmation
  |
  v
Close + Document
```

## Example Incident

**INC-001 — Domain Login Failure**

**Symptom:** User cannot sign in to Windows.

**Initial checks:**
1. Confirm username
2. Check network connectivity
3. Check account status in Active Directory
4. Check password status
5. Review relevant event logs

**Possible resolution:** Unlock account or reset credentials after identity verification.

**Documentation:** Record root cause, resolution and preventive action.

## ITIL Alignment

The lab demonstrates practical concepts related to:

- Incident management
- Request fulfillment
- Prioritization
- Escalation
- Root-cause documentation
- Knowledge management
- SLA awareness

This module is intended to demonstrate operational thinking rather than reproduce a commercial ticketing platform.
