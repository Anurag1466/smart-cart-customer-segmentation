### Smart Cart Customer Segmentation

## Project Overview

This project focuses on segmenting customers based on demographic and behavioral data to enable targeted marketing strategies.
Clustering techniques like KMeans and Agglomerative Clustering were applied and compared to identify optimal customer groups.

---

Objective

* Identify distinct customer segments
* Improve personalization and marketing strategies
* Understand customer behavior patterns

---

## Workflow

### 1. Data Preprocessing

* Loaded dataset using Pandas
* Handled missing values using SimpleImputer
* Removed outliers using pairplot analysis

### 2. Feature Engineering

* Created new features such as:

  * Age (from DOB/Year_Birth)
  * Customer Tenure

### 3. Feature Encoding

* Applied One-Hot Encoding to categorical variables

### 4. Feature Scaling

* Standardized data using StandardScaler

### 5. Dimensionality Reduction

* Applied PCA to reduce dimensions and improve clustering performance

### 6. Model Building

#### KMeans Clustering

* Optimal K determined using Elbow Method
* Produced well-separated clusters

#### Agglomerative Clustering

* Applied for comparison
* Less distinct cluster separation compared to KMeans

---

## Results & Insights

* KMeans performed better than Agglomerative Clustering in terms of cluster separation
* PCA helped improve clustering efficiency
* Identified distinct customer segments based on income, age, and spending behavior

---

## Visualizations

* Elbow Method Graph



* Cluster Scatter Plot
* PCA Visualization
* Pairplot for Outlier Detection

(Add images here)

---

## Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Seaborn, Matplotlib

---

## How to Run

```bash
pip install -r requirements.txt
python main.py
```

---

## Key Learnings

* Importance of feature scaling in clustering
* Role of PCA in improving model performance
* Comparing clustering algorithms for better insights
* Handling multicollinearity and outliers

---

## Future Improvements

* Deploy as a web dashboard
* Add real-time recommendation system
