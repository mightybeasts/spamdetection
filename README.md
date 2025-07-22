# 📧 Spam Email Detection with Machine Learning

---

## 🔍 Overview

This project demonstrates a machine learning approach to **detecting spam emails** using a labeled dataset.  
We preprocess the email text, extract features using vectorizers, and classify messages using models like **Naive Bayes**.

---

## 🧰 Key Features

✅ Clean and preprocess text data  
✅ Convert text to numerical features using **TF-IDF / CountVectorizer**  
✅ Train models like **Multinomial Naive Bayes** or **Logistic Regression**  
✅ Evaluate model with metrics: **Accuracy**, **Precision**, **Recall**, **Confusion Matrix**, **ROC Curve**  
✅ Save the trained model using **Joblib**  

---

## 🧪 Tech Stack

- 🐍 Python  
- 📊 scikit-learn  
- 🧮 NumPy & pandas  
- 📈 Matplotlib & Seaborn  
- ☁️ Google Colab (for development)

---

## 📦 How to Run

1. Clone the repo or upload the `.ipynb` notebook to Google Colab.  
2. Run all cells to train the model and visualize metrics.  
3. Use `predict_message()` to test any custom email string.  
4. Export trained model as `.pkl` using Joblib.

---

## 📸 Sample Output

- Confusion matrix heatmap  
- ROC curve with AUC  
- Final prediction with confidence  
- GridSearchCV for best parameters

---

## 👨‍💻 Author

**Faheem K**

---

## 📁 Dataset Source

[SMS Spam Collection Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)

---
