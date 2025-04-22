# 🛡️ Cybersecurity Internship Project

This repository contains tasks completed during my cybersecurity internship. The goal was to get hands-on with foundational tools and techniques used in real-world cyber defense, ranging from Linux command mastery to network analysis and phishing detection.

---

## 🔧 1. Linux Command Practice

Practiced essential **Linux commands** from basic file operations to more advanced system monitoring and networking tools.

### ✅ Topics Covered
- File & Directory Management (`ls`, `cd`, `cp`, `mv`, `rm`)
- User & Permissions (`chmod`, `chown`, `whoami`, `sudo`)
- Process & System Info (`top`, `ps`, `kill`, `htop`)
- Networking Commands (`ifconfig`, `ping`, `netstat`, `nmap`, `curl`)
- Package Management & Git (`apt`, `git clone`)

📄 _See the `Linux_Commands.docx` for the full command list + explanations._

---

## 🌐 2. Wireshark Sniffing Task

Used **Wireshark** to capture and analyze HTTP traffic from a vulnerable web app:  
🔗 `http://testphp.vulnweb.com`

### ✅ What I Did
- Started Wireshark and filtered for `http.request.method == "POST"`
- Captured a login attempt
- Extracted sensitive data like usernames and passwords from packet contents

📸 Screenshots and full report included in `Wireshark_Attack_Report.docx`

---

## 📧 3. Email Phishing Analysis

Analyzed a real-looking **phishing email** pretending to be from PayPal.

### ✅ Skills Applied
- Spotted red flags like:
  - Fake sender email (`@marine-patrimoine.fr`)
  - Scare tactics ("Your account has been limited!")
  - Suspicious links
- Wrote a clean report with prevention tips

📄 Full report available in `Email_Analysis_Report.docx`

---

## 🚀 Tools Used
- Kali Linux  
- Wireshark  
- GitHub  
- Microsoft Word / LibreOffice  
- [testphp.vulnweb.com](http://testphp.vulnweb.com) (legal practice site)

---

## 🧠 What I Learned
- Stronger command over Linux and terminal tools  
- Practical packet analysis & data sniffing  
- Email phishing structure and detection  
- Report writing for technical tasks  

---

> 🔐 This project was completed as part of my hands-on cybersecurity internship. Every task was designed to simulate real-world scenarios and build a strong foundation in infosec.