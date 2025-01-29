# ❤️ Heart Disease Prediction using Machine Learning

## 🏥 Project Overview
This project aims to predict **heart disease** using **tabular patient data** and **Machine Learning models**.  
The dataset contains various **clinical features**, and the objective is to classify whether a patient has **heart disease** or not.

## 🔬 Machine Learning Models Used
The following models were applied and compared:
- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **Logistic Regression**

Since the dataset was **imbalanced**, we used **Synthetic Minority Over-sampling Technique (SMOTE)** to improve model performance.

---

## 📊 Dataset Information
The dataset consists of multiple health-related attributes that influence heart disease risk. Some key features include:

**HeartDisease**: Target variable (1 = Yes, 0 = No)
**BMI (Body Mass Index)**: Indicator of body fat based on height and weight
**Smoking**: Whether the individual smokes (1 = Yes, 0 = No)
**AlcoholDrinking**: Whether the individual consumes alcohol (1 = Yes, 0 = No)
**Stroke**: History of stroke (1 = Yes, 0 = No)
**PhysicalHealth**: Number of physically unhealthy days in the past month
**MentalHealth**: Number of mentally unhealthy days in the past month
**DiffWalking**: Difficulty walking (1 = Yes, 0 = No)
**Sex**: Gender of the individual (0 = Female, 1 = Male)
**AgeCategory**: Categorical representation of age groups
**Race**: Ethnicity of the individual
**Diabetic**: Diabetes status with multiple categories
**PhysicalActivity**: Whether the individual engages in physical activity (1 = Yes, 0 = No)
**GenHealth (General Health)**: Self-reported general health status
**SleepTime**: Number of hours of sleep per night
**Asthma**: Whether the individual has asthma (1 = Yes, 0 = No)
**KidneyDisease**: Presence of kidney disease (1 = Yes, 0 = No)
**SkinCancer**: History of skin cancer (1 = Yes, 0 = No)

The dataset is highly imbalanced, requiring special techniques to handle the imbalance for machine learning training.

- 📁 Kaggle
  The dataset used for this study is the Indicators of Heart Disease (2022 Update) from the CDC's Behavioral Risk Factor Surveillance System (BRFSS). This dataset contains 
  300,000+ records and 15+ features related to demographics, clinical parameters, lifestyle factors, and medical history.
- **Data Format:** `.csv`

## Results and Evaluation
The models were evaluated based on accuracy, precision, recall, and F1-score. The performance comparison helped determine the most effective model for predicting heart disease.

## Conclusion
This project demonstrates how machine learning can be utilized to predict heart disease using health-related factors. Data preprocessing, feature engineering, and model evaluation are essential steps in building an accurate predictive model.
