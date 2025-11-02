# 📉 Customer Churn Analysis Dashboard (Power BI)

## 🧾 Project Overview
This project features an **interactive Power BI dashboard** built to analyze **customer churn patterns** for a telecom company.  
The goal of this analysis is to identify factors driving customer attrition and uncover actionable insights to reduce churn rates and improve customer retention.

---

## 🎯 Objectives
- Measure the **overall churn rate** and new customer acquisition.
- Identify **demographic and behavioral factors** that influence churn.
- Analyze churn by **contract type, payment method, and internet service**.
- Understand **regional patterns** and **key reasons for customer exit**.
- Provide clear, data-driven insights for **strategic decision-making**.

---

## 📊 Key Metrics
| Metric | Value | Description |
|--------|--------|-------------|
| **Churn Rate** | **26.99%** | Percentage of customers who discontinued service |
| **New Joiners** | **411** | Customers who recently joined |
| **Total Churned** | **1,732** | Total customers lost |
| **Total Customers** | **6,418** | Active and churned customers combined |

---

## 📈 Dashboard Insights

### **1️⃣ Demographic Analysis**
- **Gender:** Female customers have a higher churn rate (**64.15%**) compared to males (**35.85%**).  
- **Age Group:** The **40–60 age group** shows the highest churn rate, followed closely by the **20–40** segment.  
- **Tenure Group:**  
  - Customers with **less than 6 months** of tenure are most likely to churn.  
  - Longer-tenure customers (**>24 months**) show the lowest churn tendency.

---

### **2️⃣ Regional & Behavioral Insights**
- **Top 5 States with Highest Churn:**
  1. Jammu & Kashmir – **57.19%**  
  2. Assam – **38.13%**  
  3. Jharkhand – **34.51%**  
  4. Chhattisgarh – **30.51%**  
  5. Delhi – **29.92%**
- **Internet Type:**
  - **Fiber Optic** users have the highest churn rate (**41.10%**)  
  - **DSL** users show the lowest churn (**19.37%**)

---

### **3️⃣ Payment & Contract Insights**
- **Payment Method:**  
  - Customers paying via **Mailed Check** and **Bank Withdrawal** churn more (37.82% and 34.43% respectively).  
  - **Credit Card** users show better retention (**14.8% churn rate**).  
- **Contract Type:**  
  - **Month-to-Month** customers have the highest churn (**46.53%**).  
  - **One-Year** and **Two-Year** contracts reduce churn dramatically (11.04% and 2.73%).  

---

### **4️⃣ Reasons for Leaving**
Top reasons reported by churned customers:
- **Competitor offerings:** 761 customers  
- **Issues in the attitude of customer support personnel:** 301 customers  
- **Service dissatisfaction:** 300 customers  
- **High pricing:** 196 customers  
- **Other reasons:** 174 customers  

---

### **5️⃣ Churn by Services**
| Service | Churn % (Yes) | Retained % (No) |
|----------|----------------|----------------|
| Internet Service | 93.7% | 6.3% |
| Device Protection Plan | 29.0% | 71.0% |
| Online Security | 15.4% | 84.6% |
| Paperless Billing | 74.6% | 25.4% |
| Premium Support | 16.5% | 83.5% |
| Phone Service | 90.6% | 9.4% |
| Streaming Movies | 44.0% | 56.0% |
| Streaming Music | 38.9% | 61.1% |
| Streaming TV | 43.2% | 56.8% |

---

## 🧩 Tools and Techniques Used
- **Power BI**
  - DAX (Data Analysis Expressions) for calculations  
  - Interactive filters and slicers (Gender, Monthly Charges, Marital Status)  
  - Custom visualizations and KPI cards  
- **Data Cleaning and Transformation:** Power Query Editor  
- **Data Source:** Customer churn dataset (Telecom sector)

---

## 📍 Key Takeaways
- **Month-to-Month** and **short-tenure** customers have the highest churn risk.  
- **Credit card payment** and **longer contracts** significantly reduce churn.  
- **Internet service issues** and **competitor switching** are the main drivers of customer loss.  
- **Older, loyal customers** tend to stay longer — indicating brand trust increases with tenure.  

---

## 🧠 Learning Outcomes
This project helped me strengthen my skills in:
- Designing **data-driven dashboards** with actionable insights.  
- Using **DAX** to calculate churn metrics and KPIs.  
- Transforming raw data into visual stories for business understanding.  
- Applying **customer segmentation** and **behavioral analytics** in Power BI.  

---

## 📂 Files Included
- `Customer_Churn_Analysis.pbix` — Interactive Power BI dashboard  
- `README.md` — Project documentation  
- `dashboard.png` — Dashboard screenshots for preview  

---

## 🏁 Conclusion
This Power BI project highlights how **data visualization** can uncover critical business insights.  
By identifying key churn factors, companies can implement **targeted retention strategies** to reduce customer loss and improve lifetime value.

---

### 📸 Dashboard Preview
![Customer Churn Dashboard](Images/churn_dashboard.png)
