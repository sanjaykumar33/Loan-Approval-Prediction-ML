# Loan Approval Prediction using Machine Learning

📌 Project Overview

This project predicts whether a customer's loan application will be **Approved (1)** or **Rejected (0)** using Machine Learning.

The project demonstrates a basic end-to-end Machine Learning workflow using Python and Scikit-learn.

## 🎯 Objective

To build a Machine Learning classification model that predicts loan approval based on customer demographic and financial information.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## 🔄 Machine Learning Workflow

1. Load the dataset
2. Analyze missing values
3. Handle missing values
4. Encode categorical data
5. Separate features and target
6. Split data into training and testing sets
7. Train Logistic Regression model
8. Generate predictions
9. Evaluate model performance

## 🧹 Data Preprocessing

* Missing values in `Income` were handled using the **Mean**.
* Missing values in `Employment_Type` were handled using the **Mode**.
* `Employment_Type` was converted into numerical values using **Label Encoding**.

## 🤖 Machine Learning Model

**Algorithm:** Logistic Regression

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

## 📊 Model Performance

The Logistic Regression model achieved:

**Accuracy: 79%**

Model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 📂 Project Structure

```text
Loan-Approval-Prediction-ML/
│
├── loan_approval_1000.csv
├── loan_approval.py
└── README.md
```

## 🚀 Future Improvements

* Compare different Machine Learning algorithms
* Improve model performance using hyperparameter tuning
* Perform feature importance analysis
* Build a user interface for real-time loan prediction

## 👨‍💻 Author

**Sanjay Kumar S**

Electronics and Communication Engineering | Data Analytics | Machine Learning
