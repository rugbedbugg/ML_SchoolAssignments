# 🚀 **Machine Learning Assessments & Projects**  

## 📝 **Description**  
This repository contains solutions, implementations, and documentation related to various **machine learning assessments**. The assessments cover **data manipulation, clustering, dimensionality reduction, classification, and feature scaling**.   

---

## 📚 **Assessments Overview**  

### 🧮 **Assessment 1 - NumPy, Pandas & Matplotlib**  
✅ **Task 1:** Create a **2D NumPy array (3×4)** filled with random integers (1-100), then:  
   - Extract the **second row** and **last column**.  
   - Replace all **even numbers** in the array with `-1`.    
✅ **Task 2:** Create a **DataFrame** with columns `Name`, `Age`, `City`, and `Salary` for 5 employees, then:  
   - Add a **Bonus** column (10% of Salary).  
   - Sort the DataFrame by **Salary** in descending order.  
✅ **Task 3:** Plot a **line graph** for the equation:    
   \[
   y = 2x^2 + 3x + 5
   \]
   for `x` ranging from `-10` to `10`, with labeled axes and a title.  
✅ **Task 4:** Create a **figure with 4 subplots**:    
   - 📈 **Line graph**  
   - 🎯 **Scatter plot**  
   - 📊 **Histogram**  
   - 📉 **Bar chart**  

---

### 📏 **Assessment 2 - Feature Scaling**  
📝 **Problem Statement:**  
Given height (in feet) and weight (in grams) data for **40 people**, apply feature scaling techniques:  
✅ **Min-Max Normalization:** Scale weights between `0` and `1`.  
   - Formula:  
     \[
     X_{norm} = \frac{X - X_{min}}{X_{max} - X_{min}}
     \]  
✅ **Z-score Normalization:** Transform data to have **mean = 0** and **std = 1**.  
   - Formula:  
     \[
     X_{norm} = \frac{X - X_{mean}}{X_{std}}
     \]  

---

### 🌿 **Assessment 3 - Clustering & PCA**  
✅ **Task 1:** Implement **Hierarchical Clustering** on the **Iris Flower Dataset**.  
✅ **Task 2:** Perform **Principal Component Analysis (PCA)** on the **Mushroom Dataset (8124 samples, 22 features)**:  
   - 📂 Load and explore dataset.  
   - 📏 Normalize/standardize data if required.  
   - 🔢 Compute **Covariance Matrix, Eigenvalues & Eigenvectors**.  
   - 📊 Calculate **Explained Variance** and select `k` principal components.  
   - 🖼️ **Visualize reduced-dimensional data**.  

---

### 🌳 **Assessment 4 - Classification Algorithms**  
✅ **Task 1:** Implement **Random Forest Algorithm** on the **Bill Authentication Dataset** and evaluate performance.  
✅ **Task 2:** Apply **AdaBoost Algorithm** to classify **flower species**.  
✅ **Task 3:** Compare multiple **classification algorithms** and evaluate performance using **metrics like Accuracy, Precision, Recall, F1-score**.  

---

### 🤖 Assessment 5 - KNN & K-Modes Clustering
✅ Task 1: Implement K-Nearest Neighbors (KNN) on the Iris Dataset:
    - 📂 Load the dataset.
    - 📏 Scale features using StandardScaler.
    - 🏋️‍♂️ Train a KNN model (k=5) on the training set.
    - 📊 Evaluate using Accuracy, Precision, Recall, and F1-score.
✅ Task 2: Implement K-Modes Clustering on a Customer Segmentation Dataset:
    - 🏷️ Encode categorical variables (Gender, Age Group, Shopping Habit).
    - 🔍 Use the Elbow Method to determine the optimal number of clusters.
    - 🎯 Train a K-Modes model with the optimal k.
    - 📊 Evaluate clustering using Silhouette Score.
