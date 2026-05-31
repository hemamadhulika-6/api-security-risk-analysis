# api-security-risk-analysis
# Modern SaaS API Security Risk Analysis 🛡️

## Project Overview
This repository contains a professional, read-only API Security Risk Analysis conducted on a target SaaS-style test environment. This audit applies the **OWASP API Security Top 10** methodologies to identify hidden vulnerabilities, assess business impacts, and provide engineering teams with actionable remediation blueprints.

---

## 🛠️ Tools Used
* **Postman:** For crafting API requests, parsing responses, and checking HTTP header properties.
* **Markdown/PDF:** For drafting formal, executive-ready security documentation.
* **GitHub:** For version control and artifact deployment.

---

## 🔍 Scope & Methodology
* **Scope:** Limited exclusively to public test endpoints (`https://reqres.in/api/`).
* **Approach:** **Ethical & Read-Only**. No exploit payloads were executed, no fuzzing tools were run against production assets, and no denial-of-service states were induced.
* **Framework:** Aligned directly with the **OWASP API Security Top 10 (2023)** standards.

---

## 📁 Repository Structure
```text
├── README.md                         
├── API_Security_Risk_Report.pdf       
└── screenshots/                       
    ├── get_users_endpoint.png
    └── post_login_vulnerability.png
