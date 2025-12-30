# 🏦 Banking Risk Analytics & Dashboard (Power BI)

## 📌 Project Overview
This project focuses on **risk analytics in the banking domain**, demonstrating how data can be used to minimize lending risk and support informed decision-making.

Using Python for data analysis and Power BI for visualization, this project analyzes customer profiles, loans, deposits, and engagement metrics to determine whether applicants are likely to repay loans.

---

## 🎯 Business Problem
Banks face significant risk while lending money to customers.  
The objective of this project is to:
- Analyze customer banking behavior
- Understand loan, deposit, and engagement patterns
- Support loan approval decisions based on customer risk profile

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib)
- **Power BI**
- **Excel**
- **Jupyter Notebook**

---

## 📂 Repository Structure

Banking-Risk-Analytics-Dashboard/

- **data/** – Raw and cleaned banking datasets  
- **notebooks/** – Exploratory Data Analysis (EDA) and data analysis notebooks  
- **dashboard/** – Power BI dashboard files  
- **reports/** – Business insights, documentation, and project report  
- **README.md** – Project overview and documentation  


---

## 🔄 Project Workflow

### 1️⃣ Data Exploration & Cleaning (Python)
- Performed Exploratory Data Analysis (EDA) on banking customer data
- Created new derived columns such as:
  - Engagement Timeframe
  - Engagement Days
  - Income Bands (Low, Mid)
- Handled missing values and improved data consistency

Notebooks:
- `banking_eda_v1.ipynb`
- `banking_eda_v2.ipynb`

---

### 2️⃣ Power BI Data Modeling & Calculations
- Built data relationships using primary and foreign keys
- Created calculated columns and measures using DAX:
  - Total Clients
  - Total Loan
  - Total Deposits
  - Total Fees
  - Engagement Length
- Used DAX functions such as:
  - `SUM`
  - `DISTINCTCOUNT`
  - `SUMX`
  - `SWITCH`
  - `DATEDIFF`

---

### 3️⃣ Dashboard & Visualization (Power BI)
Developed interactive dashboards to analyze:

- Loan Analysis
- Deposit Analysis
- Client Segmentation
- Engagement Metrics

Dashboards help stakeholders evaluate:
- Customer risk profile
- Loan repayment likelihood
- High-value vs high-risk customers

---

## 📊 Key KPIs
- Total Clients
- Total Loan Amount
- Bank Loans
- Business Lending
- Total Deposits
- Total Fees
- Credit Card Balance
- Customer Engagement Length

---

## 📈 Key Insights
- Customer engagement duration strongly correlates with loan and deposit amounts
- Certain income bands show higher loan dependency
- Private banks have a higher number of active clients
- Dashboard enables quick identification of high-risk lending profiles

---

## 📄 Dataset Information
- Dataset contains multiple interconnected banking tables
- Data is used strictly for **educational and portfolio purposes**
- No real customer data is involved

---

## 🚀 How to Use This Project

1. Run Python notebooks for EDA  
2. Open Power BI file:
dashboard/banking_risk_dashboard.pbix
3. Refresh data source if required
4. Interact with dashboards using slicers and filters

---

## 📌 Future Enhancements
- Add predictive risk scoring
- Automate data refresh
- Include SQL-based analysis
- Deploy dashboard using Power BI Service

---

## 📜 License
MIT License — free to use for learning and portfolio projects.
