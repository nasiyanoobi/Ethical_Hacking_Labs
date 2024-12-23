# Lab 3: Exploiting Application Vulnerabilities using ZAP, XSS, and URL Manipulation

## Overview
This lab demonstrates how attackers exploit web application vulnerabilities such as insecure direct object references, cross-site scripting (XSS), and manipulated HTTP requests using OWASP ZAP.

## Objectives
- Learn to intercept and manipulate HTTP requests using ZAP.
- Understand the risks and implications of XSS attacks.
- Explore URL manipulation techniques to exploit insecure direct object references (IDOR).

## Key Activities
1. **Intercepting HTTP Requests:**
   - Configured OWASP ZAP to intercept and modify browser requests.
   - Manipulated GET requests to alter search terms on a target website.

2. **Cross-Site Scripting (XSS):**
   - Injected XSS payloads into a locally hosted HTML file.
   - Demonstrated how malicious scripts can execute in a user's browser.

3. **URL Manipulation:**
   - Exploited IDOR vulnerabilities by altering URL parameters to access unauthorized records.
   - Manipulated database query outputs to retrieve sensitive data.

## Tools Used
- **OWASP ZAP**
- **Kali Linux**

## Results
- Successfully intercepted and modified HTTP requests.
- Demonstrated the execution of an XSS payload to display misleading information.
- Exploited URL manipulation to retrieve unintended database records.

## Lessons Learned
- The importance of input validation to prevent XSS and URL manipulation attacks.
- Ensuring proper authentication and authorization checks to prevent IDOR vulnerabilities.

## References
- [OWASP ZAP](https://owasp.org/www-project-zap/)
- [Cross-Site Scripting (XSS)](https://owasp.org/www-community/attacks/xss/)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
