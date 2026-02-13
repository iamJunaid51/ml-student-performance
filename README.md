# Student Performance Prediction

This project demonstrates a simple supervised machine learning pipeline using Python and scikit-learn.

## Problem Statement
The goal of this project is to predict whether a student will pass an exam based on study hours and attendance percentage.

## Dataset
The dataset contains basic student information including:
- Hours studied
- Attendance percentage
- Pass/Fail label

This dataset is used for academic and learning purposes.

## Approach
- Load and explore the dataset
- Split data into training and testing sets
- Apply feature scaling using StandardScaler
- Train a Logistic Regression model
- Evaluate model performance using accuracy score

## Technologies Used
- Python 3
- pandas
- numpy
- scikit-learn

## How to Run
```bash
pip install -r requirements.txt
python src/train.py
