# MITRE ATT&CK Mapping

This document maps observed activities in the SOC home lab to relevant MITRE ATT&CK techniques to understand attacker behavior from a defensive perspective.

## Purpose
MITRE ATT&CK provides a structured framework to categorize adversary tactics and techniques.  
This mapping helps SOC analysts identify attacker intent and improve detection and response.

---

## Observed Activity: Network Reconnaissance

### MITRE Tactic
- **Reconnaissance**

### MITRE Technique
- **T1046 – Network Service Discovery**

### Observation
Basic network scanning activity generated network and system logs on the Ubuntu endpoint.

### Detection
- Alerts and logs were captured by the Wazuh agent
- Events were visible in the Wazuh dashboard

### SOC Insight
Reconnaissance activity often precedes exploitation attempts and is an early indicator of potential intrusion.

---

## Observed Activity: Authentication Events

### MITRE Tactic
- **Credential Access**

### MITRE Technique
- **T1110 – Brute Force (Simulated)**

### Observation
Authentication-related events were observed in system logs during controlled lab activity.

### Detection
- Authentication logs were collected by Wazuh
- Alerts were generated based on rule conditions

### SOC Insight
Monitoring authentication failures helps identify suspicious access attempts early.

---

## Observed Activity: Web Application Interaction

### MITRE Tactic
- **Initial Access**

### MITRE Technique
- **T1190 – Exploit Public-Facing Application (Simulated)**

### Observation
Web interaction activity generated application and access logs.

### Detection
- Logs were indexed by Wazuh
- Events were reviewed via the dashboard

### SOC Insight
Web application monitoring is critical for detecting unauthorized access attempts.

---

## Key Takeaways
- MITRE ATT&CK helps structure alert analysis
- Mapping improves understanding of attacker behavior
- Early-stage detection enables faster response
- Framework supports SOC decision-making

> All activities were conducted in a controlled lab environment for educational purposes.
