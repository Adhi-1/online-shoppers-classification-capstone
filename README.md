# 🛍️ Online Shoppers Purchasing Intention - Machine Learning Capstone

This capstone project utilizes the **Online Shoppers Purchasing Intention Dataset** from the UCI Machine Learning Repository (UCI ID: 468) to predict whether an online browsing session will result in a purchase (`Revenue = True/False`).

## 🚀 Features & Methodology
- **Data Preprocessing & Scaling:** Handled categorical variables and standardized numerical metrics using `StandardScaler`.
- **Classification Models:** Evaluated multiple algorithms including *Random Forest*, *Logistic Regression*, *Decision Tree*, *K-Nearest Neighbors*, and *Support Vector Classifier*.
- **Hyperparameter Tuning:** Optimized performance using `GridSearchCV`.
- **Feature Importance:** Analyzed key drivers of purchases (with *PageValues* identified as the most impactful feature).
- **Interactive Deployment:** Built and hosted a live web app using **Streamlit** and **Cloudflare Tunnels**.

## 🖥️ App Preview & Live Predictions

Here is how the deployed Streamlit web application looks in action for different user session behaviors:

### 1. High Intent (Purchase Likely)
> When a user exhibits high page values and high product engagement, the model successfully predicts a high intent to purchase.
![High Intent Prediction](high_intent.png)

### 2. Low Intent (Purchase Unlikely)
> When a user has zero page values, high exit rates, and bounces quickly, the model predicts low intent.
![Low Intent Prediction](low_intent.png)

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn, Joblib)
- **Streamlit** (Web UI)
- **Google Colab** (Development Environment)
