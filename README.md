# oss_audit_24bai10927
Name: Muskan
Roll Number: 24BAI10927
Course: Open Source Software (OSS)

Choice: MySQL

Project Overview:
This project is an Open Source Audit of MySQL. It explores the origin, licensing model, Linux integration, and ecosystem of MySQL. The project also includes practical implementation through Linux shell scripts.

Objectives:
1. Understand open-source philosophy and ethics.
2. Analyze MySQL’s GPL licensing model.
3. Study MySQL’s role in Linux systems.
4. Perform system-level tasks using shell scripting.

Shell Scripts:
Script 1: System Identity Report (system_identity.sh)
Purpose:
Displays important system information like kernel version, logged-in user, uptime, OS distribution, and current date/time.

Concepts Used:
Variables
Command substitution ($( ))
echo for output formatting

How it works:
The script collects system data using commands like uname, whoami, and uptime, stores them in variables, and prints a formatted report.

How to run:
chmod +x system_identity.sh
./system_identity.sh

