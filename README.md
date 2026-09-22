## Rainfall Prediction in Australia

A machine learning project that predicts whether it will rain the following day in Australia using historical weather data. The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

##  Project Overview

Weather prediction is an important application of machine learning. In this project, historical weather observations from different locations across Australia are used to predict the target variable **`RainTomorrow`**.

The problem is formulated as a **binary classification task**:

* 'Yes' → Rain is predicted for the following day
* 'No' → No rain is predicted for the following day

##  Objectives

* Analyze historical Australian weather data
* Perform data cleaning and preprocessing
* Handle missing values
* Perform exploratory data analysis (EDA)
* Engineer relevant features from the dataset
* Train a machine learning classification model
* Analyze feature importance
* Evaluate the model's prediction performance

## 🛠️ Technologies & Libraries

* Python
* Pandas – Data manipulation and preprocessing
* numPy – Numerical computations
* Matplotlib– Data visualization
* Scikit-learn – Machine learning and model evaluation
* Jupyter Notebook / Google Colab

## 🔄 Machine Learning Workflow

Raw Weather Data
       ↓
Data Cleaning
       ↓
Missing Value Handling
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Feature Selection
       ↓
Train-Test Split
       ↓
Random Forest Classifier
       ↓
Model Evaluation
       ↓
Rainfall Prediction


## Dataset

The project uses historical weather observations collected from different locations across Australia.

The dataset contains weather-related features such as:

* Temperature
* Humidity
* Atmospheric pressure
* Wind speed
* Wind direction
* Rainfall
* Sunshine
* Cloud coverage
* Location
* Date

The target variable is:


RainTomorrow

##  Data Preprocessing

The following preprocessing steps are performed:

* Identification and treatment of missing values
* Handling missing numerical features
* Handling missing categorical features
* Conversion of categorical variables into machine-readable form
* Extraction of useful information from the 'Date' feature
* Preparation of the dataset for machine learning

## Exploratory Data Analysis

The project performs exploratory analysis to understand relationships between weather variables and rainfall.

Visualizations include:

* Distribution of weather features
* Rainfall distribution
* Correlation analysis
* Categorical feature analysis
* Feature relationships
* Feature importance

## 🤖 Machine Learning Model

### Random Forest Classifier

A **Random Forest Classifier** is used to predict whether rainfall will occur on the following day.

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve predictive performance and reduce overfitting compared with a single decision tree.

The model is trained using historical weather observations and evaluated on unseen data.

## 📏 Model Evaluation

The model can be evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help evaluate how effectively the model identifies rainfall and non-rainfall days.

> **Note:** Refer to the notebook for the actual model performance and evaluation results.

## 📂 Project Structure

rainfall-prediction-australia/
│
├── Rainfall_Prediction_Project.ipynb
├── README.md
└── requirements.txt

##  How to Run

### 1. Clone the repository


git clone https://github.com/YOUR_USERNAME/rainfall-prediction-australia.git


## 2. Navigate to the project directory

cd rainfall-prediction-australia


### 3. Install the required libraries


pip install pandas numpy matplotlib seaborn scikit-learn jupyter


Or, if 'requirements.txt' is provided:


pip install -r requirements.txt


## 4. Open the notebook


jupyter notebook


Then open:


Rainfall_Prediction_Project.ipynb


You can also run the notebook using **Google Colab**.

## 💡 Key Skills Demonstrated

* Python programming
* Data preprocessing
* Data cleaning
* Exploratory Data Analysis
* Data visualization
* Feature engineering
* Machine learning
* Binary classification
* Random Forest
* Model evaluation
* Feature importance analysis



Developed as part of 'Pattern Recognition and Machine Learning' project.

