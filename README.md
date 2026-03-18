Telecom Customer Churn Analysis
Understanding customer churn behavior and identifying key factors that influence retention using Power BI.

📌 Table of Contents



---
## 📖 Overview
The Telecom Customer Churn Analysis project aims to help telecom companies understand customer behavior and identify the primary factors contributing to churn.  

Using Power BI, the analysis visualizes key metrics such as churn rate, customer tenure, payment methods, and service usage patterns—providing clear, data-driven insights to improve customer retention.

---

## 🎯 Business Objective
The main goals of this project are to:

- Identify why customers leave the telecom company  
- Find key churn drivers such as contract type, billing method, and services used  
- Enable data-driven decisions to reduce churn and improve customer satisfaction  

---

## 📂 Dataset
- **Dataset Name:** Telecom Customer Churn Dataset  
- **Records:** 7,042  
- **Columns:** 21  
- **Source:** Kaggle  
- **Attributes:** Customer demographics, contract type, payment methods, internet services, tenure, and churn status  

---

## 🛠️ Tools & Technologies
- Power BI  
- Power Query  
- DAX  
- Excel / CSV  

---

## 📁 Project Structure

│
|── Telecom_Customer_Churn_Analysis.csv
├── README.md
│
└── images/
└── dashboard.png
---

## 🧹 Data Preparation
Performed detailed data cleaning and transformation before visualization:

- Removed duplicate entries  
- Handled missing values (especially in `TotalCharges`)  
- Converted binary fields (e.g., `SeniorCitizen` → Yes/No)  

### ➕ Feature Engineering
Created calculated columns for:
- Tenure (in months)  
- Number of services used  
- Customer segmentation (Partners, Dependents, Senior Citizens)  
📌 *Refer to the data model diagram below:*  
![Data Model](images/data_model.png)
---

## 📊 Dashboard & Visuals
📌 *Refer to the data model diagram below:*  
![Data Model](images/powerbi.png)

The Power BI dashboard provides a complete view of customer churn behavior through interactive visuals:

- **KPI Cards:** Total Customers, Churned Customers, Churn Rate, Monthly Charges, Total Charges  
- **Donut Charts:** Gender distribution and Paperless Billing  
- **Bar Charts:** Internet Service, Contract Type, Payment Methods  
- **Tenure Analysis:** Customer lifecycle and retention duration  
- **Service Usage:** Add-on services such as Online Backup, Tech Support, and Streaming TV

  ## 🔍 Key Findings
- Customers with **month-to-month contracts** show the highest churn rate  
- Customers using **electronic check payment methods** are more likely to churn  
- **Fiber optic users** churn more frequently compared to DSL users  
- High adoption of **paperless billing** indicates a shift toward digital services  
- **Short-tenure customers (1–2 years)** have a significantly higher churn probability  

---

## 💡 Recommendations
- Offer **discounts or incentives for long-term contracts** to improve retention  
- Promote **auto-pay options** to reduce churn from manual payment methods  
- Enhance **fiber optic service quality and customer support experience**  
- Target **digital users (paperless billing customers)** with personalized engagement strategies  

---

## 📈 Business Impact
This analysis enables organizations to:

- Identify **at-risk customers early**  
- Develop **targeted retention strategies**  
- Improve **customer satisfaction and lifetime value**  
- Increase **profitability through data-driven decision-making**  

---

## 👩‍💻 Author & Contact
**Anagha Parkhi**  
MS in Business Analytics | Data Analyst  

- LinkedIn: *(Add your LinkedIn profile link)*  
- Tableau: *(Add your Tableau dashboard link)*  
- Email: *(Optional)*  
