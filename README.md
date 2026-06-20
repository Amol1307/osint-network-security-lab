# OSINT Reconnaissance & Network Security Lab

## Overview

This project demonstrates passive reconnaissance, service enumeration, web fingerprinting, packet analysis, and documentation techniques commonly used during cybersecurity assessments.

The assessment was performed against authorized public targets:

* example.com
* owasp.org
* scanme.nmap.org

---

## Objectives

* Perform passive OSINT reconnaissance.
* Enumerate DNS information.
* Analyze HTTP response headers.
* Identify web technologies.
* Discover subdomains using Certificate Transparency logs.
* Enumerate open ports and service versions.
* Capture and analyze network traffic using Wireshark.
* Document findings and recommendations.

---

## Tools Used

* Kali Linux
* whois
* dig
* curl
* WhatWeb
* theHarvester
* Nmap
* Wireshark

---

## Methodology

### Passive Reconnaissance

* WHOIS Enumeration
* DNS Enumeration
* HTTP Header Analysis
* Web Fingerprinting
* Passive OSINT

### Active Enumeration

* Service Version Detection using Nmap

### Packet Analysis

* Wireshark Packet Capture

---

## Findings Summary

### DNS Enumeration

* A Records identified
* MX Records identified
* NS Records identified
* TXT Records identified

### Web Technologies

Target: owasp.org

Technologies discovered:

* Cloudflare
* jQuery 3.7.1
* Google Analytics
* Google Tag Manager

### Passive OSINT

22 subdomains identified using Certificate Transparency logs.

### Network Services

Target: scanme.nmap.org

Open Ports:

* 22/tcp SSH
* 80/tcp HTTP
* 9929/tcp Nping Echo
* 31337/tcp tcpwrapped

### Packet Analysis

Protocols observed:

* ICMP
* TCP
* HTTP

---

## Project Structure

```
osint-network-security-lab
├── findings
├── reports
├── scans
├── screenshots
├── scripts
└── wireshark
```

---

## Skills Demonstrated

* OSINT & Reconnaissance
* DNS Enumeration
* HTTP Header Analysis
* Web Fingerprinting
* Subdomain Enumeration
* Service Enumeration
* Packet Analysis
* Documentation & Report Writing

---

## Future Improvements

* OWASP Top 10 Mapping
* Automated Reconnaissance Scripts
* Vulnerability Assessment
* SIEM Log Analysis
* Additional Packet Analysis

---

## Disclaimer

This project was performed exclusively against authorized and publicly available targets for educational purposes.
