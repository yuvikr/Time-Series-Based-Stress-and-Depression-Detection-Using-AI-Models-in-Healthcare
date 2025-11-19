# Time Series-Based Stress and Depression Detection Using AI Models in Healthcare

![Project Banner](depressed_proj.jpg)

## Introduction

Mental health is a vital component of overall well-being, with stress and depression being major contributors to reduced productivity, chronic illnesses, and poor quality of life. Traditional methods of assessment, such as self-reports and occasional clinical evaluations, often fail to capture real-time fluctuations in mental states.

However, with the rise of wearable devices and large-scale healthcare datasets, Artificial Intelligence (AI) and time series analysis now enable continuous monitoring of physiological and behavioural data. By uncovering patterns, anomalies, and long-term trends, these AI-driven approaches offer an opportunity for objective, real-time detection and prediction of stress and depression, ultimately supporting preventive care and timely interventions.

## Objectives

- To apply AI-driven time series analysis for detecting stress and depression levels.
- To analyse physiological and behavioural signals for identifying trends and anomalies.
- To perform detection and classification tasks (e.g., "Is the user stressed now?" or "Depressed vs Not Depressed").

## Folder Structure

The project is organized as follows:

```text
├── Output/                       # Contains screenshots of results and visualizations
├── dataset.xlsx                  # The dataset used for training and testing
├── MachineLearningModels.ipynb   # Jupyter Notebook containing data preprocessing and model training
├── webapp.py                     # Python application file (likely Streamlit or Flask) for the user interface
├── CV_BestModel.sav              # The serialized/saved best-performing machine learning model
├── depressed_proj.jpg            # Project banner image
└── README.md                     # Project documentation

```

##Machine Learning Models
The following algorithms were implemented and evaluated to determine the most effective approach for stress and depression detection:

- Random Forest
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)
- Multinomial Naive Bayes
- Logistic Regression

## Results

The model performance and application interface results are stored in the Output/ folder.
