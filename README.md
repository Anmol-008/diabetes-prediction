# 🧠 Diabetes Prediction System using Machine Learning

## 📌 Overview
This project focuses on predicting whether a patient is diabetic based on medical attributes using machine learning.

Unlike basic implementations, this project simulates a **real-world healthcare data pipeline** by working on a large dataset (~100,000 records) containing practical data issues such as missing values, invalid entries, and outliers.

The project demonstrates a complete **end-to-end machine learning workflow**, from raw data cleaning to model optimization and prediction.

---

## 🎯 Objective
To build a robust machine learning system that can:
- Handle real-world noisy healthcare data
- Predict diabetes accurately
- Minimize false negatives (critical in medical diagnosis)

---

## 📂 Dataset
- **File:** `diabetes_raw_100k.csv`
- **Size:** ~100,000 records

### Features:
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  
- Outcome (Target Variable)

---

## ⚠️ Real-World Data Challenges
The dataset includes intentionally introduced issues to simulate real-world conditions:

- Missing values across multiple features  
- Invalid zero values in medical attributes (e.g., BMI, Glucose)  
- Outliers in features like Glucose  

These were handled using appropriate preprocessing techniques.

---

## 🧹 Data Preprocessing
- Converted invalid zero values to missing values  
- Handled missing data using **median imputation**  
- Removed outliers using **IQR method**  
- Applied **feature scaling (StandardScaler)** for SVM  

---

## 📊 Exploratory Data Analysis (EDA)
- Analyzed feature distributions  
- Checked class imbalance in target variable  
- Performed correlation analysis using heatmaps  
- Identified key predictors like **Glucose, BMI, and Age**

---

## 🤖 Machine Learning Models
The following models were trained and compared:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  

---

## ⚙️ Model Optimization
- Used **GridSearchCV** for hyperparameter tuning  
- Tuned parameters:
  - C (regularization)
  - Kernel (linear, rbf)
  - Gamma  

- Used **F1-score** as evaluation metric due to class imbalance  

---

## 📈 Model Evaluation
Evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

> ⚠️ Special Focus:  
Recall was prioritized to reduce false negatives, which is critical in medical diagnosis.

---

## 🏆 Final Model
- **Algorithm:** Support Vector Machine (SVM)  
- Optimized using GridSearchCV  
- Provides balanced performance across precision and recall  

---

## 🔮 Prediction System
A prediction function is implemented to:
- Take patient input data  
- Return whether the patient is **Diabetic or Not Diabetic**

---

## 🛠️ Technologies & Tools
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📦 Project Structure

diabetes-ml-project/
├── data/
│ └── diabetes_raw_100k.csv
├── notebooks/
│ └── diabetes_analysis.ipynb
├── models/
│ └── svm_diabetes_model.pkl
├── requirements.txt
├── README.md


---

## 🚀 How to Run the Project

### 1️⃣ Clone Repository
```bash```
git clone https://github.com/your-username/diabetes-ml-project.git
cd diabetes-ml-project
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run Notebook
jupyter notebook

Open the notebook and run all cells.

📊 Key Insights
Glucose is the strongest predictor of diabetes
BMI and Age significantly influence outcomes
Data preprocessing plays a critical role in model performance
🎯 Use Cases
Healthcare risk prediction
Academic machine learning project
Internship portfolio project
Real-world ML pipeline demonstration
🧠 Key Learnings
Handling real-world messy data
Feature engineering and preprocessing
Model comparison and selection
Hyperparameter tuning using GridSearchCV
Importance of evaluation metrics beyond accuracy
👤 Author

Anmol Agrawal
B.S. Data Science (IIT Madras) | B.Tech CSE
