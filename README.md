# Credit Card Fraud Detection 🕵️‍♂️💳

This project demonstrates how to build a simple machine learning model to detect credit card fraud using logistic regression. It uses a public dataset and standard data science tools in Python.

## 📦 Dataset

The dataset used is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains transactions made by credit cards in September 2013 by European cardholders.

- Features are numerical values from PCA transformation.
- Highly imbalanced data: 492 frauds out of 284,807 transactions.

## ⚙️ Workflow

1. Load and inspect data.
2. Preprocess the dataset.
3. Split into training and test sets.
4. Train a Logistic Regression model.
5. Evaluate the model using accuracy score.

## 🛠️ Technologies Used

- Python 🐍
- pandas
- NumPy
- scikit-learn

## 🚀 How to Run

1. Clone this repository.
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download) and place `creditcard.csv` in the root directory.
3. Install the dependencies:

```bash
pip install -r requirements.txt
