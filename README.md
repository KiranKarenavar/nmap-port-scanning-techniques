# 🔐 Nmap Port Scanning Techniques – Cybersecurity Lab

## 📌 Overview
This repository documents a hands-on **Nmap Port Scanning Techniques** lab performed in a **controlled and isolated home lab environment**.  
The purpose of this project is to understand how different port scanning techniques work, how systems and firewalls respond, and how scan activity appears at the packet level using Wireshark.

This project is focused on **learning reconnaissance techniques from a defensive (Blue Team / SOC) perspective**.

---

## 🧪 Scan Techniques Covered
The following Nmap scanning techniques were performed and analyzed:

- SYN Scan (-sS)  
- TCP Connect Scan (-sT)  
- ACK Scan (-sA)  
- FIN Scan (-sF)  
- NULL Scan (-sN)  
- XMAS Scan (-sX)  
- UDP Scan (-sU)  
- Protocol Scan (-sO)  
- Ping Scan (-sn)  
- ICMP Ping (-PI)  
- SYN Ping (-PS)  
- TCP Ping (-PT)  
- Normal Output (-oN)  
- XML Output (-oX)

---

## 🔍 Analysis Performed
For each scan technique, the following was analyzed:

- Identification of **open, closed, and filtered ports**  
- Host and firewall response behavior  
- TCP flags and packet characteristics  
- Differences between stealth and full-connection scans  
- Packet-level visibility using Wireshark  

Wireshark captures were used to observe how scanning activity appears on the network, helping build **SOC-level detection awareness**.

---

## 🛠 Tools & Technologies
- **Nmap**  
- **Wireshark**  
- **Kali Linux**  
- **VMware (Isolated Lab Environment)**  

---

## 📄 Documentation
This repository includes a **professional PDF report** containing:
- Scan commands (sanitized)  
- Screenshots of terminal output  
- Wireshark packet captures  
- Explanation of each scan technique  
- Summary tables and conclusions  

All IP addresses and MAC addresses have been **masked** to follow cybersecurity best practices.

---

## 🎯 Skills Demonstrated
- Network reconnaissance analysis  
- Packet capture and filtering  
- TCP / UDP / ICMP protocol understanding  
- Port state interpretation  
- Cybersecurity documentation and reporting  
- Blue Team / SOC fundamentals  

---

## ⚠️ Disclaimer
All scanning activities were conducted **strictly within a private, isolated home lab** using owned devices.  
This project is intended **only for educational and defensive learning purposes**.

---

## 👤 Author
**Kiran Karenavar**

Aspiring Cybersecurity Analyst | Blue Team | SOC | Ethical Hacking
