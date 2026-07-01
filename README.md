# 🚦 Lagos Traffic Congestion Prediction Using Machine Learning

## 📊 Overview

An end-to-end data science and business intelligence project designed
to predict road traffic delays across critical transit corridors in
Lagos, Nigeria. This repository contains the complete technical
implementation, including data generation,
predictive machine learning pipelines (XGBoost), exploratory data
visualization scripts, and blueprints for an enterprise Power BI
dashboard.

The goal is to support **smart city planning, traffic optimization,
and data-driven transportation management** using real-world inspired
datasets and explainable AI techniques.

---

## 🎯 Research Objectives
Lagos is one of Africa’s fastest-growing megacities, where severe
traffic gridlock results in billions of Naira lost in economic
productivity, increased carbon emissions, and volatile commute times.

This project addresses a central research question: **Can machine
learning accurately forecast traffic congestion levels
($Delay\_Minutes$) by leveraging road characteristics, weather
conditions, temporal features, and traffic volume variables?**

- Analyze traffic congestion patterns across major Lagos roads
- Investigate the impact of time, weather, and road type on congestion
- Develop a predictive machine learning model for congestion classification
- Identify key factors influencing traffic delays
- Provide data-driven insights for urban transport planning

  
### Key Alignments
* **Machine Learning & Predictive Modeling** (Regression & Classification)
* **Big Data Analytics & Feature Engineering**
* **Smart Cities & Intelligent Transportation Systems (ITS)**
* **Business Intelligence & Executive Reporting** (Power BI)


---

## 📂 Dataset Description

The dataset contains hourly traffic observations across major Lagos roads.

### Features:

| Feature | Description |
|--------|-------------|
| Date | Observation date |
| Time | Hourly timestamp |
| Day_of_Week | Day classification |
| Road_Name | Major road in Lagos |
| Weather_Condition | Weather state (Clear, Rain, Haze, etc.) |
| Time_of_Day | Morning, Afternoon, Evening, Night |
| Traffic_Volume | Number of vehicles |
| Delay_Minutes | Average delay per observation |
| Congestion_Level | Target variable (Low, Moderate, Heavy Gridlock) |

---

## 🧠 Methodology

### 1. Data Collection
- Structured traffic dataset representing Lagos urban mobility patterns.
- Weather and temporal features included.

### 2. Data Cleaning
- Handled categorical encoding
- Extracted time-based features
- Converted congestion labels into ML format

### 3. Exploratory Data Analysis (EDA)
- Traffic distribution analysis
- Weather impact study
- Road-based congestion comparison
- Time-series traffic patterns

### 4. Machine Learning Models
- Logistic Regression
- Random Forest Classifier (Best Performance)
- Feature importance analysis

### 5. Evaluation Metrics
- Accuracy
- Precision / Recall / F1-score
- Confusion Matrix

---

## 📊 Key Visualizations

### 🔹 Traffic Distribution
- Congestion levels across dataset

### 🔹 Road Congestion Analysis
- Third Mainland Bridge and Lekki-Epe Expressway show highest congestion

### 🔹 Hourly Traffic Pattern
- Rush hour identification (Morning & Evening peaks)

### 🔹 Feature Correlation
- Strong correlation between Traffic Volume and Delay
  
### 🔹 Weather Impact
- Rainfall increases delay significantly

### 🔹 Traffic Volume By Delay
- Hours spent on a specific road

### 🔹 Number of Cars Distribution
- Peak hours and empty night roads

### 🔹 Congestion Levels
- Heavy Gridlock vs Moderate vs Low

### 🔹 Road Congestion Analysis
- Third Mainland Bridge and Lekki-Epe Expressway show highest congestion



---

## 🤖 Machine Learning Model

### Model Used:
- Random Forest Classifier

### Target Variable:
- Congestion_Level

### Feature Set:
- Traffic Volume (Number of Cars)
- Hour
- Road Name
- Weather Condition
- Time of Day
- Delay Minutes

### Model Output:
- Predicts congestion category:
  - Low / Free Flow
  - Moderate
  - Heavy Gridlock

---

## 📈 Feature Importance (Key Insight)

The most influential factors in predicting congestion:

1. Traffic Volume 🚗
2. Hour of Day ⏰
3. Weather Conditions 🌧️
4. Road Type 🛣️

---

## 📊 Key Insights

- Lagos traffic congestion follows a **strong bimodal pattern**
(morning and evening rush hours)
- Rainfall significantly increases traffic delay
- Certain roads consistently experience high congestion due to
infrastructure load
- Machine learning models can effectively predict congestion patterns
with high accuracy
- Traffic Volume is the strongest predictor of congestion severity

---

## 🧪 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib




## 📌 Future Improvements

Integration with real-time traffic APIs (Google Maps / TomTom)
Deep learning models for time-series forecasting
Geospatial traffic heatmaps using GIS tools
Deployment as a web dashboard (Streamlit / Flask)

________________________________

## 🎓 Academic Relevance

This project is designed for:

Graduate research in AI / Data Science
Smart City & Transportation research
Machine Learning portfolio development

________________________________

## 👤 Author

## Linda Obichukwu

Electrical & Computer Engineering Graduate
Data Analyst | Machine Learning Enthusiast
GitHub: https://github.com/Lindaobichukwu
Portfolio: https://lindaobichukwu.github.io/portfolio/

________________________________

## 📄 License

This project is intended for educational and research purposes
- Seaborn
- Scikit-learn
- Jupyter Notebook
