# 🏡 House Price Sales Prediction  

This project predicts **house sale prices** using **Regression Machine Learning algorithms**.  
The dataset is first cleaned and explored through **Exploratory Data Analysis (EDA)**, followed by training and evaluation of regression models.  

---

## 📌 Project Workflow  

### 1. Data Collection  
- Used **Data.csv** dataset containing house attributes and sale prices.  

### 2. Data Cleaning & Preprocessing  
- Handled missing values  
- Removed duplicates  
- Encoded categorical variables  
- Scaled numerical features  

### 3. Exploratory Data Analysis (EDA)  
- Distribution plots of features  
- Correlation heatmaps  
- Outlier detection  
- Feature importance analysis  

### 4. Model Building  
- Applied multiple **Regression algorithms** (Linear Regression, Decision Tree Regressor, Random Forest, KNN, etc.)  
- Selected the best performing model: **KNeighborsRegressor**  

### 5. Model Evaluation  
- Metrics used:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - R² Score  

---

## 📊 Results  

- **Best performing model**: `KNeighborsRegressor`  
- **R² Score**: -0.2538906681296613 
- **MAE**: 1629950.0  
- **MSE**: 4133854450000.0  

---

## ⚙️ Tech Stack  

- **Python** 🐍  
- **Pandas, NumPy** – Data Cleaning & Preprocessing  
- **Matplotlib, Seaborn** – Data Visualization (EDA)  
- **Scikit-learn** – Regression Models & Evaluation  
- **Joblib** – Model Saving & Loading  
