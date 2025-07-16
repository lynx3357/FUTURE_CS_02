# FUTURE_CS_02
introduction to the core activities of a Security Operations Center (SOC).
# Security Incident Analysis & Response Report — SOC Internship Task 2

## About the Task

This project was completed as part of a Security Operations Center (SOC) internship. It provides a beginner-friendly, hands-on introduction to the core duties of a SOC analyst.

The goal was to monitor simulated security alerts using a SIEM tool, identify potential threats, and simulate a proper incident response — just like a real-world SOC team working 24/7 to defend an organization from cyberattacks.

## What Was Done

- Set up and explored **Splunk Enterprise** (Free Trial) for log ingestion and security alert analysis  
- Analyzed sample logs from multiple sources, including malware alerts and authentication failures  
- Identified and classified suspicious activities, such as:
  - Rootkit, Trojan, Worm, Spyware, and Ransomware detections  
  - Unauthorized connection attempts  
  - Failed logins  
  - Suspicious file access activity  
- Drafted a detailed **Security Incident Response Report** documenting findings, impact, timeline, and remediation steps  
- Practiced reporting threats in a clear, structured format for non-technical stakeholders

## Report Overview

- **Tool Used:** Splunk Enterprise  
- **Date of Activity:** July 3, 2025  
- **Time Range Analyzed:** 04:18 – 09:11 hrs  
- **Users Involved:** alice, bob, charlie, david, eve  
- **Total Critical Alerts:** 7  
- **Malware Types Detected:** Rootkit, Trojan, Spyware, Worm, Ransomware  
- **Sample Event:**  
  - `04:19:14` — Rootkit detection on alice’s system (IP: 198.51.100.42)  
  - `09:10:14` — Ransomware alert and suspicious file access by bob  

> See the full `Security_Incident_Report.pdf` file in the repository for all details, including the timeline of events and response recommendations.

## Skills Gained

- Log analysis and SIEM dashboard interpretation  
- Threat identification and classification  
- Incident prioritization and escalation  
- Real-world report writing using industry language  
- Communication of technical findings to business stakeholders

##  Tools Used

- **Splunk Enterprise** – For searching, filtering, and analyzing logs  
- **Google Docs / MS Word** – For drafting the incident report  
- **Sample Log File:** `SOC_Task2_Sample_Logs.html` – Simulated logs containing:  
  - Malware alerts  
  - Network connections  
  - Authentication attempts  
  - File access events

##  Repository Contents

```bash
.
├── README.md                   # This file
├── SOC_Task2_Sample_Logs.html # Provided sample log data
├── Security_Incident_Report.pdf # Final report with findings and recommendations
└── Screenshots/               
