# Open Source Audit: MySQL

**Name:** Muskan  
**Roll Number:** 24BAI10927  
**Course:** Open Source Software (OSS)  
**Choice:** MySQL

## Project Overview

This project is an Open Source Audit of MySQL. It explores the origin, licensing model, Linux integration, and ecosystem of MySQL. The project also includes practical implementation through Linux shell scripts.

## Objectives

- Understand open-source philosophy and ethics
- Analyze MySQL's GPL licensing model
- Study MySQL's role in Linux systems
- Perform system-level tasks using shell scripting

## Shell Scripts

### Script 1: System Identity Report (system_identity.sh)

**Purpose:**  
Displays important system information like kernel version, logged-in user, uptime, OS distribution, and current date/time.

**Concepts Used:**
- Variables
- Command substitution ($( ))
- echo for output formatting

**How it works:**  
The script collects system data using commands like `uname`, `whoami`, and `uptime`, stores them in variables, and prints a formatted report.

**How to run:**
chmod +x system_identity.sh
./system_identity.sh

Script 2: FOSS Package Inspector (package_inspector.sh)
Purpose:
Checks whether MySQL is installed, displays its version, license, and description.

Concepts Used:
if-then-else
case statement
Package checking (rpm or dpkg)
grep

How it works:
The script verifies if MySQL exists in the system. If installed, it extracts version and license info. It also prints a short description using a case statement.

How to run:
chmod +x package_inspector.sh
./package_inspector.sh

Script 3: Disk and Permission Auditor (disk_auditor.sh)
Purpose:
Analyzes system directories and displays their size, permissions, and ownership.

Concepts Used:
for loop
du, ls -ld
awk, cut

How it works:
Loops through important directories (/etc, /home, etc.), checks if they exist, and prints their storage usage and permissions.

How to run:
chmod +x disk_auditor.sh
./disk_auditor.sh

Script 4: Log File Analyzer (log_analyzer.sh)
Purpose:
Reads a log file and counts occurrences of a keyword (like “error”).

Concepts Used:
while read loop
if condition
Command-line arguments ($1, $2)
Counter variable

How it works:
The script reads each line of a log file and checks for a keyword. It counts matches and prints total occurrences.

How to run:
chmod +x log_analyzer.sh
./log_analyzer.sh /var/log/syslog error

Script 5: Open Source Manifesto Generator (manifesto_generator.sh)
Purpose:
Generates a personalized open-source philosophy statement based on user input.

Concepts Used:
read for input
String concatenation
File writing (>, >>)
date command

How it works:
Takes user input (tool, freedom meaning, idea), generates a paragraph, and saves it in a .txt file.

How to run:
chmod +x manifesto_generator.sh
./manifesto_generator.sh

Requirements:
Linux OS (Ubuntu/Fedora)
Bash shell
MySQL installed
Terminal access

Project Components:
✔️ 5 Shell Scripts
✔️ Project Report (PDF)
✔️ README Documentation

Conclusion:
This project provided a deep understanding of open-source software through MySQL and improved practical knowledge of Linux and shell scripting.

Note
This project is created for academic purposes as part of OSS Capstone Project.
