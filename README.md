# Incident-Response-Threat-Analysis-

# Incident Response & SOC operations 

This repository showcases my **hands-on experience in Incident Response (IR), Security Operations Center (SOC) tasks, and malware analysis**. The portfolio demonstrates real-world exercises, including website defacement, perimeter breaches, and malware incident handling.

---

## 📄 Portfolio Overview

- **Course Focus:** End-to-end Incident Response lifecycle — from detection and triage to containment, eradication, and recovery.
- **Skills Developed:**  
  - SIEM & Log Analysis (Splunk)  
  - IDS & Firewall Investigation (FortiGate)  
  - Malware Analysis & Response  
  - Threat Hunting & IOC Collection  

---

## 🛠 Modules & Hands-On Exercises

1. **Module 1 – Incident vs Event vs Alert**
   - Understand SOC workflow and event triaging.
   - Skills: Executable Denylisting, File Removal.
   - 
   - ![1](https://github.com/user-attachments/assets/2981d22f-f183-49ef-9ccb-803b93d875cb)

![2](https://github.com/user-attachments/assets/08e59237-6784-4cb8-af69-8ed3364eddbc)


2. **Module 2 – Website Defacement Attacks**
   - Investigated attacks using Splunk and FortiGate IDS.
   - Skills: Connection Attempt Analysis, Remote Terminal Session Detection, File Access Pattern Analysis, Scheduled Job Analysis, Software Inventory, Operational Risk Assessment, System Vulnerability Assessment.

![4](https://github.com/user-attachments/assets/e7fd4bde-8bf6-4de2-8d00-435dad5a856b)


3. **Module 3 – Perimeter Compromise Exercise**
   - Investigated perimeter breaches, gathered IOCs, analyzed attack chain.
   - Skills: Client-server Payload Profiling, Process Spawn Analysis, Resource Access Pattern Analysis, Application Configuration Hardening.

![before](https://github.com/user-attachments/assets/25daa360-4292-4b71-8c83-e0d0bc3f83f5)

![AFTER](https://github.com/user-attachments/assets/f50a391e-853a-4627-97cf-ae53f230b8cc)



4. **Module 4 – Perimeter Compromise Challenge**
   - Conducted perimeter breach investigation and reporting.
   - Skills: Client-server Payload Profiling, Process Spawn Analysis, Resource Acc![Malware](https://github.com/user-attachments/assets/67e66de2-21ad-482c-b91f-b7c42da0e366)
ess Pattern Analysis, Scheduled Job Analysis.
  
   - ![3](https://github.com/user-attachments/assets/6d3dd461-73b5-41be-8abf-d267fdfb8b66)


5. **Module 5 – Malware Incident Handling Walkthrough**
   - Triage, investigation, and response to Defender alerts.
   - Skills: File Hashing.
  
   - 

6. **Module 6 – Malware Incident Response Exercise**
   - Investigated malware alerts and applied mitigation actions.
   - Skills: File Hashing, Operating System Monitoring, Account Locking, Process Termination, File Removal.
  
   - ![RANSOM](https://github.com/user-attachments/assets/979992c0-9180-4535-bdda-bbeec02a4d53)


7. **Module 7 – Malware Incident Response Challenge**
   - Applied skills to handle a full security incident.
   - Skills: File Hashing, Operating System Monitoring.

![suspiscious email](https://github.com/user-attachments/assets/307ea824-3005-4691-9eb4-b84a9c2f0bbc)

---

## 🔍 Case Study – Advanced Threat Investigation

- **Initial Attack Vector:** Phishing campaign delivering malicious Excel document (`A873564.xls`).  
- **Malware:** Trojan:O97M/Sadoca.C!ml & Ransom:Win32/WannaCrypt (`windows_update_tool.exe`).  
- **Lateral Movement:** PsExec exploitation targeting domain controller (`dc1.commensurate.tech`) under `www-data` user context.  
- **Persistence Mechanism:** Scheduled Task `Check for Updates` running `KB5011644.bin` every 5 minutes.  
- **Affected Systems:** `windows06.commensurate.tech`, `windows07.commensurate.tech`, `windows08.commensurate.tech`.  
- **Containment Actions:** Defender quarantined malicious files, email rule created to block `techforyou123.com` domain, network isolation of compromised endpoints.  
- **Key IOCs:** Malicious domain: `techforyou123.com`, Download URLs: `http://x1762z-ccl98b.ru/msupdate/KB5011644.bin`, File hashes from Sysmon logs, Scheduled Task: `Check for Updates`.

---

## 📊 Tools & Technologies

- Splunk (SIEM)  
- FortiGate IDS  
- Windows Defender  
- NGINX & Sysmon logs  
- PsExec  

---

## 📌 Key Takeaways

- Practical experience with **full IR lifecycle**: detection → triage → investigation → containment → recovery.  
- Hands-on skills in **SOC operations**, malware analysis, and proactive threat mitigation.  
- Familiarity with real-world attack chains and IOC collection.  

---

## 📎 Portfolio PDF

Download the complete **Incident Response Portfolio** (professional report with modules, case studies, IOCs, and skills overview):

[Incident_Response_Portfolio.pdf](./Incident_Response_Portfolio.pdf)

---

## 🎯 Career Goal

Leverage hands-on SOC and IR expertise to contribute as a **Security Analyst or Security Engineer**, enhancing organizational cybersecurity posture.
