# 👩🏽‍💼 Palmora Group HR Gender Metrics Analysis

This project provides a comprehensive HR analytics report for **Palmora Group**, a manufacturing firm in Nigeria, following concerns over gender inequality across regions and departments. The CEO, Mr. Ayodeji Chukwuma, mandated this initiative after negative publicity. This work was led by the CHRO, Mr. Yunus Shofoluwe, with the goal of supporting equity-focused decisions.

---

## 📊 Project Overview

- **Goal:** Identify gender-based disparities in pay, ratings, and headcount across departments and regions
- **Approach:** Power Query for data cleaning and transformation, Power BI for modeling and visualization
- **Datasets:**
  - `emp-data.csv`: Employee demographic and salary data
  - `Bonus Rules.csv`: Bonus allocation matrix by department and performance

---

## 🔍 Key Analysis Tasks

### 1. **Data Cleaning (Power Query)**
- Filled missing genders as **"Undisclosed"**
- Removed records with NULL departments and inactive employees
- Standardized data types for consistency
- Transformed bonus rules using **unpivoting**

### 2. **Feature Engineering**
- Created **Region** column from city locations (North, West, South)
- Converted ratings to numeric scale
- Calculated **Bonus Amount** and **Total Pay (Salary + Bonus)**

### 3. **Data Modeling (Power BI)**
- Merged bonus rules with employee data
- Built measures using DAX for:
  - Employees below minimum wage
  - Region/department salary totals
  - Total company payout

---

## 📌 Dashboard Highlights

### 👨‍👩‍👧 Gender Distribution
- **875 Employees**
- **49.3% Male**, **46.4% Female**, **4.3% Undisclosed**
- Most balanced region: **West (Lagos)**
- Male-dominated departments: **Product Management**, **Accounting**, **Legal**, and **Marketing**

### 📉 Gender Pay Gap
- **Average Male Salary:** $74,460.67  
- **Average Female Salary:** $72,246.21  
- **Lagos:** Largest gap  
- **Departments with gap:** Engineering, Services

### 💼 Ratings Insights
- **Average Male Rating:** ~3.22  
- **Average Female Rating:** ~3.05  
- Slight bias suggests review of performance systems

### ⚖️ Minimum Wage Compliance
- **607 Employees** earn below $90,000  
- **Non-compliance** requires urgent salary adjustment

### 💰 Salary & Bonus Breakdown
- **Highest Bonus Payout Region:** West  
- **Highest Payout Departments:** Engineering, Sales  
- **Total Company Payout:** $66.64 million

---

## 🎯 Actionable Recommendations

| Recommendation | Owner | Timeline |
|----------------|-------|----------|
| ✅ Adjust salaries for underpaid employees | CHRO & Finance | 1–2 weeks |
| 📊 Conduct pay equity audit | HR Analytics | 1–2 months |
| 🧠 Bias training & rating system review | HR & L&D | 1 month (start) |
| 🧲 Targeted recruitment for gender diversity | Talent & Dept. Heads | 2–3 months |
| 📢 Promote salary transparency | HR Department | 3–6 months |
| 📈 Launch HR metrics dashboard | HR Analytics | Quarterly, starting next quarter |

---

## 📌 Tools Used

- **Power Query (Excel/Power BI)** – cleaning & transformation  
- **Power BI** – DAX measures & visualizations  
- **Excel (Bonus Rules)** – rule definition  

---

## 📬 Contact

**Bamidele Ogunsanya**  
📧 Email: [bamideleogunsanya33@gmail.com]
