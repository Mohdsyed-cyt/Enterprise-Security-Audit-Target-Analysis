
# Enterprise Security Audit: Target Data Breach Analysis

## Project Overview
This repository contains a comprehensive technical audit and post-mortem of the **Target Corporation Data Breach**. The project evaluates the failure of traditional perimeter-based security and provides a strategic remediation roadmap rooted in **Zero Trust Architecture** and **Third-Party Risk Management (TPRM)**.

## Technical Audit Scope
* **Attack Vector Analysis:** Investigating the initial compromise via stolen HVAC vendor credentials.
* **Architectural Gap Analysis:** Evaluating the lack of logical segmentation between the corporate portal and the **Cardholder Data Environment (CDE)**.
* **Identity Governance:** Assessing the failure of Single-Factor Authentication (SFA) and the necessity of mandatory **MFA** for external partners.
* **Encryption Standards:** Proposing **Point-to-Point Encryption (P2PE)** to mitigate memory-scraping malware risks.

## Strategic Remediation (Zero Trust Model)
To address the systemic vulnerabilities identified, the report outlines the following high-level controls:
1. **Micro-segmentation:** Implementing software-defined perimeters to prevent lateral movement.
2. **Least Privilege Access:** Restricting third-party vendors to specific assets required for their job functions.
3. **Continuous Monitoring:** Hardening the SOC incident response lifecycle to ensure high-priority exfiltration alerts are prioritized and remediated.

## Professional Certifications Applied
* **CompTIA Security+**
* **ISC2 Certified in Cybersecurity (CC)**
* **Frameworks:** NIST Cybersecurity Framework (CSF) & PCI-DSS Compliance

---
**View the Full Technical Report:** [Download PDF Here](./Mohdsyed_Target_Breach.pdf)
EOF
