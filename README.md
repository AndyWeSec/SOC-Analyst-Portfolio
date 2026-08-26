# SOC-Analyst-Portfolio
Hands-on cyber security labs, threat investigation, and SOC Analyst training documentation.

<a href="https://www.linkedin.com/in/andy-weafer-02792039a?utm_source=share_via&utm_content=profile&utm_medium=member_ios"><img src="https://img.shields.io/badge/-linkedin-0072b1?&style=for-the-badge&logo=Linkedin&logocolour=white" /></a>

[Brief Introduction]

Welcome to my cybersecurity portfolio. This space demonstrates my practical skills in threat detection, analysis, and incident response, honed through extensive use of TryHackMe simulations and labs. I have hands-on experience leveraging leading SIEM platforms, including Splunk and Elastic, to monitor security events, investigate incidents, and fortify digital defenses. Explore my projects to see how I apply these capabilities to real-world security challenges.

### 🛠️ Core Infrastructure Competencies
* **Network Defense (pfSense):** Built custom firewall sandboxes to understand perimeter security control and rule enforcement.
* **Automation (Python/Bash):** Wrote custom scripts to scale network scanning operations and minimize manual overhead.
* **Telemetry Data (JSON Parsing):** Structured raw, unstructured log data into JSON to simulate how modern enterprise SIEMs ingest and index security events.


## Objective
To secure an entry-level SOC Analyst position where I can leverage my developing skills in threat detection, log analysis, and incident response, gained through TryHackMe’s SOC Level 1 curriculum, to contribute to effective security operations.

## Skills
• SIEM Analysis & Operations: Gained practical experience implementing and utilizing Splunk and Elastic SIEM platforms for log aggregation, security event monitoring, and initial incident triage. My understanding includes constructing basic queries to extract relevant security data.

• Foundational SOC Skills: Actively enhancing my capabilities through TryHackMe’s comprehensive SOC Level 1 course. This training is equipping me with essential skills in alert analysis, threat identification, and understanding standard operating procedures for SOC analysts.

• Cybersecurity Principles: Solid grasp of core cybersecurity concepts, including common threat types, network fundamentals, and the importance of defensive measures.

• Practical Skill Development: Adept at leveraging virtual labs and simulations (e.g., TryHackMe) to reinforce theoretical knowledge and develop practical, hands-on expertise.

## Tools

### 🛡️ Security Operations & Monitoring (SIEM)
* 📊 **Splunk**
* 🪵 **Elastic**

### 🌐 Network Security & Utilities
* 🦈 **Wireshark**
* 🗺️ **Nmap**
* 🧱 **pfSense**

### 💻 Endpoint Detection & Response (EDR)
* 🛡️ **Microsoft Defender**
* 📈 **Wazuh**
* 🔍 **Sysinternals**

### 🔍 Threat Intelligence & Malware Analysis
* 🧪 **VirusTotal**

### ⚙️ Operating Systems & Environments
* 🐉 **Kali Linux**
* 🐧 **Linux**
* 🖥️ **Windows Server**

### 💻 Scripting & Automation
* 🐍 **Python**
* 🐚 **Bash**

### 🎮 Cybersecurity Training & Labs
* 🟥 **TryHackMe**






## Certificates

### Open University - Introduction To Cyber Security
📅 **September 2025**
📜 **Certificate Earned**

Covering core concepts of online safety, threat identification, risk management, and best practices for protecting personal and organizational data.

### SOC Level 1
📅 **March 2026 - July 2026**
📜 **Certificate Earned**

Entry-level course designed to prepare for work as a Security Operations Center Analyst. It focusing on defensive security fundamentals, alert monitoring, and incident response.

Understand SOC structure, workflows, roles, and KPIs. Monitor, triage, and investigate security alerts using SIEM tools like Splunk, Elastic, and Wireshark...



## Projects

## 📁 Featured Cybersecurity Projects

### 🛡️ 1. SOC Analyst Simulator Lab
**Tools Used:** `Splunk` `Elastic` `VirusTotal` `TryHackMe`
* Simulated enterprise security alert triaging within a hands-on Security Operations Center (SOC) environment.
* Analysed simulated alerts including phishing emails, web application attacks, and insider threats to identify Indicators of Compromise (IoCs).
* Investigated malicious attachments and command-and-control (C2) domains using **VirusTotal** threat intelligence to validate true positives.


