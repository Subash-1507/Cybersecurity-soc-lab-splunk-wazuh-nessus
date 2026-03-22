# SOC Security Lab | SIEM | IDS | Vulnerability Assessment | Splunk | Wazuh | Nessus

## Overview

This repository demonstrates a comprehensive Security Operations Center (SOC) lab integrating multiple security tools for real-time monitoring, attack detection, and vulnerability assessment.

The lab simulates real-world cyberattacks including DNS Spoofing, ARP Poisoning, Brute Force, and Denial of Service (DoS), and analyzes them using SIEM and IDS tools.

---

## Documentation

* /docs/Integration of Snort IDS with Wazuh SIEM for Real-Time Intrusion.pdf
* /docs/TenableNessus.pdf
* /docs/Splunk_Practical.pdf

---

## Core Skills Demonstrated

* Security Operations Center (SOC) Monitoring
* SIEM Log Analysis (Splunk, Wazuh)
* Intrusion Detection Systems (Snort IDS)
* Vulnerability Assessment (Tenable Nessus)
* Threat Detection & Incident Analysis
* Network Security Attacks & Defense
* Log Correlation & Event Monitoring

---

## Lab Architecture

Attacker (Kali Linux) → Victim (Ubuntu) → SIEM (Splunk / Wazuh) → Dashboard Monitoring

---

## Technical Implementation

### 🔐 IDS Integration (Snort + Wazuh)

* Installed and configured Snort 3 on Kali Linux
* Created custom detection rules for ICMP and HTTP traffic
* Configured Snort logging in JSON format
* Integrated Snort logs with Wazuh agent
* Visualized alerts in Wazuh Dashboard

✔ Successfully detected network activities such as ICMP ping and HTTP requests 

---

### 📊 SIEM Implementation (Splunk)

* Configured Splunk Enterprise for centralized log monitoring
* Integrated logs from attacker and victim machines
* Analyzed logs for attack detection and correlation

#### Attacks Simulated:

* ARP Spoofing (MITM Attack)
* DNS Spoofing (Fake Website Redirection)
* Brute Force SSH Authentication
* ICMP Flood DoS Attack

✔ All attacks were successfully captured and analyzed using Splunk queries and dashboards 

---

### 🛡️ Vulnerability Assessment (Nessus)

* Performed Host Discovery Scan
* Conducted Basic Network Scan
* Executed Advanced Dynamic Scan
* Performed Web Application Vulnerability Scan

✔ Identified open ports, services, and multiple vulnerabilities with severity classification 

---

## Key Achievements

* Built a complete SOC lab environment
* Detected and analyzed multiple real-world attack scenarios
* Integrated IDS logs into SIEM platform
* Performed vulnerability assessment using Nessus
* Created detection rules and attack correlation queries
* Simulated enterprise-level security monitoring workflow

---

## Tools & Technologies

Splunk | Wazuh | Snort IDS | Tenable Nessus | Kali Linux | Ubuntu | Apache | Networking

---

## Learning Outcomes

* Hands-on experience in SIEM and IDS integration
* Practical understanding of cyberattack techniques
* Log analysis and threat detection skills
* SOC workflow and incident response basics
* Vulnerability scanning and risk assessment

---

## Purpose

This project demonstrates real-world SOC operations including attack detection, monitoring, and vulnerability assessment, aligning with industry practices in cybersecurity and blue team operations.

---

## Note

This repository focuses on practical implementation of security monitoring and attack detection in a controlled lab environment.

---

*“Detect. Analyze. Defend.”*
