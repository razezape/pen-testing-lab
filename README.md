
# Computer Network Security – Lab Environment Project </h1>

This educational basic report will introduce; Kali as the attack machine and SaturnaN & R as victim/monitoring machines. A virtual LAN (VLAN) is designed with these VMs to closely replicate the target network, which will be divided into two stages: 

1) Penetration Testing
2) Defense Strategies

<p align="center">
  <a href="https://www.kali.org/" target="_blank">
    <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux">
  </a>
  <a href="https://ubuntu.com/" target="_blank">
    <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu">
  </a>
  <a href="https://www.snort.org/" target="_blank">
    <img src="https://img.shields.io/badge/Snort-E5002B?style=for-the-badge&logoColor=white" alt="Snort">
  </a>
  <a href="https://www.netfilter.org/projects/iptables/" target="_blank">
    <img src="https://img.shields.io/badge/iptables-F59E0B?style=for-the-badge&logo=linux&logoColor=white" alt="iptables">
  </a>
</p>

This secure lab includes **3 VMs:**
- Kali Linux attacker machine
- SaturnaN vulnerable target
- SaturnaR IDS monitoring machine

---

Licencia

Copyright © 2026 Razezape. All Rights Reserved.

Este documento y su contenido se comparten con fines educativos. Queda prohibida su reproducción, distribución o modificación, total o parcial, sin autorización previa y por escrito del autor.

---

# 🧠 Topics Covered
- Performed a cybersecurity assessment on a simulated company network.
- Conducted network scanning and service enumeration.
- Analyzed vulnerabilities and tested system security.
- Practiced password auditing and secure remote access.
- Used Metasploit for controlled exploitation testing.
- Monitored and analyzed network traffic with Wireshark.
- Configured Snort IDS/IPS for intrusion detection and prevention detection.
- Implemented IPTables firewall rules for attack mitigation.
- Developed security recommendations and documented findings.

# 🌐 Network Topology

| Machine | Role | IP Address |
|----------|------|-------------|
| Kali Linux | Attacker | 172.X.X.11 |
| SaturnaN | Vulnerable Target | 172.X.X.13 |
| SaturnaR | IDS Sensor | 172.X.X.14 |

# 🔎 Reconnaissance & Enumeration

Initial reconnaissance was performed using:

```bash
sudo ifconfig - :)
```
