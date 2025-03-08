# BruteForce-Incident-Response

🛡 Brute-Force Attack Incident Response & Security Audit

Overview

This project simulates a brute-force attack on an SSH service, followed by an in-depth security investigation using Splunk SIEM. The goal is to evaluate system resilience, detect security weaknesses, and implement remediation strategies based on the NIST Cybersecurity Framework.

🔍 Project Objectives

Simulate a brute-force attack on SSH using Hydra.

Investigate security logs with Splunk SIEM to analyse authentication failures.

Apply security improvements, such as firewall rules and SSH hardening.

Develop a structured incident response playbook for security teams.

🛠 Tools & Technologies

- Kali Linux 2024.4 (Attack Simulation)

- Hydra (Brute-force attack tool)

- Nmap (Network scanning & enumeration)

- Splunk SIEM (Security log analysis & visualization)

- Linux SSH Service (Targeted system component)

🚀 Project Workflow

1️⃣ Attack Simulation

 * Used Hydra to execute a brute-force attack on SSH authentication.

 * Monitored real-time logs to detect unauthorized login attempts.

2️⃣ Log Analysis with Splunk

Collected and ingested log data into Splunk SIEM.

 * Filtered logs to identify failed login attempts and security gaps.

 * Created Splunk dashboards to visualize brute-force attack patterns.

3️⃣ Security Enhancements & Remediation

 * Applied firewall rules to restrict SSH access.

 * Implemented failed login attempt rate limiting.

 * Enforced stronger authentication policies and logging improvements.

📊 Key Findings

 * Brute-force attack successfully cracked an SSH password on attempt #500.

 * No real-time alerts were triggered, exposing logging deficiencies.

 * Lack of automated SIEM alerting allowed prolonged unauthorized access attempts.

🔧 How to Use This Repository

Clone the repo:

git clone https://github.com/YasifFarook/BruteForce-Incident-Response.git

Navigate into the directory:

_cd BruteForce-Incident-Response_

Review key files:

_/report/_ - Contains the full cybersecurity report.

_/logs/_ - Raw log files from the attack simulation.

_/scripts/_ - Automation scripts used for log parsing.

_/remediation/_ - Security hardening guides and configurations.

📸 Screenshots & Reports

Log reports are large in size and require separate viewing. Links to complimentary project files (Logs, Splunk Reports and Dashboard): https://drive.google.com/drive/folders/1WXQyBjBruXB3A1d76UP_TCkiIUl61_zE?usp=drive_link

📚 Next Steps

 * Implement automated SIEM detection rules for brute-force attack patterns.

 * Extend the project to include multi-factor authentication (MFA) enforcement.

 * Conduct periodic penetration testing to evaluate evolving security threats.

🔗 Project Report: [(https://drive.google.com/file/d/1uOfQttDGmrKyqD2j7GR5cdKuOYs9pfGa/view?usp=drive_link)]

🔗 Connect with Me: [(https://www.linkedin.com/in/yasif-farook-ab991a22b/)]

Feel free to explore, contribute, or provide feedback!

