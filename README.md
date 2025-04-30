# Churn-Analytics-in-Telecom-Domain-SQL-PowerBI-Python

#### 📊 Dashboard View - [Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjgyNWZmNzYtZDkwYy00MDk1LWI4N2YtOTRkMmVlNTYyOWIzIiwidCI6IjU2MGY2MzA2LWZiZjItNGJhYy1hZTllLWQyMTQ4YzU5OTNiNyJ9&pageName=4be53f716b9b43588d22)

## 📉 Churn Analysis Project

This project focuses on understanding and reducing customer churn for a telecom firm, though the techniques are applicable across various industries. The goal is to analyze customer data to identify patterns behind customer departures, predict potential churners, and provide actionable insights for marketing and retention strategies.


## 🎯 Project Goals

- **Visualize & Analyze Customer Data:**
  - Demographic
  - Geographic
  - Payment & Account Information
  - Service Usage
- **Profile Churners:** Identify trends and behavioral patterns
- **Predict Future Churn:** Using a Random Forest classification model
- **Inform Marketing Strategies:** Target high-risk segments with tailored campaigns

## 📦 Data & Tools

### 🔹 Data Source

- Customer data provided in CSV format and loaded into Microsoft SQL Server.

### 🔹 Tools & Technologies

| Tool                    | Purpose                              |
|-------------------------|--------------------------------------|
| **SQL Server**          | Data storage & ETL                   |
| **SSMS**                | SQL querying                         |
| **Power BI**            | Dashboard creation & visualizations  |
| **Jupyter Notebook**    | Machine learning & churn prediction  |

### 🔹 Programming & Libraries

- **Languages:** SQL, Python  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`

## 🔁 ETL Process (SQL Server)

1. **Data Loading:** Import CSV data into a staging table.
2. **Exploration:** Run queries to inspect column values and nulls.
3. **Data Cleaning:** Handle missing values, drop irrelevant records.
4. **Transformation:** Insert cleaned records into a production table.
5. **View Creation:** Create SQL views (`vw_ChurnData`, `vw_JoinData`) for Power BI.

## 📊 Power BI Visualization

An interactive dashboard was built using Power BI to explore churn dynamics.

### 🔹 Key Metrics

- Total Customers
- Churned Customers & Churn Rate
- New Joiners

### 🔹 Visual Analysis

- **Demographics:** Gender, Age
- **Geographics:** State distribution
- **Account Info:** Tenure, Contract Type, Payment Method
- **Services Used:** Internet Type, Add-ons
- **Churn Insights:** Categories and reasons for churn


## 🧠 Churn Prediction with Random Forest (Python)

A machine learning model was developed to predict which customers are likely to churn.

### 🔹 Steps

- **Preprocessing:** Encode categorical features, handle scaling
- **Model:** Random Forest Classifier
- **Evaluation:** Confusion Matrix, Accuracy, Precision, Recall
- **Feature Importance:** Identify key churn drivers
- **Prediction:** Classify churn likelihood for new customers
- **Output:** Save results to CSV

---

## 📈 Visualizing Predictions (Power BI)

Predicted churn results are integrated into Power BI for further exploration.

### 🔹 Prediction Dashboard

- Customer details of predicted churners
- Demographics & account attributes
- Geographic distribution of at-risk customers

## 👥 Target Audience

This project is relevant to any business aiming to reduce customer attrition:

- Telecom providers  
- Retailers  
- Banks and financial institutions  
- Subscription services  
- Healthcare providers

## ✅ Key Workflow Summary

1. **ETL in SQL Server**
2. **Data Cleaning & View Creation**
3. **Data Modeling and Visualization in Power BI**
4. **Churn Prediction with Random Forest in Python**
5. **Visualization of Predicted Churn in Power BI**

---

## 📌 Outcomes

- Actionable churn insights across customer profiles  
- Identification of high-risk churn segments  
- Accurate churn prediction using Random Forest (~82% accuracy)  
- Enhanced decision-making for marketing & retention teams
