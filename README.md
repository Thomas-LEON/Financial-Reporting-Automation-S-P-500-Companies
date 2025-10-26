# Financial Reporting Automation — S&P 500 Companies (Python + SQL)

This repository showcases a **Finance Commando Developer–style project** simulating the work of a data engineer within a bank’s **Finance Department**.  
It uses the **“Financial Data S&P 500 Companies”** dataset from Kaggle and demonstrates how to automate financial reporting pipelines using **Python**, **SQL**, and **Excel exports**.

---

## Objectives

- Practice SQL and Python skills relevant to a **Finance IT / Commando Developer** role.
- Automate the generation of **financial KPIs and reports** (revenues, margins, ratios).
- Ensure **data integrity** and reproducibility in the reporting process.
- Deliver results that could be directly used by a **financial control or reporting team**.

---


##  Workflow

1. **Data Import & Exploration**  
   - Load the Kaggle dataset.  
   - Inspect and clean financial columns (Revenue, Net Income, Assets, etc.).  

2. **SQL Integration**  
   - Create a SQLite database (`finance.db`).  
   - Execute queries to compute:
     - Average Net Margin per Sector  
     - Top 10 Companies by Profitability  
     - Revenue Distribution by Industry  

3. **Python Automation**  
   - Replicate SQL logic using pandas.  
   - Automate report generation and export to Excel.  

4. **Data Integrity Checks**  
   - Validate missing values or incoherent ratios.  
   - Log results for auditability.

5. **(Optional)** Power BI or Plotly dashboard for visual reporting.

---

##  Key KPIs

- **Net Profit Margin** = Net Income / Revenue  
- **Leverage Ratio** = Liabilities / Assets  
- **Return on Equity (ROE)** = Net Income / Shareholder Equity  
- **Revenue Growth YoY** = (Revenue_t – Revenue_(t-1)) / Revenue_(t-1)

---

##  Technologies

- **Python 3.10+**
- **pandas**
- **sqlite3**
- **openpyxl** (for Excel export)
- **matplotlib / seaborn** (optional for visualization)
- **Power BI / Plotly** (optional for dashboard)

---

##  Data Source

Dataset: [Financial Data S&P 500 Companies](https://www.kaggle.com/datasets/pierrelouisdanieau/financial-data-sp500-companies)

---

## Author

**Thomas Léon**  
_Quantitative Finance & Data Science enthusiast_  
GitHub: [Thomas-LEON](https://github.com/Thomas-LEON)  
LinkedIn: [linkedin.com/in/thomas-leon](https://www.linkedin.com/in/thomas-leon-893316262/)

---

*(This README will be refined and updated as the project evolves into a complete automation pipeline.)*
