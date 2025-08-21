# 🚗 Ford Car Price Prediction

This project builds a regression pipeline to predict the prices of Ford cars using structured data and multiple machine learning models. The goal is to achieve high accuracy while maintaining a clean, reproducible workflow with bilingual documentation in Arabic and English.

---
## 🔍 Workflow Overview

### 1. Explore Data 
- Loaded dataset and previewed structure
- Checked feature types and unique values
- Key columns: `model`, `year`, `mileage`, `engineSize`, `transmission`, `fuelType`, `price`

### 2. Data Analysis 
- Visualized distributions of numerical features
- Explored relationships between features and target (`price`)
- Checked correlations and identified outliers

### 3. Data Processing 
- Removed duplicates and handled missing values
- Cleaned categorical labels
- Handled outliers in `mileage`, `engineSize`, and `price`
- No feature engineering or derived features used

### 4. Data Transformation 
- One-Hot Encoding for categorical features
### 5. Modeling & Evaluation
Trained and compared multiple regression models:

| Model                   | R² Score | MSE         | MAE     |
|------------------------|----------|-------------|---------|
| Linear Regression       | 0.6710   | 4,791,404.45 | 1,704.19 |
| Random Forest Regressor | 0.8882   | 1,628,499.80 |   927.04 |
| Gradient Boosting       | 0.9064   | 1,362,440.42 |   857.81 |
| XGBoost Regressor       | 0.9069 ✅ | 1,356,347.69 |   857.06 |

- Best model: **XGBoost**
- Evaluation metrics: R², MSE, MAE

### 6. Reproducibility & Documentation | 
- Saved cleaned data and trained models
- Structured folders for clarity and reuse
- Documented all steps in both Arabic and English

---
## 📫 Connect with me
 - LinkedIn: [Esraa Mohamed](https://www.linkedin.com/in/esraa-mohamed-481545357?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BL%2Fgh6oLwQR28aZy3roTPtg%3D%3D)
 - Kaggle:   [Esraa Mohamed](https://www.kaggle.com/esraam
