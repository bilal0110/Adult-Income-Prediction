# Adult Income Prediction

## 📌 Project Overview
This project predicts whether an individual's income exceeds **$50K per year** based on census data.  
It is a **binary classification problem** using machine learning techniques.

The dataset is taken from the **1994 U.S. Census Bureau database**, extracted by **Ronny Kohavi and Barry Becker**.

---

## 🎯 Objective
To build a machine learning model that can classify income into:

- `<=50K`
- `>50K`

---

## 📊 Dataset Information

- Source: UCI Machine Learning Repository  
- Records were filtered using:
  - Age > 16  
  - AGI > 100  
  - fnlwgt > 1  
  - Hours per week > 0  

---

## 🧾 Features

- Age  
- Workclass  
- Education  
- Marital Status  
- Occupation  
- Relationship  
- Race  
- Sex  
- Capital Gain  
- Capital Loss  
- Hours per Week  
- Native Country  

---

## ⚙️ Project Workflow

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training  
5. Model Evaluation  

---

## 🤖 Models Used

- XGB Classifier

---

## 📈 Evaluation Metrics

- Accuracy  
- Confusion Matrix  

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/adult-income-prediction.git
cd adult-income-prediction
pip install -r requirements.txt
python app.py
