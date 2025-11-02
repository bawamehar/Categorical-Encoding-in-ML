# 🚗 One-Hot Encoding Techniques in Python

This repository contains a Jupyter Notebook demonstrating various ways to perform **One-Hot Encoding** — one of the most common techniques for converting categorical data into numerical format for machine learning models.

---

## 📂 Dataset

The notebook uses a dataset named **`cars.csv`** containing details such as:

| brand  | km_driven | fuel  | owner           | selling_price |
|--------|------------|--------|-----------------|----------------|
| Maruti | 145500     | Diesel | First Owner     | 450000 |
| Skoda  | 120000     | Diesel | Second Owner    | 370000 |
| Honda  | 140000     | Petrol | Third Owner     | 158000 |

This dataset helps demonstrate how categorical features like **brand**, **fuel**, and **owner** can be encoded for use in machine learning models.

---

## 🧠 Topics Covered

### 1. One-Hot Encoding using Pandas
- Performed using `pd.get_dummies()`
- Converts categorical columns into dummy variables

### 2. N-1 One-Hot Encoding (Removing Multi-Collinearity)
- Drops one dummy variable to avoid redundancy and multicollinearity in regression models

### 3. One-Hot Encoding using Scikit-learn
- Implemented with `OneHotEncoder` from `sklearn.preprocessing`
- Works efficiently in ML pipelines and with unseen test data

### 4. Encoding with Top Categories
- Combines less frequent categories into a single "Other" group before encoding
- Useful when dealing with high-cardinality categorical variables

### 5. One-Hot Encoding with ColumnTransformer
- Encodes specific columns while keeping others unchanged
- Ideal for preprocessing pipelines with both categorical and numerical features

---

## 🧰 Tools & Libraries Used

- **Python 3**
- **Pandas**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🎯 Objective

To help learners and data practitioners:
- Understand and apply different **One-Hot Encoding** methods  
- Handle **multicollinearity** in encoded data  
- Manage **rare categories** effectively  

---