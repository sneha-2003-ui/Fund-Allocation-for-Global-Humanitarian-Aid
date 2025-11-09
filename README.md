# 🌍 NGO Fund Allocation using Unsupervised Machine Learning

## 📘 Project Overview
HELP International is an international humanitarian NGO dedicated to eradicating poverty and improving living conditions for people in underdeveloped countries. 
After successfully raising **$10 million** through recent funding programs, the organization aims to **allocate these funds strategically and effectively** to the countries most in need of aid.

This project leverages **Unsupervised Machine Learning (Clustering)** techniques to identify and group countries based on various socio-economic and health indicators. The analysis helps decision-makers **prioritize countries** requiring immediate attention and funding.

---

## 🧠 Problem Statement
The CEO of HELP International needs to determine **which countries should receive aid** based on their overall development status.
The challenge lies in analyzing multidimensional data (economic, health, education, etc.) to find patterns without any predefined labels.

By applying clustering algorithms, the project classifies countries into different groups based on their need for financial assistance — enabling more **data-driven fund allocation decisions**.

---

## 🎯 Project Objective
- Analyze the socio-economic data of countries.
- Identify clusters of countries with similar development characteristics.
- Determine the cluster(s) representing countries most in need of aid.
- Support HELP International in effective fund allocation based on insights.

---

## 🧩 Approach

### 1️⃣ Data Understanding
- Dataset: **Country Data** from Kaggle or open international datasets.
- Features include:
  - GDP per capita
  - Health expenditure
  - Infant mortality rate
  - Literacy rate
  - Population growth
  - Life expectancy
  - Other socio-economic indicators

### 2️⃣ Data Preprocessing
- Handling missing values
- Scaling and normalization
- Exploratory Data Analysis (EDA)
  - Correlation between indicators
  - Distribution analysis
  - Outlier detection

### 3️⃣ Model Building
- **Algorithms Used:**
  - K-Means Clustering
  - Hierarchical Clustering
  - DBSCAN (for density-based grouping)

- **Evaluation Methods:**
  - Elbow Method & Silhouette Score for optimal cluster selection
  - Visualization using PCA (Principal Component Analysis) and 2D scatter plots

### 4️⃣ Insights & Interpretation
- Countries are grouped into distinct clusters based on development metrics.
- The cluster(s) with **low GDP, high infant mortality, and low life expectancy** are identified as **high-priority countries** for funding.

### 5️⃣ Visualization & Dashboard
- Developed an **interactive Power BI dashboard** displaying:
  - Cluster distributions across world map
  - Economic and health comparisons
  - Country-wise ranking by development index
  - Fund allocation recommendations

---

## ⚙️ Tech Stack

| Category | Tools & Libraries |
|-----------|------------------|
| **Programming Language** | Python 🐍 |
| **Libraries** | pandas, numpy, matplotlib, seaborn, scikit-learn, plotly |
| **Algorithm** | K-Means, Hierarchical Clustering, DBSCAN |
| **Visualization** | Power BI, Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |

---

## 📊 Key Deliverables
- Cleaned and preprocessed dataset
- EDA with visual insights
- Clustering results and evaluation
- Power BI dashboard for NGO decision-making
- Recommendations for optimal fund allocation

---

## 💡 Insights
- Cluster 0: Highly developed countries — minimal aid required
- Cluster 1: Developing nations — moderate funding needed
- Cluster 2: Underdeveloped nations — require **immediate support and majority of funding**

---

## 📈 Future Improvements
- Incorporate time-series data to monitor development trends
- Use weighted scoring for more granular fund distribution
- Deploy an interactive web app for real-time analysis

---

## 🙌 Acknowledgments
Special thanks to **HELP International NGO** for providing the problem statement and inspiration, and to **Kaggle** for the dataset.
