# 🛒 Big Bazaar Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project performs Customer Segmentation for a retail business (Big Bazaar) using Machine Learning.

The goal is to divide customers into different groups based on their purchasing behavior so that marketing teams can create targeted campaigns and improve customer engagement.

The project uses the K-Means Clustering algorithm to identify meaningful customer segments.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Scaling using StandardScaler
- Customer Segmentation using K-Means Clustering
- Elbow Method for Optimal Cluster Selection
- 2D Cluster Visualization
- 3D Customer Cluster Visualization

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

---

## 📊 Dataset

Dataset Used:

**Mall Customers Dataset**

Features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## ⚙️ Machine Learning Workflow

### Step 1: Import Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import StandardScaler
from sklearn.cluster import KMeans
```

### Step 2: Load Dataset

```python
df = pd.read_csv("MallCustomers.csv")
```

### Step 3: Exploratory Data Analysis

- Check missing values
- Statistical summary
- Feature distributions
- Correlation analysis

### Step 4: Data Preprocessing

- Select important features
- Scale data using StandardScaler

### Step 5: K-Means Clustering

- Train K-Means model
- Generate customer clusters

### Step 6: Elbow Method

Determine the optimal number of clusters.

### Step 7: Visualization

- Scatter plots
- Cluster analysis
- 3D customer segmentation

---

## 📈 Results

The model successfully identifies different customer groups such as:

- High Income - High Spending
- High Income - Low Spending
- Low Income - High Spending
- Low Income - Low Spending
- Average Customers

These insights can help businesses create personalized marketing strategies.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/BigBazaar-Customer-Segmentation.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebook in Google Colab or Jupyter Notebook

---

## 📚 Learning Outcomes

Through this project I learned:

- Customer Segmentation
- Unsupervised Learning
- K-Means Clustering
- Feature Scaling
- Data Visualization
- Exploratory Data Analysis

---

## 👨‍💻 Author

Samridhi

Electronics and Computer Engineering (ENC)
Thapar Institute of Engineering & Technology
