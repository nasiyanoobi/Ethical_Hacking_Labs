# Lab 4: Capturing Hashes, Brute Forcing, Wireless Testing, Cracking WPA2 Passwords, and Deauthenticating Clients with Wifite

## Overview
This lab demonstrates practical techniques for network and wireless penetration testing, including capturing hashes, brute-forcing credentials, analyzing wireless networks, and exploiting WPA2 passwords. The lab was conducted using tools such as Responder, Hydra, NetSpot, Advanced IP Scanner, and Wifite.

## Objectives
- Capture NTLM hashes using Responder.
- Perform brute force attacks against user accounts with Hydra.
- Analyze wireless networks and identify vulnerabilities.
- Crack WPA2 passwords and deauthenticate clients using Wifite.

## Key Activities
### Activity 1: Capturing Hashes
- Configured a Windows Server and Target system in a VirtualBox environment.
- Used Responder to capture NTLM hashes when a user accessed a shared folder.
- Verified the successful capture of NTLM hashes for further analysis.

### Activity 2: Brute-Forcing Services
- Created a weak account on a Metasploitable system.
- Used Hydra to brute-force the SSH credentials of the target account.
- Demonstrated methods to optimize attack speed and customize password lists.

### Activity 3: Wireless Network Analysis
- Installed and used NetSpot to discover nearby SSIDs and analyze wireless networks.
- Identified network security configurations (e.g., WPA2, WPA3) and signal strengths.
- Used Advanced IP Scanner to detect network devices and services.

### Activity 4: Cracking WPA2 Passwords with Wifite
- Deauthenticated clients from a wireless network using Wifite.
- Captured WPA2 handshake data for password cracking.
- Used wordlists to successfully crack a WPA2 password.

## Tools Used
- **Responder** for capturing NTLM hashes.
- **Hydra** for brute-forcing SSH credentials.
- **NetSpot** for wireless network analysis.
- **Advanced IP Scanner** for LAN device discovery.
- **Wifite** for WPA2 handshake capture and deauthentication.

## Results
- Successfully captured NTLM hashes and brute-forced weak SSH credentials.
- Detected 59 SSIDs and analyzed 20 network devices, identifying various services and security configurations.
- Cracked a WPA2 password and demonstrated the impact of weak wireless network security.

## Lessons Learned
- Importance of strong passwords to mitigate brute force attacks.
- Risks of NTLM hash exposure and how attackers can exploit them.
- Significance of WPA3 adoption for better wireless security.
- Necessity of network monitoring and secure configurations to protect against wireless attacks.

## References
- [Responder](https://github.com/lgandx/Responder)
- [Hydra](https://github.com/vanhauser-thc/thc-hydra)
- [NetSpot](https://www.netspotapp.com/)
- [Advanced IP Scanner](https://www.advanced-ip-scanner.com/)
- [Wifite](https://github.com/derv82/wifite2)
