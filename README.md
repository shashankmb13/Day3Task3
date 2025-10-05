# Day3Task3
Title: Basic Vulnerability Scan on Local PC — Internship Task Report

🧾 Title: Basic Vulnerability Scan on Local PC (OpenVAS)
📘 Description

This project demonstrates how to perform a basic vulnerability scan on a local computer using OpenVAS (Greenbone Community Edition) or Nessus Essentials.
It provides an introductory experience in identifying common vulnerabilities, analyzing system security posture, and applying simple remediations.

⚙️ Objective

To identify potential vulnerabilities and configuration weaknesses on a local system and understand how to mitigate them using free vulnerability scanning tools.

🧰 Tools Used

OpenVAS (Greenbone Vulnerability Manager)

Nessus Essentials

Windows or Linux system (localhost or local IP)

🧪 Steps Performed

Installed and configured the chosen vulnerability scanner.

Updated vulnerability feeds/plugins.

Set the target as localhost or the system’s local IP.

Ran a Full and Fast vulnerability scan.

Exported and analyzed the results.

Identified and documented high and medium severity issues.

Suggested practical remediation steps.

📊 Key Findings (Example Summary)
Severity	Count	Example Issues
High	2	SMBv1 enabled, Missing Windows Patch
Medium	3	Weak TLS ciphers, Default Credentials, Open RDP Port
🔐 Sample Vulnerabilities

SMBv1 Protocol Enabled: Disable SMBv1 and enable SMBv2/3.

Missing System Patches: Apply latest Windows or Linux security updates.

Weak TLS Protocols: Restrict to TLS 1.2 or higher.

Open RDP Port: Restrict RDP access through firewall or VPN.

🧾 Deliverables

Vulnerability scan report (PDF/HTML export)

Summary document with methodology and findings

Raw scan data (CSV/JSON)

Top vulnerability remediation summary

🧠 Learning Outcomes

Understanding of vulnerability scanning methodology.

Familiarity with OpenVAS and Nessus interfaces.

Awareness of system-level risks and patch management.

Practical knowledge of basic remediation techniques.

🛡️ Disclaimer

All scans were conducted on a personal or authorized test system for educational purposes only.
Unauthorized scanning of external networks is not permitted.
