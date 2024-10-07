# Heart Disease Prediction

This repository contains a project that predicts the presence of heart disease using various machine learning algorithms. The project uses a dataset that contains several health metrics to train models and evaluate their performance.

## Project Overview

This project aims to predict whether a person has heart disease based on features such as age, sex, cholesterol level, resting blood pressure, and more. We use a combination of exploratory data analysis (EDA) and machine learning algorithms to evaluate the prediction accuracy.

The models implemented include:
- Random Forest Classifier
- Gradient Boosting Classifier
- Decision Tree Classifier

## Technologies Used

- **Python**
- **Pandas**: for data manipulation
- **NumPy**: for numerical computations
- **Matplotlib**: for data visualization
- **Seaborn**: for plotting heatmaps and data correlations
- **Scikit-learn**: for machine learning model implementation

## Dataset

The dataset used in this project is the heart disease dataset. It contains features such as:
- Age
- Sex
- Chest pain type (`cp`)
- Resting blood pressure (`trestbps`)
- Cholesterol (`chol`)
- Maximum heart rate achieved (`thalach`)
- and others...

The target variable (`target`) is binary:
- 0: No Heart Disease
- 1: Heart Disease

## Exploratory Data Analysis

We performed EDA to understand the distribution of the data and visualize the correlations between various features. Key graphs and plots include:

- Bar plot showing distribution of patients with and without heart disease.
- Histograms of categorical and continuous variables based on the target label.
- Correlation heatmap of features.

## Machine Learning Models

We implemented three machine learning models to predict heart disease:
1. **Random Forest Classifier**: A robust ensemble method using decision trees.
2. **Gradient Boosting Classifier**: An advanced boosting algorithm for better accuracy.
3. **Decision Tree Classifier**: A simple tree-based model.

We applied normalization and one-hot encoding to preprocess the data and used a `train_test_split` to create training and testing sets.

## Model Evaluation

For each model, we evaluated performance using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The model scores were visualized in a bar plot, comparing the training and testing accuracy for all models.

## User Data Simulation

The project also generates user-specific data for predictions, simulating health metrics for new patients. The Random Forest classifier was trained on this simulated data with a test accuracy of around 50%.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    ```
2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook or script to train the models and view results.

## Results

### Accuracy Comparison (Iteration 1)

| Model                       | Training Accuracy % | Testing Accuracy % |
| ---------------------------- | ------------------ | ------------------ |
| Random Forest Classifier      | 85.25%             | 81.82%             |
| Gradient Boosting Classifier  | 86.84%             | 84.09%             |
| Decision Tree Classifier      | 78.69%             | 75.00%             |

### Accuracy Comparison (Iteration 2)

| Model                       | Training Accuracy % | Testing Accuracy % |
| ---------------------------- | ------------------ | ------------------ |
| Random Forest Classifier      | 79.31%             | 75.00%             |
| Gradient Boosting Classifier  | 82.47%             | 81.82%             |
| Decision Tree Classifier      | 74.07%             | 70.45%             |

---
