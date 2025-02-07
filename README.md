# Car Price Prediction  

##  Project Overview  
This project aims to develop a **predictive model for car prices** using various machine learning algorithms. A Chinese automobile company is expanding into the **US market** and wants to understand the key factors that influence car prices.  

By analyzing a dataset of cars sold in the US, we aim to:  

-  Identify **significant variables** affecting car prices.  
-  Develop **machine learning models** for price prediction.  
-  Compare different models based on performance metrics.  
-  Provide **business insights** to help the company **strategize its market entry**.  

---

##  Business Objective  
- **Understand** the pricing dynamics in the US automobile market.  
- **Develop** machine learning models to predict car prices accurately.  
- **Analyze** feature importance to identify key attributes affecting pricing.  
- **Optimize** pricing strategy for better market positioning.  

---

##  Dataset  
The dataset used in this project is sourced from **market surveys** and contains multiple attributes of cars sold in the **US market**.  

##  Project Workflow  

### **1. Data Loading & Preprocessing**  
- Load the dataset into a Pandas DataFrame.  
- Handle **missing values** and remove **duplicates**.  
- Perform **exploratory data analysis (EDA)**.  
- Encode **categorical variables** (e.g., One-Hot Encoding, Label Encoding).  
- Normalize/scale **numerical features** for consistency.  
- Remove **outliers** to improve model performance.  

---

### **2. Model Implementation**  
We implemented **five regression models** to predict car prices:  

1.  **Linear Regression**  
2.  **Decision Tree Regressor**  
3.  **Random Forest Regressor**  
4.  **Gradient Boosting Regressor**  
5.  **Support Vector Regressor (SVR)**  

---

### **3. Model Evaluation**  
Each model was evaluated using the following performance metrics:  

 **R-Squared Score (R²)** – Measures how well the model explains the variability in car prices.  
 **Mean Squared Error (MSE)** – Measures average squared error between actual and predicted prices.  
 **Mean Absolute Error (MAE)** – Measures the average absolute difference between actual and predicted prices.  

---

### **4. Feature Importance Analysis**  
 Identified **key features** affecting car prices using:  
 - **Statistical methods** (correlation analysis).  
 - **Model-based techniques** (feature importance scores from tree-based models).  
 - **Recursive Feature Elimination (RFE)** for feature selection.  

---

### **5. Hyperparameter Tuning**  
 To improve model performance, we applied:  
 - **Grid Search** – Systematic search over specified parameter values.  
 - **Randomized Search** – Random combinations of hyperparameters for faster tuning.  
 - **Cross-Validation** – Ensuring the model generalizes well to unseen data.  

---

##  Results & Insights  
 - **Best Performing Model:** `Random Forest Regressor` with an **R² Score of `0.936125`**.  
 - **Key Features Impacting Price:** `['wheelbase', 'carlength', 'carwidth', 'carheight', 'curbweight',
       'enginesize', 'boreratio', 'horsepower', 'citympg', 'highwaympg']`.  
 - **Business Recommendations:** The insights from this analysis can help the company **optimize its pricing strategy** and **compete effectively** in the US market.  

---

