# Medical Insurance SQL Analysis (PostgreSQL & PowerBi)

## Project Overview

This project focuses on analyzing a medical insurance dataset using PostgreSQL.
The objective is to extract meaningful insights related to insurance charges, patient demographics, and risk factors such as smoking, BMI, and region.

---

## Objectives

* Analyze insurance charges across different patient groups
* Compare smokers vs non-smokers costs
* Identify regional trends in insurance expenses
* Perform advanced SQL operations like ranking, window functions, and CTEs
* Derive business insights from raw healthcare data

---

## Tools & Technologies

* PostgreSQL
* SQL (Joins, Aggregations, Window Functions, CTEs)
* PowerBi for Dashboard Analysis

---

## Dataset Description

The dataset contains information about patients and their insurance details.

### Key Columns:

* `age` → Age of the patient
* `sex` → Gender
* `bmi` → Body Mass Index
* `children` → Number of dependents
* `smoker` → Smoking status (yes/no)
* `region` → Residential region
* `expenses` *(or equivalent column)* → Insurance charges

---

## Key SQL Analysis Performed

### 1. Basic Analysis

* Total number of patients
* Average insurance charges
* Distribution of smokers vs non-smokers

### 2. Aggregation & Grouping

* Average charges by region
* Average charges by gender
* Charges comparison based on children

### 3. Advanced SQL Queries

* Ranking patients by insurance charges
* Top 3 highest charges per region
* Running total of charges by age
* Subqueries for above-average analysis

### 4. Business Insights Queries

* Regions where smokers pay more than non-smokers
* Impact of children on insurance charges
* Identification of high-risk patients

---

## Key Insights

* Smokers tend to have significantly higher insurance charges compared to non-smokers
* Certain regions show higher average insurance costs
* Patients with higher BMI and smoking habits fall into high-cost categories
* Insurance charges generally increase with age

---

## 👤 Author

Balsuman Barnwal

---

## ⭐ If you found this project useful

Feel free to star the repository and share your feedback!
