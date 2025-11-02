# Customer Churn Analysis

This project focuses on understanding customer churn in a telecom company using **data analysis** and **machine learning**.  
The goal is to identify why customers leave and build a predictive model to help businesses improve retention.

---

##  Overview

Customer retention plays a key role in telecom success.  
By analyzing real customer data, this project uncovers the major factors behind churn and provides actionable insights.

It includes:
- Data preprocessing and cleaning  
- Predictive modeling using Logistic Regression  
- Interactive visualization with Power BI  

---

##  Dataset

**Source:** Telco Customer Churn (IBM Sample Data)  
**Records:** 7,043 | **Features:** 21  

**Main columns:**
- Customer details: `gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- Services: `InternetService`, `OnlineSecurity`, `TechSupport`  
- Billing info: `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`  
- Target: `Churn`

---

##  Approach

1. Cleaned data (handled missing values and inconsistencies)  
2. Encoded categorical columns & scaled numerical features  
3. Trained **Logistic Regression model** to predict churn  
4. Evaluated and visualized results  

**Model Results:**
- Accuracy: 78.6%  
- F1 Score: 0.55  

---

##  Key Insights

- Customers with **month-to-month contracts** churn the most.  
- **Senior citizens** and those with **high monthly charges** are more likely to leave.  
- **Tech support** and **online security** services increase retention.  
- **Longer tenure** reduces churn likelihood.

---

##  Tools & Technologies

- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Power BI** for interactive dashboards  
- **Git & GitHub** for version control  

---

##  Future Work

- Experiment with **Random Forest** and **XGBoost**  
- Deploy the model using **Streamlit** or **Flask**  
- Add **real-time churn monitoring** via Power BI  

---

##  Author

**Arjun Dasari**  
B.Tech Student – Data Science  
Passionate about Data Analytics and Machine Learning  
GitHub: [Arjundas08](https://github.com/Arjundas08)
