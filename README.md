# Task-4
Feature Encoding and Scaling – Adult Income Dataset Project Overview

This project is part of the AI & ML Internship – Task 4: Feature Encoding & Scaling. The objective is to preprocess the Adult Income Dataset by applying appropriate feature encoding techniques and numerical feature scaling to prepare the dataset for machine learning models.

Feature engineering is a critical step in the ML pipeline, as many algorithms require numerical and scaled input data for optimal performance.

Dataset Description

Dataset Name: Adult Income Dataset

Target Variable:

income (Binary classification: <=50K or >50K)

Columns Used

Numerical Features

age

fnlwgt

education.num

Categorical Features

workclass

education

marital.status

occupation

relationship

race

sex

native.country

Tools and Technologies

Python

Pandas

NumPy

Scikit-learn

Google Colab

Preprocessing Steps

Data Cleaning
Replaced missing values represented as ? with NaN.

Removed rows containing missing values to maintain data consistency.

Target Encoding
Applied Label Encoding to the target column (income) to convert categorical labels into numeric form.

Feature Encoding
One-Hot Encoding was applied to categorical features where no ordinal relationship exists.

This avoids introducing unintended priority or ranking between categories.

Feature Scaling
StandardScaler was applied to numerical features.

Scaling ensures all numerical features have zero mean and unit variance.

Feature Transformation
Used ColumnTransformer to apply encoding and scaling in a single pipeline.

Ensured compatibility with modern versions of scikit-learn.

Final Output

Fully preprocessed and model-ready dataset.

Encoded categorical features and scaled numerical features.

Saved processed dataset as a CSV file for reuse.# task4-feature-encoding-and-scaling

