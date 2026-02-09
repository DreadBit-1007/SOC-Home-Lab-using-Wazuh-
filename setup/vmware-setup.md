# VMware Workstation Setup

VMware Workstation was used as the virtualization platform to build an isolated SOC home lab environment.

## Installation
VMware Workstation was downloaded and installed from the official VMware website using default installation options.

## Virtual Machine Configuration
Each virtual machine was configured with:
- 2 vCPUs
- 4 GB RAM (minimum)
- 40 GB disk space
(Adjusted based on host system capacity)

## Networking Configuration
- All virtual machines were connected using an isolated internal network
- Network isolation ensures safe testing and prevents exposure to external systems
- Enables controlled communication between attacker, victim, and SOC machines

## Virtual Machines Created
- Kali Linux – attacker simulation
- Ubuntu Linux – monitored endpoint
- Wazuh – SOC and SIEM platform

## Purpose
Using VMware allows rapid creation, isolation, and snapshotting of virtual machines, which is essential for security testing and SOC analysis.
