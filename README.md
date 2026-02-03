# 🔐 API Security Risk Analysis

## 📌 Project Overview

This project presents an **API Security Risk Analysis** performed as part of an internship task. The objective is to identify common security vulnerabilities in a public demo API using ethical testing methods and to document the findings in a professional manner.

The analysis focuses on authentication, authorization, and data exposure risks commonly found in REST APIs.

---

## 🧪 API Tested

* **API Name:** JSONPlaceholder
* **Base URL:** [https://jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com)
* **Tested Endpoint:** `/users`
* **HTTP Method:** GET
* **Authentication Required:** No (Demo API)

---

## 🛠 Tools Used

* Postman
* Browser Developer Tools
* Public Demo API (JSONPlaceholder)
* MS Word / Google Docs
* GitHub

---

## 🔍 Security Issues Identified

### 1️⃣ Unauthenticated Access

* The API allows access to user data without requiring authentication.

### 2️⃣ Excessive Data Exposure

* Sensitive information such as email, phone number, address, and geo-location is exposed in API responses.

### 3️⃣ Broken Object Level Authorization (BOLA)

* User data can be accessed by modifying user IDs in the endpoint without authorization checks.

---

## 📂 Project Structure

```
API-Security-Risk-Analysis/
│
├── screenshots/
│   ├── 01_unauthenticated_access_users.png
│   ├── 02_broken_authorization_user_1.png
│   └── 03_broken_authorization_user_2.png
│
├── API_Security_Risk_Analysis_Report.pdf
└── README.md
```

---

## 📄 Report

A detailed report explaining the identified risks, their impact, and remediation suggestions is available in:

📘 **API_Security_Risk_Analysis_Report.pdf**

---

## ⚠️ Disclaimer

This project was conducted strictly for **educational and internship purposes** using a public demo API. No real-world systems were harmed or tested.

---

## ✅ Conclusion

This project demonstrates practical API security testing skills, including risk identification, impact analysis, and documentation. The findings highlight the importance of implementing proper authentication, authorization, and data protection mechanisms in APIs.

---

**Author:** *(Thanvesh Reddy)*
**Internship:** *(FutureInten)*
**Institution:** *(SRM University)*
