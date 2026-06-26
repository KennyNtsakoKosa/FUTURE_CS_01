# Vulnerability Assessment Report - FUTURE_CS_01

## Task Overview
This repository contains the deliverables for **Task 1** of the Future Interns Cyber Security Internship.

## Target Website
- **URL**: `http://demo.testfire.net` (Altoro Mutual)
- **Scope**: Read-Only Assessment of Public-Facing Pages
- **Ethics**: All activities were conducted strictly within ethical guidelines. No active exploitation, brute force, or Denial-of-Service (DoS) testing was performed.

## Tools Used
- **Nmap** – Port and service discovery
- **OWASP ZAP** – Passive vulnerability scanning
- **Browser DevTools** – Security header inspection
- **Canva** – Report design

## Findings Summary

| Risk Level | Finding |
| :--- | :--- |
| 🔴 **High** | Missing Content Security Policy (CSP) |
| 🔴 **High** | Missing Strict-Transport-Security (HSTS) |
| 🟡 **Medium** | Missing X-Frame-Options (Clickjacking risk) |
| 🟡 **Medium** | Missing X-Content-Type-Options |
| 🟡 **Medium** | Cookie without SameSite Attribute |
| 🟡 **Medium** | Exposed Port 8080 (Public Access) |
| 🟢 **Low** | Server Version Disclosure (Apache-Coyote/1.1) |
| 🟢 **Low** | Missing Cache-Control Directives |

## Deliverables
- [Vulnerability_Assessment_Report_demo.testfire.net.pdf](Vulnerability_Assessment_Report_demo.testfire.net.pdf)
- Evidence: Screenshots of Nmap scan, OWASP ZAP alerts, and Browser DevTools header inspection

## Author
**Kenny Kosa** - Cyber Security Intern, Future Interns  
CIN ID: FIT/JUN26/CS9276  
Date: June 26, 2026
