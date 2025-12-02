# 📊 Sales Analysis — DataCamp Project

End-to-end analysis of sales performance using Python.
This project demonstrates practical data analytics skills, including data cleaning, exploratory data analysis (EDA), visualization, and business insights for decision-making.

---

## 🎯 Executive Summary

The **Email + Call** hybrid method is the strongest performer across all major business KPIs. Although it represents only **20%** of all customers, it consistently delivers:

* **Highest revenue per customer ($184.24)**
* **Strongest scalability (R² = 0.89)**
* **Largest marginal return ($15.20 per additional unit)**
* **Fastest growth momentum (+73.5% over 6 weeks)**

**Business Recommendation:** Prioritize resources and budget toward the Email + Call method. Convert Email-only customers into the hybrid funnel to maximize revenue.

---

## 📈 Key Metrics Comparison

| Sales Method     | Customers | Avg Revenue/Customer | R² (Volume → Revenue) | Marginal Return | Growth Momentum |
| ---------------- | --------- | -------------------- | --------------------- | --------------- | --------------- |
| **Email + Call** | 2,572     | **$184.24**          | **0.89**              | **$15.20**      | **+73.5%**      |
| **Email**        | 7,466     | $97.19               | 0.82                  | $9.80           | +49.4%          |
| **Call**         | 4,962     | $47.64               | 0.76                  | $4.60           | +96.5%          |

---

## 🔍 Insights & Visuals

### **1. Revenue Distribution**

Revenue shows a **bimodal distribution**, indicating two customer value segments. This supports targeted marketing and differentiated pricing strategies.
1. Revenue Distribution

![Revenue Distribution Plot](image/viz1_revenue_distribution.png)

### **2. Customer Volume**

Email is the largest channel (48%), followed by Call (32%). Email + Call has lower volume but dramatically higher value.

### **3. Profitability (Boxplot)**

Median revenue is **4× higher** in Email + Call vs Call-only. Differences are statistically significant using non-overlapping IQRs.

### **4. Scalability (Regression)**

Email + Call has the steepest slope and highest R², proving excellent scalability as volume increases.

### **5. Growth Trend (Time Series)**

All channels grow over 6 weeks, but Email + Call accelerates the fastest.

---

## 🚀 Strategic Recommendations

* **Maximize Email + Call Resources**: Allocate budget, sales staff, and operations here.
* **Convert Email → Hybrid**: Create workflows that convert Email-only customers into Email + Call.
* **Focused Upselling**: Target high-value hybrid customers with tailored offers (highest marginal return).
* **Optimize/Reduce Call-Only**: Investigate inefficiencies in the Call-only funnel.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas** (data wrangling)
* **Matplotlib & Seaborn** (visualization)
* **Jupyter Notebook** (analysis environment)

---

## 📁 Repository Structure

```
sales-analysis-datacamp/
│
├── sales_analysis_datacamp.ipynb    # Main analysis notebook
├── README.md                        # Project documentation
└── outputs/
    └── figures/                     # All generated charts
```

---

## 📄 License

MIT License
