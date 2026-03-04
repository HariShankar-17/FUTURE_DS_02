# FUTURE_DS_02
# 📊 Customer Retention & Churn Analysis – Data Science & Analytics

This project is part of the **Data Science & Analytics Internship Program** and focuses on analyzing customer churn patterns for a subscription-based telecom business.

The goal of this analysis is to identify **churn drivers, retention trends, and revenue impact** using data analytics techniques.

---

# 🎯 Business Objective

Analyze customer data to identify:

- Customer churn patterns
- Key retention drivers
- Customer lifetime trends
- Revenue impact caused by churn

This analysis helps businesses understand **why customers leave and how to improve retention strategies.**

---
# 📂 Project Structure

```
FUTURE_DS_02/
│
├── notebooks/
│   └── Task2.ipynb
│
├── dataset/
│   └── cleaned_telco_churn.xlsx
│
├── dashboards/
│   ├── Executive-Overview.jpeg
│   ├── Churn-Drivers.jpeg
│   └── Retention-Insights.jpeg
│
└── README.md
```

---

# 🧰 Tools & Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Power BI**
- **Jupyter Notebook**

Python was used for **data cleaning and analysis**, while Power BI was used for **interactive dashboard creation and business storytelling.**

---

# 📊 Dataset

**Telco Customer Churn Dataset**

This dataset contains customer information such as:

- Customer demographics
- Subscription details
- Service usage
- Monthly charges
- Contract types
- Churn status

Total records analyzed: **7,032 customers**

---

# 🐍 Data Processing (Python)

The following steps were performed in Python:

### Data Cleaning

- Handled missing values
- Converted data types
- Converted churn column into binary format
- Created customer lifetime value metric

### Feature Engineering

Additional analytical columns were created:

- Tenure groups
- Monthly charge groups
- Customer type segmentation

These transformations helped enable deeper churn analysis.

---

# 📊 Power BI Dashboard

The dashboard consists of **three analytical pages**.

---

# 1️⃣ Executive Overview

Provides a high-level summary of customer churn.

Key metrics included:

- Total Customers
- Churn Rate
- Retention Rate
- Total Revenue
- Average Customer Lifetime Value

Additional visual insights:

- Churn trend over customer tenure
- Revenue distribution by contract type

![Executive Overview](Executive Overview.jpeg)

---

# 2️⃣ Churn Drivers

This page identifies the main factors influencing customer churn.

Key analyses include:

- Churn rate by contract type
- Churn rate by payment method
- Churn rate by internet service type
- Churn rate by tenure group
- Churn rate by monthly charge segment

These visuals help identify **which customer segments are most likely to churn.**

![Churn Drivers](Churn Drivers.jpeg)

---

# 3️⃣ Retention Insights

This section focuses on understanding customer retention and revenue risk.

Key analyses:

- Customer distribution across tenure lifecycle
- Revenue impact caused by churn
- High-value customer churn analysis

This helps businesses identify **high-risk customer segments and potential revenue loss.**

![Retention Insights](Retention Insights.jpeg)

---

# 🔍 Key Insights

Key findings from the analysis:

- **Month-to-month contracts show the highest churn rate**
- Customers using **electronic check payment methods churn more frequently**
- **Fiber optic internet users have the highest churn**
- Customers in the **first 12 months show the highest churn risk**
- **High-spending customers have elevated churn rates**
- Approximately **2.9M revenue is associated with churned customers**

---

# 💡 Business Recommendations

Based on the analysis, businesses can improve retention by:

- Encouraging long-term contract subscriptions
- Improving onboarding for new customers
- Targeting high-value customers with retention campaigns
- Reviewing payment friction associated with electronic check users

---

# 🚀 Conclusion

This project demonstrates how **data analytics and visualization can help businesses understand customer behavior, identify churn drivers, and make data-driven retention strategies.**

By combining **Python for data processing and Power BI for dashboard storytelling**, the analysis provides both technical insights and business value.

---
