# Enterprise Wazuh SIEM Capstone Lab

## Overview

Designed and deployed a Wazuh SIEM environment within a segmented ESXi infrastructure to monitor Windows-based systems for threat detection, vulnerability management, compliance validation, and centralized security event analysis.

This capstone project focused on blue-team operations, endpoint visibility, vulnerability detection, CIS benchmarking, and security monitoring across multiple Windows systems.

---

## Infrastructure Environment

### Virtualization Platform
- VMware ESXi

### Network Segmentation
- VLAN 30 Server Network
- Static IP Addressing

### Monitored Systems
| System | Purpose |
|---|---|
| Ubuntu Server | Wazuh SIEM Server |
| Windows Server 2022 | DNS/DHCP Server |
| Windows Server 2022 | RADIUS Server |
| Windows 11 | Endpoint Client |

---

## Technologies Used

- Wazuh 4.10
- Ubuntu Server
- Windows Server 2022
- Windows 11
- VMware ESXi
- OpenSSH
- PuTTY
- CIS Benchmarks
- Threat Hunting Dashboards
- Vulnerability Detection
- Endpoint Monitoring

---

## Project Objectives

This lab environment was designed to demonstrate:

- SIEM deployment and administration
- Endpoint monitoring and telemetry
- Centralized log analysis
- Vulnerability detection
- Threat hunting visibility
- CIS compliance benchmarking
- Agent management
- Security event correlation
- Windows infrastructure monitoring
- Blue-team defensive security concepts

---

## Wazuh Server Deployment

Configured an Ubuntu-based Wazuh server and enabled remote administration through SSH.

### Deployment Steps
- Installed and configured OpenSSH
- Installed curl dependencies
- Installed Wazuh 4.10 using the official installer
- Configured static IP addressing
- Exported and deployed VM to VMware ESXi
- Assigned VM to VLAN 30 server network

---

## Endpoint Agent Deployment

Installed and configured Wazuh agents across multiple monitored systems.

### Agent Deployment Process
- Installed Wazuh agents on Windows systems
- Configured manager IP addressing
- Registered agents through Wazuh agent manager
- Generated authentication keys
- Imported authentication keys into endpoints
- Started Wazuh agent services
- Verified agent communication with SIEM server

---

## Security Monitoring & Visibility

The Wazuh environment provided centralized monitoring for:

- Endpoint activity
- Windows event collection
- Vulnerability detection
- Threat hunting
- File integrity monitoring
- Authentication monitoring
- Registry monitoring
- Compliance validation
- Security event correlation

---

## Threat Hunting & Event Analysis

The platform was used to analyze:

- Windows logon/logoff events
- Registry integrity events
- Authentication activity
- Security alerts
- Event severity levels
- Endpoint telemetry

Threat hunting dashboards provided visibility into security events and suspicious activity patterns across monitored systems.

---

## CIS Benchmark Compliance

CIS benchmark dashboards were used to:
- Identify security misconfigurations
- Validate compliance controls
- Review failed benchmark checks
- Analyze hardening opportunities

This helped demonstrate security posture visibility within monitored Windows systems.

---

## Vulnerability Detection

Wazuh vulnerability detection identified:
- Critical vulnerabilities
- High severity vulnerabilities
- Medium severity vulnerabilities
- Low severity vulnerabilities

Detected vulnerabilities included:
- Windows Server vulnerabilities
- Microsoft Edge vulnerabilities
- Multiple CVE findings with varying CVSS severity scores

---

## Skills Demonstrated

- SIEM Administration
- Wazuh Deployment
- Windows Security Monitoring
- Linux Administration
- VMware ESXi Administration
- Threat Hunting
- Vulnerability Management
- Endpoint Security
- CIS Benchmarking
- Security Event Analysis
- Blue-Team Operations
- Infrastructure Documentation

---

## Repository Structure

```text
reports/       -> Full capstone documentation
screenshots/   -> Wazuh dashboards and monitoring screenshots
README.md      -> Project overview
```

---

## Full Documentation

The complete capstone report and implementation walkthrough can be found in the `/reports` directory.
