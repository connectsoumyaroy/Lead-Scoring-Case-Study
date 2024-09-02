# Lead Conversion Optimization Project

## Overview

This project focuses on improving lead conversion rates for X Education Company, aiming to increase their current conversion rate from 30% to an ambitious 80%. We leveraged logistic regression to identify high-potential leads and enhance the overall lead conversion process. This README outlines our approach, methodologies, and key findings.

## Project Objectives

1. **Identify High-Potential Leads:** Develop a model to score leads based on their likelihood to convert.
2. **Enhance Conversion Rates:** Refine the lead conversion process to achieve a target rate of 80%.

## Approach

### Data Cleaning

We started by meticulously cleaning the dataset, addressing issues such as missing values, outliers, and irrelevant columns. Categorical variables were transformed to null values where necessary, maintaining a high level of data integrity.

### Exploratory Data Analysis (EDA)

EDA provided crucial insights into the dataset, revealing an imbalance with a 39% conversion rate. We identified key conversion sources such as Landing Page Submissions, Google, and Direct Traffic. Important factors included SMS Sent, Email Opened, Occupation, and the time spent on the website.

### Data Preparation

We prepared the data by converting categorical variables into numerical values and creating dummy variables for multi-category columns. A 70:30 train-test split was used, and MinMax scaling was applied to ensure compatibility with the logistic regression model.

### Model Building

We employed Recursive Feature Elimination (RFE) for feature selection, refining the model to include 11 significant variables. The model was built to ensure stability and accuracy by addressing multicollinearity and p-values.

### Model Evaluation

The model's performance was evaluated by setting a prediction threshold of 0.39, aligning with the target conversion rate of 80%. Evaluation metrics showed promising results with an accuracy of 81%, sensitivity of 77%, and specificity of 83%.

## Key Recommendations

- **Focus on High-Score Leads:** Allocate resources to leads with higher scores for better conversion rates.
- **Customize Communication:** Create personalized communication scripts to improve engagement.
- **Improve Customer Interaction:** Enhance the customer portal experience to drive more conversions.
- **Explore Expansion:** Utilize lead feedback and target working professionals to broaden reach.

## Learnings

- **Collaborative Effort:** Team collaboration enriched the analysis with diverse perspectives.
- **Data Integrity:** Rigorous data cleaning was essential for accurate results.
- **Insightful EDA:** EDA provided valuable insights into conversion patterns and key drivers.
- **Feature Selection:** Choosing significant features improved model interpretability and stability.
- **Effective Metrics:** Understanding evaluation metrics was crucial for model assessment.
- **Actionable Strategies:** Recommendations were based on predictive insights, offering practical strategies for improvement.

## Conclusion

Our work effectively addressed X Education's lead conversion challenges. By implementing a logistic regression model, we provided a framework for scoring leads and optimizing resource allocation. Our data-driven approach paves the way for X Education to pursue an improved conversion rate, closely aligning with the CEO's ambitious goal.

For further details, please refer to the project documentation and code repositories.
