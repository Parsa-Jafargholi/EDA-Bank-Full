# EDA Bank Full

# Exploratory Data Analysis on Bank Marketing Dataset

This project involves an exploratory data analysis (EDA) of the Bank Marketing dataset, aiming to uncover insights and patterns that can inform marketing strategies.

---

## Dataset Overview

The dataset contains information on various marketing campaigns conducted by a Portuguese banking institution. It includes details about clients, the marketing campaigns, and whether the clients subscribed to a term deposit.

- **Source:** [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Attributes:**
  - Age
  - Job
  - Marital Status
  - Education
  - Default Status
  - Balance
  - Housing Loan Status
  - Personal Loan Status
  - Contact Communication Type
  - Last Contact Day and Month
  - Duration of Last Contact
  - Campaign (number of contacts performed during this campaign)
  - Pdays (days since the client was last contacted from a previous campaign)
  - Previous (number of contacts performed before this campaign)
  - Poutcome (outcome of the previous marketing campaign)
  - Subscription Status (target variable)

---

## Objectives

The primary objectives of this analysis are:

1. **Data Cleaning:** Handle missing values and correct inconsistencies.
2. **Descriptive Statistics:** Summarize the main characteristics of the dataset.
3. **Visualization:** Create visual representations to identify trends and patterns.
4. **Correlation Analysis:** Determine relationships between different variables.
5. **Insights:** Draw conclusions that could help improve future marketing campaigns.

---

## Analysis Steps

1. **Data Loading:** Import the dataset into a pandas DataFrame.
2. **Data Cleaning:**
   - Identify and handle missing values.
   - Correct data types where necessary.
3. **Exploratory Data Analysis:**
   - Generate summary statistics.
   - Visualize distributions of numerical variables.
   - Analyze categorical variables using bar charts.
   - Examine relationships between variables using scatter plots and correlation matrices.
4. **Insights and Recommendations:**
   - Interpret findings to provide actionable recommendations for marketing strategies.

---

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Results

The analysis revealed several key insights:

- **Age Distribution:** Clients aged between 30 and 40 are the most targeted group.
- **Job Influence:** Certain professions, such as management and blue-collar jobs, have higher subscription rates.
- **Education Level:** Clients with tertiary education are more likely to subscribe to term deposits.
- **Contact Duration:** Longer contact durations are positively correlated with subscription success.

These insights can help tailor future marketing campaigns to target demographics more effectively.

---

## Conclusion

This exploratory data analysis provides a comprehensive understanding of the factors influencing client subscription to term deposits. By leveraging these insights, the bank can optimize its marketing strategies to improve client engagement and subscription rates.

---

For a detailed walkthrough of the analysis, please refer to the [Jupyter Notebook](https://github.com/Parsa-Jafargholi/EDA-Bank-Full/blob/main/EDA%201.ipynb).
