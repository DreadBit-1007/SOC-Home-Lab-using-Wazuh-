# Lab Architecture

This project is a personal SOC-focused home lab designed to understand how attacker activities generate logs and how those logs are detected and analyzed by security teams.

## Environment Overview
The lab is built using multiple virtual machines hosted on VMware Workstation, each serving a specific role in the security workflow.

### Components
- **Hypervisor:** VMware Workstation
- **Attacker Machine:** Kali Linux  
  Used to simulate controlled attacker techniques such as reconnaissance and web testing.
- **Victim Machine:** Ubuntu Linux  
  Configured to generate system, authentication, and network logs.
- **SOC / SIEM Machine:** Wazuh  
  Used to collect logs, generate alerts, and support security analysis.

## Network Design
All virtual machines are connected using an isolated internal network to ensure:
- Safe testing
- No exposure to external systems
- Full control over traffic and logging

## SOC Workflow
This lab follows a simplified SOC analyst workflow:
1. Simulate attacker activity in a controlled environment
2. Generate logs on the victim system
3. Collect and correlate logs using Wazuh
4. Analyze alerts and investigate suspicious activity
5. Document findings and learnings

## Purpose
The primary goal of this lab is to gain hands-on experience with:
- SOC operations
- Log analysis and alert investigation
- Understanding attacker behavior from a defensive perspective
- Mapping activity to MITRE ATT&CK

This project is strictly for educational purposes and follows ethical security practices.
