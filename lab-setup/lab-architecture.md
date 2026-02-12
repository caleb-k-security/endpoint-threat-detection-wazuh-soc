# SOC Lab Architecture

## Overview
This lab simulates a real Tier-1 Security Operations Center environment for monitoring, detection, and incident investigation.

## Environment Components

Attacker Machine
- OS: Kali Linux
- Role: Simulates malicious activity

Victim Endpoint
- OS: Windows 10
- Tools Installed:
  - Sysmon
  - Wazuh Agent

SOC Server
- OS: Ubuntu Server
- Platform: Wazuh SIEM Stack

---

## Network Design
All virtual machines were connected using a NAT network within VirtualBox to enable controlled attack simulation and log transmission.

Traffic Flow:
Kali → Windows → Wazuh → Dashboard → Analyst Investigation

---

## Security Telemetry Sources
Logs collected included:

- Windows Security Logs
- Sysmon telemetry
- Authentication events
- File creation events
- Process execution logs

---

## Objective
To validate that a SOC analyst can detect, investigate, and document security incidents using real telemetry and SIEM alerts.
