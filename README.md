# 🌍 NGO Impact Analysis Dashboard (Power BI Project)

## 📘 Project Overview

This project focuses on analyzing **the impact, efficiency, and sustainability of NGO projects** across different sectors and regions.  
Using data-driven insights, the dashboard highlights how effectively NGOs utilize funding to achieve measurable social and environmental outcomes.

The dashboard was developed in **Power BI** and provides a clear, interactive view of key performance indicators (KPIs) such as funding utilization, impact scores, beneficiary reach, and sustainability index.

---

## 🎯 Objectives

- Evaluate NGO performance and project impact.
- Compare sector-wise and region-wise funding efficiency.
- Analyze trends in funding and impact over time.
- Identify high-performing NGOs and areas for improvement.
- Enable data-backed decision-making for donors and administrators.

---

## 📊 Dashboard Features

### **1️⃣ Overview Dashboard**
- Total Funding, Total Beneficiaries, Distinct NGOs, Total Projects
- Average Impact & Sustainability Index
- Sector distribution (Pie chart)
- Region-wise Impact (Map visualization)

### **2️⃣ Sector Analysis**
- Funding vs Impact Score by Sector
- Beneficiaries by Sector
- Sustainability comparison among sectors

### **3️⃣ Regional Insights**
- Funding and Impact by Region
- Funding Efficiency (Impact per Beneficiary)
- Regional Funding Map Visualization

### **4️⃣ Funding & Efficiency**
- Funding Trend (Yearly)
- Impact Trend (Yearly)
- Cost Efficiency (Impact per $1000)
- Project Duration Distribution

### **5️⃣ Sustainability Overview**
- Sustainability vs Funding Scatter Plot
- Average Sustainability by Sector
- Project Duration Analysis

---

## ⚙️ Tech Stack

| Component | Tool / Technology |
|------------|------------------|
| **Data Analysis & Visualization** | Power BI |
| **Data Source** | CSV / Excel / Kaggle Dataset |
| **Data Cleaning** | Power Query (M Language) |
| **KPIs & Metrics** | DAX (Data Analysis Expressions) |
| **Presentation** | PowerPoint (PPT) |
| **Deployment** | Power BI Service (Cloud-based) |

---

## 🧠 Data Description

| Column | Description |
|---------|-------------|
| NGO_Name | Name of the NGO |
| Project_Name | Title of the project |
| Sector | Focus area (Health, Education, Environment, etc.) |
| Region | Geographic area of operation |
| Country | Country of implementation |
| Funding_Amount | Total funding received |
| Beneficiaries | Number of people impacted |
| Start_Date / End_Date | Project timeline |
| Impact_Score | Quantitative measure of success |
| Sustainability_Index | Long-term viability indicator |

---

## 🧮 Key Metrics (DAX Measures)

- **Total Funding** = SUM(Funding_Amount)  
- **Total Beneficiaries** = SUM(Beneficiaries)  
- **Average Impact Score** = AVERAGE(Impact_Score)  
- **Average Sustainability Index** = AVERAGE(Sustainability_Index)  
- **Funding per Beneficiary** = Total Funding / Total Beneficiaries  
- **Impact per 1000 Funding** = Average Impact Score / (Total Funding / 1000)

---

## 🪄 Insights Gained

- The **Education and Health sectors** show the highest impact efficiency per funding unit.  
- Regions with **longer project durations** tend to have higher sustainability.  
- **Funding allocation** is uneven across sectors — suggesting opportunities for optimization.  
- Projects with **balanced funding and high sustainability** have better long-term results.

---

## 📤 Deliverables

- ✅ Power BI Dashboard (`.pbix`)
- ✅ Data Processing Script (Power Query + DAX)
- ✅ PowerPoint Presentation summarizing insights
- ✅ Dataset (CSV/Excel)
- ✅ README Documentation

---

## 🚀 How to Use

1. Open Power BI Desktop.
2. Import dataset (`ngo_data.csv` or Excel file).
3. Load Power Query transformations.
4. Create DAX measures as listed above.
5. Build visuals following the layout in this README.
6. Publish the dashboard to Power BI Service.
7. Export dashboard insights into PowerPoint.

---

## 🌐 Future Enhancements

- Automate data refresh using Power BI Gateway.
- Integrate live data from NGO APIs or Google Sheets.
- Add predictive models (e.g., regression on impact score).
- Enable donor-specific dashboards and funding filters.

---

## 🧑‍💼 Author

**Project Title:** NGO Impact Analysis Dashboard  
**Developed by:** Sneha Biswas  
**Tools Used:** Power BI, DAX, Power Query, Excel  
**Purpose:** To measure and visualize NGO project performance and social impact.  

---

### ⭐ If you like this project, don’t forget to star the repository!

