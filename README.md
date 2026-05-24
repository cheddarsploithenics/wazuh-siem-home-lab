# Wazuh SIEM Home Lab

## Overview

Designed and implemented a Wazuh SIEM home lab environment using Ubuntu Server, VMware, and Windows Server systems for centralized monitoring, vulnerability detection, endpoint visibility, and threat analysis.

The lab environment was built to simulate defensive security monitoring and blue-team operations within a Windows domain environment.

---

## Lab Environment

### Infrastructure
- Ubuntu Server (Wazuh Server)
- Windows Server 2022 Domain Controller
- Windows Server 2016 (Intentionally Vulnerable)
- VMware Workstation

### Tools & Technologies
- Wazuh 4.10
- OpenSSH
- PuTTY
- Windows Server
- Ubuntu Linux
- VMware
- MITRE ATT&CK Mapping
- CIS Benchmarking

---

## Project Objectives

This project focused on:

- SIEM deployment and configuration
- Endpoint monitoring
- Vulnerability detection
- Security event analysis
- Threat visibility
- CIS compliance benchmarking
- MITRE ATT&CK monitoring
- Windows server monitoring
- Blue-team security operations concepts

---

## Wazuh Server Deployment

Configured an Ubuntu-based Wazuh server and enabled remote management through OpenSSH.

### Installation Steps
- Installed OpenSSH server
- Enabled and verified SSH service
- Installed curl
- Installed Wazuh 4.10 using the official installer script
- Verified Wazuh services and HTTPS access

---

## Endpoint Agent Configuration

Configured and monitored two Windows Server endpoints:

| System | Purpose |
|---|---|
| Windows Server 2022 | Properly configured domain controller |
| Windows Server 2016 | Intentionally vulnerable monitoring target |

### Agent Management
- Added agents through Wazuh agent manager
- Generated and extracted authentication keys
- Installed Wazuh agents on Windows systems
- Connected agents to centralized Wazuh server

---

## Security Monitoring Features

The environment demonstrated:

- Vulnerability monitoring
- Endpoint visibility
- Security event collection
- Threat intelligence integration
- File integrity monitoring
- MITRE ATT&CK mapping
- CIS benchmark compliance analysis
- Alert visualization
- Security dashboard monitoring

---

## Vulnerability & Compliance Analysis

The intentionally vulnerable Windows Server 2016 machine generated:

- Critical vulnerabilities
- High severity findings
- Medium severity findings
- CIS benchmark failures
- MITRE ATT&CK tactic detections

The properly configured Server 2022 system demonstrated improved compliance and reduced vulnerability exposure.

---

## MITRE ATT&CK Visibility

Wazuh dashboards were used to monitor:
- Defense evasion activity
- Persistence attempts
- Privilege escalation
- Initial access tactics

---

## Skills Demonstrated

- SIEM Deployment
- Wazuh Administration
- Linux Administration
- Windows Server Monitoring
- Security Monitoring
- Threat Detection
- Vulnerability Management
- Endpoint Security
- Blue-Team Operations
- Security Compliance
- MITRE ATT&CK Analysis
- Virtualization

---

## Repository Structure

```text
reports/       -> Full project documentation
screenshots/   -> Wazuh dashboards and monitoring screenshots
README.md      -> Project overview
```

---

## Full Report

The complete project documentation is located in the `/reports` directory.
