# ChurnPredictX 🚀

**A machine learning-powered telecom churn prediction system using the Kaggle Telco dataset.**

## 📌 Overview  
ChurnPredictX predicts whether a telecom customer will churn based on factors like **tenure, monthly charges, contract type, online security, and more**. It leverages **Exploratory Data Analysis (EDA)** and a **Decision Tree Classifier** for accurate and interpretable predictions. Since **acquisition costs exceed retention**, this project helps businesses minimize customer churn.

## 📊 Dataset  
- **Source:** [Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Features Used:**  
  - Demographics (Gender, Senior Citizen, Partner, Dependents)  
  - Account Details (Tenure, Contract, Billing Method)  
  - Services Used (Phone, Internet, Streaming, Security)  
  - Financials (Monthly Charges, Total Charges)  
  - **Target Variable:** Churn (Yes/No)  

## 🏗️ Tech Stack  
- **Backend:** Flask  
- **Frontend:** HTML, CSS  
- **Machine Learning:** Scikit-learn, Pandas, NumPy, Matplotlib  

## ⚙️ Features  
✔ **Interactive UI** for user input (Flask-based)  
✔ **Real-time churn prediction** using trained ML model  
✔ **Feature importance analysis** to explain predictions  
✔ **Customizable and scalable** for real-world telecom businesses  

## 🚀 Installation & Usage  
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/ChurnPredictX.git
   cd ChurnPredictX
   ```  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the application  
   ```bash
   python app.py
   ```  
4. Open in browser: `http://127.0.0.1:5000`  

## 📷 Screenshot  
![ChurnPredictX UI](Screenshot%202025-02-07%20222117.png)  

## 📈 Model Performance  
- **Algorithm Used:** Decision Tree Classifier  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score  
- **Feature Importance:** Contract type, tenure, monthly charges are key indicators of churn  

## 🎯 Future Improvements  
- Implement advanced models like **Random Forest, XGBoost** for better accuracy  
- Add **SHAP values** for deeper model interpretability  
- Deploy on **Heroku/Render** for public access  

## 🤝 Contribution  
Feel free to fork the repo, raise issues, and submit pull requests.  

## 📜 License  
This project is licensed under the **MIT License**.  
