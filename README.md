# Diabetes-Prediction

# 🩺 Diabetes Prediction using Machine Learning

This project implements a **Diabetes Prediction System** using **Machine Learning classification techniques**.  
The model predicts whether a person is **diabetic or non-diabetic** based on medical and lifestyle attributes.

---

## 📌 Project Overview

Diabetes is a chronic disease that affects millions of people worldwide. Early prediction and diagnosis can help in managing the condition and preventing serious complications.  
This project uses **machine learning** to analyze patient data and predict the presence of diabetes.

- **Algorithm Used:** Logistic Regression  
- **Dataset Type:** Medical diagnostic data  
- **Problem Type:** Binary Classification  

---

## 🧠 Machine Learning Workflow

1. Import required dependencies  
2. Load and explore the dataset  
3. Perform data preprocessing  
4. Split data into training and testing sets  
5. Train the machine learning model  
6. Evaluate model performance  
7. Build a predictive system for new patient data  

---

## 🧪 Dataset Description

The dataset consists of several medical predictor variables and one target variable.

| Feature | Description |
|-------|------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | Serum insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes heredity function |
| Age | Age of the patient |
| Outcome | 1 = Diabetic, 0 = Non-Diabetic |

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  

---

## 📊 Model Performance

The model is evaluated using **accuracy score** on both training and testing datasets to ensure reliable predictions.

*(Accuracy may vary based on random state and preprocessing steps.)*

---

## 🔮 Predictive System

The trained model can predict whether a person has diabetes based on new input values.

### Example Input
```python
input_data = (5, 166, 72, 19, 175, 25.8, 0.587, 51)

Output
The Person is Diabetic

```

or

The Person is Not Diabetic

🚀 How to Run the Project

Clone the repository

git clone https://github.com/akhilsurabhi07/Diabetes-Prediction.git


Install required dependencies

pip install numpy pandas scikit-learn


Launch Jupyter Notebook

jupyter notebook


Open the notebook and run all cells sequentially

📌 Key Highlights

End-to-end ML pipeline

Binary classification using Logistic Regression

Clean data preprocessing

Real-time prediction support

Beginner-friendly and well-structured code

🔮 Future Enhancements

Apply feature scaling and normalization

Try advanced algorithms (Random Forest, SVM, XGBoost)

Add confusion matrix and ROC-AUC curve

Deploy as a web application using Flask or FastAPI

👤 Author

Akhil Surabhi
B.Tech – Computer Science and Engineering (AIML)
Vignan Institute of Technology and Science

GitHub: https://github.com/akhilsurabhi07

LinkedIn: https://www.linkedin.com/in/akhil-surabhi-641745255
