# Simulating Cyber Attacks Within a Virtual Enviornment Using Kali Linux #
 
 
 
 
 
 **[Step By Step Guide](https://github.com/Amazeexe/VMAttack-DefenseHomeLab/blob/4d864c115e6c5e789966a7eb2716752ed5e851f2/Simulating%20Cyber%20Attacks%20With%20Kali%20Linux.pdf)**
 
 
 
 **HomeLab Overview**
- Simulating Malware Creation and deployment through Kali Linux
- Sandboxxed VM Enviornment
- Windows and Linux VM on VLAN
- Used MetaSploit to craft malware of choice
- Deployed Malware as "resume.pdf" on an HTTP server using a python script
- Downloaded Malware onto the windows VM
- Examined the "resume.pdf" malware is properly running on Windows VM
- Scanned ports and found RDP (3389) to be open and vulnerable
- infiltrated Windows VM successfully and logged account credentials and system information.
- Used SYSMON and Splunk to identify the origin and path of the malicious file on the network 
