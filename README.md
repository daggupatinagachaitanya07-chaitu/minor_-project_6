📊 QuickCart Stockout Risk

An Excel-based data analytics project focused on identifying and analyzing daily inventory stockout risk across stores and products.

🎯 Project Objective

The objective of this project is to analyze SKU-store inventory data and classify stockout risk into three categories:

- 🟢 Safe
- 🟠 At-Risk
- 🔴 Imminent

The project uses data validation, business-signal analysis, model evaluation, and visualizations to understand the factors associated with inventory stockout risk.

---

📁 Project Structure

The Excel workbook contains the following sheets:

Sheet| Description
Project Overview| Project objective, dataset summary, and risk distribution
Data Validation| Dataset checks, row counts, missing values, and data-quality handling
Business Signals| Analysis of festival periods, supplier reliability, and perishability
Model Results| Comparison of classification model performance
Confusion Matrix| Random Forest prediction results
Insights| Key findings and business interpretations

---

📊 Dataset Overview

The project contains:

- 21,600 inventory records
- 12 stores
- 60 SKUs
- 15 suppliers
- 30 event records
- 30 days of inventory data

Stockout Risk Distribution

Risk Category| Records| Share
Safe| 14,131| 65.42%
At-Risk| 5,186| 24.01%
Imminent| 2,283| 10.57%

---

🔍 Key Business Insights

🎉 Festival Impact

The Imminent stockout rate increased from:

9.51% → 23.31%

when comparing non-festival periods with festival weeks.

🚚 Supplier Reliability

Lower supplier reliability was associated with a higher Imminent stockout rate.

- Low reliability: 15.83%
- Mid reliability: 3.26%
- High reliability: 3.82%

🥬 Product Perishability

Perishable products showed a higher Imminent stockout rate:

- Non-perishable: 9.30%
- Perishable: 12.77%

---

🤖 Model Performance

The project also includes a comparison of classification models.

Model| Accuracy| Balanced Accuracy| Imminent Recall
Majority Baseline| 62.3%| 33.3%| 0.0%
Logistic Regression| 91.4%| 86.8%| 91.7%
Random Forest| 93.9%| 88.2%| 73.4%

The analysis specifically considers Imminent recall, since identifying potential imminent stockouts is an important part of inventory-risk analysis.

---

📈 Excel Analysis

The workbook includes:

- Data validation
- KPI-style summaries
- Business signal analysis
- Model comparison
- Confusion matrix
- Charts and visualizations
- Key business insights

---

🛠️ Tools & Skills

Tool:

- Microsoft Excel

Skills demonstrated:

- Data Analysis
- Data Cleaning
- Data Validation
- Inventory Analytics
- Business Analytics
- Data Visualization
- KPI Analysis
- Machine Learning Model Interpretation
- Supply Chain Analytics

---

💡 Key Learning

This project helped demonstrate how structured data can be transformed into meaningful business insights by combining data validation, analytical comparisons, visualization, and model evaluation.

It also provided practical experience in analyzing inventory risk and understanding how factors such as festival periods, supplier reliability, and product perishability relate to stockout risk.

---

📂 Project File

The main deliverable is:[QuickCart_Stockout_Risk_Completed_(1).ipynb](https://github.com/user-attachments/files/32679577/QuickCart_Stockout_Risk_Completed_.1.ipynb)


"QuickCart_Stockout_Risk_Excel_Project.xlsx"

---

👨‍💻 Project

QuickCart Stockout Risk

Excel Data Analytics Minor Project
