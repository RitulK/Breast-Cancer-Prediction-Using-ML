**Breast Cancer Prediction Using Machine Learning**

Overview

This project is a web-based application that predicts the likelihood of breast cancer in patients based on user-provided medical input data. It uses a Random Forest Classifier to analyze features extracted from a public dataset and provides a diagnosis along with the confidence score. The app is built using Flask for the web interface and leverages scikit-learn for machine learning.

Features:

Web-Based Interface: An easy-to-use form where users can input medical parameters.

Machine Learning Model: A Random Forest Classifier trained on a breast cancer dataset.

Prediction and Confidence Score: The app predicts whether the patient is likely to have breast cancer and provides the confidence percentage.

Interactive Results: The app dynamically displays results based on user input.

Dataset

Link: https://raw.githubusercontent.com/apogiatzis/breast-cancer-azure-ml-notebook/master/breast-cancer-data.csv

It contains medical information about breast cancer cases, such as:

texture_mean

perimeter_mean

smoothness_mean

compactness_mean

symmetry_mean

Diagnosis (M for malignant, B for benign)

Technologies Used:

Programming Language: Python

Framework: Flask for the web application

Machine Learning: Random Forest Classifier from scikit-learn

Libraries:

Pandas: For data handling

Scikit-learn: For machine learning

Flask: For building the web interface

![image](https://github.com/user-attachments/assets/a114f0e8-7148-452d-b7b7-cd70376c29ff)
