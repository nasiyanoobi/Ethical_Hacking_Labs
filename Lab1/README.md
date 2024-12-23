# Lab 1: Wamp Server Configuration, SQL Injection, and PowerShell Exploitation

## Overview
This lab demonstrates how attackers can exploit vulnerabilities in web applications and operating systems using tools like WampServer and PowerShell. It covers:
- Setting up a vulnerable environment (WampServer and DVWA).
- Exploiting SQL injection to bypass authentication and retrieve sensitive data.
- Demonstrating fileless malware techniques using PowerShell.

## Key Activities
### WampServer and DVWA Setup
- Installed and configured WampServer and DVWA for testing.
- Set up MariaDB for database operations.

### SQL Injection
- Tested authentication bypass using SQL injection.
- Extracted user data from the database using crafted SQL queries.

### PowerShell Exploitation
- Demonstrated fileless malware techniques by downloading and executing scripts directly in memory.
- Showcased the risks of improper PowerShell execution policies.

## Results
- Successfully retrieved sensitive data through SQL injection.
- Highlighted the risks posed by fileless malware and unprotected PowerShell configurations.

## Tools Used
- **WampServer**, **DVWA**, **MariaDB**
- **PowerShell**

## Mitigations
- Use input validation and prepared statements to prevent SQL injection.
- Apply strict PowerShell execution policies and monitor system logs for anomalies.

