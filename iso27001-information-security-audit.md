# Case Study: Enterprise Information Security Audit & Risk Assessment (ISO/IEC 27001)

**Domain:** Governance, Risk & Compliance (GRC) / Information Security Auditing
**Frameworks Applied:** ISO/IEC 27001, ISO 27005, GDPR, OWASP Top 10, COBIT, NIST

---
## Executive Summary
This case study presents a comprehensive information security audit and systematic risk assessment conducted for **ABC Air**, an aviation maintenance organisation operating a web-based servicing platform built on **Flask** and hosted on **PythonAnywhere**. Evaluating confidentiality, integrity, and availability (CIA) controls against **ISO/IEC 27001** and **ISO 27005**, the audit identified high-priority technical and procedural gaps and established a structured remediation roadmap.

---

## Audit Scope & Methodology
* **ISMS Framework Selection:** Benchmarked **ISO/IEC 27001**, **COBIT**, **NIST**, **PCI DSS**, and **ITIL**, selecting **ISO/IEC 27001** for its international recognition, risk-based structure, and continual improvement lifecycle.
* **Regulatory & Secure Coding Alignment:** Audited personal data handling against **GDPR** requirements and evaluated application-layer defences against **OWASP** security guidelines.
* **SDLC & Technical Review:** Assessed security integration across the **Waterfall Software Development Life Cycle (SDLC)**, combining configuration reviews, static code analysis, and simulated penetration testing.

---

## Risk Assessment Matrix (ISO 27005)
Using the **ISO 27005** risk management workflow (context establishment, risk identification, estimation, and evaluation), potential cyber threats and fault events were prioritised by likelihood and business impact: 
| Threat / Hazard Event | Likelihood | Business Impact | Priority Level |
| :--- | :--- | :--- | :--- |
| **SQL Injection** | High | High | **High** |
| **Data Loss / Leakage** | Moderate | Very High | **High** |
| **Unauthorised Access** | High | Moderate | **High** |
| **Phishing & Social Engineering** | Moderate |High | **High** |
| **DDoS Attacks** | Low | High | **Moderate** |

---

## Key Remediation Recommendations 
To mitigate high-priority risks and strengthen ABC Air's security posture, four core controls were recommended:
1. **Access Control Hardening:** Enforce **Multi-Factor Authentication (MFA)** across all administrative and user access points to prevent unauthorised access.
2. **Application & Perimeter Defence:** Deploy a **Web Application Firewall (WAF)** and **Intrusion Detection System (IDS)** alongside regular vulnerability scanning and penetration testing to block SQL injection and DoS vectors.
3. **Human Risk Management:** Establish recurring employee security awareness training targeting phishing and social engineering tactics.
4. **Incident Response Readiness:** Formalise a structured Incident Response Plan covering rapid detection, containment, and recovery workflows.
