# Prosper-Loan-Data-Analysis
## Project Overview

This project involves comprehensive data analysis of the Prosper loan dataset. The project was completed as part of the exploratory data analysis (EDA) and explanatory data analysis phases. The main objective was to understand the factors affecting loan outcomes, borrower APR, and loan amounts by performing data wrangling, data cleaning, and exploratory analysis.

## Project Steps

### 1. Data Wrangling
Data wrangling involved gathering, assessing, and cleaning the dataset to ensure it was suitable for analysis. This step was crucial in handling missing values, correcting data types, and removing any inconsistencies.

### 2. Exploratory Data Analysis (EDA)
EDA was performed to uncover patterns, spot anomalies, and test hypotheses using summary statistics and graphical representations. Key insights were derived through visualizations to understand the distribution and relationships within the data.

### 3. Explanatory Data Analysis
In this phase, specific questions of interest were addressed through detailed analysis and visualization. The aim was to communicate findings clearly and concisely.

## Key Questions and Findings

### 1. What is the distribution of loan terms (in months) among the loans in the dataset?
- The most common loan terms are 36 months, followed by 60 months and 12 months.

### 2. How is the frequency of different employment statuses distributed in the dataset, and what are the counts for each category?
- Most borrowers are employed or work full-time, with fewer being self-employed, part-time, retired, or not employed.

### 3. What is the frequency distribution of borrowers' income ranges in the dataset, and how do the counts compare across predefined income categories?
- The highest frequency of borrowers falls in the $25,000-49,999 income range, followed by $50,000-74,999.

### 4. How are loans distributed across different loan origination quarters in the dataset, and what are the counts for each quarter over time?
- Loan origination peaks in specific quarters, suggesting seasonal trends.

### 5. What is the strongest correlation with Monthly Loan Payment?
- Monthly Loan Payment strongly correlates with LoanOriginalAmount, indicating higher loan amounts lead to higher monthly payments.

### 6. How does the relationship between the original loan amount and monthly loan payment vary across different income ranges?
- Higher income borrowers tend to have higher loan amounts and monthly payments.

### 7. How does the relationship between the borrower's rate and monthly loan payment vary across different employment statuses?
- Employed borrowers generally have lower BorrowerRates and higher MonthlyLoanPayments compared to other employment statuses.

## Visualizations

1. **Loan Term Distribution**: A pie chart to show the distribution of loan terms.
2. **Employment Status Distribution**: A bar chart showing the counts for each employment status category.
3. **Income Range Distribution**: A bar chart comparing counts across predefined income categories.
4. **Loan Origination Quarters**: A bar chart showing loan counts for each quarter over time.
5. **Correlation Heatmap**: A heatmap showing correlations between numerical variables.
6. **Scatter Plot Facet Grid**: Scatter plots of LoanOriginalAmount vs. MonthlyLoanPayment, colored by IncomeRange and EmploymentStatus.

## Conclusion

This project provided valuable insights into the factors influencing loan outcomes and borrower characteristics in the Prosper loan dataset. The EDA and explanatory analysis highlighted key trends and relationships, aiding in a deeper understanding of the data.

## Acknowledgements

Special thanks to the Udacity Data Analyst Nanodegree program for providing the framework and guidance for this project. 

## Getting Started

To explore the analysis in detail, follow these steps:

1. Clone the repository.
2. Open the Jupyter Notebooks provided in the repository.
3. Follow through the steps in the notebooks to understand the data wrangling, cleaning, and analysis processes.
