# Customer Engagement & Financial Performance in Banking

## 📄 Project Description
This project focuses on analyzing customer engagement patterns and evaluating their impact on financial performance in the banking sector. By leveraging structured banking data, the analysis uncovers how customer behavior, engagement duration, and product usage influence key financial indicators such as loans, deposits, and fee generation.

The project demonstrates an end-to-end data analytics workflow, combining Excel-based data understanding, Python-driven exploratory analysis, and analytical modeling to generate actionable business insights.

---

## 👤 Author Information
- **Author:** Priyanka Panda  
- **Role:** Data Analyst / Aspiring Business Analyst  
- **Domain:** Banking & Financial Services Analytics  
- **Skills Highlighted:** Data Analysis, EDA, Financial Analytics, Business Insights  

---

## 🎯 Project Objectives
- Analyze customer engagement behavior in a banking environment
- Measure financial performance using loans, deposits, and fees
- Identify high-value and long-term customers
- Compare business lending vs personal banking contribution
- Enable time-based analysis for financial performance tracking
- Support data-driven decision-making for banking strategies

---

## 🗂 Dataset Overview
- **Dataset Name:** Banking.xlsx  
- **Total Records:** ~3,000  
- **Unique Clients:** 2,940  
- **Data Type:** Structured tabular data  
- **Industry:** Banking & Financial Services  

### Data Includes:
- Customer demographics (Age, Gender, Nationality)
- Banking relationship and engagement duration
- Loan and deposit information
- Account types (Savings, Checking, Foreign Currency)
- Fees and engagement-related metrics

> ⚠️ Note: Due to file size limitations, the dataset is not uploaded directly to this repository.

---

## 🛠 Tools & Technologies Used

| Tool / Technology | Purpose |
|------------------|--------|
| **Microsoft Excel** | Initial data exploration, schema understanding |
| **Python (Pandas, NumPy)** | Data cleaning & exploratory data analysis |
| **Matplotlib / Seaborn** | Visualization & trend analysis |
| **Jupyter Notebook** | Analytical workflow documentation |
| **Power BI** | Data modeling & financial performance analysis |
| **DAX** | KPI creation & time intelligence |

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was conducted using Python to understand the structure, distribution, and behavior of the banking data.

### Key EDA Activities:
- Handling missing and inconsistent values
- Statistical analysis of numerical variables
- Distribution analysis of loans and deposits
- Customer segmentation based on engagement and demographics

### EDA Findings:
- Longer customer engagement correlates with higher financial contribution
- Business lending significantly outweighs personal loans
- Savings and checking accounts form the core deposit base

---

## 📊 Key Financial Metrics

### 👥 Customer Base
- **Total Clients:** 2,940

### 💰 Loan Performance
- **Total Loan Value:** $4.38 Billion  
- **Bank Loan:** $1.77 Billion  
- **Business Lending:** $2.60 Billion  

### 💵 Deposit Performance
- **Total Deposits:** $3.77 Billion  
- **Bank Deposits:** $2.01 Billion  
- **Savings Accounts:** $698.73 Million  
- **Checking Accounts:** $963.28 Million  
- **Foreign Currency Accounts:** $89.65 Million  

### 💳 Engagement & Fees
- **Total Fees Collected:** $158.19 Million  
- **Engagement Account Amount:** $16.93 Million  
- **Total Credit Card Amount:** $4.39K  

---

## 🧱 Data Modeling Approach
A STAR schema was implemented to support efficient and scalable analysis.

### Model Structure:
- **Fact Table:** Banking Clients
- **Dimension Tables:** Gender, Banking Relationship, Investment Advisor
- **Parameter Table:** Date Range Lookup (for dynamic time filtering)
- **Measures Table:** Centralized KPIs (Loans, Deposits, Fees, Clients)

This approach improves performance, readability, and analytical flexibility.

---

## ⏳ Time-Based Analysis
The project supports multiple time perspectives, including:
- All Time
- Last 30 / 90 Days
- Last 3 / 6 / 12 / 24 Months
- Current Month (CM)
- Current Quarter (CQ)
- Current Year (CY)

---

## 💡 Key Business Insights
- Customer engagement duration is a strong indicator of financial value
- Business lending is the primary driver of loan performance
- Deposits provide long-term financial stability for banks
- High-engagement customers represent lower risk and higher profitability
- Data-driven insights enable targeted banking strategies

---

## 📈 Business Impact
This analysis helps banking institutions:
- Identify high-value customers
- Strengthen engagement and retention strategies
- Optimize loan and deposit portfolios
- Improve financial planning and forecasting

---

## 🚀 Future Enhancements
- Customer churn analysis
- Customer Lifetime Value (CLV) modeling
- Risk and default prediction
- Predictive analytics and machine learning integration


---

## 📌 Disclaimer
This project is created for educational and portfolio purposes. The data used does not represent any real banking institution.
