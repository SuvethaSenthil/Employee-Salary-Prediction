# 🧠 Employee Salary Prediction

This project predicts whether an employee earns more than \$50K per year based on demographic and work-related data. It includes:

- Data Cleaning & Preprocessing  
- Multiple Machine Learning Models  
- SHAP Explainability  
- Streamlit Web App Interface  
- Batch CSV Prediction + Download  
- Model Comparison & Saving

---

## 📁 Project Structure

| File/Folder            | Description                                              |
|------------------------|----------------------------------------------------------|
| `EmployeePrediction.ipynb` | Full notebook: preprocessing, training, evaluation      |
| `app.py`               | Streamlit app to interact with model predictions         |
| `best_model.pkl`       | Best trained model saved using joblib                    |
| `requirements.txt`     | Python dependencies                                      |
| `README.md`            | Project documentation (this file)                        |

---

## 📊 Problem Statement

Given employee information (age, education, occupation, hours worked, etc.), predict whether the employee's salary is:

- `>50K`
- `<=50K`

The dataset resembles the UCI Adult Income Dataset.

---

## 🎯 Features Used

- Age  
- Education  
- Occupation  
- Marital Status  
- Gender  
- Native Country  
- Relationship  
- Capital Gain  
- Hours per Week  
- Work Class  
- Experience

---

## 🧠 Machine Learning Models Used

- ✅ Logistic Regression  
- ✅ K-Nearest Neighbors (KNN)  
- ✅ Random Forest  
- ✅ Support Vector Machine (SVM)  
- ✅ Gradient Boosting  
- ✅ Multi-Layer Perceptron (Neural Network)

All models were compared and the best one was saved as `best_model.pkl`.

---

## 📊 SHAP Explainability

Model predictions were interpreted using **SHAP (SHapley Additive Explanations)** for transparency and explainability.


---


## 🌐 Streamlit Web App

### 🔹 Features:

- Real-time prediction of salary class from user input  
- Batch prediction from uploaded CSV file  
- Download CSV with predicted results  

### 🔹 Inputs:

- Age  
- Education  
- Occupation  
- Experience  
- Hours per week

---

## 📦 `requirements.txt`


pandas
numpy
matplotlib
seaborn
scikit-learn
shap
streamlit
joblib
pyngrok

---

## 📈 Future Improvements

- Add cross-validation and hyperparameter tuning  
- Integrate REST API with Flask or FastAPI  
- Host Streamlit app on Render, Hugging Face, or AWS  
- Add login/authentication to app  
- Use Deep Learning models like TabNet for better performance
