# Loan Interest Rate Analysis & Predictive Modeling

## Project Overview

This project analyzes peer-to-peer lending data from the Bondora P2P Loans dataset. The goal is to identify key drivers of loan interest rates, profile customer risk, and build predictive models to enhance personalized loan offers. The analysis leverages advanced data wrangling, statistical inference, visualization, and regression modeling techniques using Python.

---

## Methodology

1. **Data Wrangling & Preprocessing**
   - Loaded and cleaned the raw loan dataset
   - Set unique identifiers for streamlined analysis
   - Engineered features (e.g. debt-to-income ratio, risk flags)

2. **Exploratory Data Analysis**
   - Calculated core statistics (interest mean, standard deviation, rating proportions)
   - Visualized interest rate distributions by education and other demographics
   - Investigated relationships and correlations among loan features

3. **Risk Profiling**
   - Flagged risky borrowers based on debt burden and job stability
   - Quantified the proportion and impact of high-risk loans

4. **Statistical Inference**
   - Constructed confidence intervals to validate business process consistency

5. **Predictive Modeling**
   - Built and tested both simple and multiple regression models to predict loan interest rates
   - Selected features based on correlation analysis and model performance

---

## Insights Derived

- **Interest rates given to borrowers are influenced by financial and demographic factors such as rating, income, education, and loan history.**
- **High debt-to-income borrowers with unstable employment are flagged as risky and tend to receive higher interest rates.**
- **Most borrowers receive the loan amount they request, indicating consistency in business operations.**
- **A regression model combining key features can accurately predict individual interest rates, supporting customized loan offers.**

---

## Results

- **Comprehensive risk profiling and predictive modeling pipeline constructed.**
- **Final multiple regression model achieves strong explanatory power (high \( R^2 \)) and statistical significance across predictors.**
- **Analysis and code fully reproducible in the provided Jupyter Notebook (`.ipynb`).**

---

## Technologies Used

- **Python (pandas, matplotlib, seaborn, scipy, statsmodels)**
- **Jupyter Notebook**

---

