# Healthcare Data Analysis Dashboard

##  Problem Statement
Hospitals often manage large volumes of patient records, but turning this raw data into actionable insights is a challenge.  
This project utilizes **Excel (VLOOKUP, HLOOKUP, SUMIF, PivotTables)** to analyze data from 250 patients, focusing on risk levels, treatment revenue, and diagnosis trends.  
The goal is to develop an interactive dashboard that enables healthcare administrators to make informed, data-driven decisions.

---

## 🔍 Analysis Performed
1. **Data Cleaning & Preparation**  
   - Standardized patient IDs, diagnoses, and treatment codes.  
   - Defined **High-Risk** patients based on diagnosis severity.  
   - Created supporting tables (Treatment Ratings, Costs) for lookups.

2. **Key Formulas Applied**  
   - **VLOOKUP** = Patient diagnosis, treatment costs, severity classification.  
   - **HLOOKUP** = Treatment ratings from horizontal tables.  
   - **SUMIF** = Revenue by diagnosis.  
   - **PivotTables** = Top diagnoses by revenue, monthly patient admissions.  

3. **KPIs Built**
   - **% of High-Risk Patients** = (High Risk ÷ Total Patients).  
   - **Average Treatment Score** from HLOOKUP table.  
   - **Total Revenue** from all diagnoses.  


![Health Care Analysis Dashboard](https://github.com/user-attachments/assets/743209ed-7256-4b48-99f2-0f7693eab2a0)

---

## 📊 Insights
- **High-Risk Patients:**  
  Out of **250 patients**, **68 were classified as High-Risk (27%)**.  
  This shows that more than 1 in 4 patients require extra monitoring, suggesting a need for **dedicated ICU resources** and **proactive care planning**.

- **Top 3 Diagnoses by Revenue:**  
  Using **SUMIF + Pivot**, revenue distribution revealed:  
  1. **Tuberculosis** – £3,250,000 (34% of total revenue).  
  2. **Hypertension** – £2,100,000 (22% of total revenue).  
  3. **Diabetes** – £1,750,000 (18% of total revenue).  
  These three conditions together accounted for **74% of hospital revenue**, indicating their **financial importance** in resource allocation.  

- **Treatment Effectiveness Scores:**  
  Average treatment score (from HLOOKUP): **3.9 / 5.0**.  
  - Best-performing treatment: **Insulin Therapy (4.5/5)**.  
  - Lowest-performing treatment: **Antibiotics for Pneumonia (3.2/5)**.  
  This highlights **areas of clinical strength** and where improvements are needed.

- **Admission Trends:**  
  - **Highest admissions:** June (**42 patients**, 17%).  
  - **Lowest admissions:** February (**12 patients**, 5%).  
  This suggests a **seasonal pattern** in patient inflow, which could guide staffing schedules and inventory planning.

- **Revenue Per Patient:**  
  Total hospital revenue = **£9,600,000**.  
  Average revenue per patient = **£38,400**.  
  High-Risk patients contributed **60% of total revenue**, confirming that **critical cases drive profitability** but also require **higher resource investment**.

---

##  Summary
Final Thoughts

This analysis demonstrates the power of combining VLOOKUP, HLOOKUP, and advanced Excel functions to transform scattered healthcare records into actionable insights. By cleaning, organizing, and structuring the dataset of 250 patients, we were able to create a comprehensive view of both financial performance and patient outcomes.

Key findings revealed that 22% of patients were classified as high-risk, highlighting the importance of targeted medical interventions. Revenue distribution showed that just three diagnoses contributed to over 55% of total hospital revenue, emphasising the need for resource allocation toward these high-impact cases. Additionally, treatment ratings provided a quality benchmark that can help managers quickly assess where improvements in care delivery are needed.

The dashboards and calculations built in Excel demonstrate how healthcare administrators can move from raw data to strategic insights with relatively simple tools. While this project was carried out on a sample dataset, it mirrors real-world challenges in hospital data management—helping managers answer questions like:

- Where should resources be prioritized?

- Which patient groups are most vulnerable?

- How do treatments correlate with both risk and revenue?

Ultimately, this project proves that Excel is more than a spreadsheet tool—it is a decision-making engine when combined with the right formulas and analytical approach. For hospitals and healthcare providers, this type of data-driven insight can improve patient care, optimize resource allocation, and strengthen financial performance.
 **Next Steps:**  
- Replace **VLOOKUP/HLOOKUP** with **INDEX+MATCH** for more flexibility.  
- Add **conditional formatting** to highlight high-risk patients.  
- Integrate external datasets (e.g., seasonal illness data) for predictive modeling.  

---

 **Tools Used:** Microsoft Excel (Formulas, PivotTables, Dashboard Design)  
 **Dataset Size:** 250 Patients  
 **Skills Practiced:** Data Cleaning, VLOOKUP, HLOOKUP, SUMIF, PivotTables, Dashboard Storytelling
