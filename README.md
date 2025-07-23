# 🎯 Customer Churn Analysis – Mission Brief

This project was created to **analyze telecom customer data** and find the **key reasons behind customer churn**. The main mission is to identify the behavior and patterns of users who are likely to leave the service and provide actionable insights.

---

## 🚨 Problem Statement

Telecom companies face customer attrition (churn) that affects revenue. This project attempts to answer:

- Who is more likely to churn?
- What services or billing types lead to higher churn?
- Can we spot red flags using user data?

---

## 🔧 Tools & Technologies Used

| Tool            | Purpose                  |
|-----------------|--------------------------|
| Python          | Data manipulation & logic |
| Pandas          | Data cleaning & analysis |
| Seaborn/Matplotlib | Visualization          |
| Jupyter Notebook | Analysis environment    |

---

## 📦 Data Columns (Text Tags / Topics Explored)

We analyzed the following fields (text tags) to explore churn behavior:

- `gender`
- `SeniorCitizen`
- `Partner`
- `Dependents`
- `tenure`
- `PhoneService`, `MultipleLines`
- `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`
- `Contract`, `PaperlessBilling`, `PaymentMethod`
- `MonthlyCharges`, `TotalCharges`
- `Churn` (Target variable)

---

## 📊 Analysis Summary

### 1. 👴 Senior Citizens  
- **Churned:** 26.5%  
- **Not Churned:** 73.5%

### 2. ❤️ Relationship Status  
- **With Partner – Churned:** 20.3%  
- **Without Partner – Churned:** 31.0%

### 3. 📱 Phone Services  
- Customers with **Multiple Lines** churned **28.4%** of the time  
- **No Multiple Lines** churned **23.7%**

### 4. 🔌 Internet Services  
- **DSL** users – 19.8% churn  
- **Fiber optic** users – 42.2% churn  
- **No internet service** – only 7.5% churn

### 5. 🧾 Payment Method  
- **Electronic check** – 45.1% churn  
- **Mailed check** – 19.3% churn  
- **Credit card (auto)** – 15.1% churn  
- **Bank transfer (auto)** – 14.7% churn

### 6. ⏳ Contract Type  
- **Month-to-Month:** 43.3% churn  
- **One-year:** 11.5%  
- **Two-year:** 2.7%

### 7. 🛡️ Tech Support  
- Customers **without Tech Support** churned at **38.3%**  
- Those **with Tech Support** churned at **14.2%**

---

## ✅ Conclusion (Game Strategy)

The "churn" boss can be defeated by:

- Targeting **month-to-month** users with **incentives** to move to longer contracts  
- Promoting **online security** and **tech support** services  
- Encouraging **automatic payment methods** to reduce risk of churn  
- Monitoring **fiber optic** users closely, as they show higher churn

---

