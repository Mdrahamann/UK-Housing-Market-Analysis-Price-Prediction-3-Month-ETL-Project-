# 🏡 UK Property Price Intelligence System (2025)

This project analyses real UK property transaction data from the HM Land Registry using **3 months of official 2025 data** (September, October, November).  
It demonstrates a complete **ETL pipeline**, **data cleaning**, **exploratory data analysis**, and a **machine learning model** to understand and predict property prices.

---

## 📌 Project Overview

This project uses real monthly datasets from the UK Government’s HM Land Registry.  
Each monthly file contains thousands of property transactions including:

- Sale price  
- Date of transfer  
- Postcode  
- Property type  
- New/old build  
- Duration (Freehold/Leasehold)  
- Address components  
- Region (District, County)

The goal is to build a **professional, real‑world analytics system** that can be updated monthly.

---

## 🧩 Features of This Project

### ✔ ETL Pipeline  
- Load multiple monthly datasets  
- Assign correct HM Land Registry column names  
- Merge datasets  
- Clean and validate data  
- Convert date fields  
- Create time‑based features (year, month, quarter)

### ✔ Exploratory Data Analysis  
- Price trends across months  
- Price distribution by property type  
- Top counties by average price  
- Outlier detection  
- Regional comparisons

### ✔ Machine Learning  
A predictive model using:

- Linear Regression  
- Random Forest Regressor  

Features used:
- Year  
- Month  
- Quarter  
- Property Type  
- New/Old  
- Duration  

### ✔ Business Insights  
- Which counties are most expensive  
- Which property types cost more  
- How prices vary month‑to‑month  
- What features influence price the most  

---

## 📂 Dataset

The dataset comes from the UK HM Land Registry (Open Government Licence).

Files used:
- September 2025  
- October 2025  
- November 2025  

> “Contains HM Land Registry data © Crown copyright and database right 2021.  
> This data is licensed under the Open Government Licence v3.0.”

---

## 🚀 How to Run

1. Upload the monthly CSV files into Google Colab  
2. Run the ETL script to merge and clean  
3. Run EDA cells  
4. Train ML models  
5. View insights and charts  

---

## 🔄 Future Updates

This project is designed to grow over time.  
When a new monthly dataset is released:

1. Upload the new CSV  
2. Run the update function  
3. Append to the master dataset  
4. Re-run EDA + ML  

This makes the project a **living analytics system**.

---

## 📊 Example Visuals

- Price trend (3‑month)  
- Property type distribution  
- County price comparison  

(Images stored in `/images` folder)

---

## 🧠 Skills Demonstrated

- Data Engineering (ETL)  
- Data Cleaning  
- Exploratory Data Analysis  
- Feature Engineering  
- Machine Learning  
- Real‑world dataset handling  
- Business analytics  
- Python (Pandas, NumPy, Seaborn, Scikit‑Learn)

---

## 👤 Author

**MD Jamilur Rahaman**  
MSc Data Science & Analytics  
University of Hertfordshire (2025–2026)

---

## 📜 Licence

This project uses HM Land Registry data under the Open Government Licence v3.0.
