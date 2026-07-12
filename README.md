# Active Directory Attack Lab

![Banner](Images/Banner.png)

A complete hands-on Active Directory lab that demonstrates how common Active Directory attacks are performed, how they work internally, and how they can be mitigated.

> ⚠️ **Disclaimer**
>
> This project was created for educational purposes only inside an isolated virtual lab environment. It is intended to help security professionals, students, and defenders understand Active Directory attack techniques and corresponding mitigations.

---

# Project Overview

This project simulates a realistic enterprise Active Directory environment (EvilCorp.local) containing multiple workstations, servers, users, organizational units, and services.

The objective is to understand how attackers compromise Windows domains by abusing authentication protocols, Active Directory misconfigurations, credential attacks, and lateral movement techniques.

Each attack includes:

- Attack overview
- Prerequisites
- Internal protocol explanation
- Step-by-step execution
- Screenshots

---

# Lab Infrastructure

The environment consists of:

- Domain Controller
- IIS Web Server
- HR Workstation
- IT Workstation
- Management Workstation
- Hacker Machine

![Lab Architecture](Images/Architecture.png)

---

# Demonstrated Attacks

- Enumeration
- Password Attacks
  - Brute Force
  - Password Spraying
- AS-REP Roasting
- Kerberoasting
- Pass-the-Hash
- Overpass-the-Hash
- Pass-the-Ticket
- DCSync
- DCShadow
- Silver Ticket
- Golden Ticket
- Lateral Movement
  - WMI
  - WinRM
  - PsExec
---

# Topics Covered

- Active Directory Administration
- Kerberos Authentication
- NTLM Authentication
- LDAP Enumeration
- Service Principal Names (SPNs)
- Kerberos Tickets (TGT & TGS)
- LSASS Credential Dumping
- Active Directory Replication
- Windows Remote Management
- Windows Management Instrumentation
- SMB
- DCOM

---

# Tools Used

### Offensive Security

- Mimikatz
- Rubeus
- PowerView
- CrackMapExec
- Evil-WinRM
- PsExec

### Password Cracking

- Hashcat

---

# Learning Objectives

This lab demonstrates:

- How Active Directory authentication works
- Kerberos internals
- Credential theft techniques
- Kerberos ticket attacks
- Credential replay attacks
- Active Directory replication abuse
- Remote administration abuse
- Lateral movement
- Privilege escalation
- Defensive mitigations

---

# Repository Structure

```
Active-Directory-Lab/
│
├── Documentation/
│   ├── Project Overview
│   ├── Lab Setup
│   ├── Authentication
│   ├── Credential Attacks
│   ├── Kerberos Attacks
│   ├── Lateral Movement
│   └── Mitigations
│
├── Images/
│
├── Scripts/
│
├── Tools/
│
└── README.md
```

---

# MITRE ATT&CK Coverage

This project covers techniques from multiple MITRE ATT&CK tactics, including:

- Initial Access
- Credential Access
- Discovery
- Lateral Movement
- Privilege Escalation
- Defense Evasion

---

# Author

**Samuel4O4**

---

⭐ If you found this project useful, consider giving the repository a star.
