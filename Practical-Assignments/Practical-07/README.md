# Practical Assignment 7: Regression Analysis & Hypothesis Testing

This assignment utilizes **Ordinary Least Squares (OLS) Regression** models to analyze the "Teachers' Rating Dataset." The objective is to understand how regression outputs can be used to perform standard statistical tests like T-tests, ANOVA, and Correlation.

## Objectives

1.  **Regression with T-Test:**
    * [cite_start]Build an OLS regression model to predict **teaching evaluation rates** (`eval`) based on **gender**[cite: 2].
    * [cite_start]Interpret the model summary to determine if gender has a statistically significant effect on evaluations [cite: 31-33].

2.  **Regression with ANOVA:**
    * [cite_start]Investigate whether **beauty scores** for instructors differ significantly across various **age groups**[cite: 42].
    * [cite_start]Generate and interpret an **ANOVA table** derived from the regression model [cite: 44-46].

3.  **Correlation via Regression:**
    * [cite_start]Perform a regression analysis to determine if **teaching evaluation scores** are correlated with **beauty scores**[cite: 47].
    * [cite_start]Analyze the R-squared value and the p-value of the slope coefficient to assess the strength and significance of the relationship[cite: 49].

## Libraries Used
* **Pandas:** Data manipulation and loading the dataset.
* **Statsmodels:** Creating OLS regression models (`smf.ols`) and generating ANOVA tables (`anova_lm`).