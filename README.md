# Prosper Loan Dataset Exploration

## Introduction

This project involves the exploration and analysis of the **Prosper Loan Dataset**, which contains 113,937 loan records with 81 variables per loan. These variables include information such as loan amount, borrower rate (interest rate), loan status, borrower income, and more. To simplify visualization and analysis, the dataset was reduced to 23 key features.

The analysis provides insights into borrower demographics, loan distribution, Prosper ratings, and factors influencing loan amounts, interest rates, and repayment behavior.

---

## Dataset Overview

The dataset includes information on:
- Loan amount and repayment status
- Borrower rate (interest rate)
- Borrower income range and employment status
- Prosper ratings (both numeric and alpha)
- Loan purpose (e.g., debt consolidation, home improvement)
- Homeownership status

### Features Used in This Analysis
From the 81 available variables, the analysis focused on 23 key features, ensuring clarity and relevance in the visualizations and insights.

---

## Summary of Findings

### Borrower Demographics
1. **Employment Status**: 
   - Most borrowers are employed, followed by full-time employees.
2. **Income Ranges**:
   - ~31% of borrowers earn $50,000–$74,999.
   - ~28% earn $25,000–$49,999.
   - ~18% earn $100,000 or more.
3. **Occupations**:
   - Majority of borrowers fall under "Other" occupations, followed by professionals and computer programmers.

### Loan Status and Prosper Ratings
4. **Loan Status**:
   - Most loans are categorized as *Current*, followed by *Completed* loans.
5. **Prosper Ratings**:
   - The highest Prosper numeric score is 8, followed by 4.
   - The most common Prosper rating alpha is **C**, while the least common is **AA**.

### Loan Distribution
6. **Top Borrowing States**:
   - The top 10 states for borrowing are: CA, TX, NY, FL, IL, OH, GA, VA, NJ, and PA.
7. **Loan Purpose**:
   - Most loans are used for debt consolidation, followed by other unspecified purposes and home improvement.

---

## Key Insights

### Correlations and Trends
1. **Correlation of Loan Amount**:
   - Loan original amount and monthly loan payment are highly correlated.
   - Borrower interest rate is negatively correlated with Prosper scores and loan amounts.
2. **Borrower Categories**:
   - Employed borrowers take the highest loan amounts, followed by "Other" and full-time employees.
   - Higher-income borrowers tend to receive higher loan amounts.

### Prosper Ratings and Income
3. **Income and Ratings**:
   - Borrowers with Prosper ratings from **AA to D** have higher loan amounts and higher salaries.
   - The majority of borrowers fall under the Prosper rating of **B**, regardless of income range.

### Homeownership and Interest Rates
4. **Homeownership Influence**:
   - Homeowners tend to have lower interest rates and higher Prosper ratings.
   - Borrowers without homeownership typically have higher interest rates and lower Prosper ratings.

---

## Key Insights for Presentation

### Loan Approval Dependence
- Loan approval status heavily depends on:
  1. **Income Range**
  2. **Homeownership Status**
  3. **Employment Status**

### Borrower Prosper Ratings
- Applicants with Prosper ratings from **AA to D** receive higher loan amounts, correlating with higher salaries.
- Borrowers rated **HR** (High Risk) tend to have the highest interest rates.

### Employment and Loan Distribution
- Employed and full-time employees exhibit higher mean salaries.
- Borrowers in Prosper ratings of **AA, A, and B** generally have higher monthly incomes and loan amounts.

---

## Tools and Libraries

- **Python Libraries**:
  - `pandas` and `numpy`: For data manipulation and cleaning.
  - `matplotlib` and `seaborn`: For visualizations.
- **Jupyter Notebook**: For documenting and executing the analysis.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ProsperLoanAnalysis.git
   ```
2. Load the dataset and run the Jupyter Notebook.
3. Explore the visualizations and insights presented in the analysis.

---

## Future Enhancements

1. Build predictive models to assess default risk based on borrower attributes.
2. Perform a time-series analysis of loan trends.
3. Create an interactive dashboard using Power BI or Tableau for deeper insights.
