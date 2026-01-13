# Sonar Rock vs Mine Prediction 🎯

This project is a **Machine Learning classification system** that predicts whether an object detected by sonar signals is a **Rock** or a **Mine**, using **Logistic Regression**.

---

## 📌 Project Overview

Sonar systems emit sound waves and analyze the reflected signals to detect underwater objects.  
In this project, we use **machine learning** to classify these sonar signals into:
- **R** → Rock  
- **M** → Mine  

The model is trained on numerical features extracted from sonar returns.

---

## 🛠️ Technologies Used

- **Python**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Logistic Regression**

---

## 📂 Dataset

- The dataset consists of **60 numerical features** representing sonar signal strengths.
- Each row corresponds to one sonar reading.
- The target label indicates whether the object is a **Rock (R)** or **Mine (M)**.

---

## ⚙️ Workflow

1. Load and explore the dataset  
2. Data preprocessing  
3. Split data into training and testing sets  
4. Train Logistic Regression model  
5. Evaluate model performance using accuracy score  

---

## 📊 Model Used

- **Logistic Regression**
  - Suitable for **binary classification**
  - Simple, efficient, and interpretable model

---

## ✅ Results

- The model successfully classifies sonar signals into Rock or Mine.
- Achieved good accuracy on test data.
- Demonstrates a complete **end-to-end supervised learning pipeline**.

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/vishnuharan240701605/SONAR_ROCK_MINE_PREDICTION.git
