# Loan Default Prediction

A Machine Learning project for predicting loan default based on borrower and loan-related information.

## Project Overview

The project focuses on preparing a loan dataset and building classification models to predict whether a borrower is likely to default on a loan.

The notebook includes data cleaning, preprocessing, feature engineering, model training, and evaluation.

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)

## Data Preprocessing

The dataset was prepared through several steps, including:

* Handling missing values
* Data cleaning
* Encoding categorical features
* Feature engineering
* Feature scaling
* Splitting the data into training and testing sets

## Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Project Files

```text
Loan-Default-Prediction/
│
├── Loan_default.csv
├── loan_default_prediction.ipynb
├── best_model.pkl
├── preprocessor.pkl
└── README.md
```

### Files Description

**Loan_default.csv**
The dataset used for the project.

**loan_default_prediction.ipynb**
Contains the data preprocessing, feature engineering, model training, and evaluation steps.

**best_model.pkl**
Saved trained model.

**preprocessor.pkl**
Saved preprocessing object used before model prediction.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib
* Jupyter Notebook

## How to Run

Clone the repository:

```bash
git clone https://github.com/jana-essam-ai/Loan-Default-Prediction.git
```

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

Open the notebook and run the cells in order.
