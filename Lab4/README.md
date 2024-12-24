# Lab 4: Capturing Hashes, Brute Forcing, and Wireless Testing

## Overview
This lab involves capturing hashes, brute-forcing credentials, and analyzing wireless networks using tools such as Responder, Hydra, NetSpot, and Advanced IP Scanner.

## Objectives
- Capture NTLM hashes from a Windows system using Responder.
- Perform brute force attacks against a weak user account using Hydra.
- Analyze wireless networks and devices using NetSpot and Advanced IP Scanner.

## Key Activities
### Activity 1: Capturing Hashes
- Configured a Windows Server and Target system in a VirtualBox environment.
- Used Responder to capture NTLM hashes when accessing a shared folder from the Target system.
- Verified the successful capture of NTLM hashes for potential cracking.

### Activity 2: Brute-Forcing Services
- Created a weak user account on a Metasploitable system.
- Used Hydra to brute force SSH credentials of the created account.
- Explored techniques to optimize attack speed and customize password lists.

### Activity 3: Wireless Network and Device Analysis
- Installed and used NetSpot to detect nearby SSIDs and analyze wireless networks.
- Identified SSIDs, vendors, security configurations, and signal strengths.
- Used Advanced IP Scanner to detect and analyze network devices and services.

## Tools Used
- **Responder** for capturing NTLM hashes.
- **Hydra** for brute-forcing SSH credentials.
- **NetSpot** for wireless network analysis.
- **Advanced IP Scanner** for network device discovery.

## Results
- Successfully captured NTLM hashes from a shared folder access scenario.
- Cracked weak SSH credentials using Hydra within seconds.
- Detected multiple wireless networks and devices, identifying security settings and services.

## Lessons Learned
- Importance of strong passwords to mitigate brute-force attacks.
- Risks of NTLM hash exposure and how attackers can exploit them.
- Techniques for analyzing wireless networks and identifying potential vulnerabilities.

## References
- [Responder](https://github.com/lgandx/Responder)
- [Hydra](https://github.com/vanhauser-thc/thc-hydra)
- [NetSpot](https://www.netspotapp.com/)
- [Advanced IP Scanner](https://www.advanced-ip-scanner.com/)
