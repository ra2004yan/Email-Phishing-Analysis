# Email Phishing Analysis – Chase Bank Impersonation

## Overview
This repository contains the analysis of a phishing email impersonating **Chase Bank**, attempting to trick the recipient into reactivating their account due to a supposed temporary suspension.

---

## Email Details
- **Sender IP:** 185.70.40.140  
- **Resolved Host:** [185-70-40-140.protonmail.ch](http://185-70-40-140.protonmail.ch/)  
- **Message-ID:** `<i7g9MMh5NtErtaOzQZEp3D-i-u3FWwdo0wY5mhD8Q1vIvv1yeLj-jMWPAn-HP3FugKsucesWSubO0Vns8GRFYG0aH4MyU2paqP6yUnRcgaU=@protonmail.com>`  
- **URL:** [Suspicious Link](https://dsgo.to/CQECQECnpqY3NDSGtODt9ft2qtxzcXGUveTV5fRYmtYAZsQCnpqY3NDSGtODt9ft2qtxzcXGUveTV5fRYmtYAZsQCQECnpqY3NDSGtODt9ft2qtxzcXGUveTV5fRYmtYAZsQ)  

---

## Analysis

**Sender Analysis:**  
The email claims to be from Chase Bank, but the sending domain is unrelated. The return-path shows it originated from **proton.me**, which is not affiliated with Chase Bank. The IP address resolves to ProtonMail infrastructure in Switzerland.

**URL Analysis:**  
The embedded URL was scanned using **URLscan** and **VirusTotal**, appearing clean at the time of analysis. However, phishing campaigns often use benign URLs initially, later redirecting them to malicious sites.

---

## Verdict
The email is confirmed as a **phishing attempt** designed to harvest user login credentials via impersonation and social engineering.

---

## Defensive Actions
- **Do not click** on any embedded links.
- **Delete** the email immediately.
- Report to the relevant security or IT department.

---

**Disclaimer:** This analysis is for educational and cybersecurity research purposes only.
