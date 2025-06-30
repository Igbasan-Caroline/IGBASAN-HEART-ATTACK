# IGBASAN-HEART-ATTACK
Igbasan WebApp for Heart Disease Prediction

#  Heart Disease Prediction Web App

This project is a complete machine learning pipeline and web application that predicts the presence of heart disease based on clinical features. It demonstrates how AI can be applied in real-world healthcare settings through interactive and accessible web deployment using **Flask** and **Streamlit**.

##  Project Overview

- **Domain**: Healthcare
- **Goal**: Predict whether a patient has heart disease using 13 clinical variables
- **Model Used**: Logistic Regression (with Random Forest for feature importance)
- **Deployment**: Flask Web App (HTML form) and Streamlit Web App

---

##  Dataset

- **Source**: [Kaggle – Heart Disease UCI Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **Size**: 303 records
- **Target**: `1` = Disease Present, `0` = No Disease

### Features Used:

| Feature     | Description                                                  |
|-------------|--------------------------------------------------------------|
| `age`       | Age of the patient (years)                                   |
| `sex`       | Sex (1 = male; 0 = female)                                   |
| `cp`        | Chest pain type (0–3; higher = more typical angina)          |
| `trestbps`  | Resting blood pressure (mm Hg)                               |
| `chol`      | Serum cholesterol (mg/dl)                                    |
| `fbs`       | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)        |
| `restecg`   | Resting ECG results (0–2)                                    |
| `thalach`   | Maximum heart rate achieved                                  |
| `exang`     | Exercise induced angina (1 = yes; 0 = no)                    |
| `oldpeak`   | ST depression induced by exercise                            |
| `slope`     | Slope of peak ST segment (0–2)                               |
| `ca`        | Major vessels colored by fluoroscopy (0–3)                   |
| `thal`      | Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible)   |

---

##  Features

- Data Cleaning and Visualization (Seaborn, Matplotlib)
- Model Training and Evaluation (Scikit-learn)
- Feature Importance using Random Forest
- Patient Clustering with KMeans
- Web Interfaces:
  - **Flask Web App** with form-based HTML input and prediction route
  - **Streamlit App** for interactive, real-time prediction

---

##  Technologies Used

- Python
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- **Flask** (backend server with HTML templates)
- **Streamlit** (for quick UI deployment)
- Joblib (for saving ML models)

---

##  Web Application

-  **Live App (Streamlit)**: [https://igbasan-heart-attack-predict.streamlit.app](https://igbasan-heart-attack-predict.streamlit.app)
  
-  **GitHub Repo**: [https://github.com/Igbasan-Caroline/IGBASAN-HEART-ATTACK](https://github.com/Igbasan-Caroline/IGBASAN-HEART-ATTACK)

---

##  How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/Igbasan-Caroline/IGBASAN-HEART-ATTACK.git

cd IGBASAN-HEART-ATTACK

2. Install dependencies

pip install -r requirements.txt

Run the Flask App

python app.py


Future Improvements

- Integrate database to log predictions

- Add user authentication (especially for Flask)

- Deploy both Flask and Streamlit to cloud platforms ( Streamlit Cloud)

- Support batch predictions via file upload

Author
Igbasan Caroline
LinkedIn | GitHub



