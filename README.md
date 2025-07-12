## Laptop Price Prediction - Machine Learning Capstone Project
This repository contains a complete machine learning pipeline to predict laptop prices based on their specifications. The project includes **Excel-based column cleaning**, feature engineering, EDA, model training, evaluation, and real-time prediction.

###  Project Objectives
* Predict the price of laptops based on various features like brand, type, specs, etc.
* Clean and preprocess data using **both Excel and Python**.
* Compare multiple regression models to identify the best-performing one.
* Gain insights into key features influencing price.
  
### Dataset Overview
The dataset includes:
* **Categorical**: Company, Type, OS, CPU brand/type, GPU brand
* **Numerical**: Inches, RAM, SSD, HDD, Flash Storage, Weight, Resolution
* **Target**:  Laptop **Price**

###  Data Cleaning Tools

*  **Microsoft Excel** – Used for manual inspection & cleaning of columns like `RAM`, `Weight`, `CPU`, etc.
* **Python (Pandas, NumPy)** – Used for advanced preprocessing, transformations, and feature engineering.

### Feature Engineering
* Extracted resolution width/height from `ScreenResolution`
* Created a new `Resolution_Pixels` column (width × height)
* Extracted CPU and GPU brands and types
  
### Tools & Technologies Used
* **Excel**
* **Python**
* **Pandas, NumPy, Matplotlib, Seaborn**
* **Scikit-learn**
* **Jupyter Notebook / Google Colab**

###  Machine Learning Models Used
* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor
* 
### Best Model Performance

>  **Model:** Gradient Boosting Regressor
>  **MAE:** \~10,742
>  **RMSE:** \~15,997
>  **R² Score:** **0.78**
### Feature Importance
Random Forest was used to visualize feature importance and identify the most impactful specifications.
### Real-time Price Prediction
The final model is integrated with a real-time prediction function where users can input laptop configurations and get an estimated price.
### Project by
**Namratha** 
