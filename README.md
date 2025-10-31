# Threat-Hunting-in-the-Healthcare-Sector-using-MITRE-ATT-CK
Threat hunting framework for the healthcare sector leveraging MITRE ATT&amp;CK techniques to detect, analyze, and mitigate cyber threats targeting patient data, medical devices, and hospital networks. Focused on proactive defense and incident response.
# 🏥 Threat Hunting in the Healthcare Sector using MITRE ATT&CK

A comprehensive framework and guide for conducting **threat hunting operations** within the healthcare sector.  
This repository aligns healthcare cybersecurity practices with the **MITRE ATT&CK framework** to detect, analyze and respond to threats targeting hospitals, clinics and medical IT systems.

---

## 📘 Overview
Healthcare institutions face unique cybersecurity challenges — from protecting patient data and medical devices to ensuring continuous clinical operations.  
This project provides a structured **threat hunting model** to identify, map, and mitigate adversary tactics and techniques using **MITRE ATT&CK for Enterprise and ICS**.

---

## 🎯 Objectives
- Enhance visibility into healthcare-specific threat vectors  
- Map adversary behaviors to MITRE ATT&CK techniques  
- Develop detection rules, analytics, and hunting queries  
- Improve incident response readiness  
- Build a reusable threat hunting playbook  

---

## 🧩 MITRE ATT&CK Mapping
| Tactic | Technique ID | Technique Name | Healthcare Use Case |
|--------|---------------|----------------|----------------------|
| Initial Access | T1190 | Exploit Public-Facing Application | Compromising hospital portals |
| Execution | T1059 | Command and Scripting Interpreter | Malicious scripts on lab systems |
| Persistence | T1547 | Boot or Logon Autostart Execution | Implanting backdoors in medical PCs |
| Exfiltration | T1041 | Exfiltration over C2 Channel | Stealing patient records |


---

## 🔍 Sample Hunting Areas
- Unusual data transfer from Electronic Health Record (EHR) servers  
- Suspicious PowerShell or WMI commands on hospital workstations  
- Unapproved access to radiology or pharmacy systems  
- Ransomware pre-encryption indicators  

---

## ⚙️ Tools and Technologies
- **SIEM:** Splunk / ELK Stack / Microsoft Sentinel  
- **EDR:** CrowdStrike / Defender for Endpoint  
- **Threat Intel:** MISP, VirusTotal  
- **MITRE ATT&CK Navigator** for visualization  

---

