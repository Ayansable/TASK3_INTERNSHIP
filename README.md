# TASK3_INTERNSHIP
Perform a Basic Vulnerability Scan of my  PC
# 🔍 Nmap Vulnerability Scan – Localhost (Windows)

This project documents a full vulnerability assessment of the local Windows machine using *Nmap* and its vuln script engine. The scan helps identify open ports, running services, and known vulnerabilities.

-## 📌 Objectives

- Install and configure Nmap on Windows
- Perform a full TCP scan with version detection
- Use Nmap's vulnerability scripts (--script vuln)
- Review vulnerabilities and research fixes
- Document findings and recommendations---

## 🛠 Tools Used

| Tool      | Version  | Description                      |
|-----------|----------|----------------------------------|
| Nmap      | 7.94     | Network scanner and vulnerability detection tool |
| Windows 10/11 | N/A | Target operating system |
| Npcap     | Latest   | Packet capture driver (required by Nmap) |

-## 🖥 Target System

- *IP Address:* *** (localhost)
- *OS:* Windows 10 Pro
- *Services running:* Apache, OpenSSH, HTTPS (OpenSSL)

## 🔍 Scan Command
nmap -sS -sV -T4 -Pn --script vuln 127.0.0.1 -oN vuln_scan.txt
