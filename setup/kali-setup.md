# Kali Linux Setup

Kali Linux is used as the attacker simulation machine in this SOC home lab to understand how attacker activity generates logs and alerts.

## Installation
- Kali Linux was installed as a virtual machine on VMware Workstation
- Default desktop environment was used
- VM configured with appropriate CPU, RAM, and disk resources

## System Preparation
After installation, the system was updated to ensure all packages were current.

```bash
sudo apt update && sudo apt upgrade -y
