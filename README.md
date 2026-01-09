#  Diabetes Prediction using Machine Learning

##  Overview
This project predicts whether a person is diabetic based on medical diagnostic measurements using machine learning.  
It is a complete **end-to-end ML pipeline** including data preprocessing, model training, evaluation, and prediction.

The goal is to help identify high-risk patients early and support healthcare decision-making.

---

##  Dataset
The dataset contains medical records of patients with the following features:

| Feature | Description |
|--------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Skin fold thickness |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Genetic risk |
| Age | Age of patient |
| Outcome | 0 = Non-diabetic, 1 = Diabetic |

**Source:** PIMA Indians Diabetes Dataset (Kaggle)

---

##  Project Workflow
1. Data loading  
2. Data cleaning and handling missing values  
3. Exploratory Data Analysis (EDA)  
4. Feature scaling  
5. Train-test split  
6. Model training  
7. Model evaluation  
8. Final prediction  

---

##  Machine Learning Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Random Forest  
- Decision Tree  

The best performing model is selected based on accuracy and evaluation metrics.

---

##  Model Performance
The model is evaluated using:
- Accuracy  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)  

The final model provides reliable predictions on unseen patient data.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

##  How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/KavinKohli/diabetes-prediction-ml.git
cd diabetes-prediction-ml
