# Spam-Email-Detection
Spam Email Detection System
Overview
This project implements a spam email detection system using machine learning techniques — specifically Multinomial Naive Bayes and Logistic Regression. The system classifies emails as spam or not spam (ham) based on their content.

The model is trained on the publicly available SMS Spam Collection Dataset, and the project includes:

Data preprocessing (cleaning, tokenization, stemming)

Feature extraction using TF-IDF vectorization

Model training, evaluation, and hyperparameter tuning

Visualization of data distribution and model performance metrics

A Flask API for real-time spam prediction on new emails

FEATURES

High accuracy spam detection (>97%)

Visualization of dataset distribution, confusion matrices, ROC curve, and performance metrics

REST API to classify new email text inputs

Easily extensible for other datasets or models

REQUIREMENTS

Python 3.7+

PACKAGES:

pandas

scikit-learn

nltk

matplotlib

seaborn

joblib

flask

requests (for testing API)
