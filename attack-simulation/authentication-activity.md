# Authentication Activity (Simulated)

## Description
SSH-based authentication activity was simulated in a controlled lab environment to observe how endpoint and SIEM monitoring tools detect suspicious login behavior.

## Lab Setup
- Ubuntu Linux configured as a monitored endpoint
- SSH service enabled on the endpoint
- Endpoint connected to Wazuh Manager using Wazuh Agent

## Simulated Activity
- Multiple SSH authentication attempts were generated
- Both successful and failed login events were recorded
- Activity was limited strictly to the lab environment

## Detection & Logging
- SSH authentication logs were collected from `/var/log/auth.log`
- Wazuh agent forwarded events to the Wazuh Manager
- Security alerts related to authentication failures were generated

## Analysis
- Alerts were reviewed in the Wazuh dashboard
- Event frequency and timestamps were correlated
- Rule IDs and severity levels were examined

## SOC Insight
Repeated SSH authentication failures may indicate credential-based attacks and are a common SOC monitoring use case.
