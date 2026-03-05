# Wine Quality Prediction with PCA

## Project Overview

This project applies **Principal Component Analysis (PCA)** for dimensionality reduction and machine learning classification on the Wine Quality dataset.

The goal is to analyze wine physicochemical properties and predict wine quality using machine learning models after feature transformation.

The project demonstrates the complete machine learning workflow including:

* data preprocessing
* dimensionality reduction using PCA
* model training and evaluation

---

## Dataset

Source: UCI Wine Quality Dataset

Two datasets are included:

* `winequality-red.csv`
* `winequality-white.csv`

Each dataset contains physicochemical measurements of wines such as:

* fixed acidity
* volatile acidity
* citric acid
* residual sugar
* alcohol
* sulphates

Target variable:

```
quality
```

---

## Data Preprocessing

The preprocessing steps include:

* loading datasets using **Pandas**
* feature standardization
* handling numerical features
* separating input features and target labels

---

## Dimensionality Reduction

**Principal Component Analysis (PCA)** is applied to reduce feature dimensionality while preserving the majority of data variance.

Steps:

1. Standardize features
2. Compute covariance matrix
3. Perform eigenvalue decomposition
4. Select top principal components

This transformation reduces feature correlation and improves model efficiency.

---

## Machine Learning Model

After PCA transformation, classification models are trained to predict wine quality.

Model pipeline includes:

* PCA feature extraction
* logistic regression classification
* model evaluation

---

## Technologies Used

Python
NumPy
Pandas
Scikit-learn
Matplotlib
Jupyter Notebook

---

## Repository Structure

```
wine-quality-pca
│
├── Qiheng_Li.ipynb
├── winequality-red.csv
├── winequality-white.csv
├── winequality.names
├── README.md
```

---

## Author

Qiheng Li
MEng Electrical and Electronic Engineering
New York University
