# 🐧 The Open Source Audit — Linux Kernel

**Course:** Open Source Software (OSS NGMC)  
**Student Name:** Priyanka Satapathy  
**Registration Number:** 24BSA10123  
**Software Chosen:** Linux Kernel  
**Category:** Operating System  
**License:** GNU General Public License v2 (GPLv2)

---

## 📘 Project Overview
This repository contains the files and scripts submitted as part of the capstone project **“The Open Source Audit”**. The project explores the **Linux Kernel**—the foundation of modern open-source computing—through a comprehensive written report and five hands-on shell scripts that demonstrate core OSS principles like automation, transparency, and community-driven development.

## 📂 Repository Structure

| File / Folder | Description |
| :--- | :--- |
| `Script1_System_Identity.sh` | Displays system information and OS license details. |
| `Script2_FOSS_Package_Inspector.sh` | Checks software installation, version, and description. |
| `Script3_Disk_Permission_Auditor.sh` | Reports space usage and permissions of key directories. |
| `Script4_Log_File_Analyzer.sh` | Scans log files for specific keywords like ERROR/WARNING. |
| `Script5_Open_Source_Manifesto_Gen.sh` | Creates a personalized open-source philosophy statement. |
| `OSSCapstoneProject_Report.pdf` | The full audit report (12–16 pages). |
| `README.md` | This document (overview, usage, and setup). |

---

## 💻 Setup & Requirements

### Prerequisites
To run these scripts, you need a Linux distribution (Ubuntu, Fedora, Debian, etc.) with:
* **Bash Shell**
* **Coreutils** (standard on most distros)
* **Sudo access** (required for directory audits and package checks)

### Installation
Clone this repository to your local machine:
```bash
git clone [https://github.com/YOUR_GITHUB_USERNAME/oss-audit-24bsa10123.git](https://github.com/YOUR_GITHUB_USERNAME/oss-audit-24bsa10123.git)
cd oss-audit-24bsa10123
chmod +x *.sh
1️⃣ System Identity Report Displays the distribution name, kernel version, and uptime.
bash Script1_System_Identity.sh
2️⃣ FOSS Package Inspector Checks if a specific package is installed and provides FOSS details.
bash Script2_FOSS_Package_Inspector.sh
3️⃣ Disk & Permission Auditor Audits key system directories to report usage and ownership.
bash Script3_Disk_Permission_Auditor.sh
4️⃣ Log File Analyzer Analyzes system logs for specific error patterns.
bash Script4_Log_File_Analyzer.sh /var/log/syslog error
5️⃣ Open Source Manifesto Generator Generates a custom .txt file based on user input regarding OSS values.
bash Script5_Open_Source_Manifesto_Generator.sh
