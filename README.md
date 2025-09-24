# Insurance-Cost-Analysis
## Overview
#### This project analyses a medical insurance dataset to explore how health and lifestyle factors affect insurance costs. Using Python, Pandas, Matplotlib, and Scikit-learn, I performed data cleaning, exploratory data analysis (EDA), statistical tests, and used regression analysis to explore relationships between features and insurance costs, identifying which factors are most strongly associated with higher charges.

## Dataset
- Description: Contains records of medical insurance clients, including features such as age, BMI, smoking status, and charges.
- Size: 1338 rows x 7 columns

## Features
- age
- sex
- bmi
- children
- smoker
- region
- charges

## Steps
- Data cleaning
- Following questions are answered:
  - Q1. What does the distribution of charges look like?
  - Q2. How many charges vary across regions? Is healthcare more expensive in one region vs others?
  - Q3. Do smokers pay more than non-smokers?
  - Q4. Is there a difference in charges between males and females?
  - Q5. How does BMI relate to medical charges?
  - Q6. Do age and number of children affect charges?
  - Q7. Which factor (age, BMI, children) has the strongest effect on charges?
  - Q8: Is there an association between number of children and smoking status?
  - Q9: Are smokers more likely to fall into the 'High charges' category compared to non-smokers?

## Key Findings
- 100% of smokers and 17% of non-smokers are in the top third of charges.
- Age and smoking are the strongest predictors of high insurance costs.

## Tools & Technologies
- Python
- Pandas, Matplotlib, Scikit-learn, Numpy, Seaborn
- Jupyter Notebook

## How to Run
1. Clone this repository:
    - git clone https://github.com/CryptRaid/Insurance-Cost-Analysis.git
3. Open Insurance-Cost-Analysis.ipynb in Jupyter Notebook.
4. Ensure the required python libraries are installed:
    - Pandas, Matplotlib, Scikit-learn, Numpy, Seaborn

## Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory data analysis and visualization
- Statistical analysis and hypothesis testing
- Regression analysis
- Python programming and use of data science libraries
