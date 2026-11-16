# Case Study: Multi-Site Network Security Architecture & Performance Optimisation

**Domain:** Network Security & Infrastructure Design  
**Focus:** Network Segmentation, Perimeter Defence, Latency Optimisation & Security Policy Governance  

---

## Executive Summary
This case study examines network performance bottlenecks and security vulnerabilities across **Megadodo Publications**, a growing enterprise operating across two adjacent facilities (**Ursa Major Alpha** and **Ursa Minor Beta**). Ahead of high-stakes government contract negotiations, a comprehensive architectural overhaul and security policy update were engineered to eliminate latency, enforce network segmentation, and harden perimeter defences.

---

## Infrastructure & Performance Upgrades
* **High-Speed Inter-Building Connectivity:** Replaced legacy bottlenecks across the 80-metre facility gap with a direct **fibre-optic interconnect** to minimise latency and accelerate inter-site data transfer.
* **Subnetting & Logical Segmentation:** Redesigned the IP addressing scheme into isolated subnets, separating administrative servers, general employee workstations, and guest/wireless access points to shrink broadcast domains and block lateral attacker movement.
* **Traffic Prioritisation (QoS):** Implemented **Quality of Service (QoS)** protocols to guarantee bandwidth for business-critical operations and prevent congestion.
* **Proactive Monitoring:** Established continuous network telemetry and periodic performance reviews to isolate bottlenecks early.

---

## Technical Security Controls
* **Perimeter & Internal Firewalls:** Configured stateful firewall rulesets governing inbound and outbound traffic flows across departmental boundaries.
* **Intrusion Detection & Prevention (IDPS):** Deployed inline **IDPS** sensors to inspect packet payloads, detect policy violations, and block active exploits in real time.
* **Encrypted Remote Access (VPN):** Designed secure **Virtual Private Network (VPN)** tunnels to protect data in transit for remote staff.

---

## Security Policy & Governance Amendments
Rather than discarding operational workflows, targeted amendments were integrated into the organisation's existing security policy:
1. **Identity & Access Management:** Enforced the **Principle of Least Privilege (PoLP)** alongside mandatory **Two-Factor Authentication (2FA)** and periodic privilege reviews.
2. **Cryptographic Standards:** Mandated encryption for both data at rest and data in transit, supported by scheduled encryption key rotation procedures.
3. **Incident Response & Awareness:** Updated breach containment and stakeholder notification protocols, paired with recurring employee training against phishing and social engineering.
