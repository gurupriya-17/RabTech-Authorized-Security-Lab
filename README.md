# 🔐 Authorized Security Lab – Asset Inventory & Threat Model

## RabTech Academy Cybersecurity Internship – Task 2

### 📌 Project Overview

This project focuses on preparing an authorized cybersecurity lab environment for security assessment. It identifies permitted assets, analyzes possible security threats and defines safe testing boundaries.

The project uses asset inventory, Data Flow Diagram (DFD), STRIDE threat modelling and Rules of Engagement (ROE) to establish a structured security assessment framework.

### 🎯 Objectives

- Create an isolated cybersecurity training lab.
- Identify authorized systems and their attack surfaces.
- Understand data flow and trust boundaries.
- Identify security threats using STRIDE methodology.
- Recommend security controls and mitigations.
- Establish rules for safe and responsible security testing.

### 🖥️ Authorized Lab Assets

| Asset ID | Asset Name | Environment | Address |
|---|---|---|---|
| LAB-01 | Local Training Web App | Isolated localhost | 127.0.0.1:8080 |
| LAB-02 | Deliberately Vulnerable VM | Private host-only network | 192.168.56.20 |

### 📂 Project Structure

```text
RabTech-Authorized-Security-Lab/
│
├── 01-Asset-Inventory/
│   └── authorized-lab-assets.csv
│
├── 02-STRIDE-Threat-Model/
│   └── STRIDE-Threat-Model.pdf
│
├── 03-Data-Flow-Diagram/
│   └── Data-Flow-Diagram.png
│
├── 04-Rules-of-Engagement/
│   └── Rules-of-Engagement.md
│
├── 05-Final-Report/
│   └── Final-Report.pdf
│
└── README.md
```

### 🛡️ STRIDE Threat Model

The STRIDE methodology identifies six major security threats:

1. **Spoofing** – Identity impersonation.
2. **Tampering** – Unauthorized data modification.
3. **Repudiation** – Denying performed actions.
4. **Information Disclosure** – Exposure of confidential data.
5. **Denial of Service** – Disruption of service availability.
6. **Elevation of Privilege** – Gaining unauthorized permissions.

### 📊 Expected Security Benefits

- Improved understanding of security boundaries.
- Identification of potential vulnerabilities.
- Better awareness of security risks.
- Improved protection of sensitive information.
- Responsible and controlled security assessment.

### ⚖️ Rules of Engagement

All assessment activities must follow these rules:

- Obtain written authorization before testing.
- Test only explicitly permitted assets.
- Avoid destructive activities and denial-of-service testing.
- Do not access third-party systems.
- Protect and redact collected evidence.
- Stop testing if unexpected issues occur.

### 🛠️ Tools and Technologies

- VirtualBox
- OWASP Juice Shop (optional local training application)
- draw.io
- LibreOffice Writer
- GitHub

### 📌 Project Outcome

This project provides a structured foundation for authorized security assessment through asset identification, data flow analysis, threat modelling and security testing guidelines.

### 👨‍💻 Author

**Name:** [Your Name]

**Internship:** RabTech Academy

**Domain:** Cybersecurity

**Task:** Task 2 – Legal Scope, Asset Inventory & Threat Model

---

**Disclaimer:** This repository is intended for educational and authorized cybersecurity assessment purposes only. Testing must be performed exclusively on approved lab assets.
