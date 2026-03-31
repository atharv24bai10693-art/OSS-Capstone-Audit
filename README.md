Open Source Software Audit: Git (Version Control System)

This repository contains a technical audit and automated shell scripts developed for the Capstone Project at VIT Bhopal University. The project explores the origin, licensing, and Linux integration of Git, the world's most popular open-source version control system.

👤 Developer Information
Name: ATHARV SAINI
Registration Number: 24BAI10693
Institution: VIT Bhopal University

Project Overview

Audit Subject: Git
Environment: Ubuntu 24.04 (WSL)
License: GNU GPL v2
Tools Used: Bash, Git, Dpkg, Grep, Awk
Repository Contents

This repository includes 5 automated shell scripts designed to audit the Linux environment and the Git package:

script1.sh (System Identity): Generates a report of the host system's kernel, uptime, and user identity.
script2.sh (FOSS Inspector): Verifies the installation of Git using dpkg and provides philosophical context.
script3.sh (Disk & Permission Auditor): Analyzes directory sizes and file permissions for Git binaries.
script4.sh (Log Analyzer): Simulates log parsing to identify system errors and warnings.
script5.sh (Manifesto Generator): An interactive script that generates a personalized Open Source Manifesto.
How to Run

To run these scripts on an Ubuntu/Debian system, follow these steps:

Clone the Repository:

Grant Execution Permissions: chmod +x *.sh
Execute a script: ./script1.sh
