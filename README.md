# 🔍 Vulnerability Assessment Report (Read-Only Audit)

## 📖 About the Project
This project is a professional vulnerability assessment performed on a public website using a **read-only approach**.

The goal is to identify common security weaknesses and present them in a **business-friendly format**, without exploiting any vulnerabilities.

---

## 🎯 Objective
- Analyze website security posture
- Identify potential risks
- Classify vulnerabilities (Low / Medium / High)
- Provide clear remediation steps

---

## 🌐 Target Website
http://demo.testfire.net  
(Note: Public/demo website used for educational purposes)

---

## 📌 Scope
- ✔ Read-only analysis only
- ✔ No exploitation performed
- ✔ No intrusive scanning

---

## 🛠️ Tools Used
- Nmap (Port Scanning)
- OWASP ZAP (Passive Scan)
- Browser DevTools (Headers & Cookies Analysis)

---

## 🔍 Assessment Methodology

### 1. Reconnaissance
- Identified target website
- Gathered basic information

### 2. Port & Service Analysis
- Used Nmap to detect open ports and services

### 3. Passive Vulnerability Scanning
- Used OWASP ZAP (passive mode only)

### 4. Security Headers Review
- Checked HTTP response headers using DevTools

---

## 📊 Key Findings

| Issue | Description | Risk | Recommendation |
|------|------------|------|---------------|
| Missing Security Headers | No X-Frame-Options | Medium | Add security headers |
| Open Port | HTTP (Port 80) open | Low | Restrict or secure with HTTPS |

### 1. Open Ports
- Ports 80, 443, 8080 detected
- Risk: Medium

### 2. Missing Security Headers
- CSP, X-Frame-Options missing
- Risk: Medium

### 3. No CSRF Protection
- Risk: Medium

### 4. Cookie Security Issue
- Missing SameSite attribute
- Risk: Low

### 5. Server Information Disclosure
- Server version exposed
- Risk: Low

## 📌 Conclusion
The application contains several security misconfigurations that can be mitigated by implementing proper security practices

## 📸 Evidence
All supporting screenshots and tool outputs are available in the ![Nmap](./evidence/nmap_scan_result.png)folder.

---

## 💡 Key Takeaways
✔ Demonstrates real-world vulnerability assessment skills  
✔ Focuses on ethical and non-intrusive security testing  
✔ Presents findings in a business-friendly format  

---

## ⚠️ Disclaimer
This assessment was conducted strictly in a **read-only and ethical manner**.  
No exploitation or harmful activity was performed.  

## 💡 Skills Demonstrated

- Network Scanning
- Vulnerability Analysis
- Report Writing
- Cybersecurity Fundamentals

This project is for **educational purposes only**.

---

## 👨‍💻 Author
**Akula Lakshmi Pavan**  
Cybersecurity & AI Enthusiast 🚀
