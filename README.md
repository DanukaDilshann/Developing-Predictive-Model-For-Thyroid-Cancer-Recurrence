# Studying Recurrence of Well-Differentiated Thyroid Cancer
<!-- Background image section -->
<div style="background-image: url('https://github.com/DanukaDilshann/Developing-Predictive-Model-For-Thyroid-Cancer-Recurrence/blob/main/Images/images.jpeg?raw=true'); background-size: cover; padding: 20px; border-radius: 10px; color: white; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);">

# Welcome to My Project

This is a brief introduction to my project. Here you can add any Markdown content you like.

- Feature 1
- Feature 2
- Feature 3

</div>

  
## Overview
This document presents a comprehensive study aimed at developing a predictive model for the recurrence of well-differentiated thyroid cancer using machine learning techniques. It leverages various patient factors such as age, gender, smoking history, thyroid function, and cancer stage to build and evaluate different models. The study's core focus is on enhancing diagnostic accuracy, early detection, and optimized treatment planning in clinical practice, ultimately improving patient management and outcomes.

## Objective
The objective is to develop a predictive model for the recurrence of well-differentiated thyroid 
cancer using machine learning techniques.

## Significance of the Study
Developing a machine learning model can significantly enhance diagnostic accuracy and early 
detection of thyroid cancer, thereby improving patient treatment outcomes and management. 
Integrating this model into clinical practice will aid healthcare professionals in making informed 
decisions and optimizing treatment plans.

## Dataset
The dataset contains the following variables:
- Age
- Gender
- Treatment response
- Recurrence status 
#### Additionally, the dataset includes 13 other variables.For a detailed description of all variables, see the [full variable description](https://github.com/DanukaDilshann/Predictive-Model-For-Thyroid-Cancer-Recurrence/blob/main/Data/Data%20Description.md).

## Data Preprocessing
- No missing values were found.
- 19 duplicate records were removed, leaving **364 unique patient records**.
  - #### Handling Data Imbalance
  The dataset exhibited an imbalance between the number of recurrent and non-recurrent cases. 
  To address this, we employed the Synthetic Minority Over-sampling Technique (SMOTE). SMOTE synthesizes new examples from the minority class to 
  achieve a balanced dataset, improving the performance of the machine learning models.
  - #### One-Hot Encoding
   To handle categorical variables, we applied one-hot encoding to convert them into a format suitable for machine learning algorithms.
## Machine Learning Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest


#### Other Statistical Techniques Used: 
   - Chi-Square Test: Perform a chi-square test to determine if there is a significant 
    association between categorical variables.
    
   - Kruscal wallis test: Kruskal Wallis test is a non-parametric method.it used to compare three or more independent 
      groups of sampled data and determine if there are statistically significant difference between 
       their medians. 

## Key Findings
- The SVM model achieved a 97% accuracy level, surpassing the accuracies of the other 
models.
- Additionally, our findings reveal a significant association between smoking and thyroid 
cancer recurrence. Patients who smoke have a higher likelihood of experiencing a 
recurrence.
- Further, patients with high stage thyroid cancer experience a lower response rate to the 
treatment compared to the other stage patients. 
- Moreover, patients with cancer present in multiple locations have a higher risk of thyroid 
cancer recurrence.
- However, there is no observed association between the type of thyroid function 
(hypothyroidism or hyperthyroidism) and the recurrence of thyroid cancer.
- Furthermore, younger patients show a notably better response to treatment compared to 
other age groups.


## Repository Structure
- `Data/`: Dataset [Thyroid Cancer Recurrence](https://www.kaggle.com/datasets/jainaru/thyroid-disease-data)
- `Notebooks/`: Jupyter notebooks for data analysis.
- `Reports/`: [Model Comparisons](https://github.com/DanukaDilshann/Predictive-Model-For-Thyroid-Cancer-Recurrence/blob/main/Reports/Model_Performance.md)

## How to Use
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebooks in the `Notebooks/` directory.
</div>
