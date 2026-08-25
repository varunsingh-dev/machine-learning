# 🧩 Principal Component Analysis (PCA)

## 📖 Overview

Principal Component Analysis (PCA) is a dimensionality reduction technique used to reduce the number of features in a dataset while preserving as much important information as possible.

PCA transforms the original features into a smaller set of new features called **Principal Components**.

---

## 🎯 Objective

The objective of this project is to:

* Understand dimensionality reduction.
* Apply PCA to a real-world dataset.
* Standardize the features.
* Calculate principal components.
* Analyze explained variance.
* Visualize high-dimensional data in 2D.

---

## 🧠 What is PCA?

PCA transforms correlated features into a smaller number of uncorrelated components.

The first principal component captures the maximum possible variance in the data, while subsequent components capture the remaining maximum variance.

---

## ⚙️ PCA Workflow

```text
Load Dataset
      ↓
Explore Dataset
      ↓
Select Features
      ↓
Standardize Features
      ↓
Apply PCA
      ↓
Calculate Explained Variance
      ↓
Select Principal Components
      ↓
Visualize Reduced Data
```

---

## 📊 Important Concepts

* Dimensionality Reduction
* Principal Components
* Explained Variance
* Feature Scaling
* Covariance
* Eigenvectors
* Eigenvalues

---

## 📂 Dataset

**Dataset:** `Wine.csv`

The dataset contains chemical characteristics of wine samples along with their class labels.

PCA will be applied to the numerical features.

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

* Explained Variance Visualization
* 2D PCA Visualization
* Wine Classes Visualization

---

## ✅ Advantages of PCA

* Reduces the number of features.
* Helps visualize high-dimensional data.
* Can reduce computational complexity.
* Removes some feature correlation.
* Useful as a preprocessing technique.

---

## ❌ Disadvantages of PCA

* Principal components can be difficult to interpret.
* Feature scaling is usually required.
* Some information may be lost during dimensionality reduction.
* Components are combinations of original features.

---

## 💼 Applications

PCA is commonly used in:

* Data Visualization
* Image Processing
* Feature Reduction
* Noise Reduction
* Machine Learning Preprocessing
* Pattern Recognition

---

## 💼 Interview Questions

### 1. What is PCA?

PCA is a dimensionality reduction technique that transforms original features into a smaller number of principal components while retaining important variance.

### 2. Why is feature scaling important before PCA?

Features with larger numerical scales can dominate the variance. Scaling puts features on a comparable scale.

### 3. What is a Principal Component?

A principal component is a new feature created as a combination of the original features.

### 4. What is explained variance?

Explained variance represents how much information or variability in the original dataset is captured by each principal component.

### 5. Is PCA supervised or unsupervised?

PCA is generally considered an **unsupervised dimensionality reduction technique** because it does not use target labels while finding the components.

---

## 📂 Files

* `README.md` → Project documentation
* `PCA.ipynb` → PCA implementation
* `Wine.csv` → Dataset

---

## 📝 Key Learnings

* Understood dimensionality reduction.
* Learned how PCA works.
* Standardized numerical features.
* Applied PCA using Scikit-learn.
* Analyzed explained variance.
* Reduced multiple features to two principal components.
* Visualized the transformed dataset.

---

## 👨‍💻 Author

**Varun Singh**

GitHub: `varunsingh-dev`
