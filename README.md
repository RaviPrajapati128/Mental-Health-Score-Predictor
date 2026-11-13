# 🧠 Mindscore: Student Mental Health & Wellbeing Estimator

An end-to-end Machine Learning web application designed to assess student mental health and wellbeing risks based on lifestyle metrics, daily screen time, physical activity, and academic stress indicators. Built using Python, Scikit-Learn, and FastAPI, the system processes student behavioral data to deliver real-time wellbeing predictions.

---

## 🚀 Features
- **Predictive Behavioral Modeling:** Evaluates lifestyle parameters (sleep duration, study hours, physical activity) to estimate mental health and wellbeing scores.
- **Data Preprocessing & EDA:** Analyzes feature correlations and handles missing values via a structured Jupyter Notebook pipeline.
- **RESTful API Backend:** Powered by `FastAPI` and `Pydantic` for rigorous input validation and real-time inference.
- **Model Serialization:** Exports trained machine learning models via `joblib` for seamless deployment.
- **Interactive Web Dashboard:** A responsive HTML5 frontend featuring custom CSS styling and dynamic UI feedback.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Data Manipulation & Analysis:** NumPy, Pandas, Seaborn, Matplotlib, Jupyter Notebook
- **Machine Learning:** Scikit-Learn
- **Backend Framework:** FastAPI, Uvicorn, Pydantic
- **Model Serialization:** Joblib
- **Frontend:** HTML5, CSS3, JavaScript

---

## 📊 Dataset Overview
The project utilizes student lifestyle and academic behavioral metrics (`Mental_Health_Impact.csv`), which include attributes such as:
- `Study_Hours`: Daily hours dedicated to academics.
- `Screen_Time`: Daily digital and mobile device usage.
- `Physical_Activity`: Hours spent on exercise or sports per week.
- `Sleep_Duration`: Average hours of sleep per night.
- `Stress_Level`: Categorical or numerical indicator of academic pressure.

---

## ⚙️ Project Workflow & Pipeline

1. **Exploratory Data Analysis (EDA):**  
   * Analyzed feature distributions and correlation matrices in Jupyter Notebooks to understand the impact of lifestyle habits on student mental health.
2. **Data Cleaning & Preparation:**  
   * Handled missing values, encoded categorical features, and normalized numerical metrics for model training.
3. **Model Training:**  
   * Trained and evaluated Scikit-learn predictive models to accurately map behavioral traits to mental health risk scores.
4. **API Integration:**  
   * Wrapped the serialized model inside a high-performance FastAPI application with strict schema validation.
5. **Frontend Dashboard:**  
   * Built a clean, user-facing HTML interface (`index.html`) to capture user inputs and display predictions seamlessly.

