# Studying Recurrence of Well-Differentiated Thyroid Cancer

## Overview
This project aims to develop a predictive model for the recurrence of well-differentiated thyroid cancer using machine learning techniques. The dataset includes 17 variables from 383 patients, collected over a 15-year period.

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
# Dataset Variables

| No. | Variable Name                | Type       | Description                                                                                 |
| --- | ---------------------------- | ---------- | ------------------------------------------------------------------------------------------- |
| 1   | Age                          | Continuous | The age of the patient at the time of diagnosis or treatment                                |
| 2   | Gender                       | Categorical| The gender of the patient (male or female)                                                  |
| 3   | Smoking                      | Categorical| Whether the patient is a smoker or not                                                      |
| 4   | HX-Smoking                   | Categorical| Smoking history of the patient (e.g., whether they have ever smoked)                        |
| 5   | HX-Radiotherapy              | Categorical| History of radiotherapy treatment for any condition                                         |
| 6   | Thyroid Function             | Categorical| The status of thyroid function, possibly indicating if there are any abnormalities          |
| 7   | Physical Examination         | Categorical| Findings from a physical examination of the patient, which may include palpation of the thyroid gland and surrounding structures |
| 8   | Adenopathy                   | Categorical| Presence or absence of enlarged lymph nodes (adenopathy) in the neck region                 |
| 9   | Pathology                    | Categorical| Specific types of thyroid cancer as determined by pathology examination of biopsy samples   |
| 10  | Focality                     | Categorical| Whether the cancer is unifocal (limited to one location) or multifocal (present in multiple locations) |
| 11  | Risk                         | Categorical| The risk category of the cancer based on various factors, such as tumor size, extent of spread, and histological type |
| 12  | T                            | Categorical| Tumor classification based on its size and extent of invasion into nearby structures        |
| 13  | N                            | Categorical| Nodal classification indicating the involvement of lymph nodes                              |
| 14  | M                            | Categorical| Metastasis classification indicating the presence or absence of distant metastases          |
| 15  | Stage                        | Categorical| The overall stage of the cancer, typically determined by combining T, N, and M classifications |
| 16  | Response                     | Categorical| Response to treatment, indicating whether the cancer responded positively, negatively, or remained stable after treatment |
| 17  | Recurred (Dependent)         | Categorical| Indicates whether the cancer has recurred after initial treatment                           |

This dataset includes a total of 17 variables collected from 383 patients over a 15-year period, with each patient followed for at least 10 years. Among these, 16 variables are categorical and 1 variable is continuous.

  
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
