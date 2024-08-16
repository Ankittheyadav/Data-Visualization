**README**

---

### Dashboard Overview

This repository contains the implementation for three dashboards aimed at providing a comprehensive overview of lending operations and loan performance metrics. The dashboards are designed to facilitate data-driven decision-making and enable users to assess the health of the loan portfolio effectively.

### Contents

1. [Dashboard 1: Summary](#dashboard-1-summary)
2. [Dashboard 2: Overview](#dashboard-2-overview)
3. [Dashboard 3: Details](#dashboard-3-details)
4. [SQL Queries](#sql-queries)
5. [Domain Knowledge](#domain-knowledge)
6. [Dataset Documentation](#dataset-documentation)

---

### Dashboard 1: Summary

#### Key Performance Indicators (KPIs) Requirements:
- **Total Loan Applications:** Calculates the total number of loan applications received during a specified period. Monitors Month-to-Date (MTD) Loan Applications and tracks changes Month-over-Month (MoM).
- **Total Funded Amount:** Understands the total amount of funds disbursed as loans. Monitors Month-to-Date (MTD) Total Funded Amount and analyses Month-over-Month (MoM) changes.
- **Total Amount Received:** Tracks the total amount received from borrowers to assess the bank's cash flow and loan repayment. Analyses Month-to-Date (MTD) Total Amount Received and observes Month-over-Month (MoM) changes.
- **Average Interest Rate:** Calculates the average interest rate across all loans. Monitors Month-to-Date (MTD) average interest rate and tracks Month-over-Month (MoM) variations.
- **Average Debt-to-Income Ratio (DTI):** Evaluates the average DTI for borrowers to gauge their financial health. Computes the average DTI for all loans, MTD, and tracks Month-over-Month (MoM) fluctuations.

#### Good Loan v Bad Loan KPI’s
- **Good Loan:** 
  - Good Loan Application Percentage
  - Good Loan Applications
  - Good Loan Funded Amount
  - Good Loan Total Received Amount
- **Bad Loan:**
  - Bad Loan Application Percentage
  - Bad Loan Applications
  - Bad Loan Funded Amount
  - Bad Loan Total Received Amount

#### Loan Status Grid View
- Provides insights into metrics such as 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received,' 'Month-to-Date (MTD) Funded Amount,' 'MTD Amount Received,' 'Average Interest Rate,' and 'Average Debt-to-Income Ratio (DTI).'

![Dashboard 1 Image](https://github.com/omwadera/Data-Visualization-Dashboards/blob/main/Finance%20Project%20_%20Bank%20Analysis/Images/Bank_Loan_Analysis_page-0001.jpg)

---

### Dashboard 2: Overview

#### Charts
- **Monthly Trends by Issue Date (Line Chart):** Identifies seasonality and long-term trends in lending activities.
- **Regional Analysis by State (Filled Map):** Identifies regions with significant lending activity and assesses regional disparities.
- **Loan Term Analysis (Donut Chart):** Shows the distribution of loans across various term lengths.
- **Employee Length Analysis (Bar Chart):** Assesses the impact of employment history on loan applications.
- **Loan Purpose Breakdown (Bar Chart):** Provides a visual breakdown of loan metrics based on the stated purposes of loans.
- **Home Ownership Analysis (Tree Map):** Hierarchical view of how home ownership impacts loan applications and disbursements.

#### Metrics shown:
- 'Total Loan Applications'
- 'Total Funded Amount'
- 'Total Amount Received'

![Dashboard 2 Image](https://github.com/omwadera/Data-Visualization-Dashboards/blob/main/Finance%20Project%20_%20Bank%20Analysis/Images/Bank_Loan_Analysis_page-0002.jpg)

---

### Dashboard 3: Details

#### Grid
- Provides a comprehensive view of all essential loan-related metrics and data points.
- Enables users to access critical information efficiently.
- Offers insights into loan portfolio, borrower profiles, and loan performance.

![Dashboard 3 Image](https://github.com/omwadera/Data-Visualization-Dashboards/blob/main/Finance%20Project%20_%20Bank%20Analysis/Images/Bank_Loan_Analysis_page-0003.jpg)

---

### SQL Queries

The SQL queries file contains the queries used to extract and manipulate data from the database to populate the dashboards.

---

### Domain Knowledge

The document provides an overview of the domain knowledge relevant to the lending operations and loan performance metrics.

---

### Dataset Documentation

The dataset documentation outlines the structure and contents of the dataset used for analysis and dashboard creation.

---

### Conclusion

These dashboards aim to empower users with actionable insights into lending operations and loan performance metrics, facilitating informed decision-making and effective management of the loan portfolio.
