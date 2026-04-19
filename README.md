
# Strategic Analysis: Third-Party Supply Chain Risk & Zero Trust

## Project Overview
This project provides a comprehensive post-mortem and remediation strategy for the **Target Corporation Data Breach**. The analysis identifies critical failures in traditional perimeter security and proposes a transition to a **Zero Trust Architecture** to mitigate risks associated with third-party vendor access.

## Key Security Pillars
* **Third-Party Risk Management (TPRM):** Evaluating the vulnerabilities introduced by external vendor credentials.
* **Zero Trust Framework:** implementing "Never Trust, Always Verify" principles to prevent lateral movement.
* **Identity & Access Management (IAM):** Mandating Multi-Factor Authentication (MFA) for all remote and administrative entry points.
* **Data Protection:** Enforcing Point-to-Point Encryption (P2PE) and logical network segmentation to protect the Cardholder Data Environment (CDE).

## Technical Gap Analysis
The investigation highlights four systemic failures:
1.  **Identity Failure:** Reliance on Single-Factor Authentication (SFA) for vendor portals.
2.  **Architectural Failure:** Flat network design allowing unrestricted lateral movement.
3.  **Data Failure:** Absence of P2PE, leaving payment data vulnerable to memory-scraping malware.
4.  **Operational Failure:** Breakdown in SOC incident response despite automated threat detection.

## Remediation Roadmap
This report outlines a strategic shift toward:
* **Micro-segmentation** of the internal network.
* Strict **Vendor Access Controls** and annual cybersecurity health checks.
* Compliance with **PCI-DSS** as a baseline, enhanced by active threat hunting.

---
**View the Full Technical Case Study:** [Download PDF Here](./Mohdsyed_Target_Breach.pdf)
EOF
