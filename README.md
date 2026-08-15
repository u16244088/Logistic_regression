# Logistic Regression – Credit Card Approval Prediction

##  Project Overview

This project demonstrates the implementation of a **Logistic Regression classification model** to predict whether an individual's **credit card application will be approved or rejected**.

The project focuses on building a complete machine learning workflow, from **data loading and preprocessing to exploratory data analysis, model training, and performance evaluation**.

The Logistic Regression model is implemented **from scratch** to strengthen understanding of the underlying mathematics and concepts behind classification algorithms.

##  Objectives

By completing this project, the key objectives are to:

* Implement **Logistic Regression from scratch** for a binary classification problem.
* Preprocess a real-world dataset containing **numerical and categorical features**.
* Handle **missing values** and differences in feature scales.
* Perform **Exploratory Data Analysis (EDA)** to understand the dataset and identify important patterns.
* Train a Logistic Regression model to predict credit card application outcomes.
* Evaluate the model using appropriate **classification metrics**.
* Develop practical problem-solving skills by applying machine learning to a real-world classification problem.

## 📊 Dataset

The dataset contains information about individuals applying for credit cards. It includes a combination of:

* Numerical features
* Categorical features
* Missing values
* Features with different numerical ranges

The target variable represents whether an individual's **credit card application was accepted or rejected**.

## Project Workflow

The project follows a standard machine learning workflow:

```text
Data Loading
     ↓
Data Exploration
     ↓
Data Cleaning
     ↓
Missing Value Handling
     ↓
Categorical Feature Encoding
     ↓
Feature Scaling
     ↓
Exploratory Data Analysis
     ↓
Train/Test Split
     ↓
Logistic Regression
     ↓
Model Evaluation
```

##  Data Preprocessing

Before training the model, the dataset is prepared to ensure that it is suitable for machine learning.

The preprocessing steps include:

* Inspecting the structure and characteristics of the dataset.
* Identifying and handling **missing values**.
* Separating numerical and categorical variables.
* Encoding categorical variables into numerical representations.
* Scaling numerical features where necessary.
* Preparing the feature matrix and target variable.
* Splitting the dataset into training and testing sets.

##  Exploratory Data Analysis

Exploratory Data Analysis is performed to understand the underlying patterns within the data.

This includes investigating:

* Feature distributions
* Relationships between variables
* Class distribution
* Potential correlations
* Differences between approved and rejected applications

These insights help build an understanding of the factors that may influence credit card approval.

##  Logistic Regression

Logistic Regression is a supervised machine learning algorithm commonly used for **binary classification**.

In this project, the model predicts one of two possible outcomes:

```text
1 → Application Approved
0 → Application Rejected
```

The model uses the **sigmoid function** to convert the predicted value into a probability:

[
\sigma(z) = \frac{1}{1 + e^{-z}}
]

The resulting probability is then used to classify an application into one of the two classes.

##  Implementation From Scratch

Rather than relying entirely on a pre-built machine learning library, Logistic Regression is implemented from scratch to understand the core mechanics of the algorithm.

The implementation covers concepts such as:

* Model parameters and weights
* Bias/intercept
* Sigmoid activation
* Prediction
* Loss function
* Gradient descent
* Parameter updates
* Classification threshold

This provides a deeper understanding of how Logistic Regression learns from data.

##  Model Evaluation

The trained model is evaluated on unseen test data using classification metrics such as:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-score**
* **Confusion Matrix**

These metrics help determine how effectively the model distinguishes between approved and rejected credit card applications.

## 🛠️Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **Machine Learning / Statistical Modelling**

## 📁 Project Structure

```text
logistic-regression/
│
├── README.md
├── logistic_regression.ipynb
├── data/
│   └── dataset.csv
│
└── requirements.txt
```

##  Key Learning Outcomes

Through this project, I gained practical experience in:

* Building a machine learning classification pipeline.
* Implementing Logistic Regression from first principles.
* Preparing real-world datasets for modelling.
* Handling missing and categorical data.
* Performing exploratory data analysis.
* Evaluating classification models.
* Understanding the mathematical foundations behind Logistic Regression.

##  Conclusion

This project demonstrates the complete process of developing a **binary classification model**, from raw data preparation through to model evaluation. Implementing Logistic Regression from scratch provides a stronger understanding of how classification algorithms work internally and how preprocessing and data quality can influence model performance.

