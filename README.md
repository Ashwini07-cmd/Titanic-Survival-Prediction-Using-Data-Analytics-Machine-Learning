# Titanic Survival Prediction using Data Analytics & Machine Learning

## 📌 Project Overview
This project analyzes the Titanic passenger dataset to understand how demographic and socio-economic factors influenced survival outcomes.
Using exploratory data analysis, feature engineering, and logistic regression, the project identifies key variables affecting survival probability.
The project is structured following a research-oriented data science workflow, making it suitable for academic and internship applications.

## 🎯 Objectives
Perform exploratory data analysis (EDA) to uncover survival patterns
Apply feature engineering to prepare data for modeling
Train a machine learning classification model
Interpret model coefficients to understand feature importance
Evaluate model performance using standard metrics

## Dataset
 - Source: Titanic Dataset (public dataset)
 - Target Variable: Survived
 - Key Features Used:
   - Passenger Class (Pclass)
   - Sex (Sex)
   - Age (Age)
   - Fare (Fare)

## ⚙️ Feature Engineering
Missing age values were handled using median imputation
Categorical variables were converted using one-hot encoding
Relevant features were selected based on interpretability and model performance

## 🤖 Machine Learning Model
Model Used: Logistic Regression
Train-Test Split: 80% training, 20% testing
Evaluation Metrics:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix

## Visuals
  - Age VS Survival
<br>
<img src="https://github.com/Ashwini07-cmd/Titanic-Survival-Prediction-Using-Data-Analytics-Machine-Learning/blob/ec3c99be12814678f900290b5e1da91ee206afd8/Age%20VS%20Survival.png" width="700"/>
<br>

  - Survival Rate By Passenger Class
<br>
<img src="https://github.com/Ashwini07-cmd/Titanic-Survival-Prediction-Using-Data-Analytics-Machine-Learning/blob/ec3c99be12814678f900290b5e1da91ee206afd8/Survival%20Rate%20by%20Passenger%20Class.png" width="700"/>
<br>

 - Feature Importance For Titanic Survival Prediction 
<br>
<img src="https://github.com/Ashwini07-cmd/Titanic-Survival-Prediction-Using-Data-Analytics-Machine-Learning/blob/ec3c99be12814678f900290b5e1da91ee206afd8/feature%20importance%20for%20titanic%20survival%20prediction.png" width="700"/>
<br>

## 🔍 Model Performance
Achieved approximately 80% accuracy
The model effectively distinguishes survival outcomes using simple, interpretable features

## 📈 Model Interpretation
Logistic regression coefficients were analyzed to understand feature impact:
Sex (Male) showed the strongest negative influence on survival
Passenger Class significantly impacted survival probability
Age and Fare showed moderate influence
This interpretation helps explain why certain passengers were more likely to survive, making the analysis suitable for fairness and bias discussions.

## 🛠️ Technologies Used
     - Python
     - Pandas, NumPy
     - Matplotlib, Seaborn
     - Scikit-learn
     - Jupyter Notebook
