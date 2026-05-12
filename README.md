<p align="center">
  <h1>Computer Network Security – Lab Environment Project 🔐</h1>
</p>

This project was developed for inside a controlled virtual lab environment and have two parts: 

1) Penetration Testing
2) Defense Strategies

The lab included 3 VMs:
- Kali Linux attacker machine
- SaturnaN vulnerable target
- SaturnaR IDS monitoring machine

# 🧠 Topics Covered
- Performed a cybersecurity assessment on a simulated company network.
- Conducted network scanning and service enumeration.
- Analyzed vulnerabilities and tested system security.
- Practiced password auditing and secure remote access.
- Used Metasploit for controlled exploitation testing.
- Monitored and analyzed network traffic with Wireshark.
- Configured Snort IDS for intrusion detection.
- Implemented IPTables firewall rules for attack mitigation.
- Developed security recommendations and documented findings.

---

# 🛠️ Tools Used

| Tool | Purpose |
|------|----------|
| Nmap | Host discovery & service enumeration |
| Nessus | Vulnerability scanning |
| Hydra | SSH password cracking |
| Medusa | Parallel authentication attacks |
| Ncrack | Network authentication cracking |
| Metasploit | Auxiliary SMTP testing |
| Wireshark | Packet capture & analysis |
| Snort | Intrusion Detection System |
| SSH / SCP | Remote access & secure file transfer |

---

# 🌐 Network Topology

| Machine | Role | IP Address |
|----------|------|-------------|
| Kali Linux | Attacker | 172.16.0.11 |
| SaturnaN | Vulnerable Target | 172.16.0.13 |
| SaturnaR | IDS Sensor | 172.16.0.14 |

---

# 🔎 Reconnaissance & Enumeration

Initial reconnaissance was performed using:

```bash
sudo ifconfig
