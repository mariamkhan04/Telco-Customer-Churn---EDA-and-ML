# 📊 **Telco Customer Churn Prediction**

## 📌 **Project Overview**
Customer churn is a major challenge for telecom companies. Retaining customers is more cost-effective than acquiring new ones, but requires understanding the drivers of churn.  
This project uses the **IBM Telco Customer Churn dataset** to:
- Perform Exploratory Data Analysis (EDA) to uncover churn patterns
- Build classification models to predict churn
- Translate findings into **actionable business recommendations**


## 🛠 **Tools & Skills Used**
- **Programming:** Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn)  
- **Data Analysis & Visualization:** EDA, feature engineering, statistical summaries, plots  
- **Machine Learning:** Logistic Regression, Random Forest, SMOTE (for imbalance handling)  
- **Evaluation:** Accuracy, Precision, Recall, F1-score, ROC-AUC, Feature Importance  
- **Business Understanding:** Translating ML insights into actionable churn-reduction strategies  
- **Version Control:** Git/GitHub  
- **Environment:** Jupyter Notebook  


## 📂 **Dataset**
- **Source:** IBM Telco Customer Churn Dataset  
- **Rows:** ~7043  
- **Columns:** 21  
- **Features:** Customer demographics, subscription details, account information, and churn status.  


## 🔍 **Exploratory Data Analysis (EDA)**
**Key questions explored:**
- What is the churn rate and is it imbalanced?  
- How do contract type, payment method, internet service, and tenure impact churn?  
- Which add-on services reduce churn (e.g., online security, tech support)?  
- Which customer segments are most at risk?  

**Visualizations:**  
- Churn distribution  
- Churn by contract type, payment method, and internet service  
- Tenure & Monthly Charges distribution  
- Scatterplots and boxplots for churn patterns  



## 🤖 **Machine Learning**
**Models Trained:**  
- Logistic Regression (baseline)  
- Random Forest (with SMOTE for imbalance)  

**Preprocessing:**  
- Encoding categorical features  
- Scaling numerical features  
- Train/Test Split (80/20 stratified)  
- Class imbalance handled with SMOTE + class weights  

**Evaluation Metrics:**  
- Accuracy, Precision, Recall, F1-Score  
- ROC-AUC (Random Forest ~0.84)  
- Feature importance analysis  



## 📈 **Key Findings**
- **Churn Rate:** ~26%  
- **High-Risk Customers:** Month-to-Month contracts, electronic check payment, short-tenure customers  
- **Protective Factors:** Yearly contracts, online security, and tech support  


## 💡 **Business Recommendations**
- Convert **month-to-month → long-term contracts** with discounts/bundles  
- Strengthen **first-year customer engagement** with welcome offers  
- Incentivize **migration from electronic check → auto-pay/credit card**  
- Protect **high-value customers** with personalized retention campaigns  


## 📌 **Project Structure**

```bash
├── src/
        ├── Telco_customer_churn.xlsx # Dataset
├── customerChurn.ipynb # Jupyter Notebook with full analysis
├── requirements.txt # necessary libraries and packages 
├── Executive_summary.md # summary of overall projects 
└── README.md # Project documentation
```

## 🚀 **How to Run**
1. Clone the repository  
2. Install requirements:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run cells sequentially


## 👩‍💻 Author

[Mariam Khan](https://www.linkedin.com/in/mariam-khan0424/)