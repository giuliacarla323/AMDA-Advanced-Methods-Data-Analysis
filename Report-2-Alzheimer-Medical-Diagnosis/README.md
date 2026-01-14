# Medical Diagnosis for Alzheimer's Disease using Diverse Classification Methods

This project explores the application of various machine learning paradigms for the early detection of Alzheimer's disease, focusing on model performance and clinical reliability.

## 🎯 Objectives
The primary goal was to compare three distinct machine learning approaches to identify the most effective model for clinical diagnosis:
- **Linear Models**: Logistic Regression for an interpretable baseline.
- **Ensemble Learning**: Random Forest for capturing non-linear relationships.
- **Deep Learning**: Multi-Layer Perceptron (MLP) for high-dimensional pattern recognition.

## 📊 Dataset & Preprocessing
The study used a clinical dataset of **2,149 patient records** characterized by **35 features**.
- **Data Integrity**: Implemented a pipeline for data cleaning and feature scaling.
- **Class Imbalance**: Utilized **SMOTE** (Synthetic Minority Over-sampling Technique) to address the minority class.
- **Validation**: Applied **stratified cross-validation** to ensure generalizability.

## 🛠️ Implementation Details
- **Logistic Regression**: Analyzed as a baseline with high interpretability.
- **Random Forest**: Configured as an ensemble of decision trees to improve stability.
- **MLP (Deep Learning)**: Designed with optimized hidden layers for binary classification.

## 📈 Key Results
- **Random Forest** achieved the best performance with a **ROC-AUC score of 0.9422**, showing a superior balance between precision and recall.
- **Logistic Regression** provided a robust and explainable baseline.
- **MLP** showed potential but struggled with misdiagnosing healthy patients in this specific clinical context.
