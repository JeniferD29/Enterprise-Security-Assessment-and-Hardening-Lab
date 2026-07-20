# Assessment Methodology

## Overview

The Vulnerability Assessment and Penetration Testing (VAPT) engagement followed a structured methodology inspired by industry-standard penetration testing practices.

The objective was to identify, validate, exploit, and document security weaknesses within the simulated enterprise environment.

---

## Phase 1 – Lab Design

- Planned the enterprise infrastructure.
- Configured virtual machines.
- Installed required enterprise services.
- Introduced controlled security vulnerabilities.

---

## Phase 2 – Reconnaissance

The initial phase focused on discovering the attack surface.

Activities included:

- Host discovery
- Port scanning
- Service identification
- Version detection

**Primary Tool**

- Nmap

---

## Phase 3 – Enumeration

After identifying exposed services, detailed enumeration was performed.

Activities included:

- Directory enumeration
- FTP enumeration
- SMB enumeration
- Web application analysis

**Primary Tools**

- Gobuster
- NetExec
- enum4linux
- Browser-based testing

---

## Phase 4 – Vulnerability Assessment

Security weaknesses were identified through both automated and manual testing.

The findings were validated before exploitation to eliminate false positives.

---

## Phase 5 – Exploitation

Validated vulnerabilities were exploited in a controlled environment to demonstrate their impact.

Examples include:

- SQL Injection
- Backup File Exposure
- File Upload Vulnerability

---

## Phase 6 – Privilege Escalation

Following initial system access, privilege escalation techniques were performed to obtain administrative (root) access.

System enumeration was conducted using Linux privilege escalation methodologies.

---

## Phase 7 – Reporting

All findings were documented with:

- Technical Description
- Risk Rating
- Supporting Evidence
- Impact Analysis
- Remediation Recommendations

---

## Methodology Workflow

```
                                   Planning
                                      │
                                      ▼
                                 Lab Deployment
                                      │
                                      ▼
                                 Reconnaissance
                                      │
                                      ▼
                                  Enumeration
                                      │
                                      ▼
                                Vulnerability Assessment
                                      │
                                      ▼
                                  Exploitation
                                      │
                                      ▼
                                Privilege Escalation
                                      │
                                      ▼
                                  Reporting
                                      │
                                      ▼
                                  Remediation
```

---

## Conclusion

Following a structured assessment methodology ensured comprehensive coverage of the target environment while maintaining accurate documentation and reproducible assessment results.
