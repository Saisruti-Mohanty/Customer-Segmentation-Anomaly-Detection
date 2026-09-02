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

📈 Visualizations

The project includes visualizations for:

K-Means customer clusters
DBSCAN clusters and noise points
Isolation Forest anomalies
LOF anomalies
Comparison of detected anomalies
🚀 How to Run
1. Clone the repository
git clone https://github.com/Saisruti-Mohanty/Customer-Segmentation-Anomaly-Detection.git
2. Open the project folder
cd Customer-Segmentation-Anomaly-Detection
3. Install required libraries
pip install pandas numpy matplotlib scikit-learn jupyter
4. Open the notebook
jupyter notebook Customer_Segmentation.ipynb

Run the notebook cells to reproduce the analysis.

📁 Project Structure
Customer-Segmentation-Anomaly-Detection/
│
├── Customer_Segmentation.ipynb
├── Mall_Customers.csv
├── .gitignore
├── LICENSE
└── README.md
🎯 Future Improvements
Build an interactive Streamlit application
Allow users to upload their own datasets
Compare anomaly detection algorithms interactively
Add anomaly scoring
Create an automated customer analysis report
👩‍💻 Author

Saisruti Mohanty

B.Tech – Computer Science and Data Science
