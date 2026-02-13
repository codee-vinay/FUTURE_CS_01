# 🔐 Task 1 – Vulnerability Assessment Report (Read-Only Scope)

This folder contains my submission for **Task 1** of the **Future Interns Cyber Security Internship**.  
The objective of this task is to perform a **passive and ethical vulnerability assessment** on a public website and present the findings in a professional report.

---

## 🎯 Task Objective

- Analyze a public website for common security weaknesses  
- Perform only **read-only / passive** checks  
- Identify and classify risks (Low / Medium / High)  
- Explain issues in simple, business-friendly language  
- Suggest practical remediation steps  
- Document everything in a professional vulnerability assessment report  

---

## 🌐 Target Website

- **Website Tested:** http://testphp.vulnweb.com  
- **Type:** Public test website  
- **Scope:** Read-only / Passive analysis  

> ⚠️ No exploitation, brute-force, or harmful actions were performed.

---

## 🛠️ Tools Used

- **Nmap** – For basic port and service scanning  
- **Browser Developer Tools** – For inspecting HTTP headers  
- **OWASP ZAP (Passive Scan)** – For identifying security misconfigurations  
- **Google Docs / Word** – For report writing and formatting  

---

## 📄 Contents of This Folder

- 📘 `Vulnerability_Assessment_Report.pdf` – Final report  
- 📁 `screenshots/` – Evidence screenshots including:
  - Nmap scan results  
  - Browser header inspection  
  - OWASP ZAP alerts  
- 📄 `README.md` – This file explaining Task 1  

---

## 🧪 Summary of Findings

Some of the key issues identified during the assessment:

- Website uses HTTP instead of HTTPS (Medium Risk)  
- Outdated PHP Version (High Risk)  
- Content Security Policy (CSP) Header Not Set (Medium Risk)  
- Missing Anti-Clickjacking Header (Medium Risk)  
- Absence of Anti-CSRF Tokens (Medium Risk)  
- Server Leaks Information via Headers (Low Risk)  

Detailed explanations, risks, and remediation steps are available in the report.

---

## ⚖️ Ethics & Scope

- Only **publicly accessible pages** were tested  
- Only **passive scanning and configuration checks** were performed  
- No login bypass, exploitation, or attacks were attempted  
- This task was completed strictly for **learning and educational purposes**

---

## 👤 Author

- **Name:** Veera Venkata Vinay Yamala
- **Internship:** Future Interns – Cyber Security  
- **Task:** Task 1 – Vulnerability Assessment Report

---

## 📢 Note

This project is part of an educational internship program and is intended to demonstrate:
- Basic security assessment skills  
- Ethical testing practices  
- Proper documentation and reporting  

