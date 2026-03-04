# Insurance Charge Prediction Using Machine Learning
## Project Overview
This project applies supervised machine learning techniques to predict insurance-related outcomes using structured demographic and policy data. The objective was to evaluate model performance and determine whether nonlinear approaches improve predictive accuracy compared to traditional linear modeling. 
Two models were implemented and compared:
* Linear Regression
* Random Forest Regressor

NOTE: This notebook was developed and executed using Google Colab.

---

## Problem Statement
Accurate prediction of insurance-related outcomes is critical for underwriting precision, pricing strategy, and financial risk management. Traditional linear models may fail to capture complex nonlinear relationships within policyholder data.

This project evaluates whether ensemble-based machine learning models provide improved predictive performance over baseline linear regression. 

---

## Dataset Overview
The dataset includes structured features such as:
* Age
* BMI
* Number of dependents
* Smoking status
* Region
* Other demographic attributes

Target Variable:
* Insurance outcome

Data was cleaned, encoded, and split into training and testing sets before modeling.

---

## Modeling Approach

1. Data preprocessing and encoding
2. Train/test split
3. Linear Regression implementation
4. Random Forest implementation
5. Model evaluation using R²

---

## Results
| Model               | Train R² | Test R² |
|---------------------|----------|---------|
| Linear Regression   | 0.75     | 0.74    |
| Random Forest       | 0.97     | 0.86    |

Random Forest outperformed Linear Regression on both training and test datasets, demonstrating improved predictive performance while capturing nonlinear relationships.

---

## Business Implications
Improved predictive accuracy enables:
* More precise underwriting
* Optimized pricing strategies
* Reduced financial risk exposure
* Enhanced decision-making through data-driven modeling

Machine learning approaches provide measurable value over traditional linear techniques in structured insurance datasets. 

---

## Future Improvements
* Hyperparameter tuning (GridSearchCV)
* Cross-validation
* Testing gradient boosting models

---

## Technologies Used
* Python
* pandas
* numpy
* scikit-learn
* matplotlib

---

## Dataset Source
The dataset used in this project was obtained from Kaggle:
"Medical Cost Personal Dataset"
https://www.kaggle.com/code/mragpavank/medical-cost-personal-datasets/notebook

The dataset includes demographic and health-related attributes used to predict insurance charges.

To reproduce this project:
1. Download the dataset from Kaggle.
2. Place the CSV file in a retrievable directory.
3. Run the notebook using the desired approach.

---

## Author

Kelli Carroll
Data Analyst | Data Scientist
