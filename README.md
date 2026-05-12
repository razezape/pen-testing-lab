<p align="center">
  <h1>Computer Network Security – Lab Environment Project </h1>
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
