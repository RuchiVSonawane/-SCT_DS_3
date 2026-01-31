# Task 3: Decision Tree Classification – Bank Marketing Dataset

## 📌 Objective
The objective of this task is to build a **Decision Tree classification model**
to predict whether a customer will subscribe to a **term deposit** based on
their personal and campaign-related attributes.

This task demonstrates a complete **machine learning workflow** including
data preprocessing, model training, evaluation, and interpretation.

---

## 📊 Dataset
- **Name:** Bank Marketing Dataset  
- **Source:** UCI Machine Learning Repository  
- **Description:**  
  The dataset contains information about bank customers such as age, job,
  balance, loan status, and campaign details.  
- **Target Variable:**  
  - `y` → Indicates whether the customer subscribed to a term deposit (`yes` / `no`)

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## ⚙️ Methodology
The following steps were followed in this task:

1. **Data Loading**
   - Loaded the Bank Marketing dataset using Pandas.

2. **Data Preprocessing**
   - Converted categorical variables into numerical form using one-hot encoding.

3. **Train-Test Split**
   - Split the dataset into training (80%) and testing (20%) sets.

4. **Model Training**
   - Trained a Decision Tree Classifier with controlled depth to avoid overfitting.

5. **Model Evaluation**
   - Evaluated the model using accuracy score.
   - Visualized performance using a confusion matrix.

6. **Feature Importance Analysis**
   - Identified the most influential features affecting customer subscription decisions.

---

## 📈 Results
- The Decision Tree model achieved **good accuracy** on the test dataset.
- The confusion matrix showed effective classification of both positive and negative cases.
- Feature importance analysis highlighted key factors influencing customer decisions.

---

## 🔍 Key Insights
- Campaign-related features such as contact duration significantly impact predictions.
- Limiting tree depth improves generalization and reduces overfitting.
- Decision Trees provide clear interpretability through feature importance.

---

## ✅ Conclusion
This task demonstrates how a Decision Tree classifier can be used to solve a
real-world classification problem. The model provides both predictive power
and interpretability, making it a useful tool for business decision-making.

---

## 📁 Repository Structure
SCT_DS_3/
│── dataset/
│ └── bank.csv
│── images/
│── task3_decision_tree.ipynb
│── README.md

