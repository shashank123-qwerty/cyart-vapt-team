# Week 4 – Advanced VAPT (Vulnerability Assessment & Penetration Testing)

This repository documents **advanced theoretical knowledge and practical labs** covering exploitation, API security, privilege escalation, network attacks, mobile application testing, and a full VAPT capstone engagement.  
The work aligns with **PTES methodology** and industry best practices.

---



### 1. Advanced Exploitation Techniques

#### Core Concepts
- **Exploit Chaining**  
  Combine multiple vulnerabilities to achieve full compromise.  
  *Example:* XSS → Session Hijacking → RCE, or CSRF + SQL Injection for admin access.

- **Custom Exploit Development**  
  Modify Exploit-DB PoCs or write custom scripts (Python/C).  
  *Example:* Heap overflows and browser heap spraying.

- **Bypassing Modern Defenses**  
  Evasion of ASLR, DEP, and WAFs using:
  - Return-Oriented Programming (ROP)
  - Polymorphic payloads
  - Shellcode obfuscation

#### Key Objective
Develop the ability to craft and chain complex exploits while bypassing modern security controls.

#### Learning Resources
- Exploit-DB advanced PoCs
- TCM Security – Exploit Development
- EternalBlue (CVE-2017-0144) analysis

---

### 2. API Security Testing

#### Core Concepts
- **OWASP API Top 10 (2023)**  
  Focus on Broken Object Level Authorization (BOLA).

- **Testing Techniques**
  - Manual testing using Burp Suite
  - Automated testing using Postman and sqlmap

- **Advanced Attacks**
  - Rate limit bypass
  - GraphQL injection
  - Token abuse

#### Key Objective
Build expertise in testing and securing modern REST and GraphQL APIs.

#### Learning Resources
- OWASP API Security Project
- PortSwigger API Labs
- SANS API Pentesting Case Studies

---

### 3. Privilege Escalation & Persistence

#### Core Concepts
- **Privilege Escalation**
  - Kernel exploits
  - Misconfigured services
  - Weak file permissions (SUID binaries)

- **Persistence Techniques**
  - Cron jobs
  - Malicious services
  - Startup scripts

- **Living-off-the-Land (LotL)**
  - PowerShell
  - WMI
  - Native Linux tools

#### Key Objective
Achieve deep system compromise and maintain long-term access.

#### Learning Resources
- HackTricks Privilege Escalation
- Offensive Security PWK
- TryHackMe Labs

---

### 4. Network Protocol Attacks

#### Core Concepts
- **Protocol Exploitation**
  - SMB, DNS, SNMP, FTP
  - SMB relay attacks

- **Man-in-the-Middle (MitM)**
  - ARP spoofing
  - DNS poisoning
  - SSL stripping

- **Misconfigurations**
  - Telnet
  - SMBv1
  - Weak encryption

#### Key Objective
Exploit insecure network protocols for credential access and data interception.

---

### 5. Mobile Application Penetration Testing

#### Core Concepts
- **OWASP Mobile Top 10**
  - M1: Improper Platform Usage
  - M2: Insecure Data Storage

- **Testing Techniques**
  - Static Analysis: MobSF
  - Dynamic Analysis: Frida, Drozer

- **Secure Design**
  - Obfuscation
  - Secure storage
  - Runtime protection

#### Key Objective
Identify and exploit vulnerabilities in Android applications.

---

### 6. Reporting & Remediation

#### Core Concepts
- **Advanced Reporting**
  - CVSS/DREAD scoring
  - Exploit chains
  - Business impact

- **Stakeholder Communication**
  - Executives
  - Developers
  - Auditors

- **Remediation**
  - Secure coding
  - Patch management
  - Zero Trust architecture

#### Key Objective
Deliver professional, actionable penetration testing reports.

---
