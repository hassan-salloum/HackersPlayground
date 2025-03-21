### CheatSheet Pentesting Notes
-------------------------------------------------------------------------------------------------------------------------------

Advanced Pentesting cheatsheet: 
[Pentest-CheatSheet.xlsx](https://github.com/VraiHack/Advanced-Pentesting-cheatsheet/raw/main/Pentest-CheatSheet.xlsx)

AD enumeration cheatsheet:
[AD Enumeration (Forest,Domain,DC,OU,Groupe,Users,Machines,Policy,Trust).pdf](https://github.com/VraiHack/Advanced-Pentesting-cheatsheet/blob/main/AD%20Enumeration%20(Forest%2CDomain%2CDC%2COU%2CGroupe%2CUsers%2CMachines%2CPolicy%2CTrust).pdf)

AMSI evasion and clear text password to spike the mimikatz hash

triggerable-outlook-malware

rainloop-webmail: This is a simple tutorial (check attached PDF) helping you to implement your own mail server on an ubuntu machine.
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





