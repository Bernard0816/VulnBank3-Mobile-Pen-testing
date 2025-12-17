# VulnBank3-Mobile-Pen-testing
Android Mobile Penetration Test using reverse engineering, OWASP MASVS, CVSS scoring, and professional reporting.

​You​
#  VulnBank3 Android Mobile Application – Penetration Test

## 🔐 Project Overview
This repository documents a **mobile application penetration test** conducted against the **VulnBank 3.0 Android APK** using static analysis and reverse-engineering techniques.

The assessment focused exclusively on **client-side security weaknesses** that could be exploited by attackers without server access.

📅 Date: December 2025
👤 Author: Bernard Mbata
📌 Role: Lead Penetration Tester

---

## 🎯 Assessment Objectives
- Identify hardcoded secrets embedded in the APK
- Analyze authentication and JWT implementation
- Review local storage mechanisms (SharedPreferences)
- Detect insecure configuration and debug artifacts
- Map findings to **OWASP Mobile Top 10** and **CVSS v3**

---

## 🛠 Tools & Techniques Used
- `apktool`
- `jadx-gui`
- Static reverse engineering
- JWT inspection via `jwt.io`
- AndroidManifest and SharedPreferences review

---

## 🚨 Key Findings Summary

| ID | Vulnerability | Severity | CVSS |
|----|--------------|----------|------|
| EPT-001 | Hardcoded Admin JWT Token | Critical | 9.8 |
| EPT-002 | Hardcoded API Key in APK | Critical | 9.5 |
| EPT-003 | Debug API Endpoint Exposed | High | 8.5 |
| EPT-004 | Plaintext Credentials & Balance | High | 8.5 |
| EPT-005 | Weak JWT Validation | High | 8.7 |
| EPT-006 | Insecure SharedPreferences Usage | Medium | 6.5 |

---

## 📄 Full Technical Report
The complete penetration testing report is available here:

📘 **[VulnBank3 Mobile Penetration Test Report](report/VulnBank3_Mobile_Penetration_Test_Report.pdf)**

The report includes:
- Executive summary
- Methodology
- CVSS scoring
- Detailed findings with screenshots
- Impact analysis
- Remediation guidance

---

## 🧠 Key Skills Demonstrated
- Mobile application security (Android)
- Reverse engineering
- OWASP MASVS & MSTG alignment
- JWT security analysis
- Secure storage assessment
- Professional penetration testing reporting

---

## ⚠️ Disclaimer
This project was conducted **strictly for educational and demonstration purposes**.
No real production systems were harmed or accessed.

See [`disclaimer.md`](disclaimer.md) for full details.
## ⚠️ Legal & Ethical Disclaimer

This repository and its contents are provided **for educational and portfolio demonstration purposes only**.

- The application tested (VulnBank3.apk) is a deliberately vulnerable test application.
- No real banking systems, customer data, or production environments were targeted.
- All findings were obtained through static analysis and controlled testing.
- This work complies with ethical hacking standards and responsible disclosure practices.

Unauthorized testing of systems without explicit permission is illegal.
