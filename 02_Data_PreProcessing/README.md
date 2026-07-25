# 🧹 Data Preprocessing

## 📖 What is Data Preprocessing?

Data Preprocessing is the process of cleaning and transforming raw data into a format that can be used for Machine Learning models.

Real-world datasets often contain missing values, duplicate records, incorrect data types, and categorical variables. Preprocessing helps improve the quality of the data before model training.

---

# 🎯 Objectives

- Clean raw data
- Handle missing values
- Encode categorical variables
- Split data into training and testing sets
- Scale numerical features

---

# 📌 Steps in Data Preprocessing

## 1. Import Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

---

## 2. Load Dataset

```python
df = pd.read_csv("dataset.csv")
```

---

## 3. Check Dataset

- Shape
- Columns
- Data Types
- Missing Values

Useful functions:

```python
df.head()
df.info()
df.describe()
df.isnull().sum()
```

---

## 4. Handle Missing Values

Common methods:

- Remove missing rows
- Replace with Mean
- Replace with Median
- Replace with Mode

Example:

```python
df.fillna(df.mean(), inplace=True)
```

---

## 5. Encoding Categorical Data

Convert text values into numbers.

Example:

- Male → 1
- Female → 0

Methods:

- Label Encoding
- One-Hot Encoding

---

## 6. Feature Scaling

Feature scaling ensures all numerical values are on a similar scale.

Methods:

- Standardization
- Normalization

---

## 7. Train-Test Split

Split data before training.

Example:

```python
from sklearn.model_selection import train_test_split
```

Typical ratio:

- Train → 80%
- Test → 20%

---

# 🛠️ Libraries Used

- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# 📂 Files

- preprocessing.ipynb
- dataset.csv

---

# 📈 Status

✅ Completed

---

Created by **Varun Singh**
