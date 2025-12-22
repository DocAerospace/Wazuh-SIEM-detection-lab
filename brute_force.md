# Incident Response Playbook – Brute Force Login Attempts

## Overview
This playbook addresses detection and response to brute force authentication attempts against user accounts or services.

**MITRE ATT&CK:**  
- T1110 – Brute Force

---

## Detection Sources
- SIEM authentication failure alerts
- Windows Security Logs
- Cloud identity provider alerts

---

## Triage
- Identify targeted accounts
- Determine source IPs and geographic origin
- Check for successful authentication following failures

---

## Containment
- Temporarily lock affected accounts
- Block malicious IP addresses
- Enforce MFA and other password security policies if not already enabled

---

## Eradication
- Reset compromised credentials
- Review access permissions
- Remove unauthorized access

---

## Recovery
- Restore account access securely
- Notify impacted users if required
- Monitor authentication logs

---

## Lessons Learned
- Adjust account lockout policies
- Improve alert thresholds
- Strengthen identity protection controls
