# Wazuh Alert Analysis

This document summarizes sample security alerts generated in the SOC home lab and how they were analyzed.

## Alert Source
- Monitored endpoint: Ubuntu Linux
- SIEM: Wazuh

## Example Alert: Suspicious Authentication Activity

### Description
Wazuh generated an alert related to authentication activity on the Ubuntu endpoint.

### Analysis
- Reviewed alert details in the Wazuh dashboard
- Examined associated authentication logs
- Identified the event as suspicious but limited to the lab environment

### Investigation Steps
- Checked source IP address
- Correlated event timing with simulated activity
- Verified no persistence or privilege escalation occurred

### Outcome
- Alert successfully detected
- No further action required due to controlled environment

## SOC Takeaway
This exercise helped understand how authentication-related events are detected and investigated by SOC analysts.
