# Diabetes Classification using KNN (K-Nearest Neighbors)

## 📌 Project Overview
This project implements a machine learning classification model using the **K-Nearest Neighbors (KNN)** algorithm to predict whether a patient has diabetes based on clinical and physiological health indicators. The project demonstrates a complete ML pipeline from preprocessing to model evaluation and optimization.

---

## 📊 Dataset
Source: Diabetes Classification Dataset  
Target Variable: `Diabetes`  
- 0 → Non-Diabetic  
- 1 → Diabetic  

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Removal of unnecessary columns
- Feature selection
- Standardization using StandardScaler

### 2. Exploratory Data Analysis
- Class distribution analysis
- Dataset imbalance detection

### 3. Feature Engineering
- Feature scaling
- Variable selection

### 4. Model Building
- K-Nearest Neighbors (KNN) classifier
- Train-test split
- Baseline model training

### 5. Model Evaluation
- Accuracy score
- Confusion matrix
- Classification performance analysis

### 6. Hyperparameter Tuning
- GridSearchCV with cross-validation
- Optimal k-value (number of neighbors) selection

### 7. Feature Selection
- ANOVA (F-test) for feature importance ranking

### 8. Class Balancing
- Downsampling majority class
- Balanced dataset creation

### 9. Simplified Model
- Single-feature model using Glucose
- Performance comparison

---

## 🧪 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📈 Results
- High classification accuracy
- Optimized KNN model with cross-validation
- Strong predictive power of glucose levels
- Balanced dataset improves fairness and model learning
- Statistically validated feature importance
 
