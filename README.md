# AMCAT-Data-Analysis

# Exploratory Data Analysis on Salary Dataset

## Overview

This repository contains a comprehensive exploratory data analysis (EDA) on a salary dataset, focusing on the salaries of fresh graduates in the field of Computer Science. The analysis aims to provide insights into salary distributions, outliers, and factors influencing salary levels based on various characteristics such as job designation, education, gender, and personality traits.

## Objectives

- To analyze the distribution of salaries among fresh graduates in specific job roles related to Computer Science.
- To identify and visualize any outliers in the salary data.
- To explore the relationships between various numerical and categorical variables, particularly focusing on:
  - Salary and job designations
  - Salary based on personality traits
  - Gender distribution among specializations
- To test specific claims regarding salary ranges for fresh graduates in Computer Science-related roles.

## Dataset

The dataset includes the following columns:
- **ID**: Unique identifier for each entry.
- **Salary**: Annual salary of the employee.
- **DOJ**: Date of Joining.
- **DOL**: Date of Leaving (if applicable).
- **Designation**: Job title of the employee.
- **JobCity**: Location of the job.
- **Gender**: Gender of the employee.
- **DOB**: Date of Birth.
- **10percentage**, **12percentage**, **GPA**: Educational performance metrics.
- **ComputerScience**: Indicator for specialization in Computer Science (1 for Yes, 0 for No).
- **Personality Traits**: Various columns indicating personality attributes such as conscientiousness, agreeableness, etc.

## Analysis Steps

1. **Introduction**: Provide a detailed description of the dataset and objectives.
2. **Data Import and Overview**: Load the dataset and display its structure, including shape and descriptive statistics.
3. **Univariate Analysis**: Analyze individual variables, including:
   - Probability distribution functions (PDFs) and histograms.
   - Boxplots to identify outliers.
   - Countplots for categorical variables.
4. **Bivariate Analysis**: Investigate relationships between:
   - Numerical columns using scatter plots and pair plots.
   - Categorical and numerical columns using boxplots and bar plots.
   - Categorical columns using stacked bar plots.
5. **Research Questions**: Explore specific claims regarding salary ranges and gender specialization preferences.
6. **Conclusion**: Summarize the findings from the analysis.
7. **Bonus Questions**: Additional insights or research questions for further exploration.

## Requirements

To run the analysis, ensure you have the following Python packages installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn
