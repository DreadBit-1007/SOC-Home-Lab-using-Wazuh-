# VMware Setup

VMware Workstation was used as the hypervisor to host all virtual machines in this SOC home lab.

## Configuration
- Installed VMware Workstation on the host system
- Created separate virtual machines for each role:
  - Kali Linux (Attacker)
  - Ubuntu Linux (Victim)
  - Wazuh (SOC / SIEM)

## Networking
- Configured all VMs to use an isolated internal network
- Ensured VMs can communicate with each other while remaining isolated from external networks

## Purpose
Using a virtualized environment allows safe simulation of attacker activity and SOC analysis without impacting real-world systems.