---

### 🔍 2. Active Directory & Endpoint Detection Lab
**Tools Used:** `Wazuh EDR` `Windows Server` `Kali Linux` `Sysinternals` `Wireshark`
* Built a complete telemetry environment by deploying a Windows Server Active Directory domain controller and workstation alongside a **Wazuh EDR** manager.
* Simulated real-world attack vectors (such as brute force and privilege escalation) from a **Kali Linux** instance to generate realistic log data.
* Analysed endpoint telemetry using **Sysinternals** and parsed malicious network traffic within **Wireshark** to map events against the MITRE ATT&CK framework.


---

### 🧪 3. Network Test Project & Automation Sandbox
**Tools Used:** `Python` `Bash` `Nmap` `pfSense`
* Configured a custom **pfSense firewall** network sandbox to securely test script automation and network scanning utilities.
* Developed custom **Python** and **Bash** scripts to automate baseline **Nmap** network scans and flag unauthorized open ports.
* Parsed raw log outputs into structured JSON format to test ingestion capabilities for downstream monitoring platforms.


### Project 1
## 🎯 Why This Matters to a SOC Analyst (Interview Talking Points)

* **Operational Reality:** Phishing remains the #1 initial access vector for enterprise breaches. As a Tier 1 analyst, a massive percentage of daily ticket volume involves triaging suspicious user-reported emails.
* **Core Competency:** This lab demonstrates my ability to analyze raw email headers, extract sending infrastructure (SPF/DKIM/DMARC alignment), pivot to OSINT tools for domain reputation, and safely detonate malicious attachments or URLs.
* **Interview Application:** When an interviewer asks, *"Walk me through your process for investigating a suspected phishing email,"* I can use this project to explain my structured verification workflow, from header analysis to parsing malicious artifacts without alerting the attacker.

https://github.com/AndyWeSec/SOC-Simulator-Phishing

### Wireshark Investigation
## 🎯 Why This Matters to a SOC Analyst (Interview Talking Points)

* **Operational Reality:** When automated EDR or SIEM alerts are ambiguous, network packet analysis provides the ultimate truth. Analysts must know how to look past a log entry and read raw network traffic during a critical incident.
* **Core Competency:** This project proves my proficiency with Wireshark filters, identifying anomalous TCP/UDP traffic, isolating data exfiltration attempts, and reconstructing malicious network flows (such as detecting C2 beacons or unauthorized data transfers).
* **Interview Application:** When an interviewer asks, *"How do you differentiate a false positive from a true malicious connection when looking at network traffic?"* I can reference this investigation to explain how I filter packet captures to pinpoint command-and-control behavior or protocol anomalies.

https://github.com/AndyWeSec/SOC-Analayst-Wireshark-Investigation

### Project 2 
## 🎯 Why This Matters to a SOC Analyst (Interview Talking Points)

* **Operational Reality:** Phishing remains the #1 initial access vector for enterprise breaches. As a Tier 1 analyst, a massive percentage of daily ticket volume involves triaging suspicious user-reported emails.
* **Core Competency:** This lab demonstrates my ability to analyze raw email headers, extract sending infrastructure (SPF/DKIM/DMARC alignment), pivot to OSINT tools for domain reputation, and safely detonate malicious attachments or URLs.
* **Interview Application:** When an interviewer asks, *"Walk me through your process for investigating a suspected phishing email,"* I can use this project to explain my structured verification workflow, from header analysis to parsing malicious artifacts without alerting the attacker.
https://github.com/AndyWeSec/SOC-Simulator-Phishing-2

### Project 3
## 🎯 Why This Matters to a SOC Analyst (Interview Talking Points)

* **Operational Reality:** Attackers rarely stop at a single action. SOC analysts must be able to stitch together fragmented clues across multiple logs to track a full, multi-stage attack lifecycle.
* **Core Competency:** This "invite-only" scenario simulates a sophisticated corporate threat. Completing it demonstrates my ability to think like an incident responder, map attacker actions directly to the MITRE ATT&CK framework, and establish a clear timeline of events.
* **Interview Application:** When an interviewer asks, *"Tell me about a complex incident scenario you analyzed and how you approached it,"* I can walk them through this project to show how I investigated a realistic threat end-to-end—from initial alert discovery to root cause analysis.

https://github.com/AndyWeSec/SOC-Analyst-Invite-Only-Scenario
