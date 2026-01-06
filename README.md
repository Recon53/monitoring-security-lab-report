<p align="center">
  
![Status](https://img.shields.io/badge/Status-Completed-green)
![Platform](https://img.shields.io/badge/Platforms-Ubuntu%20%7C%20Windows-blue)
![Category](https://img.shields.io/badge/Focus-Monitoring%20%26%20Security-orange)
![Ransomware Lab](https://img.shields.io/badge/Lab-Ransomware%20Simulation-red)

</p>

<p align="center">
  <img src="banner.png" alt="Monitoring & Security Lab: Ubuntu and Windows">
</p>

![License](https://img.shields.io/github/license/Recon53/monitoring-security-lab)

A hands-on lab demonstrating how to detect ransomware behavior using system logs, monitoring tools, and real incident workflows.

## Features

- Monitors system performance on Ubuntu & Windows
- Detects suspicious and abnormal processes
- Reviews security logs and event history
- Compares baseline vs ransomware-modified files
- Includes screenshots, explanations, and results
- Demonstrates real ransomware detection workflow

## Table of Contents

- [Overview](#monitoring--security-lab-ubuntu-and-windows)
- [Features](#features)
- [Screenshots](#screenshots)
- [How to Use This Project](#how-to-use-this-project)
- [Future Work / Next Steps](#-future-work--next-steps)
- [Why This Project Matters](#-why-this-project-matters)
- [Author](#author)
- [License](#license)

---

# Monitoring & Security Lab: Ubuntu and Windows
<p align="center">
  <img src="https://img.icons8.com/color/96/linux.png"/>
  <img src="https://img.icons8.com/color/96/windows-10.png"/>
  <img src="https://img.icons8.com/color/96/shield.png"/>
</p>

## Overview
This project documents a hands-on monitoring and security lab performed using both **Ubuntu Linux** and **Microsoft Windows**.

The objective of this lab was to learn how operating systems:

- Monitor performance and activity  
- Detect suspicious behavior  
- Protect files from malware such as ransomware  

The work includes screenshots, explanations, and analysis showing how system tools reveal what is happening “behind the scenes”.

---

## Key Features

   Real system monitoring on Ubuntu and Windows  
   Detection of suspicious processes and ransomware behavior  
   Comparison of baseline vs. infected file hashes  
   Use of security tools (Sysmon, ClamAV, Fail2ban, journalctl, Task Manager)  
   Full report with screenshots, analysis, and conclusions  
   Demonstrates real-world SOC investigation workflow

---

## How to Use This Project

This repository is meant for learning and academic research.

- Open the `/report` folder to read the full lab document.
- Open the `/screenshots` folder to view images and evidence.
- Use the README as a quick overview of what the lab covers.

The labs demonstrate how monitoring tools help detect suspicious behavior and ransomware activity.

---

## Results Overview

Throughout this lab, monitoring tools helped identify:
- Suspicious process activity in PowerShell
- Ransomware-like behavior changing multiple file hashes
- Differences between baseline and post-encryption file states

- ---

## Screenshots Preview

<p align="center">
  
**Ubuntu Monitoring**
  
<img src="screenshots/Figure%2001%20—%20top.PNG" width="600"/>

### Windows Monitoring

<img src="screenshots/Figure%2010%20%E2%80%94%20topWindows_TaskManager.PNG" width="650">

### Ransomware Hash Comparison

<img src="screenshots/Figure%2016%E2%80%94%20Hash%20comparison%20(baseline%20vs%20after).PNG" width="650">
</p>

---

## Lab Objectives
- Monitor system performance and activity  
- Review logs and security tools  
- Detect suspicious or abnormal behavior  
- Understand ransomware behavior and defenses  
- Compare baseline activity versus ransomware activity  

---

## Ubuntu Section — Tools Used
- `top` and `htop` process monitoring  
- `journalctl` log analysis  
- Disk and memory usage  
- Service management (`systemctl`)  
- Antivirus and intrusion protection (ClamAV + Fail2ban)  
- File permissions and access control  

---

## Windows Section — Topics Covered
- Task Manager performance monitoring  
- PowerShell process monitoring  
- Viewing Windows services  
- SafeSim ransomware simulation  
- Baseline vs post-encryption comparison  
- Log analysis and incident response concepts  

---

## Repository Contents
| Folder/File | Description |
|------------|------------|
| **report/** | Full lab report (Word document with screenshots) |
| **screenshots/** | Screenshots captured during the lab |
| **README.md** | Project overview |

---

## What This Lab Demonstrates
✔ How monitoring tools reveal hidden system activity  
✔ Why logs are critical in cybersecurity  
✔ How ransomware alters files and system behavior  
✔ The importance of collecting **baseline data**  
✔ Real-world investigation techniques used by analysts  

---

## Future Improvements
- Add log collection using Splunk or ELK
- Automate monitoring with scripts
- Expand to cloud environments
- Experiment with additional malware research (safe lab setup)

---

## Author
**Miguel Guadalupe**  
Graduate Cybersecurity Student

---

### How to View the Full Report
Open the file located in:

---

## Built With

- Ubuntu 22.04
- Windows 10
- Sysmon
- PowerShell
- Bash
- ClamAV
- Fail2ban
- VirtualBox

---

## Future Work / Next Steps

These are ideas planned for future versions of this lab:

🔹 Add SIEM integration (Splunk / Elastic)  
🔹 Automate log collection with PowerShell / Bash scripts  
🔹 Add alerts when suspicious hashes are detected  
🔹 Expand lab to include cloud monitoring (Azure / AWS)  
🔹 Build a defensive playbook for incident response

---

## Results Summary

During this lab, monitoring tools provided visibility into several key behaviors:

- ✔ Identified suspicious processes running in the background
- ✔ Observed PowerShell executing unusual commands
- ✔ Detected changes to multiple files in a short period of time
- ✔ Compared baseline file hashes vs ransomware-modified hashes
- ✔ Confirmed ransomware-like behavior without harming the real system

These results demonstrate how logs, process monitors, and hash comparisons help detect ransomware activity early — before major damage occurs.

---

## Why This Project Matters

This project shows how everyday system tools can reveal ransomware behavior,
suspicious processes, and unusual file activity.  
It helps students, analysts, and defenders understand what’s happening
“behind the scenes” when malware runs — and how to spot the signs early.

---

## License

This project is licensed under the MIT License.  
See the **LICENSE** file for details.

---

### Author & Credits

**Author:** Miguel Guadalupe  
**Program:** FIU Cybersecurity  
**Focus:** Monitoring, Ransomware Research, System Defense  
**Year:** 2026




