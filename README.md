# Credit Scoring Model (Machine Learning)

## Project Overview

This project implements a **Credit Scoring Model** using Machine Learning to predict whether a customer is **high risk or low risk** when applying for credit. The model analyzes financial and demographic information to estimate the likelihood of credit risk.

The project is implemented in **Python using Jupyter Notebook** and demonstrates the complete Machine Learning workflow including data preprocessing, model training, and evaluation.

---

## Dataset

The dataset used in this project is based on the **German Credit Data** dataset.

### Features in the Dataset

* Age
* Sex
* Job
* Housing
* Saving accounts
* Checking account
* Credit amount
* Duration
* Purpose

Since the dataset does not contain a direct **risk label**, a target column named **Risk** was created based on the credit amount.

Rule used:

* Credit amount **greater than 5000 → High Risk (1)**
* Credit amount **less than or equal to 5000 → Low Risk (0)**

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn

---

## Machine Learning Workflow

The following steps were performed:

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Encoding Categorical Variables
5. Creating Target Variable (Risk)
6. Splitting Data into Training and Testing Sets
7. Training Machine Learning Model
8. Evaluating Model Performance

---

## Model Used

The project uses the **Random Forest Classifier** to predict credit risk.

Random Forest is an ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Evaluation Metrics

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

These metrics help measure how well the model predicts credit risk.

---

## Project Files

```
Credit_Scoring_Project
│
├── Credit_Scoring_Model.ipynb
├── german_credit_data.csv
└── README.md
```

---

## How to Run the Project

1. Clone the repository
2. Install required libraries:

```
pip install pandas numpy scikit-learn
```

3. Open the Jupyter Notebook
4. Run all cells to train and evaluate the model.

---

## Conclusion

This project demonstrates how Machine Learning can be used for **credit risk prediction**. Such models can assist financial institutions in making better lending decisions by identifying high-risk applicants.

---

## Author

Muhammad Shahbaz Malik
CA/SE3/9717
