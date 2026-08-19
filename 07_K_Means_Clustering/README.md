# 🎯 K-Means Clustering

## 📖 Overview

K-Means Clustering is an **Unsupervised Machine Learning algorithm** used to divide data into groups called **clusters** based on similarities between data points.

Unlike supervised learning algorithms, K-Means does not require a target variable.

---

## 🎯 Objective

In this project, K-Means Clustering is used to segment mall customers into different groups based on their:

* Annual Income
* Spending Score

The goal is to identify different customer segments that can help businesses make better marketing decisions.

---

## 🧠 What is Clustering?

Clustering is an unsupervised learning technique that groups similar data points together.

For example, customers can be divided into groups such as:

* High Income & High Spending
* High Income & Low Spending
* Low Income & High Spending
* Low Income & Low Spending

---

## ⚙️ How K-Means Works

K-Means follows these basic steps:

1. Choose the number of clusters `K`.
2. Randomly initialize cluster centroids.
3. Assign each data point to its nearest centroid.
4. Calculate new centroid positions.
5. Repeat the process until the centroids stabilize.
6. Assign each data point to its final cluster.

---

## 📊 Elbow Method

The **Elbow Method** is used to find the optimal number of clusters.

It calculates the **Within-Cluster Sum of Squares (WCSS)** for different values of K.

The point where the decrease in WCSS starts slowing down significantly is called the **Elbow Point**.

---

## 📐 Important Concepts

* Centroid
* Cluster
* Euclidean Distance
* WCSS
* Elbow Method
* Unsupervised Learning

---

## 📂 Dataset

**Dataset:** `Mall_Customers.csv`

The dataset contains information about mall customers.

### Important Features

* `CustomerID`
* `Gender`
* `Age`
* `Annual Income (k$)`
* `Spending Score (1-100)`

For clustering, we will primarily use:

* `Annual Income (k$)`
* `Spending Score (1-100)`

---

## 📊 Project Workflow

```text
Load Dataset
      ↓
Explore Dataset
      ↓
Check Missing Values
      ↓
Select Features
      ↓
Apply Elbow Method
      ↓
Choose Optimal K
      ↓
Train K-Means Model
      ↓
Assign Clusters
      ↓
Visualize Clusters
      ↓
Analyze Customer Segments
```

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📈 Visualizations

This project includes:

* Customer Income vs Spending Score
* Elbow Method Graph
* K-Means Cluster Visualization
* Cluster Centroids

---

## 💼 Business Applications

Customer segmentation can help businesses:

* Create targeted marketing campaigns
* Identify high-value customers
* Understand customer behavior
* Develop personalized offers
* Improve customer retention strategies

---

## ✅ Advantages

* Simple and easy to understand
* Fast and computationally efficient
* Works well with large datasets
* Easy to visualize
* Useful for customer segmentation

---

## ❌ Disadvantages

* Requires choosing the number of clusters
* Sensitive to outliers
* Sensitive to initial centroid selection
* Works best when clusters are relatively well separated

---

## 💼 Interview Questions

### 1. What is K-Means Clustering?

K-Means is an unsupervised Machine Learning algorithm that groups similar data points into K clusters.

### 2. What does K represent in K-Means?

K represents the number of clusters that we want the algorithm to create.

### 3. What is a centroid?

A centroid is the center point of a cluster.

### 4. What is the Elbow Method?

The Elbow Method helps determine the optimal number of clusters by analyzing the WCSS for different values of K.

### 5. Is K-Means supervised or unsupervised?

K-Means is an **Unsupervised Machine Learning algorithm**.

### 6. What is WCSS?

WCSS stands for **Within-Cluster Sum of Squares**. It measures how close the data points are to their respective cluster centroids.

---

## 📂 Files

* `README.md` → Project documentation
* `K_Means_Clustering.ipynb` → Complete implementation
* `Mall_Customers.csv` → Dataset

---

## 🎯 Project Outcome

The final model will divide customers into different segments based on their annual income and spending behavior.

These customer segments can provide useful business insights for targeted marketing and customer management.

---

## 📝 Key Learnings

* Understood Unsupervised Machine Learning
* Learned K-Means Clustering
* Used the Elbow Method
* Selected an optimal number of clusters
* Trained a K-Means model
* Visualized customer clusters
* Analyzed customer segments
* Derived business insights from clustering

---

## 👨‍💻 Author

**Varun Singh**

GitHub: `varunsingh-dev`

---

⭐ If you found this project useful, consider giving the repository a star.
