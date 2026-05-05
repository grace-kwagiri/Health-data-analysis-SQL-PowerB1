# 🏥 Healthcare Data Analysis (SQL + Power BI)

## 📊 Overview

This project analyzes a healthcare relational database to generate insights across patient demographics, appointments, billing, diagnoses, and medications.

Using SQL, I performed end-to-end data analysis to uncover trends that support operational decision-making, financial optimization, and improved patient care.

---

## 📌 Problem Statement

Healthcare providers generate large volumes of data across multiple systems, but often lack structured analysis to extract actionable insights.

This project addresses that gap by analyzing patient, appointment, billing, and clinical data to identify trends, inefficiencies, and opportunities for improvement.

---

## 🗂️ Dataset Description

- Relational database with **6 interconnected tables**:
  - Patients  
  - Appointments  
  - Billing  
  - Doctors  
  - Medications  
  - Diagnoses  

- Total of **17 analytical queries** developed

---

## 🛠️ Tools & Technologies

- **SQL** (PostgreSQL/MySQL)
- Data Analysis & Query Optimization
- Relational Database Design
- Power BI (for visualization – optional if you add dashboard)

---

## 🔍 Key Analysis Areas

### 👤 Patient-Level Insights
- Identified high-billing patients using aggregate queries  
- Flagged patients with **above-average healthcare costs**  
- Detected patients with **low insurance coverage (<70%)**  

---

### 📅 Appointment & Scheduling Analysis
- Analyzed **monthly appointment trends (Feb 2024)**  
- Identified **peak appointment days** using date functions  
- Calculated **doctor-level no-show rates using CTEs**  
- Retrieved most recent appointment per patient  

---

### 🩺 Clinical Insights
- Identified **most common diagnosis** across patients  
- Detected **multi-diagnosis patients (complex cases)**  
- Analyzed **hypertension prevalence by age group**  
- Identified diabetic patients and tracked medication renewal patterns  

---

### 👨‍⚕️ Doctor Performance & Revenue
- Ranked doctors by **total revenue generated** using window functions  
- Measured **completed appointments per doctor**  
- Identified **highest-performing clinic locations**  

---

### 💊 Medication Analysis
- Filtered high-dosage medications (>50mg) using data cleaning techniques  
- Analyzed **medication distribution across patients**  

---

## ⚙️ SQL Techniques Used

- **JOINs** (multi-table relational queries)  
- **Aggregate Functions:** SUM, COUNT, AVG, MAX  
- **Window Functions:** `RANK()` for performance analysis  
- **Common Table Expressions (CTEs)** for complex query structuring  
- **Subqueries** for dynamic filtering  
- **Date Functions:** EXTRACT, TO_CHAR  
- **Data Cleaning:** REPLACE + CAST  

---

## 📈 Key Insights

- A subset of patients contributes disproportionately to total billing (financial outliers)  
- Some patients receive **low insurance coverage**, indicating potential financial risk  
- Appointment demand varies significantly by **day of the week**, impacting staffing needs  
- Certain doctors demonstrate **lower no-show rates**, suggesting more effective scheduling practices  
- Chronic conditions like **hypertension and diabetes** show clear demographic patterns  
- Revenue generation is uneven across doctors and clinic locations  

---

## 🚀 Business Impact

This analysis can help healthcare providers:

- Improve **resource allocation and staffing decisions**  
- Identify **high-risk and high-cost patients**  
- Optimize **appointment scheduling systems**  
- Enhance **insurance and billing strategies**  
- Support **data-driven clinical decision-making**  

---

## 🤝 Author

**Grace Kwagiri**  
Junior Data Analyst | Python • SQL • Business Intelligence  

