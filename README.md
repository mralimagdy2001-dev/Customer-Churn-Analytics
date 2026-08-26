# 📊 Customer Churn Analysis & Executive Dashboard

An end-to-end data analysis project focused on understanding customer churn, identifying retention risk drivers, and providing executive-level recommendations. This repository includes dataset analyses, service adoption patterns, and an automated Python tool that generates a print-ready executive PDF report.

## Dashboard Preview
[Welcome Page.png]
[Customer Insights.png]
[Service Insights.png]
[Payment Insights.png]

---

## 📌 Executive Summary & Key KPIs

This analysis evaluates key performance indicators across **$16.05M** in yearly subscriber charges, evaluating administrative ticket friction and service-level churn metrics.

| Metric | Value | Business Context |
| :--- | :--- | :--- |
| **Overall Churn Rate** | **26.5%** | Benchmark churn rate across all customer cohorts |
| **Total Yearly Charges** | **$16.05M** | Cumulative annual revenue evaluated |
| **Admin Support Tickets** | **2,955** | Billing and administrative inquiry volume |
| **Streaming Adoption Rate** | **38.4%** | Average adoption across TV & Movie entertainment services |

---

## 🔍 Key Findings & Insights

### 1. High-Risk Churn Drivers (Internal Services)
* **Fiber Optic Internet:** Exhibits the highest churn rate at **41.8%**, signaling potential pricing friction, competitive aggressive onboarding, or quality-of-service gaps.
* **Streaming TV / Movies:** Shows a **30.1%** churn rate among subscribers.
* **DSL Internet:** Displays moderate stability with a **19.0%** churn rate.
* **No Internet Service:** Represents the most stable group with only **7.4%** churn.

### 2. Payment Method Impact
* **Electronic Check:** Shows an alarmingly high churn rate of **45.3%**, strongly correlated with manual billing friction and high customer turnover.
* **Automated Payments:** Customers using automated billing exhibit significantly higher retention:
  * **Bank Transfer (Automatic):** 16.7% Churn
  * **Credit Card (Automatic):** 15.2% Churn

### 3. Service & Entertainment Adoption
* **Fiber Optic** accounts for the largest core user base at **44.0%** (3,096 customers).
* **Streaming TV** and **Streaming Movies** have strong adoption rates (**38.4%** and **38.8%** respectively), with **27.5%** subscribing to both entertainment options simultaneously.

---

## 💡 Strategic Business Recommendations

1. **Fiber Optic Retention Campaign:** 
   Investigate service uptime and re-evaluate promotional pricing models for Fiber Optic users to mitigate the 41.8% churn risk.
2. **Incentivize Automated Billing (Auto-Pay):** 
   Offer a minor monthly bill credit (e.g., $2–$5) for customers transitioning from *Electronic Check* to *Credit Card / Bank Transfer Auto-Pay* to drop payment-related attrition.
3. **Bundle Streaming Package Offerings:** 
   Leverage high streaming adoption (~38%) by creating discounted "Entertainment Bundles" to lock in single-service users into long-term contracts.

---

## 🛠️ Tools & Technologies Used

* **Power BI**
* **Excel**
* **Figma**
* **Data Modeling**
  
---

## 📁 Repository Structure

```text
Customer-Churn-Analytics/
│
├── Dataset/
│   └── 02 Customer Churn-Dataset.xlsx
│
├── Power BI/
│   └── Customer_Churn_Dashboard.pbix
│
├── Images/
│   ├── Welcome Page.png
│   ├── Customer Insights.png
|   ├── Service Insights.png
|   └── Payment Insights.png
| 
├── Documentation/
│
└── README.md
```

---

## 👤 Author

**Ali Magdy**

[GitHub](https://github.com/mralimagdy2001-dev) | [LinkedIn](https://www.linkedin.com/in/ali-magdy-mahmoud/)
