# 🫀 Heart Disease Prediction

This project predicts the likelihood of heart disease using machine learning techniques.  
It involves **data analysis**, **feature engineering**, **training multiple models**, and finally building an interactive **Streamlit web app** to make real-time predictions.

---

## 📂 Project Overview
1. **Data Analysis & Preprocessing**  
   - Explored the raw dataset (EDA with visualizations & statistics).  
   - Handled missing values and cleaned noisy data.  
   - Added new derived columns for better feature representation.  

2. **Model Training**  
   - Trained and evaluated multiple machine learning models, including:  
     - K-Nearest Neighbors (KNN)  
     - Logistic Regression  
     - Support Vector Machine (SVM)  
     - Decision Tree, Random Forest, and others.  
   - Compared their performance using accuracy, precision, recall, F1-score, and ROC-AUC.  
   - Selected the **best performing model** for deployment.

3. **Streamlit Application**  
   - Built an interactive web app where users can input patient details (age, sex, cholesterol, etc.).  
   - The model outputs a simple **“Yes / No”** answer to indicate if the person is at risk of heart disease.  

---

## 🚀 Tech Stack
- **Python**  
- **Jupyter Notebook** (data exploration & model training)  
- **Pandas, NumPy** (data handling)  
- **Matplotlib, Seaborn** (visualizations)  
- **Scikit-learn** (machine learning models)  
- **Joblib** (saving/loading the trained model)  
- **Streamlit** (building the web app)  

---

## 📊 Results
- The Logistic Regression model achieved the best balance of accuracy, precision, and recall.  
- The final model reached ~85% accuracy on the test dataset.  
- Compared to other models (KNN, SVM, Decision Tree, Random Forest), Logistic Regression provided the most reliable results.  
- The Streamlit app allows users to enter details and get a prediction instantly.  
