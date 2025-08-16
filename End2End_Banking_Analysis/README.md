# 🏦 Banking Risk Analytics Project  

## 📌 Problem Statement  
The objective of this project is to develop a basic understanding of **risk analytics** in the banking and financial services sector.  
Banks face the challenge of **minimizing the risk of losing money while lending to customers**. By analyzing customer data, banks can make informed lending decisions and reduce loan defaults.  

---

## ✅ Solution  
Using **Power BI dashboards** along with **SQL and Python-based data analysis**, this project provides an analytical framework to:  
- Assess applicants’ financial profiles.  
- Identify patterns in deposits, loans, savings, and spending behavior.  
- Predict the likelihood of repayment.  
- Support decision-making on **whether to approve or reject a loan application**.  

---

## 📊 About the Dataset  
- The dataset contains **banking and client details** stored in multiple relational tables.  
- Tables are interlinked using **primary and foreign keys**.  
- Data includes:  
  - **Customer Demographics** (age, income, properties owned, etc.)  
  - **Banking Activities** (deposits, savings, loans, credit card balance)  
  - **Business Lending** and other financial services  
- Raw data was imported from **Excel into SQL**, then cleaned and processed in **Python**, and finally visualized in **Power BI**.  

---

## 🔧 Tools & Technologies  
- **SQL** → Data storage, schema design, and querying.  
- **Python (Pandas, NumPy, Seaborn, Matplotlib)** → Data cleaning, preprocessing, and EDA.  
- **Power BI** → Interactive dashboards for business insights.  

---

## 📈 Key Insights  
- Customers with **higher deposits also maintain stronger saving balances**.  
- **Age and income** positively correlate with retirement savings and loan capacity.  
- **Property ownership** shows weaker correlation with banking activity, suggesting external dependency (real estate market, inheritance, etc.).  
- **Business lending** operates as a distinct financial segment, partially overlapping with personal loans.  

---

## 📊 Power BI Dashboard (Preview)  
![Alt Text](https://github.com/BhaskarDeka007/Data_Analysis_Projects/blob/main/End2End_Banking_Analysis/Output_Images/PowerBI_DashBoard_Images/Home_page.png)
![Alt Text](https://github.com/BhaskarDeka007/Data_Analysis_Projects/blob/main/End2End_Banking_Analysis/Output_Images/PowerBI_DashBoard_Images/Deposit_analysis.png)
![Alt Text](https://github.com/BhaskarDeka007/Data_Analysis_Projects/blob/main/End2End_Banking_Analysis/Output_Images/PowerBI_DashBoard_Images/Loan_analysis.png)
![Alt Text](https://github.com/BhaskarDeka007/Data_Analysis_Projects/blob/main/End2End_Banking_Analysis/Output_Images/PowerBI_DashBoard_Images/Summary.png)
![Alt Text](https://github.com/BhaskarDeka007/Data_Analysis_Projects/blob/main/End2End_Banking_Analysis/Output_Images/PowerBI_DashBoard_Images/Drill_Through.png)
---

## 📂 Project Structure  
├── Data/ # Raw and processed datasets (Excel/CSV)
---
├── Output_Images/ # Exported plots, heatmaps, and visualizations
---
├── PowerBI/ # Power BI dashboard files (.pbix)
---
├── BankingAnalysis.ipynb # Jupyter Notebook (Data Cleaning, EDA, Insights)
---
├── SQL_File.sql # SQL script for importing and managing data
---
├── README.md # Project documentation

