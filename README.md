Monitoring & Security Lab: Ubuntu and Windows
Overview

This project documents a hands-on monitoring and security lab performed using both Ubuntu Linux and Microsoft Windows.
The objective of this lab was to learn how operating systems monitor performance, detect suspicious activity, and protect files from malware such as ransomware.

The work includes screenshots, explanations, and analysis showing how system tools reveal what is happening “behind the scenes”.

Lab Objectives

Monitor system performance and activity

Review logs and security tools

Detect suspicious or abnormal behavior

Understand ransomware behavior and defenses

Compare baseline activity versus ransomware activity

Ubuntu Section

Tools and concepts explored:

top and htop process monitoring

journalctl log analysis

Disk and memory usage

Service management (systemctl)

Antivirus and intrusion detection (ClamAV + Fail2ban)

File permissions and access control

Windows Section

Monitoring and ransomware simulation topics covered:

Task Manager performance monitoring

PowerShell process monitoring

System services and auditing logs

SafeSim ransomware simulation

Baseline vs post-encryption file comparison

Log analysis and incident response concepts

What This Lab Demonstrates

✔ How system tools reveal hidden activity
✔ Why logging and monitoring are critical
✔ How ransomware changes files and system behavior
✔ The importance of having baseline data before infection
✔ Real security investigation techniques used in the field

Files Included

📄 report/ – Full lab report (Word document with screenshots)
🖼 screenshots/ – Individual screenshots from the lab
📄 README.md – Project summary

Future Work

This lab can be extended by:

Collecting logs with Splunk or ELK

Adding real-world malware samples (safe research environment)

Automating monitoring with scripts

Expanding to cloud and container monitoring

Author

Miguel Guadalupe
Graduate Cybersecurity Student

How to View the Report

Click the report folder and open:

Combined_Monitoring_and_Security_Lab_Report.docx
