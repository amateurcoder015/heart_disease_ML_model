# 🫀 Heart Disease Prediction Model  

This project is a **machine learning-based web application** that predicts the likelihood of heart disease in a patient.  
It combines **exploratory data analysis (EDA)**, data preprocessing, model building, and a **Streamlit-powered interactive interface**. 
<br><br>
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)]((https://htdqcsdoettchqnq97nugy.streamlit.app/))


---

## 📌 Project Overview  
Heart disease is one of the leading causes of death worldwide. Early prediction and detection can help in timely treatment and prevention.  
This project uses patient health data (such as age, cholesterol, resting BP, chest pain type, etc.) to predict whether the patient is likely to have heart disease.  

---


## 📊 Exploratory Data Analysis (EDA)  
- Distribution plots for numerical features  
- Correlation heatmap between features  
- Countplots for categorical variables  
- Outlier detection and handling  
- Feature relationships with target (`HeartDisease`)  

---

## ⚙️ Data Preprocessing  
- Handling missing values  
- Encoding categorical variables (OneHotEncoding)  
- Scaling numerical features (`StandardScaler`)  
- Train-test split for model validation  

---

## 🤖 Model Building  
- Models tested: Logistic Regression, Random Forest, etc.  
- Evaluated using Accuracy, Precision, Recall, F1-Score  
- Selected the best performing model for deployment  

---

## 🌐 Streamlit App  
The Streamlit app (`app.py`) provides an **interactive UI** for making predictions.  
Users can input patient details, and the model will predict the probability of heart disease.  

### Running the App  
```bash
# Install dependencies
pip install -r requirements.txt  

# Run the app
streamlit run app.py
```
---

## Learning Outcomes
- How to perform EDA & visualization effectively
- Preprocessing categorical and numerical data
- Building, training, and evaluating ML models
- Creating an end-to-end ML pipeline with deployment-ready code
- Developing an interactive web app using Streamlit

