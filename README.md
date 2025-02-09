# Titanic-survival-prediction

# 📌 Project Overview

This project uses LightGBM to predict whether a passenger survived the Titanic disaster. Additionally, we leverage Explainable AI (XAI) techniques like SHAP to interpret model predictions.

# 🚀 Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/Pavithra412/Titanic-survival-prediction.git
cd Titanic-survival-prediction

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the model training & XAI script

python train_lightgbm.py

# 📊 Results & Model Performance

✅ Accuracy: ~82% (LightGBM)
✅ Explainability: SHAP values show feature importance

# 📌 Features Used

Pclass (Passenger class)

Sex (Gender)

Age (Filled missing values with median)

SibSp (No. of siblings/spouses aboard)

Parch (No. of parents/children aboard)

Fare (Ticket fare)

Embarked (Port of embarkation, filled missing values with mode)

# 📜 Explanation with SHAP

This project utilizes SHAP (SHapley Additive exPlanations) to interpret the model’s decisions. The summary plot highlights which features most influence survival predictions.

# 📌 Future Enhancements

Try different models (XGBoost, CatBoost, etc.)

Feature engineering for better performance

Deploy as a web app (Flask/Django)

# 👨‍💻 Author
Pavithra B

