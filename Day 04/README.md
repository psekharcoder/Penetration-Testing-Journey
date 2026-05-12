📘 Day 04 – SMB Enumeration using Metasploit (Kali Linux)

📌 Objective
To perform SMB enumeration using Metasploit Framework in Kali Linux and analyze SMB services running on a target machine in order to understand information gathering techniques used during network reconnaissance.

🔎 Approach

Initialized Metasploit Framework using msfconsole
Performed SMB service scanning against the target machine
Identified open SMB ports and detected Samba service details
Used auxiliary scanner modules for SMB enumeration
Analyzed responses returned from SMB enumeration modules

⚙️ Steps Performed

Started Metasploit Framework using msfconsole
Searched for SMB-related auxiliary modules
Loaded smb_version scanner module
Configured target IP address using RHOSTS
Executed SMB version scan against target machine
Identified Samba service running on the target
Performed additional SMB share and user enumeration attempts
Verified SMB ports using Nmap scanning techniques

📊 Observations

SMB service was detected on ports 139 and 445
Target machine was identified running Samba service on a Unix/Linux system
Metasploit successfully retrieved SMB version information
Enumeration process revealed details about SMB protocol implementation
Filtered ports were initially observed due to firewall/network configuration on Windows 7 testing environment

🧠 Key Learnings

Understanding SMB enumeration methodology using Metasploit
Practical usage of auxiliary scanner modules in Metasploit Framework
Importance of SMB services during reconnaissance and penetration testing
Difference between open and filtered ports during network scanning
Hands-on exposure to SMB-based information gathering techniques

🎯 Outcome

Successfully performed SMB enumeration using Metasploit Framework in Kali Linux. Gained practical understanding of SMB reconnaissance, service detection, and enumeration techniques used during network analysis and penetration testing activities.

⚠️ This work is intended for educational purposes only.

