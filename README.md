# **Credit Card Transaction & Customer Analysis Dashboard**

## **Objective**
The objective of this project is to develop a **credit card analytics dashboard** that provides **real-time insights** into transaction trends, customer spending behavior, and key financial metrics. By integrating **PostgreSQL** with **Power BI**, this dashboard enables stakeholders to monitor and optimize credit card operations efficiently.

---

## **Workflow**
1. **Data Collection**
   - Two CSV files are used:
     - `cc_data.csv` (Credit Card Transactions)
     - `customer_data.csv` (Customer Demographics)

2. **Data Storage**
   - The data is uploaded into **PostgreSQL** as two tables:
     - `credit_card_transactions`
     - `customer_details`

3. **Data Processing & Visualization**
   - Power BI is connected to PostgreSQL.
   - Data is transformed and structured for visualization.
   - Dashboards are created for in-depth analysis.

---

## **Datasets**
### **1. Credit Card Transaction Data (`cc_data.csv`)**
- **Columns:**
  - `transaction_id`: Unique transaction identifier  
  - `transaction_date`: Date of transaction  
  - `card_category`: Credit card type (Gold, Silver, Blue, Platinum)  
  - `transaction_amount`: Value of transaction  
  - `revenue`: Revenue generated  
  - `interest_earned`: Interest collected  

### **2. Customer Data (`customer_data.csv`)**
- **Columns:**
  - `customer_id`: Unique customer identifier  
  - `age_group`: Age category (20-30, 30-40, etc.)  
  - `income_level`: Low, Medium, High  
  - `job_type`: Business, White-Collar, Government, etc.  
  - `marital_status`: Single, Married, Unknown  
  - `spending_habit`: Preferred spending category (Bills, Travel, Food, etc.)  

---

## **Visualizations**
### **1. Credit Card Customer Report**
This dashboard focuses on **customer behavior, revenue distribution, and spending habits**.

![Customer Report](Customer_report.jpeg)

### **2. Credit Card Transaction Report**
This dashboard highlights **transaction trends, revenue by expenditure type, and credit card performance**.

![Transaction Report](Transaction_Report.jpeg)

---

## **Insights**
### **Week-over-Week (WoW) Change**
- **Revenue increased** by **28.8%**.

### **Year-to-Date (YTD) Overview**
- **Total Revenue:** **$57M**  
- **Total Interest Earned:** **$8M**  
- **Total Transaction Amount:** **$46M**  
- **Male vs. Female Revenue Contribution:**  
  - **Male:** **$31M**  
  - **Female:** **$26M**  
- **Credit Card Performance:**  
  - **Blue & Silver cards** contribute **93% of overall transactions**.
- **Top Geographic Regions:**  
  - **TX, NY & CA** contribute **68% of total revenue**.
- **Activation Rate:** **57.5%**  
- **Delinquency Rate:** **6.06%**

### **Top Findings**
1. **Businessmen and White-Collar customers** contribute the highest revenue.  
2. **Spending Trends:** Bills, Entertainment, and Fuel are the top expenditure categories.  
3. **Best Performing Credit Card:** **Blue Card** contributes **$47M revenue**.

---

## **Technologies Used**
- **Database:** PostgreSQL  
- **Data Processing:** Pandas (Python)  
- **Visualization:** Power BI  
- **Data Storage:** CSV  
- **Version Control:** Git & GitHub  

---

