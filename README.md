# Ride-Estimator-Model

# 🏍️ Ride Estimator

A web app that estimates the price of pre-owned bikes with amazing accuracy using advanced machine learning techniques.

---

## 📖 Project Overview

The goal of this project is to build an intelligent web application that accurately predicts the market value of pre-owned bikes, offering data-driven insights for users. This app ensures reliability by leveraging machine learning and a robust dataset.

This project allowed me to:
- Apply machine learning techniques to solve real-world problems.
- Develop a user-friendly web interface for seamless interaction.
- Utilize Python libraries for data processing and visualization.
- Deploy a fully functional web application using Flask.

---

## 📊 Dataset Used

The dataset used is **Bike.csv**, sourced from Kaggle.  
It includes detailed information about various pre-owned bikes, making it ideal for price prediction.  

### **Dataset Headings**  
- **bike_name**: Name of the bike model.  
- **price**: Listed price of the bike.  
- **city**: Location where the bike is listed for sale.  
- **kms_driven**: Total distance traveled by the bike (in kilometers).  
- **owner**: Ownership status (e.g., first owner, second owner).  
- **age**: Age of the bike (in years).  
- **power**: Engine power (measured in CC).  
- **brand**: Manufacturer of the bike.

---

## 🚀 Steps Followed

### 1️⃣ Data Gathering
- Loaded the raw dataset using **Pandas**.
- Conducted initial **Exploratory Data Analysis (EDA)** to understand data patterns and ensure the dataset's suitability for analysis.

### 2️⃣ Data Cleaning
- Addressed missing and inconsistent values.  
- Standardized column names and ensured data format consistency.  
- Removed duplicate entries and rows with null values.  
- Encoded categorical variables (e.g., `owner`, `brand`) using **label encoding**.  

### 3️⃣ Feature Engineering
- Selected key features affecting bike prices:
  - **bike_name, kms_driven, owner, age, power, brand**
- Created derived features, such as:
  - **Price per kilometer:** Ratio of price to kms driven for added insights.

### 4️⃣ Data Splitting
- Divided the dataset into **Training** (80%) and **Testing** (20%) sets.

### 5️⃣ Model Building
- Used **Linear Regression** for its simplicity and effectiveness in price prediction tasks.
- Tuned hyperparameters to improve model performance.

### 6️⃣ Model Evaluation
- Evaluated the model on the test set using:
  - **Mean Absolute Error (MAE)**
  - **Root Mean Square Error (RMSE)**
  - **R² Score**

### 7️⃣ Model Deployment
- Trained the final model and saved it using **Joblib**.
- Built a web interface with **Flask**, allowing users to input bike details and get real-time price estimates.

---

## 🌟 Key Features of Ride Estimator

- **Accurate Predictions**: Quickly estimate the market value of any pre-owned bike.
- **Interactive Exploration**: Browse through different bike models with detailed insights.
- **Data-Driven Insights**: Backed by a robust dataset for reliable predictions.
- **Fast and Effective**: Generate results within seconds.

---

## 📘 Learnings

1. **Data Cleaning and Preparation**  
   Enhanced skills in handling missing values, encoding, and feature engineering.

2. **Machine Learning**  
   Gained a deeper understanding of regression models and evaluation techniques.

3. **Web Development**  
   Learned to integrate machine learning models into a Flask-based web application.

4. **Deployment**  
   Successfully deployed a real-time, user-friendly prediction system.

