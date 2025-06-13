# 🩺 KidneyCare Predictor

**KidneyCare Predictor** is a Streamlit-based machine learning web application for the **early detection of Chronic Kidney Disease (CKD)**. It integrates multiple ML models to provide an interpretable, scalable solution for clinical decision support.

---

## 📌 Abstract

Chronic Kidney Disease (CKD) is a growing global health challenge, often diagnosed at advanced stages due to the lack of early detection tools. Late-stage diagnosis leads to severe complications, including kidney failure, cardiovascular diseases, and increased healthcare burdens.

This project proposes **"KidneyCare Predictor: AI-Driven Early Detection of Chronic Kidney Disease Using Clinical and Laboratory Data"**, an intelligent predictive model designed to assist in early diagnosis and intervention.

The system leverages machine learning techniques to analyze structured patient data, including blood pressure, creatinine levels, glucose concentration, and other clinical parameters. Using supervised learning models such as **Decision Trees**, **Random Forest**, and **Logistic Regression**, the system predicts CKD likelihood with high accuracy. Data augmentation and feature engineering techniques are applied to improve model robustness and reduce biases.

---

## 🧠 Features

- 📋 Inputs based on clinical and laboratory data
- ⚙️ Integrated ML models: Logistic Regression, Decision Tree, Random Forest
- 📊 Real-time model performance metrics (Accuracy, Precision, Recall, F1-score)
- 📈 Visualizations: Correlation heatmaps, feature importance, EDA
- 🧵 Streamlit UI for interactive prediction and analysis

---

## 🧱 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **ML Libraries**: Scikit-learn, Pandas, NumPy, Seaborn, Matplotlib
- **Deployment**: Streamlit Cloud / Localhost

---

## 📁 Project Structure

KidneyCare-Predictor/  
├── app.py                      - Streamlit application  
├── models/                     - Serialized models (Pickle files)  
├── data/                       - Dataset (CSV format)  
├── utils/                      - Helper functions for EDA and preprocessing  
├── requirements.txt  
└── README.md

## Getting Started

1. Clone the Repository  
   git clone git@github.com:supramm/KidneyCare-Predictor.git  
   cd KidneyCare-Predictor  

2. Install Dependencies  
   pip install -r requirements.txt  

3. Run the App  
   streamlit run app.py  

## ML Models Used

Logistic Regression  
Decision Tree  
Random Forest  

All models are evaluated using Accuracy, Precision, Recall, and F1-score.

## Methodology

- Data Cleaning and Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering and Selection  
- Model Training and Evaluation  
- Deployment via Streamlit  

## License

This project is licensed under the MIT License.

## Author

Supram Kumar  
GitHub: https://github.com/supramm  
Made with love for better healthcare through AI.
