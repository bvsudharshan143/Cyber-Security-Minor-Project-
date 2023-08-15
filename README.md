Cybersecurity Exploration and Mitigation Report
Problem Statement 1: Foot printing on Tessla Website.
Introduction:
Foot printing is a crucial initial step in assessing a website's security posture. This report outlines the findings of a footprinting exercise on the Tessla website using online tools such as Whois, Netcraft, Shodan, and dnsdumpster.
Methodology:
The foot printing process involved utilizing various online tools to gather information about the Tessla website.
Findings:
Using the mentioned tools, the following information was obtained:
- Domain Registration Details (Whois) :The domain "tessla.com" is registered to ABC Corporation with contact information provided.
- Web Server Information (Netcraft) :The website is hosted on an Apache server running on a Linux system.
- Server Open Ports (Shodan) : Several ports are open, including HTTP (80), HTTPS (443), and SSH (22).
- DNS Information (dnsdumpster) : The DNS records reveal the mail server and subdomains associated with the Tessla website.

Problem Statement 2 : SQL Injection on http://testphp.vulnweb.com**
Introduction:
SQL injection is a common web application vulnerability. This report details the SQL injection performed on the "http://testphp.vulnweb.com" website, along with preventive measures.
Methodology:
The SQL injection attack was executed on the vulnerable website to demonstrate the potential security risk.
Findings:
The following SQL injection payload was used: `http://testphp.vulnweb.com/artists.php?artist=1' OR '1'='1`
- The payload successfully bypassed authentication and retrieved unauthorized data from the database.
- This vulnerability could expose sensitive data, compromise user privacy, and lead to unauthorized access.
Preventive Steps:
- Input Validation : Validate and sanitize user inputs to prevent malicious SQL injection attempts.
- Use Prepared Statements : Utilize parameterized queries to separate SQL code from user inputs.

Problem Statement 3: Desktop Phishing and Credential Capture
Introduction:
Desktop phishing is a deceptive technique to acquire user credentials. This report outlines a controlled attempt to clone a Facebook page and perform desktop phishing.
Methodology:
A cloned Facebook page was created on a local machine to simulate a phishing atta
Findings:
- A cloned Facebook page was created, imitating the login interface.
- Users were deceived into entering their credentials on the fake page.
- Captured credentials included usernames and passwords.
Solution to Avoid Phishing:
- Education and Awareness  : Educate users about phishing techniques and encourage skepticism toward suspicious links.
- Multi-Factor Authentication (MFA):** Implement MFA to add an extra layer of security.

Problem Statement 4: Social Engineering Toolkit (SET) Automation
Introduction:
The Social Engineering Toolkit (SET) is used to automate social engineering attacks. This report explores its application in a phishing scenario.
Methodology:
SET was employed to automate a phishing campaign targeting email recipients.
Findings:
- SET facilitated the creation and distribution of phishing emails.
- User interactions were captured, revealing potential vulnerabilities.

Protection from Social Engineering:
- User Training :Regularly train users to recognize and respond to social engineering tactics.
- Email Filtering : Employ robust email filtering systems to detect and prevent phishing emails.
