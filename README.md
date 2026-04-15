# 📊 Student Study Time vs Productivity Analyzer

## 📌 Overview  
Students often spend long hours studying but still feel unproductive. This project uses Machine Learning to analyze how different factors affect student productivity and predicts a productivity score based on study habits and lifestyle.

---

## 🎯 Objective  
To build a Machine Learning model that predicts student productivity using key factors such as:
- Study hours  
- Sleep duration  
- Distractions  
- Break time  
- Revision habits  

The goal is to help students optimize their study patterns for better efficiency.

---

## 🧠 Approach  
This project is designed as a Supervised Machine Learning Regression problem, where:
- Input → Study & lifestyle features  
- Output → Productivity score (continuous value)

---

## ⚙️ Methodology  

### 📊 Data Collection  
- Created a synthetic dataset simulating real student behavior  
- Features used:
  - Study Time  
  - Break Time  
  - Distractions  
  - Sleep Hours  
  - Mood Level  
  - Subject Type  
  - Environment  
  - Device Usage  
  - Weather  

---

### 🧹 Data Preprocessing  
- Cleaned and structured the dataset  
- Separated:
  - X (input features)  
  - y (productivity score)  
- Prepared data for training  

---

### 🔀 Train-Test Split  
- Split data into training and testing sets  
- Model trained on training data and evaluated on unseen data  

---

### 🤖 Algorithms Used  
- Linear Regression (Primary Model)  
  - Helps understand how each factor affects productivity  

- Random Forest Regressor (Advanced Model)  
  - Improves accuracy  
  - Reduces overfitting  

---

### 📈 Model Evaluation  
Used the following metrics:
- Mean Squared Error (MSE) → Measures prediction error  
- R² Score → Measures how well the model explains the data  

Higher R² score indicates better performance.

---

## 📊 Results & Insights  
- Increased study hours improve productivity (up to a limit)  
- Distractions significantly reduce productivity  
- Proper sleep improves efficiency  
- Revision plays a key role in retention  

---

## 🛠️ Tech Stack  
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## 🙌 Conclusion  
This project demonstrates how Machine Learning can be used to analyze and improve student productivity and bridges the gap between theory and real-world application.

---

## ✨ Note  
This project will be further refined to enhance model accuracy and performance.

---
