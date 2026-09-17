# online-shoppers-classification-capstone
"A machine learning classification capstone project predicting e-commerce customer purchase intent using UCI repository data and deployed via a Streamlit web interface."

# 🛍️ Online Shoppers Purchasing Intention - Machine Learning Capstone

This capstone project utilizes the **Online Shoppers Purchasing Intention Dataset** from the UCI Machine Learning Repository (UCI ID: 468) to predict whether an online browsing session will result in a purchase (`Revenue = True/False`).

## 🚀 Features & Methodology
- **Data Preprocessing & Scaling:** Handled categorical variables and standardized numerical metrics using `StandardScaler`.
- **Classification Models:** Evaluated multiple algorithms including *Random Forest*, *Logistic Regression*, *Decision Tree*, *K-Nearest Neighbors*, and *Support Vector Classifier*.
- **Hyperparameter Tuning:** Optimized performance using `GridSearchCV`.
- **Feature Importance:** Analyzed key drivers of purchases (with *PageValues* identified as the most impactful feature).
- **Interactive Deployment:** Built and hosted a live web app using **Streamlit** and **Cloudflare Tunnels**.

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn, Joblib)
- **Streamlit** (Web UI)
- **Google Colab** (Development Environment)
