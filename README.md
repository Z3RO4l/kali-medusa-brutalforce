#**Brute-Force Attack Using Kali Linux and Medusa**

This project demonstrates brute-force attacks in a controlled environment, using Kali Linux and the Medusa tool, as proposed in the challenge. 
Metasploitable 2 was used as the controlled test environment.

-------------------------------------------------------------------------------------------------------
**CHALLENGE OBJECTIVES**

Understand brute-force attacks against different services (FTP, web, and SMB);

Use Medusa and Hydra for security auditing;

Document the entire process clearly;

Identify vulnerabilities and propose mitigation measures.

----------------------------------------
**CONFIGURED ENVIRONMENT**

-Attacker machine: Kali Linux;

-Target machine: Metasploitable 2;

-Virtualization: Oracle VirtualBox;

-Network: Host-only Adapter;

-Target machine IP: 192.168.56.101;

-Attacker machine IP: 192.158.56.102.

--------------------------------------------------------------------------------------------------------
# **REPOSITORY STRUCTURE**

Creating the Wordlists:

The wordlists were created using common usernames and passwords, as well as previously known credentials found through Nmap searches in vulnerable environments such as Metasploitable 2.


cat ~/dio-kali-medusa/wordlists/passwords.txt                                     cat ~/dio-kali-medusa/wordlists/users.txt

conteúdo                                                                                
msfadmin                                                                                -msfadmin
admin                                                                                   -admin
123456                                                                                  -root
letmain                                                                                 -user
admin123                                                                                -guest
qwerty                                                                                  -postgres
abc123                                                                                  -service
password123                                                                             -tomcat
welcome23
root
toor
test
12345678
iloveyou
football
monkey

**Mitigation Measures**

Use strong, complex passwords (at least 12 characters);

Implement account lockout after five failed attempts;

Enable multi-factor authentication (MFA/2FA);

Disable unnecessary services;

Remove or disable default accounts, or strengthen their security;

Keep the system up to date;

Monitor authentication logs regularly.

================================================================================================================================================================================

##**Final Thoughts**

This challenge was extremely valuable in consolidating my knowledge of brute-force attacks. I saw firsthand how vulnerable default configurations, such as those in Metasploitable, are to simple attacks.

I learned that brute-force attacks are “noisy” and easily detected with good defenses, but they can still be highly effective against misconfigured systems. Documentation and mitigation are just as important as carrying out the attack.

I’m very grateful to be learning cybersecurity and to become, with each challenge, a better-prepared professional ready to work in the ethical hacking field.

================================================================================================================================================================================








