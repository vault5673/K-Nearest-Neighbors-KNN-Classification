# 🌸 K-Nearest Neighbors (KNN) Classification – Iris Dataset

This project demonstrates how to build a classification model using the K-Nearest Neighbors (KNN) algorithm with the Iris dataset. The objective is to classify iris flowers into one of three species based on their sepal and petal measurements.

---

## 📁 Dataset

The dataset used is the classic **Iris dataset**, which includes 150 samples from three species of Iris flowers: *setosa*, *versicolor*, and *virginica*. Each sample has four features: sepal length, sepal width, petal length, and petal width.

---

## 🔄 Steps in the KNN Workflow

### 🔍 1. Import and Explore the Dataset
The Iris dataset is loaded and basic structure and class distribution are examined to understand the classification problem.

### 🧹 2. Feature Normalization
Since KNN is distance-based, all features are scaled using `StandardScaler` to ensure fair contribution from each feature during distance calculation.

### ✂️ 3. Train-Test Split
The dataset is split into training and testing sets (70-30 split) to evaluate model performance on unseen data.

### 🤖 4. Train the KNN Classifier
The `KNeighborsClassifier` from Scikit-learn is used. Multiple models are trained with different values of **K** (number of neighbors) to find the optimal choice.

### 📈 5. Model Evaluation
Accuracy is calculated for each value of K and plotted. The best model is further evaluated using a **confusion matrix** to show classification performance for each class.

### 🎨 6. Visualize Decision Boundaries
Using only the first two features, the decision boundary of the best KNN model is plotted to visualize how the classifier separates classes.

---

## ✅ Final Output

- Normalized feature values
- Tested multiple K values and selected the best
- Accuracy plot for K selection
- Confusion matrix for evaluation
- Decision boundary visualization for understanding model behavior

---

## 📚 Requirements

This project is implemented in Python using:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn

---
