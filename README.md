# 📌 Samfosterbrown API Testing

## 📖 Project Overview
This repository contains the API testing workflow for the **Samfosterbrown** project.  
The API endpoints were tested using **Postman** and automated with **Newman**.  
As an **SQA Engineer**, I ensured that each endpoint was validated against functional, negative, and boundary scenarios.  

---

## ✅ Tools & Frameworks Used
- **Postman** – Manual API test execution  
- **Newman** – Automated CLI-based test execution  
- **Google Sheets** – Manual reporting and test tracking  
- **Newman HTML Extra Report** – Automated report generation  
- **Figma** – UI/UX reference for validation  

---

## 📊 Test Reports
### 🔹 Google Sheet Report  
The detailed manual test cases and results are documented here:  
👉 [Google Sheet Report](https://docs.google.com/spreadsheets/d/1eae_maGFAWWkxLleG1aCpVqaWMzCBtvuS1MBhQ3kbuI/edit?usp=sharing)

The test case report includes the following columns:
- TestCase ID  
- Module / Feature / Folder  
- Request Name  
- Endpoint  
- Testing Type  
- HTTP Method  
- Status Code  
- Issue Type  
- Description  
- Expected Result  
- Actual Result  
- Status  
- Attachments  
- Remarks  
- Developer’s Comments  
- Solved Attachments  
- Re-testing  
- Date  

---

### 🔹 Newman HTML Report  
Automated API test execution report was generated using **Newman HTML Extra**.  
The report includes:
- Execution summary  
- Pass/Fail counts  
- Assertion details  
- Response time stats  

> 📁 The HTML report file is available in this repository under `/reports/newman/`.

---

## 🎨 Figma Reference
The Figma design for frontend validation is available here:  
👉 [Figma Link](https://www.figma.com/design/8TNjGqKs6NKL9dEoc2IfQ0/Samfosterbrown-%7C%7C-Swiftech-%7C%7C-FO71AB7CA9781?node-id=0-1&p=f&t=IUO2w4r9rBqlNnGA-0)

---

## 🚀 How to Run API Tests
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-repo>/samfosterbrown-api-testing.git
   cd samfosterbrown-api-testing
2. Install Newman (if not installed)
   ```bash
   npm install -g newman newman-reporter-htmlextra
3. Run the Postman collection with HTML report generation
   ```bash
   newman run Samfosterbrown.postman_collection.json -e Samfosterbrown.postman_environment.json -r htmlextra --reporter-htmlextra-export reports/newman/Samfosterbrown_Report.html
---
## 📌 Summary
- API endpoints were successfully tested with Postman.
- Test results documented in Google Sheets
- Automated runs validated via Newman, with detailed HTML Extra Report.
- Figma design reference cross-checked to align API with frontend requirements.
---
## 👨‍💻 Author: 
 Md Abdur Rahaman Tutul
📌 Role: Software Quality Assurance (SQA) Engineer
📅 Date: October 2025

