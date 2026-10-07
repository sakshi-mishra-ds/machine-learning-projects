# Accident Severity Prediction

A Machine Learning project that predicts the severity of road accidents using accident-related features such as location, time, weather, road conditions, vehicle information, and driver details.

##  Project Overview

Road accidents can vary in severity depending on several factors such as weather conditions, road conditions, traffic conditions, number of vehicles involved, and other environmental and driver-related factors.

This project uses Machine Learning techniques to analyze accident data and predict accident severity.

##  Objective

The main objectives of this project are:

- Analyze road accident data
- Perform data preprocessing and feature engineering
- Convert categorical features into numerical values
- Train a Machine Learning classification model
- Predict accident severity
- Evaluate model performance

##  Dataset

The dataset contains information related to road accidents.

### Dataset Features

Some of the important features include:

- State Name
- City Name
- Year
- Month
- Day of Week
- Time of Day
- Accident Severity
- Number of Vehicles Involved
- Vehicle Type Involved
- Number of Casualties
- Weather Condition
- Road Type
- Road Condition
- Lighting Condition
- Traffic Condition
- Speed Limit
- Driver Age
- Driver Gender
- Driver License Status
- Alcohol Involvement
- Road-related factors

The original dataset contains **3,000 records and 22 features**.

A smaller sample dataset containing **500 records and 22 features** is also included in this repository for easier demonstration.

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Machine Learning

## Machine Learning

The project uses a classification approach for predicting accident severity.

### Algorithm Used

- Random Forest Classifier

### Data Preprocessing

The following preprocessing steps were performed:

1. Loading the dataset
2. Checking the dataset structure
3. Encoding categorical variables
4. Preparing features and target variable
5. Splitting the data into training and testing sets
6. Training the Machine Learning model
7. Making predictions
8. Evaluating model performance

##  Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix
## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/sakshi-mishra-ds/machine-learning-projects.git
```

### 2. Open the project

Open the project folder in Jupyter Notebook or JupyterLab.

### 3. Install required libraries

```bash
pip install pandas numpy scikit-learn
```

### 4. Run the notebook

Open accident_severity_prediction.ipynb and run the cells sequentially.


