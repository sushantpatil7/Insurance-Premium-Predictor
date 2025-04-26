<<<<<<< HEAD
# Insurance Premium Prediction

## Problem Statement :
The goal of this project to give people an estimate of how much they need based on their individual health situation. After that, customers can work with any health insurance carrier and its plans and perks whilwe keeping the projected cost from our study in mind. This can assist a person in concentrating on the health side of an insurance policy rather than the ineffective part.

## Dataset :
The dataset is taken from a Kaggle. You can download the dataset from [here](https://www.kaggle.com/noordeen/insurance-premium-prediction)

## Approach :
Applying machine learing tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and model testing to build a solution that should able to predict the premium of the personal for health insurance.

- **Data Exploration :** Exploring the dataset using pandas, numpy, matplotlib, plotly and seaborn.
- **Exploratory Data Analysis :** Plotted different graphs to get more insights about dependent and independent variables/features.
- **Feature Engineering :** Numerical features scaled down and Categorical features encoded.
- **Model Building :** In this step, first dataset Splitting is done. After that model is trained on different Machine Learning Algorithms such as:
    1) Linear Regression
    2) Decision Tree Regressor
    3) Random Forest Regressor
    4) Gradient Boosting Regressor
    5) XGBoost Regressor
    6) KNN
- **Model Selection :** Tested all the models to check the RMSE & R-squared.
- **Pickle File** : Selected model as per best RMSE score & R-squared and created pickle file using pickle library.
- **Webpage &Deployment :** Created a web application that takes all the necessary inputs from the user & shows the output. Then deployed project on the Heroku Platform.


## Deployment Link :
https://insurance-premium-prediction1.herokuapp.com/


## Web Inerface :
![alt text](https://github.com/nikhilpatil44/insurance-premium-prediction/blob/main/images/webapp%20interface-2.png)


![alt text](https://github.com/nikhilpatil44/insurance-premium-prediction/blob/main/images/webapp%20interface-1%20.png)


## Libraries used :
    1) Pandas
    2) Numpy
    3) Matplotlib, Seaborn, Plotly
    4) Scikit-Learn
    5) Flask
    6) HTML
    7) CSS

## Technical Aspects :
    1) Python 
    2) Front-end : HTML, CSS
    3) Back-end : Flask
    4) Deployment : Heruko

=======
# Insurance-Premium-Predictor
The Insurance Premium Predictor is a machine learning project that predicts the estimated insurance cost (premium) a customer would have to pay based on their personal details like age, gender, BMI, number of children, smoking habits, and region. It uses regression models to find patterns in the data and generate accurate premium predictions.

Objective:
Predict the insurance premium amount a user needs to pay based on their profile.

Input Features:

Age of the person

Gender (Male/Female)

Body Mass Index (BMI)

Number of children

Smoker status (Yes/No)

Residential region (e.g., southeast, northwest)

Target:
Insurance expenses (premium amount)

Tech Stack:

Python (for coding and model building)

Pandas and NumPy (for data handling)

Scikit-learn (for building machine learning models)

Matplotlib and Seaborn (for data visualization)

Flask or Django (optional, if deployed as a web app)

## 🖼️ User Interface

### 🏠 Home Page
Here is the main UI screen:

![Home Page](images/insurance_main.png)

---

### 📄 Prediction Result
Here is the result after predicting insurance premium:

![Prediction Result](images/insurance_main2.png)
>>>>>>> b0a07a0068e5569e2c218028eb4c915d89cad1ea
