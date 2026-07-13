# Penetration-Testing

## Overview

This repository contains a web application vulnerability assessment performed against the intentionally vulnerable OWASP Juice Shop application for educational purposes.

The assessment follows the OWASP Web Security Testing Guide (WSTG v4.2) and references the OWASP Top 10 (2021).

> Disclaimer:
> This assessment was performed against an intentionally vulnerable training application. The repository is intended solely to demonstrate penetration testing methodology, documentation, and reporting skills.

---

## Assessment Details

- Target: OWASP Juice Shop
- Testing Type: Black-box Web Application Assessment
- Methodology: OWASP WSTG v4.2
- Reference: OWASP Top 10 (2021)

---

## Tools Used

- Nmap
- Nikto
- Nessus
- Acunetix

---

## Key Findings

| Severity | Count |
|----------|------:|
| Critical | 0 |
| High | 4 |
| Medium | 3 |
| Low | 2 |

Major findings included:

- Slow HTTP DoS
- Missing Content Security Policy (CSP)
- Missing Subresource Integrity (SRI)
- CORS Misconfiguration
- Missing HSTS
- Weak SSL/TLS Configuration
- Information Disclosure
- robots.txt Exposure

---

## Report

The complete assessment report is available here:

**Penetration_Testing_Report.pdf**

---

## Screenshots

### Nmap

![Nmap](images/nmap.png)

### Nikto

![Nikto](images/nikto.png)

### Nessus

![Nessus](images/nessus.png)

### Acunetix

![Acunetix](images/acunetix.png)

---

## Skills Demonstrated

- Vulnerability Assessment
- Web Application Security Testing
- Reconnaissance
- Security Reporting
- Risk Assessment
- OWASP WSTG
- OWASP Top 10
- Security Documentation

---

## Author

Mudassar Ali Zaman
