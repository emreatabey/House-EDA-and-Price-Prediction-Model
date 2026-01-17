# House: EDA and Price Prediction Model 🏠
This notebook focuses on exploratory data analysis (EDA), feature engineering, and regression modeling to predict house prices using the Kaggle "House Prices - Advanced Regression Techniques" dataset.

## Workflow
* **Data Cleaning & Preprocessing:**
    * Comprehensive handling of missing values across multiple features.
    * Outlier detection and removal to ensure robust model performance.
* **Feature Engineering & Selection:**
    * Feature selection based on correlation analysis with the target variable.
    * Encoding of categorical variables to make them suitable for machine learning algorithms.
* **Model Training:** Comparison of multiple regression models:
    * **Linear Models:** Linear Regression, Ridge, Lasso, and ElasticNet.
    * **Advanced Models:** Support Vector Regression (SVR), Random Forest, and **XGBoost**.
* **Model Evaluation:** Performance assessment using cross-validation and final validation against the Kaggle leaderboard.

## Tech Stack
* **Language:** Python
* **Libraries:**
    * **Data Manipulation:** `Pandas`, `NumPy`
    * **Visualization:** `Matplotlib`, `Seaborn`
    * **Machine Learning:** `Scikit-learn`, `XGBoost`

## Dataset
* **Source:** [Kaggle : House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## Evaluation Metric
* **Kaggle Public Score:** **0.14655** (Root Mean Squared Error - RMSE)

## Submission
The results are exported in the required format for Kaggle evaluation.

* **Format:** CSV
* **Key Columns:** `Id`, `SalePrice`
