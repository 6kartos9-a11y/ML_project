# 💼 Salary Prediction using Machine Learning

## 📌 Overview

This project predicts employee salary using multiple real-world features
such as experience, education, job role, company size, and skills.\
It uses **Linear Regression** with proper preprocessing techniques.

------------------------------------------------------------------------

## 🎯 Objective

-   Predict salary based on multiple factors\
-   Apply real-world machine learning workflow\
-   Improve accuracy compared to single-feature models

------------------------------------------------------------------------

## 📊 Dataset Features

-   YearsExperience\
-   EducationLevel\
-   JobRole\
-   Location\
-   CompanySize\
-   SkillsScore\
-   Certifications\
-   Age\
-   Industry\
-   Salary (Target)

------------------------------------------------------------------------

## ⚙️ Technologies Used

-   Python\
-   Pandas\
-   NumPy\
-   Scikit-learn

------------------------------------------------------------------------

## 🔍 Workflow

### 1. Data Loading

-   Loaded CSV dataset using Pandas

### 2. Preprocessing

-   Separated features and target\
-   Applied One-Hot Encoding for categorical data

### 3. Model Building

-   Used Linear Regression\
-   Created pipeline for preprocessing + model

### 4. Training

-   Split dataset into training and testing sets\
-   Trained model using `.fit()`

### 5. Prediction

-   Predicted salary using `.predict()`

### 6. Evaluation

-   Used R² Score to measure performance

------------------------------------------------------------------------

## 📈 Results

-   Good R² score achieved\
-   Model performs better than simple regression

------------------------------------------------------------------------

## ⚠️ Limitations

-   Dataset is synthetic (generated)\
-   May not fully represent real-world complexity

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Use real-world datasets\
-   Try advanced models (Random Forest, XGBoost)\
-   Add more features

------------------------------------------------------------------------

## ▶️ How to Run

``` bash
pip install pandas scikit-learn
```

``` bash
python your_script.py
```

------------------------------------------------------------------------

## 🧠 Conclusion

This project demonstrates a complete machine learning pipeline using
multiple features, improving prediction accuracy and making it closer to
real-world scenarios.
