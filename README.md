# 💳 Credit Card Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project focuses on customer segmentation for credit card users based on their spending behavior, payment habits, credit utilization, and cash advance activities.

Using K-Means Clustering, customers are grouped into distinct segments to help financial institutions design targeted marketing campaigns, improve customer retention, and identify high-value or high-risk customers.

The dataset contains behavioral information for approximately 8,950 active credit card holders over the last six months.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA) on customer spending behavior.
* Handle missing values and prepare the dataset for clustering.
* Standardize features to ensure fair clustering.
* Determine the optimal number of customer segments using the Elbow Method and Silhouette Score.
* Apply K-Means Clustering to identify meaningful customer groups.
* Visualize customer segments using PCA.
* Generate actionable business insights from each cluster.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## 📂 Dataset Features

| Feature                | Description                     |
| ---------------------- | ------------------------------- |
| BALANCE                | Current balance on account      |
| PURCHASES              | Total purchase amount           |
| ONEOFF_PURCHASES       | One-time purchase amount        |
| INSTALLMENTS_PURCHASES | Purchases made in installments  |
| CASH_ADVANCE           | Cash advances taken             |
| PURCHASES_FREQUENCY    | Frequency of purchases          |
| PURCHASES_TRX          | Number of purchase transactions |
| CREDIT_LIMIT           | Customer credit limit           |
| PAYMENTS               | Total payments made             |
| MINIMUM_PAYMENTS       | Minimum payments made           |
| PRC_FULL_PAYMENT       | Percentage of full payments     |
| TENURE                 | Duration of credit card usage   |

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

### Data Quality Checks

* Missing value detection
* Data type verification
* Statistical summaries

### Distribution Analysis

* Balance distribution
* Purchase behavior distribution
* Credit limit distribution
* Payment distribution

### Outlier Detection

* Boxplots for major financial variables
* Identification of extreme spending patterns

### Correlation Analysis

* Correlation matrix
* Heatmap visualization

---

## ⚙️ Data Preprocessing

### Data Cleaning

* Handled missing values in important financial variables.
* Removed customer identifiers that do not contribute to clustering.

### Feature Scaling

* Standardized all numerical features before clustering.
* Ensured equal importance across variables measured on different scales.

---

## 🤖 Clustering Approach

### 1. Elbow Method

Used to identify the optimal number of clusters by analyzing Within Cluster Sum of Squares (WCSS).

### 2. Silhouette Score

Evaluated clustering quality by measuring cluster separation and cohesion.

### 3. K-Means Clustering

Applied K-Means clustering to group customers with similar spending and payment behaviors.

---

## 📈 PCA Visualization

Principal Component Analysis (PCA) was used to reduce dimensionality and visualize customer segments in a two-dimensional space while preserving most of the information from the original dataset.

---

## 📊 Results

The model successfully segmented customers into four distinct groups.

### Cluster 0 — Low Activity Customers

* Low balance
* Low purchases
* Low transaction frequency
* Lower engagement

### Cluster 1 — Frequent Purchasers

* High purchase frequency
* Large number of transactions
* Regular card usage

### Cluster 2 — Cash Advance Users

* High cash advance amounts
* Higher financial risk profile
* Lower purchasing activity

### Cluster 3 — Premium Customers

* High balances
* High purchases
* Higher credit limits
* Most valuable customer segment

---

## 💡 Business Insights

### Low Activity Customers

* Offer cashback incentives
* Promote reward programs

### Frequent Purchasers

* Personalized promotions
* Loyalty rewards

### Cash Advance Users

* Financial planning products
* Debt management offers

### Premium Customers

* Premium credit cards
* Exclusive benefits
* VIP reward programs

---

## 📉 Model Evaluation

| Metric            | Purpose                              |
| ----------------- | ------------------------------------ |
| WCSS              | Determine optimal number of clusters |
| Silhouette Score  | Measure cluster quality              |
| PCA Visualization | Validate cluster separation          |

---

## 🚀 Key Learnings

* Customer segmentation using unsupervised learning.
* Feature scaling importance in clustering.
* Optimal cluster selection using Elbow Method and Silhouette Score.
* Dimensionality reduction using PCA.
* Converting analytical findings into business recommendations.

---

## 📷 Visualizations Included

* Correlation Heatmap
* Feature Distributions
* Boxplots
* Elbow Curve
* PCA Cluster Plot
* Cluster Comparison Charts

---

## 👩‍💻 Author

**Vedika Singh**

Computer and Communication Engineering (CCE) Student
Manipal Institute of Technology
