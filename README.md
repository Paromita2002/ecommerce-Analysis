📌 Customer Segmentation Using RFM Analysis in E-Commerce
📝 Project Overview

This project applies RFM (Recency, Frequency, Monetary) analysis to an e-commerce dataset to segment customers based on their purchasing behavior. The objective is to identify high-value customers, detect at-risk groups, and optimize marketing strategies using data-driven insights.

🛠️ Tools & Technologies Used

• Python  — Data analysis, preprocessing, RFM calculations

• Jupyter Notebook  — Exploratory data analysis, methodology implementation

• Pandas, Matplotlib, Seaborn  — Data manipulation & visualization

• Power BI  — Dashboard creation & interactive insights

• Git & GitHub  — Version control & project documentation

📂 Dataset

Description:

• Covers transactions between 01/12/2010 – 09/12/2011 for a UK-based non-store online retailer

• Key fields: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

Preprocessing steps:

• Removed missing values, duplicates, and canceled orders

• Handled non-product stock codes

• Converted invoice dates into datetime format

🛠 Methodology

Data Cleaning & Preparation
• Ensured dataset consistency and reliability for analysis.

• RFM Feature Engineering

  Recency (R): Days since last purchase
  Frequency (F): Number of purchase occasions
  Monetary (M): Total spending amount

• Customer Segmentation

• Assigned RFM scores

• Classified customers into actionable groups (High Value, Loyal, At Risk, etc.)

Pareto Principle (80/20 Rule)

• Found that 26% of customers contribute to 80% of sales.

• Found that 21% of products generate 80% of revenue.

• Found that 23% of products contribute to 80% of sales volume.

🤔 Why Pareto Principle over other frameworks?

I chose the Pareto Principle because:

• It directly highlights the imbalance in contribution (few customers/products drive most revenue).

• Unlike clustering or arbitrary grouping, Pareto is easy for stakeholders to interpret and act on.

• It connects naturally with business decision-making (prioritizing top contributors).

• Alternative principles (e.g., cohort analysis, long-tail distribution) are valuable, but Pareto offers quick, high-impact insights in e-commerce contexts.

📊 Visualizations & Dashboard

• Customer Trends: Purchase behavior patterns over time

• Heatmap: Correlations between Recency, Frequency, and Monetary

• Segmentation: Distribution of customers across RFM groups

• Interactive Power BI Dashboard: Sciler for region, date, product categories

🚀 Key Insights

• Top 26% of customers drive ~80% of sales → high-value target group

• At-risk customers identified → opportunity for retention campaigns

• Loyal and frequent buyers → potential brand ambassadors

• Pareto analysis showed marketing budget should focus on the top-performing products & customers
