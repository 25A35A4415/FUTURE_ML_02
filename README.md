# FUTURE_ML_02 - Support Ticket Classification

## Project Overview

This project is developed as part of the Future Interns Machine Learning Internship.

The goal of this project is to build a Machine Learning model that automatically classifies customer support tickets and assigns priority levels (High, Medium, Low).

This system helps support teams handle customer issues faster by identifying important tickets automatically.

---

## Problem Statement

Customer support teams receive many tickets every day. Manually checking and prioritizing each ticket takes time.

This project uses Natural Language Processing (NLP) and Machine Learning to classify support tickets and predict their priority level.

---

## Objectives

- Clean and preprocess customer ticket text
- Convert text data into numerical features
- Train a machine learning classification model
- Predict ticket priority levels
- Evaluate model performance

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- NLTK
- TF-IDF Vectorizer
- Logistic Regression

---

## Workflow

1. Data Collection
2. Data Cleaning
3. Text Preprocessing
4. Feature Extraction using TF-IDF
5. Model Training
6. Prediction
7. Model Evaluation

---

## Machine Learning Model

Algorithm Used:

**Logistic Regression**

Reason:
- Works well for text classification problems
- Fast and efficient
- Suitable for multi-class classification

---

## Dataset

The dataset contains customer support tickets with their assigned priority levels.

Features:

- Ticket Text
- Priority Level

Priority Classes:

- High
- Medium
- Low

---

## Text Processing

The following preprocessing steps were performed:

- Converted text into lowercase
- Removed unwanted characters
- Converted text into numerical vectors using TF-IDF

---

## Model Evaluation

The model performance was evaluated using:

- Accuracy Score
- Classification Report

---

## Sample Prediction

Example:

Input:

"My money was deducted and transaction failed"

Output:

Priority: High

---

## Project Files
