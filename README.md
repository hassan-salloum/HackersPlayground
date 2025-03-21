# **HackersPlayground**

Welcome to **HackersPlayground**—a curated repository of cybersecurity resources, tools, and checklists designed for penetration testing, ethical hacking, and red teaming. This collection includes scripts, documentation, and techniques essential for exploit development, security assessments, and advanced attack simulations.

## 📌 **Contents**

### 🔍 **Reconnaissance & Enumeration**
- **Active Directory Enumeration** (Forest, Domain, Domain Controller, Organizational Units, Groups)

### 🎯 **Advanced Exploitation Techniques**
- **InvokeReflectiveNcat.pdf** – Reflective injection of NCAT for stealthy bind shells.
- **Obfuscated_Invoke-Mimikatz.pdf** – Evasion techniques for Mimikatz execution.
- **Triggerable_Outlook_Malware.pdf** – Exploiting Outlook for malware delivery.

### 🔐 **Security Checklists & Cheat Sheets**
- **Linux Server Security Checklist.xlsx** – Hardening best practices.
- **Pentest-CheatSheet.xlsx** – Quick reference for penetration testing.

### ⚔️ **Pentesting & Hacking Resources**
- **Amazing-Pentest-Toolkit.xlsx** – A collection of essential pentesting tools.
- **DOS Types and Tools.xlsx** – Denial-of-Service (DoS) attack methodologies.
- **HOW TO BUILD YOUR OWN MAIL SERVER.pdf** – Step-by-step guide for setting up a secure mail server on Ubuntu.

### 🎓 **Exam & Study Guides**
- **eCPPTv2_Exam_Review-2021.pdf** – Study materials for eCPPT certification.

## ⚠️ **Disclaimer**
This repository is strictly for educational and research purposes. The author is not responsible for any misuse. Ensure compliance with local laws and ethical guidelines before utilizing any of the provided materials.

## 📢 **Contributing**
Have valuable resources or tools to share? Feel free to fork this repository and submit a pull request!

---

## 📝 **Additional Notes**

### **Building a Secure Mail Server**
The guide on setting up a mail server using **RainLoop Webmail** covers:
- Required components:
  - **SMTP Server** → Postfix
  - **IMAP Server** → Dovecot
  - **Web Server** → Nginx
  - **Web Mail Interface** → RainLoop
- Security Enhancements:
  - SPF & DKIM configuration with Postfix
  - Enabling HTTPS on Nginx
  - Redirecting HTTP to HTTPS
  - Implementing **WAF** (Web Application Firewall) using ModSecurity for Nginx

### **InvokeReflective-Ncat**
- A stealth technique for injecting **NCAT** into target memory to establish a bind shell.
- **Evasion strategies**:
  - Bypassing antivirus by removing comments and obfuscating function names.
  - Evading IDS via XOR-based payload obfuscation.

🚀 **Happy Hacking!** 🔥
