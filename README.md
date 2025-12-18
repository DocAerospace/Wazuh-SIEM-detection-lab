# Wazuh-SIEM-detection-lab
Wazuh SIEM lab integrating Windows Sysmon telemetry, alert tuning, and custom PowerShell encoded command detection mapped to MITRE ATT&amp;CK



# Wazuh SIEM Lab – Windows Endpoint Monitoring and Custom Detection

## Overview
I built a Wazuh based SIEM lab to ingest Windows Sysmon telemetry, tune noisy alerts, and develop custom detections mapped to MITRE ATT&CK.

## Architecture
Wazuh Manager in Ubuntu, Windows 10 Agent, Sysmon telemetry, Wazuh Dashboard

## What i did.....
I deployed Windows Wazuh agent and verified active connectivity
I ingested Sysmon process creation events
I tuned noisy Windows privilege failure alerts to reduce false positives
I created custom detection for encoded PowerShell execution
I mapped detection to MITRE ATT&CK T1059.001
I validated detections using live attack simulation

## Screenshots are included in the WazuhScreenshots folder
