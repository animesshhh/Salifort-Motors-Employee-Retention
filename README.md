# Salifort-Motors-Employee-Retention
This repository contains predictive models, including logistic regression and random forest, used to identify key factors influencing employee attrition. Insights from the models help guide HR strategies for improving employee satisfaction and reducing turnover.

## Project Overview
This project focuses on improving employee retention at Salifort Motors by predicting which factors are most likely to make an employee leave the company. The goal is to create a machine learning model that can provide insights into the most influential factors and help the HR team make informed decisions to enhance employee satisfaction and retention.

---

## Problem Statement
Salifort Motors seeks to address the question: **What’s likely to make an employee leave the company?**  
Understanding the reasons behind employee attrition is crucial for improving retention rates and maintaining a motivated and productive workforce.

---

## Approach
Since the target variable (employee retention) is categorical, we approached the problem by building both **logistic regression** and **tree-based machine learning models**. The **random forest** model slightly outperformed the decision tree model in predicting whether an employee will leave the company.

The models were trained using a variety of employee attributes, and the results provided insights into the key factors that influence an employee's decision to leave.

---

## Results and Impact
The random forest model identified several key factors that strongly influence employee retention. The insights gathered from this model will enable Salifort Motors' HR team to implement strategies to improve employee retention and prevent turnover.

### Key Findings:
- **Most Relevant Variables:**
  - `last_evaluation`
  - `number_project`
  - `tenure`
  - `overworked`
  - `salary_low`
  - `work_accident`
  
- **Key Insights:**
  - Employees who have been at the company for four years tend to be more dissatisfied. This warrants further investigation or possible promotions for long-tenured employees.
  - Employees working on too many projects or putting in excessive hours are more likely to leave, suggesting a need for more balanced workloads or compensation for extra work.
  - Evaluation scores should be more proportionately tied to employee contributions rather than excessively rewarding employees who work 200+ hours per month.

### Visualizations:
1. **Bar Plot of Relevant Variables**  
   ![Bar Plot](img1.jpg)  
   The bar plot above highlights the most important factors, such as `last_evaluation`, `number_project`, `tenure`, and `overworked`, that contribute to employee attrition.

2. **Feature Importance from Random Forest Model**  
   ![Random Forest Feature Importance](img2.jpg)  
   In the random forest model, the most important variables are `last_evaluation`, `tenure`, `number_project`, `overworked`, `salary_low`, and `work_accident`. These variables are the strongest predictors of whether an employee will leave the company.

---

## Next Steps & Recommendations
Based on the model's insights, the following recommendations are proposed for Salifort Motors to enhance employee retention:

1. **Limit Project Load**: Cap the number of projects an employee can work on to prevent burnout.
2. **Review Tenure-Based Promotions**: Consider promoting employees who have been with the company for four or more years, or investigate why these employees tend to be dissatisfied.
3. **Reward Long Working Hours**: Either reward employees who work longer hours or reduce the expectation for overtime work.
4. **Clarify Overtime Pay Policies**: Ensure that employees are familiar with the company's overtime policies, and make expectations about workload and time off explicit.
5. **Reevaluate Evaluation Scores**: Implement a proportionate scale for evaluation scores, rewarding employees based on their contributions and effort rather than solely on the number of hours worked.
6. **Address Company Culture**: Hold discussions at the company-wide and team levels to address potential issues with work culture, especially concerning workload and recognition.

---

## Model Comparison

The random forest model emerged as the top performer, offering the highest accuracy of 89% and a clear understanding of the most impactful factors in employee retention.

---

## Tools & Technologies
- **Python** (for data preprocessing and model building)
- **Random Forest**, **Logistic Regression** (for predictive modeling)
- **Matplotlib**, **Seaborn** (for data visualization)
- **Pandas**, **NumPy** (for data manipulation)

