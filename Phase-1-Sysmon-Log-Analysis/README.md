# Phase 1 - Windows Sysmon Log Analysis
## Objective
The objective of this lab was to install and configure Microsoft Sysmon on a Windows system and analyze endpoint activity using Windows Event Viewer.
---
## Environment
- Windows 11
- Sysmon
- Windows Event Viewer
- PowerShell
- Command Prompt
---
## Activities Performed
- Installed Sysmon
- Applied Sysmon configuration
- Verified Sysmon service
- Generated Windows events
- Analyzed Process Creation events
- Analyzed Network Connection events
- Analyzed DNS Query events
---
## Event IDs Investigated
| Event ID | Description |
|----------|-------------|
| 1 | Process Creation |
| 3 | Network Connection |
| 22 | DNS Query |
---
## Commands Tested
- tasklist
- whoami
- ipconfig /all
- net user
- powershell
---
## Skills Learned
- Sysmon Installation
- Windows Event Viewer
- Process Analysis
- Network Activity Monitoring
- DNS Monitoring
- Basic Threat Hunting
---
## Status
Phase 1 Completed Successfully
