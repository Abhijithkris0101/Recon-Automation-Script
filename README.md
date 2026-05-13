# Recon Automation Script

## Description

This is a Python-based reconnaissance automation tool designed for basic cybersecurity and network enumeration tasks.

The script performs:
- Domain resolution
- Port scanning using Nmap
- Common subdomain enumeration
- Automatic report generation

It helps automate the initial reconnaissance phase of penetration testing and bug bounty workflows.

---

## Features

- Resolves target domain to IP address
- Runs Nmap service/version detection scan (`-sV`)
- Enumerates common subdomains
- Generates a detailed recon report
- Saves results into a `.txt` file
- Simple command-line interface

---

## Technologies Used

- Python 3
- Socket module
- Subprocess module
- Nmap

---

## Requirements

Before running the script, install the following:

### 1. Python 3
Download Python from:

https://www.python.org/downloads/

### 2. Nmap
Download Nmap from:

https://nmap.org/download.html

Make sure Nmap is added to your system PATH.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Abhijithkris0101/Recon-Automation-Script.git

---

## Usage

After starting the script, enter a target domain when prompted.

Example:

```bash

python recon.py
Enter target domain (example.com): google.com

==== Basic Recon Automation Script ====

[+] Domain resolved: google.com --> 142.250.183.14

[+] Running Nmap scan on 142.250.183.14...

[+] Enumerating common subdomains...

[FOUND] www.google.com --> 142.250.183.196

[+] Report saved as: google.com_recon_report.txt

google.com_recon_report.txt
