# Holiday Package Purchase Prediction

## Project Overview

This project predicts whether a customer will purchase a holiday package
using machine learning techniques. The main objective is to help travel
companies identify potential customers who are more likely to buy a
holiday package so they can target their marketing efforts effectively.

The dataset was taken from Kaggle and analyzed using Exploratory Data
Analysis (EDA). Multiple machine learning models were trained and
compared to find the best performing model.

------------------------------------------------------------------------

## Dataset

The dataset used in this project is publicly available on Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction

The dataset contains customer-related information such as demographics,
travel history, income, and other attributes that influence whether a
customer decides to purchase a holiday package.

------------------------------------------------------------------------

## Project Workflow

### 1. Data Preprocessing

-   Handling missing values
-   Encoding categorical variables
-   Preparing the dataset for machine learning models

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset and identify patterns that
affect customer purchase behavior.

### 3. Model Training

Multiple machine learning algorithms were trained and evaluated:

-   Logistic Regression
-   Decision Tree
-   Random Forest
-   Gradient Boosting
-   AdaBoost
-   XGBoost

### 4. Model Evaluation

The models were evaluated using metrics such as Accuracy, Precision,
Recall, F1 Score, and ROC-AUC score.

### 5. Hyperparameter Tuning

XGBoost showed the best performance among all models. Hyperparameter
tuning was applied to further improve its performance.

------------------------------------------------------------------------

## Model Performance Comparison


| Model | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.8354 | 0.6829 | 0.2932 | 0.8078 | 0.6301 |
| Decision Tree | 0.9192 | 0.8077 | 0.7696 | 0.9185 | 0.8626 |
| Random Forest | 0.9274 | 0.9545 | 0.6597 | 0.9221 | 0.8260 |
| Gradient Boosting | 0.8589 | 0.7732 | 0.3927 | 0.8398 | 0.6824 |
| AdaBoost | 0.8354 | 0.6630 | 0.3194 | 0.8115 | 0.6400 |
| **XGBoost** | **0.9356** | **0.9507** | **0.7068** | **0.9318** | **0.8490** |

Among all models, XGBoost performed the best with strong accuracy and
overall performance.

------------------------------------------------------------------------

## XGBoost Performance After Hyperparameter Tuning


| Dataset | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|--------|----------|-----------|--------|----------|---------|
| Training Set | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 1.0000 |
| Test Set | 0.9509 | 0.9554 | 0.7853 | 0.9490 | 0.8882 |

After hyperparameter tuning, XGBoost achieved **95.09% accuracy** on the
test dataset.

------------------------------------------------------------------------

## Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   XGBoost
-   Jupyter Notebook

------------------------------------------------------------------------

## Key Learnings

-   Performing Exploratory Data Analysis to understand datasets
-   Training and comparing multiple machine learning models
-   Improving model performance using hyperparameter tuning
-   Evaluating classification models using different metrics

------------------------------------------------------------------------

## Future Improvements

-   Deploy the model using Streamlit or Flask
-   Improve feature engineering
-   Use larger datasets for better generalization
-   Add model explainability techniques such as SHAP

------------------------------------------------------------------------

## Author

This project was developed as part of learning and practicing machine
learning workflows and building real-world predictive models.
