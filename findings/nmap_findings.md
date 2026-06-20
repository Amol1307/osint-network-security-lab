# Nmap Service Enumeration Findings

## Target

scanme.nmap.org

## Tool Used

Nmap 7.99

## Scan Type

Service Version Detection (-sV)

## Open Ports Discovered

### Port 22/tcp

Service: SSH

Version:
OpenSSH 6.6.1p1 Ubuntu 2ubuntu2.13

Risk Level:
Low

---

### Port 80/tcp

Service: HTTP

Version:
Apache httpd 2.4.7

Risk Level:
Low

---

### Port 9929/tcp

Service:
Nping Echo

Risk Level:
Informational

---

### Port 31337/tcp

Service:
tcpwrapped

Risk Level:
Informational

---

## Host Information

Operating System:
Linux

Host Status:
Up

## Notes

The target exposed four open TCP ports. SSH and HTTP services were identified successfully. Service version enumeration provided useful information that could assist vulnerability assessment activities.
