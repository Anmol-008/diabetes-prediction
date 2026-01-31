# Diabetes Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting whether a person is diabetic based on medical and health-related parameters.  
A supervised machine learning classification model is trained on patient data and used to make reliable predictions.

The project covers the **end-to-end machine learning workflow**, including data preprocessing, model training, evaluation, and inference using a saved model.

---

## 🎯 Objective
To build a machine learning model that can:
- Analyze patient health metrics
- Predict diabetes occurrence
- Demonstrate practical application of ML in healthcare

---

## 📂 Dataset
- **File:** `diabetes.csv`
- The dataset includes the following features:
  - Pregnancies
  - Glucose level
  - Blood pressure
  - Skin thickness
  - Insulin
  - BMI
  - Diabetes pedigree function
  - Age

---

## 🧠 Machine Learning Approach
- **Problem Type:** Binary Classification
- **Algorithm:** Supervised Machine Learning (Scikit-learn)
- **Model Output:**  
  - `0` → Non-Diabetic  
  - `1` → Diabetic

The trained model is saved as:
model.pkl

This allows the model to be reused for predictions without retraining.

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
diabetes-prediction/
├── README.md
├── requirements.txt
├── diabetes.csv
├── diabetes_prediction.ipynb
├── model.pkl


---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash

git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
2️⃣ Install Dependencies

Make sure Python is installed, then run:

pip install -r requirements.txt

3️⃣ Run the Notebook
jupyter notebook


Open diabetes_prediction.ipynb

Run all cells in sequence
```


---

## 📊 Results

The model predicts whether a patient is Diabetic or Non-Diabetic

Model performance is evaluated using standard classification metrics

Visualizations help understand feature importance and data distribution

## 🔍 Key Learnings

Data preprocessing and feature handling

Training and evaluating classification models

Saving and loading trained ML models

Applying machine learning to healthcare data

## 📌 Use Cases

Academic machine learning project

Healthcare data analysis example

Resume and internship portfolio project

## 👤 Author

Anmol Agrawal

