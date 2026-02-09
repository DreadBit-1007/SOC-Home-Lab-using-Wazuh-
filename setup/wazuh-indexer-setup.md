# Wazuh Indexer Setup

The Wazuh Indexer is responsible for storing and indexing security event data.

## Installation Overview
- Installed on the Wazuh VM following official Wazuh documentation
- Configured as a single-node indexer for lab purposes

## Service Management
```bash
sudo systemctl enable wazuh-indexer
sudo systemctl start wazuh-indexer
