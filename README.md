# ❤️ Heart Disease Prediction باستخدام Machine Learning

## 📌 Overview

This project uses a **Random Forest Classifier** to predict the likelihood of heart disease based on medical attributes.
It takes user input values (like age, cholesterol, etc.) and outputs whether the person is at **high risk** or **low risk**.

---

## 🚀 Features

* Data preprocessing using StandardScaler
* Machine learning model using Random Forest
* User input-based prediction system
* Model evaluation with:

  * Accuracy score
  * Classification report
  * Confusion matrix visualization
  * ROC curve & AUC score

---

## 📂 Dataset

The dataset used is `heart_disease_data.csv`, which should contain the following columns:

* age
* sex
* cp (chest pain type)
* trestbps (resting blood pressure)
* chol (cholesterol level)
* fbs (fasting blood sugar)
* restecg (resting ECG results)
* thalach (maximum heart rate achieved)
* exang (exercise-induced angina)
* oldpeak (ST depression)
* slope (slope of peak exercise ST segment)
* ca (number of major vessels)
* thal
* target (0 = no disease, 1 = disease)

---

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Usage

Run the script:

```
python your_script_name.py
```

Then enter the required medical values when prompted.

Example:

```
Enter value for age: 52
Enter value for sex: 1
...
```

---

## 🧠 Model Used

* Random Forest Classifier (100 estimators)
* Train-test split: 80/20
* Feature scaling using StandardScaler

---

## 📊 Output

* Prediction result:

  * High risk of heart disease
  * Low risk of heart disease

* Performance metrics:

  * Accuracy score
  * Classification report

* Visualizations:

  * Confusion Matrix
  * ROC Curve

---

## ⚠️ Disclaimer

This project is for educational purposes only.
It is **not a medical diagnostic tool** and should not be used as a substitute for professional healthcare advice.

---

## 📌 Future Improvements

* Hyperparameter tuning
* Use of other models (e.g., Logistic Regression, XGBoost)
* Web app deployment (Flask/Streamlit)
* Real-time data integration

---

## 👨‍💻 Author

Your Name
GitHub: https://github.com/pranav4141

---
