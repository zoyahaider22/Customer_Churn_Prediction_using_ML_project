
# 📊 Customer Churn Prediction using Machine Learning

This project aims to predict customer churn in the telecom industry using machine learning models. Accurate churn prediction helps telecom companies proactively retain customers, reduce revenue loss, and enhance customer satisfaction.

## 🔍 Problem Statement

Customer churn is a critical concern for telecom providers. It refers to the loss of clients or subscribers. Predicting churn accurately allows businesses to take preventive measures and improve customer retention strategies.

---

## 💡 Solution Overview

This project builds a predictive system using:
- **Data Preprocessing** (missing value handling, label encoding)
- **Exploratory Data Analysis (EDA)**
- **Class Imbalance Handling** using **SMOTEENN**
- **Model Training** with **Decision Tree**, **Random Forest**, and **XGBoost**
- **Hyperparameter Tuning** with **GridSearchCV**
- **Deployment** via a simple **Streamlit web application**

---

## 📁 Dataset

- Source: [IBM Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Rows: 7043
- Features: 21 (demographic, service, billing info, etc.)

---

## ⚙️ Technologies & Libraries

- **Python 3.10+**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`
- `xgboost`
- `imbalanced-learn` (SMOTE, SMOTEENN)
- `pickle` for model serialization
- `Streamlit` for model deployment

---

## 📈 Model Performance

| Model         | Accuracy (CV Avg) | F1-Score (Churn) | Recall (Churn) |
|---------------|------------------|------------------|----------------|
| Decision Tree | 92.2%            | 72%              | 75%            |
| Random Forest | 94.7%            | 78%              | 79%            |
| **XGBoost**   | **94.9%**        | **80%**          | **81%**        |

✅ **XGBoost** was selected as the final model for deployment.

---

## 📊 Key Visuals

- Confusion Matrix
- ROC Curve
- Feature Importance Plot

---

## 🚀 How to Use

1. **Clone the repository**  
   ```bash
   git clone https://github.com/zoyahaider22/Customer_Churn_Prediction_using_ML_project.git
   cd Customer_Churn_Prediction_using_ML_project
````

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**

   ```bash
   streamlit run app.py
   ```

4. **Input customer details** in the app interface and get real-time churn prediction with probability.

---

## 🧠 Future Scope

* Integrate behavioral data (call logs, complaints) for improved accuracy
* Cloud deployment and API integration
* Real-time monitoring dashboard
* Use of advanced techniques like LightGBM, AutoML, or Edge AI

---

## 📚 References

* [Scikit-learn Documentation](https://scikit-learn.org/)
* [XGBoost Documentation](https://xgboost.readthedocs.io/)
* [SMOTEENN - imbalanced-learn](https://imbalanced-learn.org/stable/)


---

## 🔗 GitHub Link

[https://github.com/zoyahaider22/Customer\_Churn\_Prediction\_using\_ML\_project](https://github.com/zoyahaider22/Customer_Churn_Prediction_using_ML_project)

---

## 🙋‍♀️ Author

**Zoya Haider**
M.Tech in Data Science, Jamia Hamdard University
📧 [zoyahaidersusz@gmail.com](mailto:zoyahaidersusz@gmail.com)
📍 Patna, Bihar, India
[LinkedIn](https://www.linkedin.com/in/zoya-haider-13b14b262)

---

⭐️ *If you found this project helpful, please consider giving it a star!*

```

