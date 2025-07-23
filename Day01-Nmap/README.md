#  Day 1: Nmap Port Scanning

This folder contains the Day 1 project for the cybersecurity journey — focused on Nmap scanning and analysis.

---

##  Tools Used:
- Nmap
- Python3 HTTP Server
- Kali Linux 

---

##  Commands Used:

### LAN Scanning
- `ip a`
- `nmap -sn 192.168.1.0/24`
- `python3 -m http.server 8080`
- `nmap -sV -p 8080 127.0.0.1`

### Internet Scanning
- `nmap scanme.nmap.org`
- `nmap -sV scanme.nmap.org`
- `nmap -sV -p 22,80 scanme.nmap.org`
- `nmap -sV -Pn --max-retries 2 scanme.nmap.org`

---

##  Notes:
- Faced SYN stealth delays and filtered responses while scanning internet targets.
- Used `-Pn` and limited retries to handle network restrictions.

---
