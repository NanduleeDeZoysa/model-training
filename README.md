# Student Placement Prediction using Machine Learning

## Project Overview
This project aims to predict the placement status (Placed or Not Placed) of international students using machine learning techniques. It analyzes how different educational and socio-economic factors affect employability after graduation.

Multiple machine learning models are built and compared to identify the most effective approach for prediction.

## Dataset Information
Source: Kaggle - Global Student Migration and Higher Education Trends  
Link: https://www.kaggle.com/datasets/atharvasoundankar/global-student-migration-and-higher-education-trends  

- Number of records: ~5,000  
- Number of features: ~20  
- Data types: Categorical and Numerical  
- Time period: 2019–2023  
- Target variable: Placement Status (Placed / Not Placed)  
- Scope: Global dataset (multiple countries)

## Data Preprocessing
The dataset was processed using the following steps:

- Feature scaling  
- Label encoding  
- One-hot encoding  
- Outlier removal  
- Feature engineering  
- Dimensionality reduction using PCA  

## Machine Learning Models Used
The following models were implemented and evaluated:

- Logistic Regression  
- Decision Tree  
- Support Vector Machine (SVM)  
- Random Forest  
- Gradient Boosting  

## Hyperparameter Tuning
- GridSearchCV  
- RandomizedSearchCV  

## Evaluation Metrics
The models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- AUC Score  

## Results Summary

- SVM achieved the highest accuracy (0.523) and AUC (0.522)  
- Decision Tree showed the highest recall  
- Logistic Regression showed stable but weak performance  
- Random Forest and Gradient Boosting showed moderate results  
- Overall performance of all models was close to baseline

## Key Findings
- The dataset is balanced (50% Placed, 50% Not Placed)  
- Feature correlation with target variable is weak  
- Data leakage was identified and removed during preprocessing  
- Model performance remained low due to limited predictive features  

## Ethical Considerations
- Removed features that caused data leakage  
- Ensured fair evaluation of models  
- Avoided misleading performance inflation  
- Highlighted limitations of dataset quality and feature strength  

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Future Improvements
- Improve feature engineering  
- Use advanced models like XGBoost or LightGBM  
- Add more meaningful socio-economic features  
- Experiment with deep learning approaches  
- Improve dataset quality and feature relevance  

## Author
Machine Learning Project - Student Assignment