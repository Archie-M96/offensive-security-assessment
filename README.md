# 8-Level Offensive Security Assessment & Cryptographic Analysis

## Executive Summary
This repository contains an end-to-end technical vulnerability assessment report compiled during an intensive, unguided 33-hour technical security challenge against external target infrastructure. 

The assessment mapped observed flaws, automated proof-of-concept exploits, and developer remediation roadmaps directly to **NIST SP 800-115**, **OWASP Top 10**, and **CWE** industry standards.

---

## Deliverables & Documentation
* 📄 **[Download Full Assessment Report (PDF)](./Archie_M_Technical-Challenge-Walkthrough.pdf)** (11-page technical walkthrough with full reproduction steps)

---

## Target Scope & Vulnerability Matrix

| Level / Target Vector | Vulnerability Category | Primary Tooling / Technique | Standards Reference |
| :--- | :--- | :--- | :--- |
| **Reconnaissance & OSINT** | Public Record Exposure | DNS TXT Harvesting, `dig`, Nmap | CWE-200 |
| **Authentication Logic** | Client-Side Security Bypass | DOM Inspection, Client-Side Validation Stripping | OWASP A07:2021 |
| **Cryptographic Flaws** | Insecure Cryptographic Implementation | AES Key Brute-Forcing, CryptoJS In-Browser Hooking | OWASP A02:2021 / CWE-327 |
| **Forensic Analysis** | Covert Data Channels | Steganography & Metadata Analysis | NIST SP 800-115 |
| **Session & Parameter Handling**| Broken Access Control | Parameter Tampering, Header Manipulation | OWASP A01:2021 |

---

## Methodologies Applied
* **Target Enumeration:** Systematic attack-surface discovery across web endpoints, DNS records, and source files.
* **Exploitation Automation:** Custom Python and browser-console scripts to automate cryptanalysis routines and payload delivery.
* **Remediation Roadmaps:** Providing defense-in-depth guidance, safe cryptographic defaults, and secure server-side validation models for engineering teams.

---

## Author
**Archie Magoro**  
*Final-Year IT Diploma Student (Cloud Computing & Cybersecurity)*  
*Belgium Campus iTVersity*  
* [LinkedIn](https://linkedin.com/in/archie-magoro-8a4260410) | [GitHub](https://github.com/Archie-M96)
