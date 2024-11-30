# Network-Penetration-Test-Report-DEPI
A detailed penetration testing report for network and web applications, covering reconnaissance, exploitation, and mitigation strategies.
## Network Penetration Test Report - DEPI


Network Penetration Test Report - DEPI
Overview

This repository includes a penetration testing report documenting:

    Scope: Network and Web Applications (IP: 192.168.220.135)
    Test Date: 28/09/2024
    Conducted By: by AbdElRhman Mohamed Salah Khalil (Group DEPI ONL1_ISS5_G1E)
    Training Organization: Global Knowledge

Report Contents

The report is organized into the following phases:

    Reconnaissance: Gathering information about the target.
    Weaponization: Discovering additional services via port knocking.
    Delivery: Enumerating directories and hidden services.
    Exploitation: Identifying vulnerabilities and exploiting them.
    Privilege Escalation: Gaining root access and retrieving the flag.

Key Findings

    Misconfigured Port Knocking revealed an HTTP service on port 1337.
    SQL Injection vulnerability in the login form allowed database exfiltration.
    Outdated operating system (Ubuntu 14.04) was vulnerable to privilege escalation.

Recommendations

    Secure port knocking mechanisms and enable logging.
    Use prepared statements to prevent SQL injection.
    Regularly update and patch the system to close known vulnerabilities.

Tools Used

    Netdiscover: IP discovery
    Nmap: Port scanning and service enumeration
    Dirb: Directory enumeration
    CyberChef: Decoding data
    Burp Suite: Intercepting requests
    SQLMap: Exploiting SQL vulnerabilities
    Searchsploit: Privilege escalation exploit
