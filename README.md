<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00FF00&center=true&vCenter=true&width=600&lines=MR-BASTOLA;Security+Engineer;Network+Architect;SOC+%7C+Pentesting+%7C+Forensics" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Offensive-Security-00FF00?style=for-the-badge&logo=kalilinux&logoColor=black" alt="Offensive Security" />
  <img src="https://img.shields.io/badge/Network-Architecture-0055cc?style=for-the-badge&logo=cisco&logoColor=white" alt="Network Architecture" />
  <img src="https://img.shields.io/badge/SOC-Operations-7733bb?style=for-the-badge&logo=datadog&logoColor=white" alt="SOC Operations" />
  <img src="https://img.shields.io/badge/Digital-Forensics-cc2222?style=for-the-badge&logo=autopsy&logoColor=white" alt="Digital Forensics" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://tryhackme.com/p/YOUR_THM"><img src="https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white" alt="TryHackMe" /></a>
  <a href="mailto:your-email@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=Mr-Bastola&label=INTRUSIONS%20DETECTED&color=00ff00&style=flat-square" alt="Visitors" />
</p>

---

## `$ whoami`

Security-focused systems thinker and network architect. I reverse-engineer systems to expose vulnerabilities, analyze deep-packet data streams, and build production-grade monitoring defense architectures. 

Currently bridging the gap between offensive testing and defensive engineering through real-time automation and infrastructure telemetry.

---

## ⚡ Featured Project

### 🛡️ [NetSentinel](https://github.com/Mr-Bastola/NetSentinel) — Enterprise-Grade Network Detection & Response (NDR)
An asynchronous network discovery and observability platform designed to map, monitor, and defend end devices in real time.
* **Engine & Topology:** Utilizes ARP and ICMP Ping routines to dynamically map network layouts, intelligently isolating Access Points from end devices (Servers, Mobile, PCs, Tablets) with a customizable interactive GUI.
* **SIEM & SOC Analytics:** Features a high-fidelity monitoring dashboard that processes live traffic, system services, and user behavior metrics.
* **Deterministic Alerting:** Employs a crisp risk-scoring framework (Low/Med/High) evaluating True/False Positives and Negatives with verbose diagnostic logging for critical states.
* **Adaptive Controls:** Integrated with an inline, user-configurable rule engine for rapid IP/MAC blocking and custom AI-powered chat assistants via API to query event logs natively.

---

## 🕵️ System Briefing

* 🖥️ **Command Center** → Kali Linux · Ubuntu · Windows Server · Debian
* 🔍 **Focus Areas** → Network Observability · Penetration Testing · Digital Forensics · OSINT
* 🧪 **Home Lab** → Proxmox VE · VirtualBox · pfSense Firewall · AWS Sandbox
* 🛡️ **Defense** → SIEM (Wazuh/ELK) · IDS/IPS (Suricata) · Log Auditing · Hardening
* 🎯 **Core Focus** → Traffic Analysis · Threat Detection Engineering · Packet Forensics · Incident Response

---

## ⚙️ Core Competencies

### 🔴 Offensive Security
`Nmap` · `Metasploit` · `Burp Suite` · `SQLmap` · `Gobuster` · `Hydra` · `Hashcat` · `Aircrack-ng` · `Netcat` · `John the Ripper`

### 🔵 Defensive & SOC
`Wazuh SIEM` · `Snort` · `Suricata` · `ELK Stack` · `Splunk` · `UFW` · `iptables` · `Fail2Ban` · `MITRE ATT&CK` · `YARA Rules`

### 📡 Networking & Simulation
`TCP/IP` · `DNS` · `DHCP` · `HTTP/S` · `VLANs` · `NAT/PAT` · `OSPF` · `BGP` · `Wireshark` · `Tcpdump` · `Cisco IOS` · `pfSense`

### 🔍 Forensics & OSINT
`Volatility` · `Autopsy` · `Ghidra` · `CyberChef` · `Binwalk` · `ExifTool` · `Shodan` · `theHarvester` · `Maltego` · `Recon-ng`

---

## 💻 Programming & Scripting

* **Python** → Asynchronous network sockets (`Scapy`, `Requests`), custom security tooling, automation.
* **Bash & PowerShell** → Linux hardening, event log parsing, cron monitoring scripts.
* **JavaScript & C++** → Web UI layouts, asynchronous APIs, underlying structural data logic.

---

## 🏗️ Infrastructure & Environment

| Category | Stack |
|---|---|
| **OS / Virtualization** | Kali Linux · Ubuntu · Debian · Windows Server · Proxmox · VirtualBox |
| **Cloud Infrastructure** | AWS (EC2, S3, IAM) · Azure Fundamentals · Cloudflare WAF |
| **Containers & Config** | Docker · Vagrant · Infrastructure-as-Code principles |
| **Web Infrastructure** | Nginx Reverse Proxy · Apache · Secure RESTful APIs · WebSockets |

---

## 🎓 Academic Foundation — BCSIT

| Core Focus | Applied Systems Translation |
|---|---|
| **Computer Networks** | Routing protocols, stateful packet inspection, switching logic |
| **Operating Systems** | Memory management, kernel architectures, Linux system internals |
| **DBMS** | Relational structures, query optimization, input validation (SQLi mitigation) |
| **DSA** | Algorithmic efficiency, time complexity optimizations, custom parsers |
| **Software Engineering** | Modular architecture design, SDLC management, secure coding standards |

---

## 🧪 Home Lab Architecture

```text
[ ATTACK EDGE ]  --->  Kali Linux | Custom Python Scripts | Exploit Frameworks
       │
       ▼
[ EDGE ROUTER ]  --->  pfSense Firewall (VLAN Segmentation, NAT, ACL Rules)
       │
       ▼
[ MONITOR HUB ]  --->  Wazuh Manager + ELK Stack Telemetry (Syslog ingestion)
       │
       ▼
[ VIRTUAL LAB ]  --->  Proxmox VE + VirtualBox
                        ├── Windows Server 2022 (Active Directory & GPO Lab)
                        ├── Linux Servers (Ubuntu/Debian hardened nodes)
                        └── Targets (DVWA, Metasploitable, VulnHub Boxes)
