# Anu Swathi - Task5
# Heart Disease Classification using Decision Trees and Random Forests 🩺

This project demonstrates the implementation of **tree-based classification models**—Decision Tree and Random Forest—on the **Heart Disease Dataset**. The primary objective is to understand model training, overfitting control, feature importance, and evaluation using cross-validation.

## 🎯 Objective

- Implement **Decision Tree** and **Random Forest** classifiers
- Visualize the decision tree
- Analyze and control overfitting using max depth
- Interpret **feature importances**
- Compare model accuracy
- Evaluate models using **cross-validation**

## 🧰 Tools & Libraries Used

- Python 3
- Scikit-learn
- Pandas
- Matplotlib & Seaborn
- Graphviz (for tree visualization)

## 📊 Dataset

- **Name**: Heart Disease Dataset
- **Source**: [UCI Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease) 
- **Target Variable**: 'target' (1: Disease, 0: No disease)

## 🛠️ Project Workflow

### 1. Load and Prepare Data
- Load CSV using pandas
- Check for null values
- Separate features ('X') and labels ('y')
- Split data into training and testing sets

### 2. Train a Decision Tree Classifier
- Use 'DecisionTreeClassifier' from 'sklearn'
- Fit the model
- Visualize the tree using Graphviz

### 3. Analyze Overfitting
- Vary 'max_depth' from 1 to 20
- Plot training vs test accuracy

### 4. Train a Random Forest
- Use 'RandomForestClassifier'
- Compare accuracy with Decision Tree
- Interpret **feature importances**

### 5. Cross-Validation
- Use 'cross_val_score' from sklearn
- Evaluate average accuracy and standard deviation

## 📈 Visual Outputs

1.Decision Tree Diagram

2.Accuracy vs Tree Depth Plot

3.Feature Importance Bar Chart

4.Confusion Matrix Heatmaps



