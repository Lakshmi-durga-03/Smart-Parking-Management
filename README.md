# 🚗 Smart Parking Management

Smart Parking Management is a **Machine Learning project** designed to predict parking space occupancy using data collected from an **Industrial Internet of Things (IIoT) smart parking environment**.

The project follows a complete machine learning pipeline, including **data preprocessing, exploratory data analysis, feature encoding, feature selection using Chi-Square, model training, and performance comparison**.

## 📌 Overview

Finding available parking spaces can be difficult, especially in crowded areas. A smart parking system can use data from parking sensors and other environmental factors to determine whether a parking space is **Free or Occupied**.

This project uses machine learning classification algorithms to predict the occupancy status of parking spaces.

The target variable is:

- `Occupied` → `1`
- `Free` → `0`

The project also compares multiple classification models to understand which model performs better on the given dataset.

## ✨ Features

- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data preprocessing and cleaning
- 🔢 Categorical feature encoding
- 📈 Feature scaling using Min-Max Scaling
- 🎯 Chi-Square feature selection
- 🤖 Machine learning classification
- 📊 Model accuracy comparison
- 📋 Precision, Recall and F1-Score evaluation
- 📉 Visualization of model performance
- 🚗 Parking occupancy prediction

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning Algorithms
- Logistic Regression
- Decision Tree
- Random Forest

### Machine Learning Techniques
- Label Encoding
- Min-Max Scaling
- Chi-Square Feature Selection
- Train-Test Split
- Classification Evaluation

### Development Environment
- Jupyter Notebook
- Google Colab

## 📂 Project Structure

```text
Smart-Parking-Management/
│
├── IIoT_Smart_Parking_Management.csv
│
├── Smart_Parking_Management_ML_Project.ipynb
│
└── README.md
```

## 🔄 Machine Learning Workflow

The project follows these major steps:

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Categorical Encoding
   ↓
Missing Value Handling
   ↓
Exploratory Data Analysis
   ↓
Feature Scaling
   ↓
Chi-Square Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Prediction
   ↓
Performance Evaluation
```

## 📊 Dataset

The project uses the **IIoT Smart Parking Management dataset**.

The dataset contains information related to smart parking conditions and includes the target variable:

```text
Occupancy_Status
```

The target is converted into a binary classification:

```text
Occupied → 1
Free     → 0
```

## 🔍 Data Preprocessing

The following preprocessing steps are performed:

1. Load the dataset using Pandas.
2. Convert the target variable into binary values.
3. Encode categorical columns using `LabelEncoder`.
4. Handle missing values.
5. Convert features into numeric values.
6. Apply Min-Max scaling to normalize the feature values.

## 🎯 Feature Selection

The project uses **Chi-Square feature selection** to identify the most relevant features.

`SelectKBest` is used with the Chi-Square statistical test to select the top features based on their scores.

This helps identify which input features have a stronger relationship with parking occupancy.

## 🤖 Machine Learning Models

Three classification algorithms are trained and compared:

### 1. Logistic Regression

Used as a baseline classification model for predicting whether a parking space is occupied or free.

### 2. Decision Tree

A tree-based classification algorithm that makes predictions by splitting the data based on feature values.

### 3. Random Forest

An ensemble learning algorithm that combines multiple decision trees to make predictions.

## 📈 Model Evaluation

The trained models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

The project also generates an **accuracy comparison graph** to visually compare the performance of the models.

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Lakshmi-durga-03/Smart-Parking-Management.git
```

### 2. Navigate to the project folder

```bash
cd Smart-Parking-Management
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Run the Jupyter Notebook

Open:

```text
Smart_Parking_Management_ML_Project.ipynb
```

You can run the notebook using **Jupyter Notebook** or **Google Colab**.

## ☁️ Google Colab

The notebook can also be opened directly in Google Colab.

The notebook contains a **Open in Colab** button at the beginning for easy execution.

## 📊 Output

The project generates:

- Dataset information
- Target variable distribution
- Feature correlation heatmap
- Chi-Square feature scores
- Model accuracy comparison
- Precision, Recall and F1-Score
- Overall model performance summary

The model with the highest accuracy is identified from the evaluated models.

## 🎯 Objective

The main objective of this project is to demonstrate how **machine learning can be applied to smart parking systems to predict parking space occupancy** and support more efficient parking management.

## 🚀 Future Enhancements

- Develop a real-time parking availability web application.
- Integrate live IoT parking sensor data.
- Add a parking slot visualization dashboard.
- Implement real-time occupancy prediction.
- Add location-based parking search.
- Integrate a database for storing parking information.
- Deploy the trained model as an API.
- Build a mobile application for users.

## 📜 License

This project is intended for educational and academic purposes.
