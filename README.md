# FICBANK Security Assessment (Nmap & Nessus)

## Objective
Conduct a vulnerability assessment of a financial institution’s IT infrastructure to identify security risks, open ports, and system weaknesses.

## Tools Used
- Nmap
- Nessus
- Kali Linux

## Key Activities
- Performed Nmap scan to identify open ports and services
- Conducted Nessus vulnerability scan to detect system weaknesses
- Analyzed vulnerabilities based on severity (Critical, High, Medium, Informational)
- Evaluated overall system security posture

## Key Findings
- Identified 9 open ports including high-risk ports (445 and 3389)
- Discovered 642 vulnerabilities:
  - 115 Critical
  - 189 High
  - 82 Medium
  - 256 Informational
- Detected outdated and unpatched software
- Identified lack of security monitoring

## Risk Impact
The system is highly vulnerable to unauthorized access, malware attacks, and potential data breaches due to unpatched systems and exposed services.

## Remediation Recommendations
- Apply regular system and software updates
- Close unnecessary open ports
- Restrict remote desktop access
- Implement continuous monitoring (SIEM)
- Enforce multi-factor authentication (MFA)

## Outcome
This project demonstrates hands-on experience in vulnerability scanning, risk analysis, and security assessment using industry tools.
