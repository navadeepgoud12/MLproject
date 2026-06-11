# 🎓 Student Performance Prediction System

An end-to-end Machine Learning project that predicts a student's mathematics score based on demographic, educational, and academic factors. This project helps analyze the factors influencing student performance and provides accurate score predictions using machine learning models. :contentReference[oaicite:0]{index=0}

---

## 🚀 Project Overview

Student performance is influenced by various factors such as:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

This project uses machine learning techniques to predict a student's mathematics score based on these features. The goal is to help educators and institutions gain insights into student performance and identify areas where additional support may be needed. :contentReference[oaicite:1]{index=1}

---

## 📌 Features

✅ Data Ingestion Pipeline

✅ Data Preprocessing and Transformation

✅ Exploratory Data Analysis (EDA)

✅ Model Training and Evaluation

✅ Hyperparameter Tuning

✅ Prediction Pipeline

✅ User-Friendly Web Interface

✅ End-to-End Machine Learning Workflow

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- CatBoost
- XGBoost

### Web Framework
- Flask

### Deployment & Tools
- Git
- GitHub
- VS Code

---

## 📂 Project Structure
MLproject/
│
├── artifacts/
├── notebook/
├── src/
│ ├── components/
│ ├── pipeline/
│ ├── logger.py
│ ├── exception.py
│ └── utils.py
│
├── templates/
├── static/
├── app.py
├── requirements.txt
├── setup.py
└── README.md


---

## 🔄 Project Workflow

### 1. Data Collection
Dataset containing student demographic and academic information.

### 2. Data Preprocessing
- Handling missing values
- Encoding categorical features
- Feature scaling

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis
- Correlation analysis
- Feature importance visualization

### 4. Model Training
Various machine learning algorithms were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- CatBoost Regressor
- XGBoost Regressor

### 5. Model Selection
The best-performing model was selected based on evaluation metrics.

### 6. Prediction
Users can enter student details through the web interface and receive predicted mathematics scores.

---

## 📊 Model Evaluation Metrics

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 💻 Installation

### Clone Repository

```bash
git clone https://github.com/navadeepgoud12/MLproject.git
cd MLproject
conda create -n venv python==3.8 -y
conda activate venv
pip install -r requirements.txt
python app.py
