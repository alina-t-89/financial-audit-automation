# Financial Audit Automation: Risk & Compliance Scanner

## Project Overview
This project demonstrates a Python-based automated auditing workflow designed to scan large-scale financial datasets (100,000+ transactions). It focuses on identifying systemic risks, such as missing primary documentation (VAT compliance) and high-value procurement anomalies.

## Key Features
* **Big Data Processing:** Efficiently handles and cleans 100,000+ rows of financial data using **Pandas** and **NumPy**.
* **Risk Detection:** Automated identification of transactions with missing documentation (`Document_Status = False`), critical for tax and audit compliance.
* **Anomaly Identification:** Specialized logic to spot high-value outliers in specific categories (e.g., Office Supplies with 0% tax rate) to detect potential fraud or entry errors.
* **Risk Profiling & Visualization:** Categorical analysis using **Matplotlib** to visualize financial exposure and prioritize internal control efforts.

## Business Impact
* **Operational Efficiency:** Reduced the time required for data validation from days of manual work to seconds of automated processing.
* **Financial Exposure Mitigation:** Identified over **400,000,000 KZT** in high-risk transactions lacking proper documentation.
* **Strategic Prioritization:** Revealed a **4x higher risk concentration** in IT Services and Legal sectors, allowing management to focus audit resources where they matter most.
* **Actionable Reporting:** Automated export of high-priority audit lists to Excel for immediate follow-up by operational teams.

## Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib
* **Output Formats:** Interactive Jupyter Notebook (.ipynb), Excel (.xlsx)

---
*Developed as part of a financial data analytics portfolio.*
