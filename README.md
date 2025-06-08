# THFD-SHNML
<b>Threat Hunting Framework Development: Securing Hybrid Networks using Machine Learning</b>
<h2>Description: </h2>
This project includes three VMs: <br><br>

<img src="https://img.shields.io/badge/Ubuntu-orange?style=flat-square&logo=ubuntu"/><br>
<img src="https://img.shields.io/badge/Kali_Linux-blue?style=flat-square&logo=kalilinux"/><br>
<img src="https://img.shields.io/badge/Windows-red?style=flat-square&logo=windows&logoColor=white"/><br>

- Kali Linux is the attacking VM
- Windows VM is the Victim
- Ubuntu VM holds the Splunk SIEM and Machine Learning ToolKit

<h2>Project Summary:</h2>
This project focused on developing a Threat Hunting Framework to secure hybrid networks using machine learning and open-source tools. Within a virtual lab environment consisting of Ubuntu, Kali Linux, and Windows VMs, you simulated a real-world reverse TCP PowerShell attack using Metasploit. Splunk Enterprise, installed on Ubuntu, collected logs from the victim and attacker machines using Universal Forwarders. I also integrated threat intelligence from AlienVault OTX and built a Machine Learning Toolkit (MLTK) model in Splunk to detect anomalies, specifically identifying traffic on port 4444 as malicious. Alerts were configured to notify on suspicious activity, and a bash script was used to stop the attack. The project demonstrated end-to-end threat detection, logging, alerting, and basic mitigation, providing practical experience in cybersecurity operations. Key qualities of a Cybersecurity or SOC Analyst demonstrated in this project include strong analytical skills, familiarity with SIEM tools like Splunk, the ability to detect and respond to threats, and knowledge of scripting and automation for defense and incident response.
