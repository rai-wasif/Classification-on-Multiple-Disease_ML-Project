# 🏥 Classification on Multiple Disease
> *Leveraging Machine Learning for Early Diabetes Detection & Better Disease Management.*

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Enabled-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/ML-Classification-green?style=for-the-badge)

## 📖 Overview
This project utilizes machine learning techniques to predict the risk of **Diabetes** based on a variety of health-related features. By analyzing lifestyle choices and medical history—such as BMI, smoking habits, and heart condition—the model aims to facilitate early detection, allowing for timely intervention and better long-term health management.

---

## 📊 Dataset Features
The model is trained on key health indicators that significantly influence diabetes risk:

| Feature | Description |
| :--- | :--- |
| **❤️ Heart Disease** | History of heart conditions or prior attacks. |
| **⚖️ BMI** | Body Mass Index; a primary indicator of obesity. |
| **🚬 Smoking** | Smoking history, known to impact insulin sensitivity. |
| **🍷 Alcohol Drinking** | Habits affecting liver function and insulin resistance. |
| **🧠 Stroke** | History of stroke indicating vascular health risks. |
| **🏃 Physical Activity** | Frequency of exercise (crucial for weight management). |
| **🛌 Sleep Time** | Average sleep duration, linked to hormonal regulation. |
| **🏥 General Health** | Self-reported overall health status. |
| **🧘 Phys/Mental Health** | Days of poor physical or mental health in the past month. |

---

## ⚙️ Approach & Methodology

### 1. Preprocessing 🧹
* **Data Cleaning:** Handling missing values and outliers.
* **Encoding:** Converting categorical variables (e.g., "Yes"/"No") into numerical format.
* **Scaling:** Normalizing numerical features like BMI to ensure fair model weighting.

### 2. Handling Imbalance ⚖️
* Datasets in healthcare are often imbalanced (fewer positive cases).
* We employ techniques like **SMOTE (Synthetic Minority Over-sampling Technique)** or Class Weighting to ensure the model learns to identify high-risk patients effectively.

### 3. Model Selection 🤖
We experiment with a robust suite of algorithms to find the best performer:
* Logistic Regression
* Decision Trees & Random Forests
* Support Vector Machines (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* XGBoost
* Neural Networks

### 4. Evaluation & Tuning 📈
* **Metrics:** Accuracy, Precision, Recall, and F1-score.
* **Tuning:** Hyperparameter optimization (GridSearchCV/RandomizedSearchCV) to maximize predictive performance.

---

## 🎯 Project Goal
To develop a high-accuracy predictive model that serves as a reliable tool for healthcare professionals, aiding in the **early identification of at-risk individuals** and promoting proactive health decisions.

---

### 🚀 Getting Started

```bash
# Clone the repository
git clone [https://github.com/your-username/Classification-on-Multiple-Disease.git](https://github.com/your-username/Classification-on-Multiple-Disease.git)

# Install dependencies
pip install -r requirements.txt

# Run the analysis
python main.py
