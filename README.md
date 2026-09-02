# Customer Segmentation & Anomaly Detection

A machine learning project that combines customer segmentation with anomaly detection using clustering and outlier detection techniques.

## 📌 Project Overview

This project analyzes customer behavior using:

- K-Means Clustering
- DBSCAN
- Isolation Forest
- Local Outlier Factor (LOF)

The project first identifies customer segments based on their annual income and spending score. It then applies different anomaly detection techniques to identify unusual customer behavior.

## 📊 Dataset

The project uses the **Mall Customers Dataset**.

The dataset contains information about customers including:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

For the machine learning analysis, the main features used are:

- Annual Income (k$)
- Spending Score (1-100)

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🤖 Machine Learning Algorithms

### 1. K-Means Clustering

K-Means is used to divide customers into different groups based on their annual income and spending score.

### 2. DBSCAN

DBSCAN is a density-based clustering algorithm that can identify dense customer groups and mark unusual points as noise.

### 3. Isolation Forest

Isolation Forest detects anomalies by identifying observations that are easier to isolate from the rest of the data.

### 4. Local Outlier Factor (LOF)

LOF identifies customers whose local density is significantly different from the density of their neighboring customers.

## ⚙️ Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Feature Selection
   ↓
Feature Scaling
   ↓
K-Means Clustering
   ↓
DBSCAN
   ↓
Isolation Forest
   ↓
Local Outlier Factor
   ↓
Visualization & Comparison
