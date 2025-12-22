# Incident Response Playbook – Malware Detection on Endpoint

## Overview
This playbook outlines response steps for malware detected on an endpoint through EDR/SIEM alerts.

**MITRE ATT&CK:**  
- T1204 – User Execution  
- T1055 – Process Injection

---

## Detection Sources
- EDR alerts
- SIEM correlated events
- Antivirus detections

---

## Triage
- Identify malware type and severity
- Review affected processes and files
- Check for lateral movement indicators

---

## Containment
- Isolate the endpoint
- Quarantine malicious files
- Disable affected user accounts if needed

---

## Eradication
- Remove malware artifacts
- Apply system patches
- Update antivirus definitions

---

## Recovery
- Restore system functionality
- Reimage system if required
- Resume normal operations

---

## Lessons Learned
- Improve endpoint protections
- Enhance user awareness
- Update incident handling procedures
