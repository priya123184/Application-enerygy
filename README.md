# Appliances Energy Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting **appliances energy consumption** using Python and Machine Learning.

The project includes the complete machine learning workflow, starting from data preprocessing and exploratory data analysis to model building, prediction, and evaluation.

## 🎯 Objective

The main objective of this project is to analyze energy consumption data and build a machine learning model that can predict the energy consumed by appliances based on different environmental and household-related features.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset

The project uses the **Appliances Energy Prediction Dataset**.

The dataset contains information related to:

- Appliances energy consumption
- Temperature
- Humidity
- Weather-related measurements
- Lighting
- Time-related features
- Other environmental factors

### Target Variable

**Appliances** – represents the energy consumption of appliances.

This is a **Regression problem** because the target variable contains continuous numerical values.

## 🔄 Project Workflow

### 1. Data Collection
Loaded the Appliances Energy Prediction dataset using Python.

### 2. Data Preprocessing

Performed preprocessing steps such as:

- Checking the dataset shape
- Checking data types
- Handling missing values
- Removing unnecessary columns
- Separating features and target variable
- Encoding categorical data where required
- Feature scaling

### 3. Exploratory Data Analysis

Used data visualization techniques to understand the dataset and relationships between variables.

Libraries used:

- Matplotlib
- Seaborn

Visualizations included:

- Correlation heatmap
- Distribution plots
- Box plots
- Feature relationship analysis

### 4. Feature Selection

Selected relevant features that can help the machine learning model predict appliance energy consumption.

### 5. Train-Test Split

The dataset was divided into:

- Training data – used to train the model
- Testing data – used to evaluate the model

### 6. Feature Scaling

Standardization was performed using **StandardScaler** to bring numerical features to a similar scale.

### 7. Machine Learning Model Building

Machine learning models were trained using **Scikit-learn**.

The workflow included:

- Model initialization
- Model training using training data
- Prediction using testing data

### 8. Model Evaluation

The trained model was evaluated using appropriate regression evaluation metrics.

Common metrics used include:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help measure how accurately the model predicts appliance energy consumption.

## 📈 Machine Learning Pipeline

```text
Dataset
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Machine Learning Model
   ↓
Prediction
   ↓
Model Evaluation
```

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Python programming for data analysis
- Data preprocessing
- Exploratory Data Analysis
- Data visualization
- Feature selection
- Feature scaling
- Train-test splitting
- Machine learning model building
- Making predictions
- Evaluating machine learning models

## 🚀 Future Improvements

The project can be improved by:

- Testing additional regression algorithms
- Hyperparameter tuning
- Feature engineering
- Comparing multiple models
- Improving prediction performance
- Deploying the trained model as a web application



### Project Status

✅ Completed — Python to Machine Learning Model Building and Evaluation
