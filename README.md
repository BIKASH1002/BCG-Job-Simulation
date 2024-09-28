![MasterHead](https://github.com/user-attachments/assets/00f1ac28-f797-458b-9167-ccc6c4d59b62)

# Data Science Job Simulation - Boston Consulting Group (BCG) via Forage

<div align = "justify">

# Overview

This repository contains my submission for the Data Science Job Simulation program conducted by Boston Consulting Group (BCG) through Forage. The job simulation focused on analyzing and addressing customer churn for an energy company (PowerCo). Over the course of four tasks, the performed key data science steps include writing professional communication, conducting exploratory data analysis, feature engineering, model development and reporting the results. Each task is outlined below with relevant details.

# Setup

- **Visual Studio:** for development

- **Git Bash:** for updating repository

# Task 1: Writing a Mail to Associate Director

**Objective**

In the first task, it was required to draft a professional email to the Associate Director of BCG, outlining the approach to understanding and mitigating customer churn at PowerCo.

**Content of the Email**

- Introduced the business problem of customer churn at PowerCo.

- Highlighted the importance of identifying key factors influencing customer churn.

- Proposed a data-driven investigation using techniques such as Exploratory Data Analysis (EDA), segmentation, predictive modeling and customer lifetime value (CLV) analysis.

- Requested the necessary data from PowerCo, including customer information, pricing data, feedback and competitor data.

[View Task 1 mail](https://github.com/BIKASH1002/BCG-Job-Simulation/blob/21a25ca488133cd7f86c74b38082fe16c7f4551c/Task%201/Mail%20to%20AD.pdf)

# Task 2: Exploratory Data Analysis (EDA)

**Objective**

The second task focused on performing an in-depth Exploratory Data Analysis (EDA) to understand the characteristics of PowerCo’s customers and identify potential indicators of churn.

**Key Steps**

- Imported and cleaned the dataset to remove any null values or inconsistencies.
  
- Described the statistics for key variables such as consumption, margins, and churn rates.

- Detected outliers that could potentially skew the analysis and require treatment in later stages.

- Visualized the distribution of various factors such as sales channels, number of products, and customer tenure to identify trends affecting churn.

[View Task 2 code](https://github.com/BIKASH1002/BCG-Job-Simulation/blob/21a25ca488133cd7f86c74b38082fe16c7f4551c/Task%202/Task%202.ipynb)
  
**Visualizations**

- Churn distribution across various customer categories.
 
- Impact of sales channels, products and contract durations on churn rates.

# Task 3: Feature Engineering

**Objective**

In the third task, it was required to engineer new features to improve the predictive power of the model.

**Key Steps**

- Created new features such as off-peak-diff to capture variations in off-peak energy pricing.
  
- Transformed categorical variables into numerical codes for model compatibility.
  
- Scaled numerical features to ensure that features with different ranges do not adversely affect the model.
  
- Processed missing values to prepare the dataset for modeling.
  
**Final Feature Engineered Data**

The feature-engineered dataset consisted of 52 columns with transformed variables ready for model training.

[View Task 3 code](https://github.com/BIKASH1002/BCG-Job-Simulation/blob/21a25ca488133cd7f86c74b38082fe16c7f4551c/Task%203/Task%203.ipynb)

# Task 4: Modeling, Evaluation and Executive Summary

**Objective**

The final task involved building a predictive model to forecast customer churn and summarizing the findings in an executive report.

**Key Steps**

- **Modeling:** Trained a Random Forest Classifier on the engineered dataset to predict customer churn.

- **Evaluation:**

  - Achieved 90% accuracy.

  - Precision for predicting non-churn customers was 90%, while churn prediction had a lower precision due to class imbalance.

  - Created a confusion matrix and feature importance plots to assess the model’s performance.
 
[View Task 4 code](https://github.com/BIKASH1002/BCG-Job-Simulation/blob/21a25ca488133cd7f86c74b38082fe16c7f4551c/Task%204/Task%204.ipynb) 

**Executive Summary**

- The churn rate in the dataset was found to be 9.7%.
  
- Key drivers for churn included yearly consumption, forecasted consumption and net margin.
  
- Implementing a 20% discount strategy could be effective for high-value customers with a high likelihood of churn.

[View Exceutive Summary](https://github.com/BIKASH1002/BCG-Job-Simulation/blob/21a25ca488133cd7f86c74b38082fe16c7f4551c/Task%204/Executive%20Summary.pdf)

# Conclusion

This project provided a comprehensive experience of a real-world data science workflow from communicating with stakeholders to building predictive models. The insights derived from the data, along with the predictive model, could help PowerCo reduce customer churn and focus on retention strategies for high-value customers.

</div>

# Credits

BCG, Forage
