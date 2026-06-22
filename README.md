# Loan Default Risk Analysis and Financial Insights Dashboard

## Project Overview

Financial institutions rely on data-driven decision-making to evaluate loan applications, manage risk, and maintain profitable lending portfolios. This project analyzes loan application data to identify key factors influencing loan approval decisions and assess potential lending risks.

Using Python and Google Colab, applicant data was cleaned, explored, and visualized to uncover relationships between credit history, income levels, education, loan amounts, and loan approval outcomes.

---

## Business Problem

Loan providers must balance profitability with risk management. Approving high-risk applicants can lead to loan defaults, while rejecting qualified applicants can reduce revenue opportunities.

This project aims to answer the following business questions:

* What factors influence loan approval decisions?
* How important is credit history in determining approval outcomes?
* Does income level affect loan approval?
* Are there demographic factors associated with approval rates?
* What insights can help improve lending strategies?

---

## Dataset Information

### Dataset Name

Loan Prediction Dataset

### Dataset Source

Kaggle

### Dataset Statistics

| Metric             | Value                        |
| ------------------ | ---------------------------- |
| Total Applications | 614                          |
| Total Features     | 13                           |
| Missing Values     | Cleaned During Preprocessing |
| Target Variable    | Loan_Status                  |

---

## Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Project Workflow

### 1. Data Collection

Imported loan application data into Google Colab for analysis.

### 2. Data Cleaning

Handled missing values using appropriate statistical techniques:

* Mode for categorical variables
* Median for numerical variables

### 3. Feature Engineering

Created new analytical features:

* Total Income
* Income Category

### 4. Exploratory Data Analysis (EDA)

Analyzed:

* Applicant income
* Loan amount distribution
* Credit history
* Education level
* Loan approval patterns

### 5. Data Visualization

Created visualizations to communicate lending trends and risk indicators.

### 6. Business Insights

Generated recommendations to support lending decisions and risk management.

---

## Key Performance Indicators (KPIs)

The project focuses on the following KPIs:

* Total Loan Applications
* Loan Approval Rate
* Average Applicant Income
* Average Loan Amount
* Credit History Impact
* Income Category Approval Rates
* Education-Based Approval Rates

---

## Visualizations

### Loan Approval Distribution

### Credit History vs Loan Approval

### Income Category vs Loan Approval

### Education vs Loan Approval

### Loan Amount Distribution

### Applicant Income Distribution

## Key Findings

### Credit History is the Strongest Predictor of Loan Approval

Applicants with positive credit histories received substantially more loan approvals than those with poor or missing credit histories.

### Loan Approval Rate Exceeds Rejection Rate

The majority of applicants were approved, indicating a generally qualified borrower population.

### Income Categories Show Similar Approval Patterns

Loan approvals occur across low-, medium-, and high-income groups, suggesting income alone is not the primary approval factor.

### Education Has Limited Influence on Approval

Both graduates and non-graduates receive approvals, though graduates show slightly higher approval counts.

### Applicant Income Distribution is Highly Skewed

Most applicants fall within lower-to-middle income ranges, while a small number earn significantly higher incomes.

### Most Loan Amounts are Moderate

The lending portfolio is concentrated around small and medium-sized loans, reducing exposure to extreme lending risk.

---

## Business Recommendations

### 1. Prioritize Credit History Assessment

Strengthen credit evaluation processes to improve lending quality and reduce default risk.

### 2. Implement Risk-Based Lending

Adjust lending criteria and pricing based on borrower risk profiles.

### 3. Expand Financial Education Programs

Support applicants with weaker credit histories through financial literacy initiatives.

### 4. Increase Access for Qualified Borrowers

Create lending opportunities for creditworthy low- and medium-income applicants.

### 5. Monitor High-Value Loans Closely

Apply additional review procedures for large loan requests to minimize portfolio risk.

---

## Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Financial Analytics
* Risk Analysis
* Data Visualization
* Business Intelligence
* Insight Generation
* Reporting and Communication

---

## Project Structure

loan-default-risk-analysis/

├── notebook/

│   └── Loan_Default_Risk_Analysis.ipynb

├── visuals/

│   ├── loan_approval_distribution.png

│   ├── credit_history_vs_approval.png

│   ├── income_vs_approval.png

│   ├── education_vs_approval.png

│   ├── loan_amount_distribution.png

│   └── applicant_income_distribution.png

├── data/

│   └── train_u6lujuX_CVtuZ9i.csv

└── README.md

---

## Results

The analysis revealed that credit history is the most significant factor influencing loan approvals. Income and education contribute to lending decisions but are less predictive than credit-related factors. The findings provide actionable insights for improving loan evaluation processes and reducing financial risk.

---

## Conclusion

This project demonstrates how financial analytics can be used to evaluate borrower characteristics, identify lending risks, and support data-driven loan approval decisions. The insights generated can help financial institutions improve risk management, optimize lending strategies, and enhance portfolio performance.

---

## Author

**Margaretmary Ajuruchi**

Data Analytics Portfolio Project | Loan Default Risk Analysis & Financial Analytics
