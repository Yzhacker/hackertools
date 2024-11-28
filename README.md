# hackertools



2. Reconnaissance (Recon)
Tools Used:

┌──(root㉿kali)-[/home/kali]
└─# ifconfig

┌──(root㉿kali)-[/home/kali]
└─# arp-scan --localnet

┌──(root㉿kali)-[/home/kali]
└─# netdiscover -r <target>
Nmap: Port scans, service identification, and version detection.
┌──(root㉿kali)-[/home/kali]
└─# nmap -sV -Pn <target>
    


Gobuster/BfExploit: Directory and file brute-forcing on HTTP servers.
Nikto: Web vulnerability scanner.


Dirb/Dirbuster: Brute-force tools for directory enumeration.
3. Enumeration
Tools Used:

Hydra: Brute-force tool for protocols like SSH, FTP, HTTP, etc.
Nikto: Web scanner for detecting application vulnerabilities.
Nmap Scripts (-sC): Service enumeration and vulnerability detection.
Gobuster/Dirbuster: Directory and file scanning.
Protocol brute-forcing examples:
FTP: hydra -l username -P password_list ftp://target
SNMP: snmpwalk -v1 -c community_target 192.168.0.1
4. Vulnerability Identification
Tools Used:

Metasploit Framework: Exploiting known vulnerabilities.
CVE Exploits Database: To find suitable exploits.
SQLmap: For SQL injection exploitation.
Nessus/OpenVAS: Vulnerability scanners.
Wireshark: Analyzing network traffic.
Burp Suite: Web vulnerability analysis (e.g., XSS, CSRF).
Metasploit Auxiliary Modules: Port and service scanners.
5. Exploitation
Tools Used:

Metasploit Framework: For exploitation modules like ProFTPD vulnerabilities.
MS17-010 Exploit (EternalBlue): Exploit SMB vulnerabilities.
Empyre/Empire: C2 frameworks for remote shell management.
Veil-Evasion: Create payloads to bypass detection.
Powersploit: PowerShell scripts for exploitation.
Netcat (nc): Interaction with services.
6. Privilege Escalation
Tools Used:

LinPEAS/WinPEAS: Identify misconfigurations and permissions.
GTFOBins: Commands for privilege escalation on Linux.
SUID3dump: Find SUID binaries.
Impacket: Tools for lateral movement in Windows environments.
Mimikatz: Extract credentials and hashes.
7. Post-Exploitation
Tools Used:

Metasploit Meterpreter: Interactive remote shell.
Cobalt Strike: C2 Framework for automation.
Mimikatz: Credential extraction.
Rubeus: Kerberos ticket extraction.
Ncat (nc): Persistent connections and data exfiltration.








