# Iris Flower Classification Using Machine Learning

This project is a beginner-level Machine Learning classification project built using Python and Scikit-learn. The model classifies iris flowers into different species based on their physical measurements.

## Project Overview

The project demonstrates the complete Machine Learning workflow:

- Loading and understanding a dataset
- Data preprocessing
- Separating features and target
- Splitting data into training and testing sets
- Feature scaling
- Training a Logistic Regression model
- Making predictions
- Evaluating model performance

This project was completed as part of the DecodeLabs Artificial Intelligence Industrial Training Program.

---

# Dataset

The project uses the Iris Dataset from Scikit-learn.

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Classes:
- Setosa
- Versicolor
- Virginica

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

# Machine Learning Workflow

## 1. Load Dataset
The Iris dataset is loaded using Scikit-learn and converted into a Pandas DataFrame.

## 2. Data Preprocessing
The preprocessing phase includes:
- Checking missing values
- Checking duplicate rows
- Removing duplicates
- Inspecting dataset information

## 3. Feature & Target Separation
- Features (X): flower measurements
- Target (y): flower species

## 4. Train/Test Split
The dataset is split into:
- 80% training data
- 20% testing data

## 5. Feature Scaling
StandardScaler is used to normalize feature values before training.

## 6. Model Training
A Logistic Regression model is trained using the training dataset.

## 7. Prediction & Evaluation
The model is evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

# Results

Model Accuracy:
```python
Accuracy: 1.0

---

How to Run
Install Required Libraries -> pip install pandas numpy scikit-learn
Run the Notebook -> Open the notebook using Jupyter Notebook or VS Code and run all cells.

Concepts Learned
This project helped practice:
Supervised Learning
Classification Problems
Data Preprocessing
Feature Scaling
Logistic Regression
Model Evaluation Metrics


