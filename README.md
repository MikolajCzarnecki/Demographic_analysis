# Data Science Project: Statistical Analysis of Consumer Behavior in Bajtocja
Project Overview

This project involves a statistical analysis of simulated consumer behavior data from a fictional region, Bajtocja. The dataset, project_data1.csv, contains survey results on various consumer habits and demographic details.
Data Description

The dataset includes the following variables:

    id: Observation identifier
    weight: Respondent's weight (kg)
    height: Respondent's height (cm)
    gender: Gender (1 – "female", 2 – "male")
    children: Number of dependents
    age: Respondent's age (years)
    income: Reported income (in bajtalars)
    savings: Reported savings (in bajtalars; negative values indicate expenses exceed income)
    single: Household status (1 – "single-person household", 0 – "multi-person household")
    palce: Size of the respondent's locality (1 – "up to 10,000 residents", 2 – "10,000 to 100,000 residents", 3 – "over 100,000 residents")
    food_expenses: Reported food expenditure (in bajtalars)

Tasks
Task 1: Data Exploration

    Load the data and provide a summary.
    Determine the number of observations and the structure of the dataset (e.g., types of variables, missing values).
    Present and comment on frequency tables or descriptive statistics for the variables.
    Visualize the distributions of variables and compare them to normal distributions using histograms or Q-Q plots.

Task 2: Correlation Analysis

    Calculate and visualize the correlation matrix for quantitative variables using a heatmap.
    Analyze the relationships between qualitative variables.

Task 3: Data Visualization

    Create at least three different types of visualizations:
        Scatter plots of all quantitative variables against wydatki_zyw.
        Box plots of a selected quantitative variable by locality.
        Stacked bar charts comparing gender and household status.
    Additional visualizations are encouraged.

Task 4: Confidence Intervals

    Compute 99% confidence intervals for the mean, standard deviation, and quartiles of the wiek variable.
    Discuss the assumptions used and their validity.

Task 5: Income Classes Analysis

    Categorize respondents into income classes based on income percentiles:
        Lower class (below 25th percentile)
        Middle class (25th to 75th percentile)
        Upper-middle class (75th to 90th percentile)
        Upper class (above 90th percentile)
    Analyze and compare food expenditure across these income classes.

Task 6: Hypothesis Testing

    Conduct hypothesis tests to address:
        Differences in savings between genders.
        Correlation between the proportion of income spent on food and savings.
        Whether the average weight of women is greater than 56 kg.
    Formulate and test an additional hypothesis about a chosen variable.

Task 7: Regression Analysis

    Build an initial regression model to predict food_expenses using all available variables.
    Evaluate model performance and compliance with Classical Linear Regression assumptions (linearity, homoscedasticity, absence of autocorrelation).
    Detect and address multicollinearity and outliers.
    Refine the model and interpret the significant coefficients.
    Describe the characteristics of the top 10% of predicted food expenditures.
