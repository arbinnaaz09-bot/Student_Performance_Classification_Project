## Student Performance Classification Project

## Project Overview

This project builds a supervised machine learning classification model to predict whether a student will pass or fail.

Two machine learning algorithms were compared:

- Logistic Regression
- Random Forest Classifier

## Dataset

The dataset contains 395 student records and 33 original features.

The target variable was created using the final grade:

- Pass = 1 when G3 >= 10
- Fail = 0 when G3 < 10

The columns G1, G2, and G3 were removed from the input features to prevent data leakage.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Environment Setup

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter