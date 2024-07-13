# code_alpha_task01
# Titanic Classification Project
## Overview:
This project aims to build a system to predict whether a person would survive the Titanic disaster based on various factors such as socio-economic status, age, gender, and more. This is part of an internship task.
## Table of Contents

 - Introduction
 - Data Preprocessing
 - Model Building
 - Evaluation and Results
 - Conclusion
 - How to Run
 - Dependencies
 - Contact

## Introduction
The Titanic dataset provides information on the passengers aboard the Titanic, which sank after colliding with an iceberg. This project utilizes the dataset to predict survival using several machine learning algorithms.
## Data Preprocessing
 1. **Loading and Exploring Data :** Initial exploration of the dataset including shape, data types, and missing values.
 2. **Handling the Missing Values:** 
 Visualization of missing data, imputation of missing ages based on passenger class, and removal of columns  with excessive missing values.

 3. **Features Selection and Encoding:** Removal of unnecessary columns, conversion of categorical variables to numerical using one-hot encoding, and preparation of the dataset for model training.
## Model Building
1. **Logistic Regression:** A linear model for binary classification.
2. **Decision Tree Classifier:** A non-linear model that splits data based on feature values.
3. **Random Forest Classifier:** An ensemble method using multiple decision trees.
4. **Gradient Boosting Classifier:** An ensemble method that builds trees.
## Evaluation and Result
For each model, the following metrics were calculated:

+ Accuracy
+ Precision
+ Recall
+ Confusion Matrix
The Gradient Boosting Classifier achieved the highest accuracy, making it the best-performing model in this project.
## Conclusion
The Gradient Boosting Classifier was identified as the best model for predicting survival on the Titanic. Factors such as socio-economic status, age, and gender were significant in determining survival.

## How to Run
  1. Clone the Repository
```
git clone https://github.com/Touseef-Asif/codealpha_task01.git

```
2. Navigate to the Project directory
```
cd titanic-classification

```
3. Install the required Dependencies
```
pip install numpy
pip install pandas
pip install scikit-learn
pip install matplotlib
pip install seaborn

```
4. Run the Jupyter Notebook to see the data preprocessing, model training, and evaluation steps:
```
jupyter notebook https://github.com/Touseef-Asif/codealpha_task01/blob/main/Titanic_dataset_classification_task01.ipynb

```

## Contact
If you have any questions or feedback, please feel free to reach out to me:

+ Name: Touseef Asif
+ Email: touseefasifbgh533@gmail.com
+ GitHub: https://github.com/Touseef-Asif
