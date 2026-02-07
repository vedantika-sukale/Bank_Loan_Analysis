# 📊 Bank Loan Analysis Dashboard (Power BI + SQL Server)

## 📌 Project Overview
This project showcases an **interactive Bank Loan Analysis Dashboard** built using **Power BI Desktop**, with data preparation performed in **SQL Server Management Studio (SSMS) 2022**.  
The dashboard provides insights into loan performance, borrower behavior, and portfolio risk using industry-standard banking KPIs.

The project demonstrates an **end-to-end analytics workflow**, starting from raw CSV data ingestion to SQL-based analysis and final visualization in Power BI.

---

## 🎯 Business Objectives
- Analyze overall loan application trends
- Identify **Good vs Bad loan** distribution
- Track **Month-to-Date (MTD)** and **Month-over-Month (MoM)** performance
- Evaluate borrower risk using **Debt-to-Income (DTI)** and **Interest Rate**
- Enable interactive, data-driven decision-making

---

## 📂 Dataset
- **Source:** Publicly available banking dataset used in a tutorial  
- **Original Format:** CSV  
- **Records:** ~38,576 rows  
- **Database:** SQL Server 2022  


### Key Columns
- Loan Status  
- Funded Amount  
- Amount Received  
- Interest Rate  
- Debt-to-Income Ratio (DTI)  
- Term  
- Purpose  
- State  
- Employment Length  

---

## 🛢 Data Preparation (SQL Server)
The raw CSV dataset was first imported into **SQL Server Management Studio (SSMS) 2022**.

### Steps Performed:
- Imported CSV data into SQL Server tables
- Executed SQL queries to solve all problem-statement questions
- Filtered and validated data for accuracy
- Created a dedicated **SQL query document** for analysis
- Used SQL output as the data source for Power BI

This approach reduced transformation complexity and ensured cleaner data for visualization.

---

## 📊 Key KPIs
- **Total Loan Applications**
- **Total Funded Amount**
- **Total Amount Received**
- **Average Interest Rate**
- **Average Debt-to-Income Ratio (DTI)**
- **Good Loan vs Bad Loan Percentage**
- **MTD & MoM Growth Metrics**

---

## 📑 Dashboard Pages

### 1️⃣ Summary Dashboard
Provides a high-level snapshot of loan performance:
- Key KPIs
- Good vs Bad loan analysis
- Loan status distribution

---

### 2️⃣ Overview Dashboard
Focuses on trend and category analysis:
- Monthly loan application trends
- State-wise loan distribution
- Loan purpose analysis
- Employment length and home ownership insights

---

### 3️⃣ Details Dashboard
Supports granular analysis:
- Loan-level detailed table
- Interactive filters and slicers
- Ad-hoc data exploration

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **SQL Server Management Studio (SSMS) 2022**
- **DAX**
- **Power Query**
- **CSV Data Handling**
- **Data Modeling & Visualization**

---

## 🧠 Key Learnings
- End-to-end data analytics workflow
- SQL-based problem solving for business questions
- Designing banking KPIs
- Building interactive Power BI dashboards
- Improving usability through layout and color customization

---

## 🔍 Insights Generated
- Majority of loans fall under the **Good Loan** category
- Higher DTI values are associated with increased default risk
- Loan demand varies significantly across states
- Seasonal trends observed in monthly loan applications

---

## 📷 Dashboard Preview
_Add screenshots of the dashboards below_

/images/summary_dashboard.png
/images/overview_dashboard.png
/images/details_dashboard.png


---

## 🚀 Future Enhancements
- Add **Approval Rate** and **Default Rate** KPIs
- Implement drill-through analysis
- Automate SQL-to-Power BI data refresh
- Add borrower risk segmentation

---

## 📎 How to Use
1. Download the `.pbix` file from this repository
2. Open it in **Power BI Desktop**
3. Update SQL Server connection if required
4. Refresh data and explore dashboards using filters

---

## 🧾 Disclaimer
This project was created for **learning and portfolio purposes** using a tutorial-provided dataset.  
Standard industry KPIs and dashboard patterns were followed, with independent implementation and customization.

---
