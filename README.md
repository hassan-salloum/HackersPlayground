# HackersPlayground 
Welcome to **HackersPlayground**, a collection of cybersecurity resources, tools, and checklists for penetration testing and ethical hacking. This repository contains various files and scripts useful for red teaming, exploit development, and security assessments.

## 📌 Contents

- **Reconnaissance & Enumeration**
  - AD Enumeration (Forest, Domain, DC, OU, Group)
- **Advanced Exploitation Techniques**
  - InvokeReflectiveNcat.pdf
  - Obfuscated_Invoke-Mimikatz.pdf
  - triggerable_outlook_malware.pdf
- **Security Checklists & Cheat Sheets**
  - Linux Server Security Checklist.xlsx
  - Pentest-CheatSheet.xlsx
- **Pentesting & Hacking Resources**
  - Amazing-Pentest-Toolkit.xlsx
  - DOS Types and Tools.xlsx
  - HOW TO BUILD YOUR OWN MAIL SERVER.pdf
- **Exam & Study Guides**
  - eCPPTv2_Exam_Review-2021.pdf

 ## ⚠️ Disclaimer

This repository is meant for **educational purposes only**. The author is not responsible for any misuse of the content. Ensure you comply with local laws and regulations before using any of the provided materials.

## 📢 Contributing

If you have useful resources or tools to add, feel free to fork this repository and submit a pull request!


## Notes
Concerning the "HOW TO BUILD YOUR OWN MAIL SERVER" is a rainloop-webmail: This is a simple tutorial helping you to implement your own mail server on an ubuntu machine.
main part: necessary elements for our mail server we need to install
    SMTP Server = Postfix
    IMAP Server = Dovecot
    WEB SERVER = Nginx
    WEB MAIL = rainloop

Security layers
    Setup SPF & DKIM with POSTFIX
    Enable https on nginx
    Redirect-http-to-https for Nginx
    INSTALL WAF for NGINX = NGINX ModeSecurity


InvokeReflective-Ncat: this is a simple designe to reflectively inject the NCAT in the targe memory and compromise the target via a bind shell
We can evade A/V by removing all comments and renaming/obfuscating functions from Invoke-ReflectivePEInjection code.
And evading IDS by doing a XOR obfuscation/de-obfuscation for the attack’s stage payload.

---

**Happy Hacking! 🔥**



