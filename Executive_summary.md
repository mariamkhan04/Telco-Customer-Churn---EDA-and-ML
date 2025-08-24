## **Executive Summary – Telco Customer Churn Project**

This project analyzes the IBM Telco Customer Churn dataset to identify key factors driving customer churn and build predictive models for proactive retention.

### **Problem:**
Churn significantly impacts telecom profitability, as acquiring new customers is more expensive than retaining existing ones.

### **EDA Findings:**

- **Churn Rate:** ~26% (imbalanced target).
- **Key Drivers:** Month-to-Month contracts, Electronic Check payments, and customers in their first year (low tenure).
- **High-Risk Segment:** Short-tenure, high-monthly-charge customers on electronic check.
- **Protective Factors:** Yearly contracts, online security, and tech support reduce churn.

## **Modeling:**

- **Logistic Regression and Random Forest** trained with class imbalance handling.
- **Evaluation metrics (ROC-AUC ~0.84 for RF)** show good predictive power.
- **Feature importance** confirms **contract type, tenure, and payment method** as strongest churn predictors.

## **Business Recommendations:**

- Convert short contracts → long-term plans (discounts, bundles, loyalty perks).
- Engage new customers in the first year (welcome offers, early support).
- Migrate electronic check users → auto-pay methods with incentives.
- Protect high-value customers with personalized retention campaigns and churn alerts.

✅ By combining data-driven insights with targeted retention strategies, this project demonstrates how analytics can reduce churn, increase retention, and improve lifetime customer value.