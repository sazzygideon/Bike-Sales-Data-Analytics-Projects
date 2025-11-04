# Bike-Sales-Data-Analytics-Projects
This project demonstrates a complete data analytics workflow using Excel. It covers data cleaning, data transformation, exploratory analysis, and dashboard visualization to uncover insights about customer demographics and bike purchasing behavior. The final dashboard provides an interactive view of trends and patterns.

---

## 📌 Project Overview
This project focuses on analyzing customer data to understand factors influencing bike purchases. It involves:
- **Data Cleaning**: Standardizing inconsistent entries and creating new derived columns.
- **Data Analysis**: Using pivot tables to summarize trends and relationships.
- **Dashboard Visualization**: Building an interactive dashboard for quick insights.

---

## 🛠 Steps Performed

### 1️⃣ Data Cleaning
- Corrected inconsistent values in columns such as:
  - **Marital Status**: Converted abbreviations (e.g., `M` → `Married`, `S` → `Single`).
  - **Gender**: Standardized to `Male` and `Female`.
- Created **Age Brackets**:
  - Adolescents, Middle Age, Old Age based on age ranges.
- Normalized commute distance categories:
  - `0-1 Miles`, `1-2 Miles`, `2-5 Miles`, `5-10 Miles`, `More than 10 miles`.
- Removed duplicates and ensured uniform formatting across all fields.

---

### 2️⃣ Data Analysis
- Built **Pivot Tables** to summarize:
  - **Average Income** by Gender and Purchase Status.
  - **Purchase Counts** by Commute Distance.
  - **Purchase Distribution** across Age Brackets.
- Derived insights such as:
  - Middle-aged customers are the largest bike buyers.
  - Shorter commute distances correlate with higher purchase rates.
  - Higher income groups tend to purchase more bikes.

---

### 3️⃣ Dashboard Visualization
- Designed an **interactive dashboard** in Excel featuring:
  - Slicers for filtering by Gender, Region, and Age Bracket.
  - Charts showing purchase trends by distance and age group.
  - KPIs summarizing total purchases and income averages.

---


## 📂 Files Included
- **Excel Project Dataset.xlsx**
  - `bike_buyers`: Raw dataset.
  - `Working Sheet`: Cleaned and transformed data.
  - `Pivot Table`: Summary tables for analysis.
  - `Dashboard`: Interactive visualization.

---

## 🔍 Key Insights
- Customers with **short commutes (0-1 miles)** are more likely to purchase bikes.
- **Middle-aged individuals** dominate bike purchases compared to adolescents and older age groups.
- **Income level** positively influences purchase decisions.

---

## ✅ How to Use
1. Download the Excel file from this repository.
2. Open `Excel Project Dataset.xlsx` in **Excel 2010 or later** (required for slicers).
3. Navigate through:
   - **Working Sheet** for cleaned data.
   - **Pivot Table** for summarized insights.
   - **Dashboard** for interactive analysis.

---

## 📈 Future Enhancements
- Export cleaned data for predictive modeling in Python or R.
- Build advanced dashboards using **Power BI** or **Tableau**.
- Apply machine learning to predict purchase likelihood.

---

## 👤 Author
**IGBINAZAKA, OSAZEE**  
Student | Data Analyst

---

## 📜 License
This project is licensed under the MIT License.
