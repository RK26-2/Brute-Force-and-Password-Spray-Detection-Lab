# Brute-Force-and-Password-Spray-Detection-Lab
**Brute‑Force & Password Spray Detection Lab (Microsoft Sentinel):**
This repository contains my end‑to‑end detection engineering lab focused on identifying and investigating Brute‑Force and Password Spray attacks using Microsoft Sentinel. The project demonstrates real SOC workflows including log ingestion, analytics rule creation, MITRE mapping, workbook visualisation, automation, and incident investigation.

🔍 **Lab Overview:**
This lab covers:

- Brute‑force attack detection using Windows Security Events (4625/4624)

- Password spray detection using Azure AD Sign‑in Logs

- Custom analytics rules in Microsoft Sentinel

- MITRE ATT&CK mapping (T1110.001 & T1110.003)

- Identity visibility using Sentinel workbooks

- Automation rules for incident tagging

- Conceptual SOAR playbook design

- Full SOC‑style investigation and reporting

## 📁 Repository Structure

📦 **BruteForce-and-Password-Spray-Lab:**
 - ┣ 📄 👉 snapshots: [Few-snapsots](Few-snapshots/)
 
 - ┣ 📄 👉 Full Report: [BruteForce-Lab-Report.pdf](BruteForce-Lab-Report.pdf)
 
 - ┣ 📁  README.md
 
 ┗ 📄 .gitignore

📄 **Full Report:**
The complete SOC investigation report is available here:

👉 Full Report: [BruteForce-Lab-Report.pdf](BruteForce-Lab-Report.pdf)


*This includes:*

- Attack simulation steps

- KQL queries

- Analytics rule configuration

- MITRE mapping

- Investigation findings

- Automation

- Workbooks

- Appendix with evidence

🖼 **Evidence Screenshots:**
Some screenshots referenced in the report are stored in:

👉 snapshots: [Few-snapsots](Few-snapshots/)


🧠 **MITRE ATT&CK Mapping:**
- T1110.001 — Password Guessing (Brute‑Force)

- T1110.003 — Password Spraying

- TA0006 — Credential Access

⚙️ **Analytics Rules Implemented**
- Multiple Failed RDP Logons (Brute‑Force)

- Multiple Failed Sign‑ins Across Accounts (Password Spray)

- Both rules were tested and validated using simulated attacks.

📊 **Workbooks Used:**
- Identity & Access Workbook — Windows Security Events

- Microsoft Entra ID Audit Logs Workbook — Azure AD identity activity

- These dashboards were used to visualise authentication patterns and confirm log ingestion.

🤖 **Automation:**
- Automation Rule: Automatically tags brute‑force incidents

- Playbook Concept: Watchlist‑based IP blocking (documented but not deployed due to subscription limits)

🧪 **Skills Demonstrated:**
*Detection engineering*

- KQL investigation

- MITRE ATT&CK mapping

- Identity log analysis

- Sentinel automation

- SOC incident workflow

- Professional report writing

**What I Learned:**
Through this lab, I strengthened my detection engineering and SOC investigation skills using Microsoft Sentinel. I learned how to ingest Windows Security Events and Azure AD sign‑in logs, build custom analytics rules for brute‑force and password spray attacks, and validate detections using KQL. I also gained experience using Sentinel workbooks for identity visibility, applying automation rules to classify incidents, and exploring SOAR concepts through playbook design. Overall, this project improved my confidence in analysing authentication attacks, mapping detections to MITRE ATT&CK, and documenting a full SOC investigation workflow.
