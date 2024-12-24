# Lab 5: Exploiting Host Vulnerabilities using SAM, Hashcat, and Shell

## Overview
This lab focuses on exploiting host vulnerabilities, including dumping and cracking Windows SAM credentials, password cracking using Hashcat, and setting up reverse and bind shells to gain access to a target system. The exercises were performed using tools like Metasploit and Hashcat on a Metasploitable Windows host.

## Objectives
- Extract and crack password hashes from the Windows SAM.
- Use Hashcat to perform dictionary attacks on password hashes.
- Establish reverse and bind shells using Metasploit.

## Key Activities
### Activity 1: Dumping and Cracking the Windows SAM
- Exploited a Windows system vulnerability to create a Meterpreter-based reverse shell.
- Dumped the Windows SAM file using the `mimikatz_command` for offline analysis.
- Captured NTLM hashes and prepared them for cracking.

### Activity 2: Cracking Passwords Using Hashcat
- Extracted the `/etc/shadow` file from a Kali Linux system to simulate password cracking.
- Cleaned and prepared the hash data for processing.
- Used the `rockyou.txt` wordlist to perform a dictionary attack with Hashcat.
- Successfully cracked SHA-512 hashes to retrieve user passwords.

### Activity 3: Setting Up Reverse and Bind Shells
- Used Metasploit to exploit the ManageEngine ConnectionID Write vulnerability on a Windows host.
- Configured the `windows/meterpreter/reverse_tcp` payload to establish a reverse shell.
- Created a bind shell using the `windows/shell_bind_tcp` payload to connect directly to the target.

## Tools Used
- **Metasploit** for vulnerability exploitation and shell setup.
- **Hashcat** for password cracking.
- **Mimikatz** for extracting Windows SAM hashes.

## Results
- Successfully dumped Windows SAM credentials and extracted NTLM hashes.
- Cracked password hashes using Hashcat with SHA-512 hashes.
- Established both reverse and bind shells on a Metasploitable Windows system, demonstrating control over the target.

## Lessons Learned
- Understanding the importance of securing credential storage and system vulnerabilities.
- Using dictionary attacks to crack password hashes effectively.
- Gaining practical experience in reverse and bind shell setups.

## References
- [Metasploit Framework](https://github.com/rapid7/metasploit-framework)
- [Hashcat](https://hashcat.net/hashcat/)
- [Mimikatz](https://github.com/gentilkiwi/mimikatz)
