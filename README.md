# 🔐 Black Box Penetration Test on DVWA

This repository documents a **black-box penetration test** performed on **Damn Vulnerable Web Application (DVWA 1.0.7)** as part of the MSc in Cybersecurity program.  
The project demonstrates professional penetration testing skills, from reconnaissance to exploitation and remediation.

---

## 🎯 Project Overview
- **Target System:** DVWA 1.0.7 (VirtualBox)
- **Attacker Machine:** Kali Linux
- **Testing Type:** Black-box Penetration Test
- **Scope:** Identify, exploit, and recommend fixes for vulnerabilities

---

## 🛠️ Tools Used
- **Nmap** – Network scanning & enumeration  
- **Gobuster** – Directory brute-forcing  
- **Hydra** – Brute-force attacks on services  
- **John the Ripper** – Password cracking  
- **Netcat** – Reverse shell  
- **Python (pty.spawn)** – Interactive TTY upgrade  
- **HashID** – Identify hash algorithms  

---

## 🔎 Methodology
1. **Reconnaissance & Scanning** – Host discovery, open ports, service enumeration  
2. **Exploitation** – Attacking vulnerable services and web apps  
3. **Privilege Escalation** – Gaining root via sudo misconfiguration  
4. **Post-Exploitation** – Recommendations for securing the system  

---

## ⚡ Key Exploits
- [**CVE-2018-12613** – Unauthorized access to phpMyAdmin](exploits/phpmyadmin_exploit.md)  
- [**CVE-2013-0156** – Command Injection → Reverse shell](exploits/command_injection.md)  
- [**CVE-2019-14287** – Privilege Escalation via sudo misconfig](exploits/sudo_misconfig.md)  

---

## 📄 Report
The full detailed penetration testing report is available here:  
👉 [View Report (PDF)](report/DVWA_PenTest_Report.pdf)

---

## 🧑‍💻 Author
**Kaung Si Thu** – MSc in Cybersecurity | BSc in Computer Networks  
Skilled in network infrastructure, information security, and penetration testing techniques.
