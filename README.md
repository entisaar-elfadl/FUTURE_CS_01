# FUTURE_CS_01
## Vulnerability Assessment Report for a Live Website
This repository contains the deliverables for Task 1 of the Future Interns Cyber Security Internship. The project involved conducting a read-only vulnerability assessment of the OWASP Juice Shop demo application using passive security assessment techniques.

### Objective
The objective of this task was to perform a read-only vulnerability assessment on a public website. The assessment focused on identifying common security weaknesses without performing any intrusive or exploitative activities. 

### Target Website
OWASP Juice Shop Demo

URL:
https://demo.owasp-juice.shop

### Scope
This assessment included:

- Network port scanning
- Identification of exposed services
- HTTP security header analysis
- SSL/TLS configuration review

### Tools Used
- Nmap
- SecurityHeaders.com
- SSL Labs
- Browser Developer Tools
- Microsoft Word (Report Writing)

### Methodology
1. Selected a public website suitable for security assessment.
2. Performed a network scan using Nmap.
3. Reviewed HTTP security headers.
4. Evaluated SSL/TLS configuration.
5. Documented findings and recommended remediation steps.

### Repository Structure
```text
FUTURE_CS_01
│
├── Evidence
│   ├── header_scanner.png
│   ├── header_scanner2.png
│   ├── nmap_screenshot.png
│   └── security_headers.png
├── Report
│   └── Task 1 Report.pdf
└── README.md
```
### Overall Risk Assessment
The assessment identified several low and medium risk security observations. While the application implements some security controls, improvements such as implementing additional HTTP security headers and reviewing exposed services would strengthen its overall security posture.

### Key Findings
The assessment identisfied several security observations, including:

- Multiple publicly exposed network services
- Security header configuration observations
- SSL/TLS configuration review
- Recommendations to improve the website's security posture

### Ethical Statement
This assessment was conducted for educational purposes as part of the Future Interns Cyber Security Internship. Only passive, read-only analysis techniques were used. No exploitation, brute force attacks, denial-of-service attacks, or unauthorized access attempts were performed.

### Author
**Entisaar Elfadl**

Bachelor of Business Science (Computer Science)

University of Cape Town

Future Interns Cyber Security Intern (2026)