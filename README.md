# Detection-Lab

# 🕵️ Detection Lab  

## 🎯 Objective  
The Detection Lab project was built to create a **realistic and controlled environment** for simulating cyberattacks and analyzing their detection within a Security Information and Event Management (SIEM) system.  

The goals were to:  
- Ingest and analyze **logs** from different systems and applications.  
- Generate **test telemetry** that mimics real-world attack techniques.  
- Practice **threat detection, hunting, and incident response**.  
- Strengthen understanding of **network security, adversary behaviors (TTPs), and defense strategies**.  

---

## 🛠️ Lab Setup  

- **Environment:** Virtualized lab (VirtualBox / VMware / Cloud VM)  
- **Endpoints:** Windows 10 + Windows Server (Domain Controller)  
- **SIEM:** Splunk / Elastic Stack / Microsoft Sentinel (choose as per your setup)  
- **Attack Simulation Tools:**  
  - [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) (MITRE ATT&CK simulations)  
  - [Caldera](https://github.com/mitre/caldera) (adversary emulation)  
  - Custom PowerShell/Bash scripts  
- **Log Sources:** Windows Event Logs, Sysmon, Firewall logs, Endpoint Security logs  

---

## 🔍 Detection Focus  

The lab focused on detecting and investigating:  
- **Privilege Escalation** attempts (e.g., Pass-the-Hash, UAC bypass)  
- **Persistence mechanisms** (scheduled tasks, registry modifications)  
- **Credential Access** (Mimikatz activity, LSASS dumps)  
- **Lateral Movement** (SMB, RDP brute force attempts)  
- **Command & Control (C2) traffic** (suspicious PowerShell/HTTP beaconing)  

---

## 📊 Outcomes  

- Successfully generated and ingested attack telemetry into the SIEM.  
- Built custom **detection rules** (queries, dashboards, alerts).  
- Mapped detections to the **MITRE ATT&CK framework**.  
- Improved skills in **log analysis, threat hunting, and SOC workflows**.  
- Created a reusable environment for continuous learning and testing new detections.  

---

## 📁 Repository Structure  


---

## 📌 Next Steps  

- Expand lab with **Linux endpoints** and cloud telemetry.  
- Integrate **SOAR automation** (Shuffle, TheHive).  
- Share detection rules in **Sigma format** for community use.  

---

🔗 **Related Tools & Frameworks:**  
[MITRE ATT&CK](https://attack.mitre.org/) | [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) | [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) | [Caldera](https://github.com/mitre/caldera)  
