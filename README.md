# 🏥 INSU_PREDICT – Medical Insurance Cost Prediction

## Overview
**INSU_PREDICT** is a machine learning project that predicts medical insurance costs based on user data such as age, BMI, gender, smoking habits, region, and number of children. The objective is to help insurance providers estimate premiums more fairly and accurately using data-driven insights.

---

## 🔍 Problem Statement
Insurance companies often rely on manual or fixed models to assign premium costs, which can be inconsistent or unfair. This project builds a predictive model using real-world data to understand how different features affect the final charges and to make accurate cost predictions.

---

## 📊 Features Used
- Age
- Gender
- BMI (Body Mass Index)
- Smoking Status
- Region
- Number of Children

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Modeling Techniques**: Linear Regression, Random Forest, XGBoost  
- **Development Tools**: Jupyter Notebook

---

## 🧪 Workflow
1. **Data Cleaning & Preprocessing**  
   - Handled missing values (if any)  
   - Converted categorical variables using one-hot encoding  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions and correlations  
   - Found trends like smokers having significantly higher charges  

3. **Model Training & Evaluation**  
   - Trained multiple regression models  
   - Evaluated performance using MAE, RMSE, and R² Score  

4. **Result Interpretation**  
   - Identified the most influential features  
   - Tuned models for better performance

---

## 📈 Results
- Achieved strong prediction accuracy on unseen test data
- Found **smoking** and **BMI** to be among the most important factors
- Compared models and selected the best based on error metrics

---

## 🚀 Future Improvements
- Add UI to take live user inputs and show predicted insurance cost
- Include more features like medical history, exercise habits, etc.
- Deploy as a web app using Flask or Streamlit

---

## 📁 Files Included
- `insurance.csv` – Dataset  
- `insu_predict.ipynb` – Jupyter Notebook with full workflow  
- `README.md` – Project documentation  

---

## 📬 Contact
Have questions or suggestions? Feel free to reach out at:  
📧 [vipinpavel3@gmail.com](mailto:vipinpavel3@gmail.com)

---

