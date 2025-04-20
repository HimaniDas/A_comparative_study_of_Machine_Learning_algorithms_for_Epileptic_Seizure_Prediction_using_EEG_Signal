# Epileptic Seizure Prediction using EEG Signals

## 📄 Project Overview

This project presents a comparative study of various machine learning algorithms for predicting epileptic seizures using EEG (Electroencephalogram) signals. Our work evaluates nine machine learning models to determine the most effective technique for accurate seizure prediction.

## 🧠 Motivation

Epilepsy affects millions of people worldwide. Predicting seizures in advance can greatly improve patient safety and quality of life. Traditional seizure detection requires expert interpretation of EEG data, which is time-consuming. Our goal is to automate this process using machine learning to assist medical professionals and provide early warnings to patients.

## 📊 Dataset

The EEG dataset used for this study was sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Epileptic+Seizure+Recognition). Each data record consists of a 23.6-second EEG reading, with each sample representing a point in time. The dataset contains five classes, with only one representing seizure activity.

## 🔧 Machine Learning Models Used

We implemented and compared the performance of the following algorithms:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression
- Gaussian Naive Bayes
- Decision Tree
- Random Forest
- Extra Tree Classifier
- Gradient Boosting
- AdaBoost

## 📈 Results

After training and evaluation, **Support Vector Machine (SVM)** showed the best performance, achieving an accuracy of **98.26%** in predicting epileptic seizures.

## 🔍 Methodology

The steps followed in this project:
1. Data Preprocessing (cleaning, normalization, train-test split)
2. Feature Engineering and Visualization
3. Training of Multiple ML Models
4. Evaluation using metrics like Accuracy, F1-Score, ROC-AUC, Precision, and Recall
5. Comparison of Model Performance

## 📂 Project Structure

```plaintext
├── data/                  # EEG dataset
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── models/                # Trained model files (optional)
├── results/               # Plots, performance metrics
├── thesis_report.pdf      # Full project documentation
└── README.md              # Project summary
