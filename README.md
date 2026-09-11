# Splunk Threat Hunting Suite

Custom Splunk SPL queries for detecting Active Directory attacks, LSASS memory dumping, and encoded PowerShell execution.

## Detections Included
* **T1003.001 - LSASS Memory Dumping:** Sysmon Event ID 10 analysis.
* **T1558.003 - Kerberoasting Attack:** Event ID 4769 SPN requests.
* **T1059.001 - Encoded PowerShell Execution:** Suspicious command-line detection.
