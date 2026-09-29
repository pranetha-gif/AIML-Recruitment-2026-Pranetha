# AIML Recruitment Task 2026

## Candidate Details
- **Name**: Pranetha
- **Role**: AI-ML Recruitment Task Submission (First Year)

## Tasks Completed
- **Task 1**: Exploratory Data Analysis & Preprocessing (Auto MPG)
- **Task 2**: Linear Regression Model (MPG Prediction)

## Problem Statement
Perform data preprocessing, exploratory data analysis, and build a Linear Regression model on the Auto MPG dataset to predict vehicle fuel efficiency based on vehicle characteristics.

## Approach
1. **Preprocessing**: Filled missing `horsepower` values with median imputation, verified data types, and exported the cleaned dataset.
2. **EDA**: Visualized MPG distributions, feature correlations, boxplots by cylinders and origin, and tracked MPG trends over model years.
3. **Feature Engineering**: One-hot encoded categorical variable `origin` and split the dataset 80/20 (train/test).
4. **Modeling**: Built single-feature and multi-feature Linear Regression models, evaluated using MAE, MSE, RMSE, and $R^2$.

## Technologies Used
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## Results
- **Task 1**: Vehicle weight ($r \approx -0.83$) and horsepower ($r \approx -0.77$) have strong negative correlations with MPG.
- **Task 2**: Multi-feature Linear Regression achieved $R^2 \approx 0.84$ on the test set, vastly outperforming the single-feature weight model ($R^2 \approx 0.65$).

## Key Learnings
1. Learned how median imputation handles missing numeric data safely.
2. Understood how one-hot encoding converts categorical variables into numerical values for regression.
3. Learned how to evaluate model performance and verify that train/test scores match to rule out overfitting.

## Challenges & Solutions
- **Challenge**: Interpreting multiple model evaluation metrics (MAE, MSE, RMSE, $R^2$).
- **Solution**: Calculated and compared metrics on both train and test splits to ensure strong generalization.
