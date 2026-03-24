### Open Source Audit Project – MySQL
Student Details:
Name: Muskan
Roll Number: 24BAI10927
Course: Open Source Software (OSS)

Project Overview:
This project is an Open Source Audit of MySQL. It analyzes its origin, licensing (GPL), Linux integration, and ecosystem. The project also includes 5 shell scripts demonstrating practical Linux and open-source concepts.

Objectives:
Understand open-source philosophy
Analyze MySQL’s licensing model
Explore MySQL in a Linux environment
Implement shell scripting concepts

Shell Scripts:
1. System Identity Report (system_identity.sh)
Description:
This script displays essential system information such as kernel version, logged-in user, system uptime, OS distribution, and current date/time.

Concepts Used:
Variables, command substitution ($( )), echo formatting

Execution Steps:
chmod +x system_identity.sh
./system_identity.sh

2. FOSS Package Inspector (package_inspector.sh)
Description:
This script checks whether MySQL is installed on the system. If installed, it displays version, license, and summary details. It also prints a short description using a case statement.

Concepts Used:
if-else, case statement, package commands (rpm/dpkg), grep

Execution Steps:
chmod +x package_inspector.sh
./package_inspector.sh

3. Disk and Permission Auditor (disk_auditor.sh)
Description:
This script analyzes important system directories and reports their disk usage, permissions, and ownership details.

Concepts Used:
for loop, du (disk usage) ,ls -ld (permissions & ownership), awk, cut

Execution Steps:
chmod +x disk_auditor.sh
./disk_auditor.sh

4. Log File Analyzer (log_analyzer.sh)
Description:
This script reads a log file line by line and counts how many times a specific keyword (such as "error") appears. It helps in analyzing system logs.

Concepts Used:
while read loop, if condition, Command-line arguments ($1, $2), Counter variables

Execution Steps:
chmod +x log_analyzer.sh
./log_analyzer.sh /var/log/syslog error

5. Open Source Manifesto Generator (manifesto_generator.sh)
Description:
This script takes user input and generates a personalized open-source philosophy statement. The output is saved into a .txt file.

Concepts Used: 
read for user input, String concatenation, File handling (>, >>), date command

Execution Steps:
chmod +x manifesto_generator.sh
./manifesto_generator.sh

Requirements:
1. Linux Operating System (Ubuntu/Fedora)
2. Bash Shell
3. MySQL installed
4. Basic terminal knowledge

How to Run the Project:
1. Clone the repository:
git clone <your-repo-link>
cd <repo-folder>
2. Give execution permission to scripts:
chmod +x *.sh
3. Run any script:
./script_name.sh

Project Components:
✔️ 5 Shell Scripts (.sh files)
✔️ Project Report (PDF)
✔️ README Documentation

Conclusion:
This project provides a deeper understanding of open-source software through MySQL. It also enhances practical knowledge of Linux commands and shell scripting, demonstrating how open-source tools are used in real-world systems.

Note:
This repository is created for academic purposes as part of the OSS Capstone Project.
   
