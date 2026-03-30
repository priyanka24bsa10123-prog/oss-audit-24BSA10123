# The Open Source Audit: Capstone Project

## Student Details
* **Name:** Priyanka Satapathy
* **Registration Number:** 24BSA10123
* **Course:** Open Source Software (OSS NGMC Course)

## Software Audit Details
* **Software:** Linux Kernel
* **Category:** Operating System
* **License:** GPL v2

## Project Overview
This repository contains the deliverables for "The Open Source Audit" capstone project. It includes a comprehensive analytical project report (PDF format) and a set of five Bash shell scripts that demonstrate practical Linux command-line skills and an understanding of open-source automation.

---

## Shell Scripts Description

The following five scripts interact with the Linux system to audit the environment, verify installations, and analyze logs:

1. **Script 1: System Identity Report (`script1_system_identity.sh`)**
   Acts as a welcome screen that introduces the system. It displays the Linux distribution name, kernel version, current logged-in user, system uptime, and a message stating the open-source license covering the OS.

2. **Script 2: FOSS Package Inspector (`script2_package_inspector.sh`)**
   Checks whether the chosen software (Linux Kernel/`linux-image`) is installed on the system, retrieves its version details, and prints a short description of its purpose based on the package name.

3. **Script 3: Disk and Permission Auditor (`script3_disk_auditor.sh`)**
   Loops through a list of important system directories (such as `/etc`, `/var/log`, `/home`) to report the space each uses, as well as the owner and permissions of the directories.

4. **Script 4: Log File Analyzer (`script4_log_analyzer.sh`)**
   Reads a specified log file (e.g., `/var/log/syslog` or `/var/log/messages`) line by line, counts how many lines contain a specific keyword (like "ERROR" or "WARNING"), and prints a summary.

5. **Script 5: Open Source Manifesto Generator (`script5_manifesto_generator.sh`)**
   An interactive script that asks the user three questions about their open-source philosophy, composes a short personalized paragraph, and saves it to a `.txt` file.

---

## Dependencies / Prerequisites

To run these scripts, you will need:
* A working Linux environment (Ubuntu, Debian, Fedora, CentOS, or a Virtual Machine).
* **Bash Shell**: The default command interpreter on most Linux distributions.
* **Standard Linux Utilities**: The scripts utilize common built-in tools such as `uname`, `whoami`, `uptime`, `rpm` or `dpkg`, `grep`, `awk`, `df`, `ls`, and `cat`.
* **Permissions**: Script 3 and Script 4 might require `sudo` privileges depending on the directories and log files being audited (e.g., reading `/var/log/messages`).

---

## Step-by-Step Instructions to Run the Scripts

**Step 1: Clone the repository**

Open your Linux terminal and clone this project repository:

```bash
git clone <your-github-repo-url>
cd <repository-folder>
Step 2: Make the scripts executable

Before running the scripts, you must grant them execution permissions:

Bash
chmod +x script1_system_identity.sh
chmod +x script2_package_inspector.sh
chmod +x script3_disk_auditor.sh
chmod +x script4_log_analyzer.sh
chmod +x script5_manifesto_generator.sh
Step 3: Execute the scripts

Run each script directly from the terminal.

Run Script 1:

Bash
./script1_system_identity.sh
Run Script 2:

Bash
./script2_package_inspector.sh
Run Script 3:

(Note: You may need to use sudo if checking restricted system directories).

Bash
./script3_disk_auditor.sh
Run Script 4:

(Note: This script requires command-line arguments: the path to the log file and an optional keyword).

Bash
./script4_log_analyzer.sh /var/log/syslog "error"
Run Script 5:

Follow the interactive on-screen prompts to generate your manifesto text file:

Bash
./script5_manifesto_generator.sh
