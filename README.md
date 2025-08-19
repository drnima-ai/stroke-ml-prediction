# 🧠 Machine Learning for Stroke Prediction

This repository is a continuation of the [Exploratory Data Analysis (EDA)](https://github.com/drnima-ai/stroke-data-analysis) performed on the Kaggle Stroke Dataset.  
After cleaning and preparing the data in the EDA repository, this project focuses on building and evaluating machine learning models to predict the likelihood of stroke.

---

## 📊 Dataset Overview
- **Source:** Kaggle Stroke Prediction Dataset  
- **Samples:** 5110 patients  
- **Features:** Demographic and health metrics (e.g., Age, Hypertension, BMI, Smoking status)  
- **Target Variable:** 0 (No Stroke) / 1 (Stroke)  

---

## 🧠 Machine Learning for Stroke Prediction
After preparing the dataset, we implemented multiple machine learning models to predict stroke occurrence.  

### 🔢 Modeling Workflow:
1. Load the preprocessed data.  
2. Separate features (X) and the target variable (y).  
3. Split the data into training and testing sets.  
4. Handle the class imbalance using **SMOTE**.  
5. Train and evaluate three classification models:
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
   - Random Forest Classifier  
6. Compare model performance, focusing on **Recall** and **F1-Score** for the positive class (stroke=1).  

---

## 📈 Model Performance Metrics
- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1-Score**  
- **Confusion Matrix**  
- **Model Comparison & Conclusion**  

---

## 🧰 Technologies Used
- Python (Pandas, NumPy, Scikit-learn)  
- Data Visualization: Seaborn, Matplotlib  
- Jupyter Notebook  
- Git & GitHub  

---

## 📎 View the Notebook
👉 [Machine Learning for Stroke Prediction - Jupyter Notebook](https://github.com/drnima-ai/stroke-ml-prediction/blob/main/Machine%20Learning%20for%20Stroke%20Prediction.ipynb)  

---

## 📈 Future Improvements
- Hyperparameter tuning (e.g., GridSearchCV)  
- Additional models (SVM, XGBoost)  
- Cross-validation for more robust evaluation  
- Deployment (Flask, Streamlit)  

---

## 👨‍⚕️ About the Author
**Nima Karimi, M.D.**  
Medical Doctor | Data Science Enthusiast  
Special interest in medical applications of AI and machine learning  
🎸 Also a professional guitarist  

📧 Email: nima.karimi.20@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/drnima-ai)  

---

## 🛡️ License
This project is licensed under the MIT License.
