#🫀 Heart Disease Prediction Model

This project is an end-to-end Machine Learning pipeline to predict the likelihood of heart disease in patients based on clinical features.
It was built as a learning project to practice EDA, preprocessing, model building, and deployment with Streamlit.

🚀 Project Workflow
1. Exploratory Data Analysis (EDA)

Before modeling, I performed EDA to:

Understand data distributions (Age, Cholesterol, Blood Pressure, etc.)

Compare target variable (HeartDisease) with categorical features (Sex, ChestPainType, etc.)

Visualize relationships using histograms, boxplots, countplots, correlation heatmaps, and scatter plots.

Key Insights from EDA:

Certain chest pain types and exercise angina strongly correlate with heart disease.

Age, cholesterol, and blood pressure show noticeable trends with the target.

Feature scaling is required for numerical columns.

2. Data Preprocessing

Steps taken:

Encoding categorical variables → One-hot encoding (e.g., Sex_M, ChestPainType_ATA, etc.)

Feature scaling → Standardized numerical features (Age, RestingBP, Cholesterol, MaxHR, Oldpeak) using StandardScaler.

Ensured consistency between training data and raw input features for Streamlit.

3. Model Building

I trained multiple models and compared them:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

XGBoost (optional, depending on environment setup)

Metrics Used:

Accuracy

Precision / Recall

ROC-AUC Score

Final model was selected based on a balance between accuracy and interpretability.

4. Deployment with Streamlit

A simple Streamlit web app was built for user interaction.

Users can input their health data (Age, BP, Cholesterol, etc.).

The model predicts whether they are at risk of heart disease (Yes / No).

Streamlit handles preprocessing internally so inputs match the trained model’s feature set.
