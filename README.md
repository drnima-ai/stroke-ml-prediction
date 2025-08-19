# 🧠 Stroke Prediction - Machine Learning  

This repository is a continuation of the **[Exploratory Data Analysis (EDA)](https://github.com/drnima-ai/stroke-data-analysis)** performed on the [Kaggle Stroke Prediction Dataset]. After cleaning and preparing the data in the EDA phase, this project focuses on building and evaluating machine learning models to predict stroke risk in patients.  

Our main challenge, as identified in the EDA, is the **severe class imbalance**: only a small fraction of patients had a stroke. Therefore, the success of our models is measured not only by overall accuracy, but more importantly by **Recall** and **F1-Score** for the positive class (stroke = 1).  

---

## 📊 Dataset Overview  
- **Source**: [Kaggle Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)  
- **Samples**: 5,110 patients  
- **Features**: Demographics, health conditions, and lifestyle factors (e.g., Age, Hypertension, BMI, Smoking Status)  
- **Target Variable**:  
  - `0` = No Stroke  
  - `1` = Stroke  

---

## 🧠 Machine Learning for Stroke Prediction  

After preparing the dataset, multiple machine learning models were implemented to predict stroke risk.  

### 🔢 Modeling Workflow  
1. Feature and Target Separation  
2. Train-Test Split  
3. Handling Class Imbalance with **SMOTE**  
4. Model Training & Evaluation  

**Models Trained:**  
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  

**Performance Metrics:**  
- Accuracy  
- Precision  
- Recall (focus metric)  
- F1-Score  
- Confusion Matrix  
- ROC-AUC  

---

## 🧰 Technologies Used  
- **Python** (Pandas, NumPy, Scikit-learn, Imbalanced-learn)  
- **Data Visualization**: Seaborn, Matplotlib  
- **Jupyter Notebook**  
- **Git & GitHub**  

---

## 📎 View the Notebook  
👉 [Notebook Link](PUT-YOUR-NOTEBOOK-LINK-HERE)  

---

## 📈 Future Improvements  
- Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)  
- Testing additional models (XGBoost, LightGBM)  
- Applying cross-validation for robust evaluation  
- Deployment (Flask / Streamlit for web apps)  

---

## 👨‍⚕️ About the Author  
**Nima Karimi, M.D.**  
- Medical Doctor | Data Science Enthusiast  
- Passionate about AI & machine learning in healthcare  
- 🎸 Also a professional guitarist  

📧 Email: nima.karimi.20@gmail.com  
🔗 [LinkedIn Profile](PUT-YOUR-LINKEDIN-LINK-HERE)  

---

## 🛡️ License  
This project is licensed under the **MIT License**.  
