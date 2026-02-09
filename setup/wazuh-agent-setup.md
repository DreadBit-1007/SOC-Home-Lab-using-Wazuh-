# Wazuh Agent Setup

The Wazuh Agent is installed on monitored endpoints to collect system and security logs.

## Installation
Agent was installed on the Ubuntu endpoint using the official package repository.

```bash
sudo apt update
sudo apt install wazuh-agent -y

Service Configuration

sudo systemctl enable wazuh-agent
sudo systemctl start wazuh-agent
