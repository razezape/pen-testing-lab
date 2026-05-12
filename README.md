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

The objective was to:
- perform reconnaissance and vulnerability scanning,
- identify weaknesses,
- execute password attacks,
- analyze captured network traffic,
- and configure intrusion detection with Snort.

---

# 🧠 Topics Covered

- Network Scanning
- Service Enumeration
- Vulnerability Analysis
- Password Cracking
- SSH Access
- Secure File Transfer
- Metasploit Auxiliary Modules
- Wireshark Packet Analysis
- Snort IDS Configuration
- SMTP Traffic Monitoring

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
