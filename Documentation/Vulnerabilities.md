# Vulnerabilities

## Overview

The enterprise environment was intentionally configured with multiple vulnerabilities to simulate a realistic Vulnerability Assessment and Penetration Testing (VAPT) engagement.

Each vulnerability was successfully identified, validated, and documented during the assessment.

---

# HC-VULN-01 – Directory Listing Enabled

**Risk Level:** Medium

### Description

Directory listing was enabled on the web server, allowing unauthenticated users to browse sensitive directories.

### Impact

- Information Disclosure
- Exposure of Internal Files

### Status

Successfully Identified

---

# HC-VULN-02 – Backup File Exposure

**Risk Level:** High

### Description

Sensitive backup files containing application configuration and database credentials were publicly accessible.

### Impact

- Credential Disclosure
- Database Information Exposure

### Status

Successfully Exploited

---

# HC-VULN-03 – SQL Injection

**Risk Level:** Critical

### Description

The application was vulnerable to SQL Injection, allowing unauthorized interaction with the backend database.

### Impact

- Database Disclosure
- Authentication Bypass
- Data Extraction

### Status

Successfully Exploited

---

# HC-VULN-04 – Unrestricted File Upload

**Risk Level:** Critical

### Description

The upload functionality failed to properly validate uploaded files.

### Impact

- Arbitrary File Upload
- Potential Remote Code Execution

### Status

Successfully Exploited

---

# HC-VULN-05 – Weak FTP Configuration

**Risk Level:** Medium

### Description

The FTP service contained weak authentication and insecure configuration.

### Impact

- Unauthorized File Access

### Status

Successfully Identified

---

# HC-VULN-06 – SMB Information Disclosure

**Risk Level:** Medium

### Description

SMB shares exposed sensitive information during enumeration.

### Impact

- Internal Information Disclosure
- Enumeration of Shared Resources

### Status

Successfully Identified

---

# HC-VULN-07 – Linux Privilege Escalation

**Risk Level:** High

### Description

Privilege escalation vectors allowed elevation from a standard user account to root privileges.

### Impact

- Complete System Compromise

### Status

Successfully Exploited

---

## Summary

The assessment successfully demonstrated the complete lifecycle of a professional VAPT engagement, from reconnaissance and enumeration through exploitation, privilege escalation, reporting, and remediation planning.
