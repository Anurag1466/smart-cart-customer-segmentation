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

* KMeans created clearly separable customer groups based on income and spending
* Agglomerative clustering showed overlapping clusters, making segmentation less interpretable
* PCA helped improve clustering efficiency
* Identified distinct customer segments based on income, age, and spending behavior

---

## Visualizations

* Elbow Method Graph

![image alt](https://github.com/Anurag1466/smart-cart-customer-segmentation/blob/76b505e9bae12451078dbfb06a74e467e7dd910e/Screenshot%202026-05-03%20183009.png)

* KMeans Clustering Visualization

![image alt](https://github.com/Anurag1466/smart-cart-customer-segmentation/blob/76b505e9bae12451078dbfb06a74e467e7dd910e/Screenshot%202026-05-03%20182823.png)

* Agglomerative Clustering Visualization

![image alt](https://github.com/Anurag1466/smart-cart-customer-segmentation/blob/76b505e9bae12451078dbfb06a74e467e7dd910e/Screenshot%202026-05-03%20182935.png)

* Pairplot for Outlier Detection

![image alt](https://github.com/Anurag1466/smart-cart-customer-segmentation/blob/76b505e9bae12451078dbfb06a74e467e7dd910e/Screenshot%202026-05-03%20181040.png)

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

## Business Impact
- Enables targeted marketing campaigns
- Helps identify high-value customers
- Improves customer retention strategies

---
  
## Future Improvements
* Deploy as a web dashboard
* Add real-time recommendation system
