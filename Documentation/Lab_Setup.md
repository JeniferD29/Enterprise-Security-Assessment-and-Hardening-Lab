# Lab Setup

## Overview

This document describes the setup of the simulated enterprise environment used for the Vulnerability Assessment and Penetration Testing (VAPT) project.

The objective was to build a realistic corporate infrastructure with intentionally introduced vulnerabilities for security assessment, exploitation, and remediation practice.

---

## Virtual Environment

**Host Machine**
- Windows 11

**Virtualization Platform**
- Oracle VirtualBox

**Attacker Machine**
- Kali Linux

**Target Machine**
- Ubuntu Server 24.04 LTS

---

## Enterprise Services Configured

The following services were installed and configured on the Ubuntu Server.

- Apache2 Web Server
- PHP
- MariaDB
- OpenSSH
- vsftpd (FTP)
- Samba (SMB)

These services simulate a small enterprise application server commonly found in corporate environments.

---

## Web Application

A custom web application representing **HexaCore Technologies Pvt. Ltd.** was developed for this project.

The application included:

- Home Page
- About Page
- Services
- Solutions
- Careers
- Contact Page
- Employee Login Portal
- Admin Portal
- Document Management Portal

---

## Vulnerability Configuration

To simulate a realistic penetration testing engagement, multiple security weaknesses were intentionally introduced into the environment.

Examples include:

- Directory Listing
- Backup File Exposure
- SQL Injection
- Unrestricted File Upload
- Weak FTP Configuration
- SMB Information Disclosure
- Linux Privilege Escalation

These vulnerabilities were introduced solely for educational purposes within an isolated laboratory environment.

---

## Network Configuration

The attacker and target machines were connected through an isolated virtual network.

```
                                    Windows 11 Host
                                            │
                                            ▼
                                    Oracle VirtualBox
                                            │
                                     ┌───────────────┐
                                     │               │
                                     ▼               ▼
                                 Kali Linux     Ubuntu Server
                                 (Attacker)       (Target)
```

---

## Project Outcome

The completed environment successfully simulated an enterprise infrastructure suitable for performing a complete Vulnerability Assessment and Penetration Testing (VAPT) engagement, including reconnaissance, enumeration, exploitation, privilege escalation, reporting, and remediation planning.
