# Sysmon Event IDs Observed

## Overview

During this lab, Microsoft Sysmon was used to monitor Windows endpoint activity. The following Event IDs were observed and analyzed using Windows Event Viewer.

---

## Event ID 1 – Process Creation

**Purpose:**
Logs every process created on the system.

**Examples Observed:**
- PowerShell
- tasklist
- whoami
- ipconfig /all
- net user

**Learning:**
This event helps SOC analysts identify suspicious process execution.

---

## Event ID 3 – Network Connection

**Purpose:**
Logs outbound network connections created by a process.

**Example Observed:**
- OneDrive.exe established a network connection.

**Learning:**
Useful for detecting malware communicating with external servers.

---

## Event ID 13 – Registry Value Set

**Purpose:**
Logs registry value modifications.

**Learning:**
Useful for detecting persistence techniques and registry-based malware activity.

---

## Event ID 22 – DNS Query

**Purpose:**
Logs DNS requests made by processes.

**Example Observed:**
- s.cloud.360safe.com

**Learning:**
Helps identify suspicious domain lookups and Command & Control (C2) communication.

---

# Summary

During this project, I learned how Sysmon records endpoint activity including:

- Process Creation
- Network Connections
- Registry Modifications
- DNS Queries

These logs were analyzed using Windows Event Viewer as part of a SOC Analyst lab.
