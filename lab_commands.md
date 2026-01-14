# Module-2:FootPrinting and Reconnaissance
1. Perform footprinting through search engines\
Gather information using advanced Google hacking techniques

2. Perform footprinting through Internet Research Services\
Find the company's domains, sub-domains, and Hosts using Netcraft and DNSdumpster

3. Perform footprinting through social networking sites\
Gather personal information from various social networking sites using Sherlock
4. Perform Whois footprinting\
Perform Whois lookup using DomainTools

5. Perform DNS footprinting\
Gather DNS information using nslookup command line utility and online tool

6. Perform network footprinting\
Perform network tracerouting in Windows and Linux Machines

7. Perform email footprinting\
Gather information about a target by tracing emails using eMailTrackerPro

8. Perform footprinting using various footprinting tools\
Footprinting a target using Recon-ng

9. Perform Footprinting using AI\
Footprinting a target using Shellgpt




### Lab 1: Perform Footprinting Through Search Engines
-> intitle:login site:eccouncil.org this is how you search for the exact site you need

### Lab 2: Perform Footprinting Through Internet Research Services
-> https://www.netcraft.com -> Research Tool -> Site report
->  https://dnsdumpster.com/ -> 

### Lab 3: Perform Footprinting Through Social Networking Sites
-> parrot terminal -> sudo su -> sherlock "Name"
->  Social Searcher (https://www.social-searcher.com) to gather information about targeted company

### Lab 4: Perform Whois Footprinting
-> windows -> https://whois.domaintools.com 

### Lab 5: Perform DNS Footprinting
-> cmd -> nslookup -> set type=a/ set type=cname 
-> http://www.kloth.net/services/nslookup.php

### Lab 6: Perform Network Footprinting(study Tracerouting)
-> run tracert -> tracert /? -> tracert -h 5 www. ---- .com
-> pingplotter
-> traceroute ng

### Lab 7: Perform Email Footprinting

### Lab 8: Perform footprinting using various footprinting tools
-> recon/domains-contacts/whois_pocs
Footprinting a Target using Recon-ng

# Module-3: Scanning Networks
1. Perform host discovery\
Perform host discovery using Nmap

2. Perform port and service discovery\
Explore various network scanning techniques using Nmap

3. Perform OS discovery\
Perform OS discovery using Nmap Script Engine (NSE)

4. Scan beyond IDS and Firewall\
Scan beyond IDS/firewall using various evasion techniques

5. Perform network scanning using various scanning tools\
Scan a target network using Metasploit

6. Perform Network Scanning using AI\
Scan a Target using ShellGPT

### 1.  Perform host discovery(NMAP)
-> nmap -sn -PR [Target IP Address]
-> nmap -sn -PU [Target IP Address]
-> nmap -sn -PE [Target IP Address]
-> nmap -sn -PP [Target IP Address]
-> nmap -sn -PM [target IP address]
-> nmap -sn -PS [target IP address]
-> nmap -sn -PA [target IP address]
-> nmap -sn -PO [target IP address]

### 2. Perform Port and Service Discovery
-> windows -> zenmap -> nmap -sT -v [Target IP Address]













































