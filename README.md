# 🔍 Level 1 SOC Analyst Lab

## 📌 Project Description

This project uses the TryHackMe Junior Security Analyst Intro lab to demonstrate a basic Security Operations Centre (SOC) investigation.

Investigating SIEM alarms, spotting malicious behaviour, analysing indicators of compromise (IoCs), and following to the SOC escalation 


--- 

# 🚨 Overview of the Event

Suspicious authentication activity involving an external IP address trying to access the company's SSH service was discovered by a SIEM warning.

The following malicious IP address was found during the investigation:

**The malicious IP address is:** 221.181.185.159

Unauthorised SSH connection attempts and suspicious login behaviour were connected to the activity. 

---

# 🧪 Investigation Procedure 

## 1. Analysis of SIEM Alerts

Examined the security alarms that the SIEM platform produced.

Determined:

- Untrustworthy SSH authentication activity
- Several tries to establish a connection with port 22
- A malicious attempt at authentication that was successful

---

## 2. Threat Intelligence Analysis

The IP scanner tool was used to investigate the suspicious IP address.

Results:

| Indicator | Details | 
|---|---| 
| IP Address | 221.181.185.159 | 
| Threat Type | Malicious activity | 
| Confidence Score | 100% malicious | 
| Service Targeted | SSH (Port 22) |



---

# 🛠️ Utilised Tools

- The SOC Analyst Lab at TryHackMe
- The SIEM Platform
- IP Reputation scanner
- ScannerLogs of Security Events

---

# 🔎 Key Findings

- Suspicious SSH activity was found
- A malicious external IP address was found
- Verified indicator of compromise (IoC)
- The event was escalated in accordance with SOC protocols

---

# ✅ Response Actions 

Suggested SOC response:

- Block the firewall's malicious IP address
- Keep an eye out for additional compromises on the impacted systems
- Examine the logs of SSH authentication
- Examine potential account compromise
- Implement more robust access controls

---

# 📚 Exhibited Skills

- Investigation of SIEM alerts
- Log analysis
- Intelligence about threats
- Identification of the Indicator of Compromise (IoC)
- The procedure for escalating incidentsWorkflow for SOC analysts

---

# 📸 Evidence

### Task Completion
![Task 1](task_1.png)
![Task 2](task_2.png)
![Task 3](task_3.png)
![Task 4](task_4.png)

### SOC Dashboard
![Dashboard](Soc-analyst-dashboard.png)

