# Breast Cancer Prediction Streamlit App

This project is a web application built using Streamlit to predict breast cancer based on user input and analyze a dataset of breast cancer cases. The app allows users to explore breast cancer-related data, predict malignancy of tumors, and evaluate different machine learning models.

## Overview
This project is a machine learning-powered web application developed using Streamlit to predict breast cancer diagnoses. Breast cancer prediction is critical for early detection, where the goal is to accurately classify tumors as malignant or benign based on medical data, helping to guide treatment decisions.
## Key Features
### 1. *Data Exploration and Visualization*:

The app provides interactive exploration of a breast cancer dataset, which typically includes features derived from medical scans, such as tumor size, texture, and radius. Users can visualize data patterns, such as the distribution of benign vs. malignant tumors, using charts, histograms, and correlation heatmaps.

### 2. *Cancer Diagnosis Prediction*:

The core functionality of the app is to predict whether a tumor is malignant or benign based on user inputs. The prediction is powered by machine learning models trained on historical medical data. The app offers real-time predictions by accepting user-specified features (e.g., radius, texture) and predicting whether the tumor is likely to be malignant or benign.

### 3. *Machine Learning Models*:

The app implements multiple machine learning models such as K-Nearest Neighbors (KNN), Random Forest, and Logistic Regression to classify tumors as malignant or benign. These models are trained on labeled datasets where each tumor is identified as either malignant or benign, aiming to achieve high classification accuracy and reduce misdiagnosis risks.

### 4. *Model Evaluation and Comparison*:

Users can evaluate the performance of different machine learning models using metrics like accuracy, precision, recall, F1-score, and AUC-ROC. The app allows comparison of model performance in identifying malignant tumors while minimizing the risk of incorrectly classifying benign cases as malignant.

## About Dataset

The dataset used in this project contains breast cancer cases with detailed medical information. It includes features extracted from digitized images of breast masses, particularly important for early cancer detection.
### Features
-Radius_mean, Texture_mean, Perimeter_mean, etc.: Various medical features related to the tumor's characteristics.

-Diagnosis: The target variable indicating whether the tumor is benign (0) or malignant (1).
