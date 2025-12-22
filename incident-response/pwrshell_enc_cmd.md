# Incident Response Playbook – Encoded PowerShell Command

## Overview
This playbook outlines the response process for detecting and handling encoded/obfuscated PowerShell execution, commonly associated with malware delivery, lateral movement, or post-exploitation activity.

**MITRE ATT&CK:**  
- T1059.001 – PowerShell

---

## Detection Sources
- SIEM alerts (PowerShell with -EncodedCommand flag)
- EDR telemetry
- Windows Event Logs (Event ID 4688, 4104)

---

## Triage
- Identify the affected host and user account
- Validate whether the execution is expected or malicious
- Review command-line arguments and parent process
- Check for additional suspicious activity on the host

---

## Containment
- Isolate the endpoint from the network if malicious activity is confirmed
- Disable compromised user account if necessary
- Block malicious hashes or scripts

---

## Eradication
- Remove malicious scripts or persistence mechanisms
- Patch vulnerabilities if applicable
- Reset credentials associated with the incident

---

## Recovery
- Restore system to last known good state
- Reconnect host to the network after validation
- Monitor for recurrence

---

## Lessons Learned
- Update detection rules to reduce false positives
- Improve logging and PowerShell restrictions
- Document indicators of compromise
