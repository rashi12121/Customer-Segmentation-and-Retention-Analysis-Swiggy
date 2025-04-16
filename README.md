# 🍽️ Swiggy RFM Analysis – Understanding Customer Engagement for Heritage Table

## 📌 Project Overview  
Swiggy, a leading food delivery platform, noticed a decline in repeat orders and customer engagement, raising concerns about potential customer churn. To address this issue and improve customer retention, a detailed RFM (Recency, Frequency, Monetary) analysis was conducted.

This analysis focuses on understanding customer behavior using transaction data from October to December 2024. The goal is to identify valuable customer segments and develop targeted strategies to re-engage users and foster loyalty.

---

## 🗂️ Database Info  

The analysis is based on the following datasets:

- **Order Data**: Contains customer food order transactions from October to December 2024.
- **Existing Customer Details**: Includes customer segments/status as of October 1, 2024, based on their previous food ordering behavior.

📁 **[Dataset](https://github.com/rashi12121/Customer-Segmentation-and-Retention-Analysis-Swiggy/blob/main/Swiggy-Data.csv)**

All analysis was performed using **Google Sheets**.

---

## ❓ Questions to Answer

1. What are the recency, frequency, and monetary patterns of Swiggy customers?
2. Which customers have churned or stopped engaging with Heritage Table?
3. How many customers have upgraded, downgraded, or maintained their segment status?
4. What trends exist in high-paying vs low-paying customer behavior?
5. Which segments are most engaged, and which need reactivation strategies?

---

## 🔍 Exploratory Data Analysis (EDA)

- Cleaned and structured transaction and customer status data.
- Calculated RFM scores for each customer based on January 1, 2025.
- Created RFM segments to classify customers (e.g., Champions, Loyal, At Risk).
- Compared previous statuses (October 2024) with updated ones (January 2025) to detect churn, upgrades, downgrades, and stability.

---

## 📊 Visualization

- Tables showing RFM scoring and segment distribution.
- Conditional formatting to highlight customer movement across statuses.
- Summary counts of churned, upgraded, downgraded, and stable customers.

![Customer Churned Analysis Dashboard](https://github.com/rashi12121/Customer-Segmentation-and-Retention-Analysis-Swiggy/blob/main/Swiggy-Customer%20Churn%20Analysis%20Dashboard.pdf)

## 💡 Key Insights

- A noticeable number of customers moved to lower engagement segments, indicating signs of churn.
- Loyal and champion customers showed higher frequency and monetary values.
- Several customers improved their RFM scores, showing positive engagement.
- Clear segmentation allows for personalized marketing and retention strategies.

---

## 🛠️ Tools Used

- 📄 Google Sheets (Data cleaning, formulas, RFM scoring)
- 📊 Conditional formatting and pivot tables for analysis
- 🧮 Manual comparison logic for segment movement tracking
