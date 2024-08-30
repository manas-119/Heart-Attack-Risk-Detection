Overview
The Heart Attack Risk Predictor is a web application that leverages a machine learning model to predict the likelihood of a heart attack based on various health metrics. Users can sign up, log in, and input their health data into a form. The application processes this data and returns a prediction on the user's risk level.

Features
User Authentication: Sign up and login functionality to securely access the prediction tool.
Health Metrics Form: A form where users input specific health-related parameters.
Risk Prediction: The app uses a trained Decision Tree model to predict the likelihood of a heart attack based on the user's inputs.
Input Parameters
The prediction model uses the following input parameters:

AGE: Age in years.
SEX: Gender (1 = male; 0 = female).
CP (Chest Pain Type):
Value 0: Typical angina (most serious)
Value 1: Atypical angina
Value 2: Non-anginal pain
Value 3: Asymptomatic (least serious)
TRESTBPS: Resting blood pressure (in mm Hg).
CHOL: Serum cholesterol in mg/dl.
FBS (Fasting Blood Sugar > 120 mg/dl): (1 = true; 0 = false)
Less than 100 mg/dL: Normal
100 to 120 mg/dL: Prediabetes
125 mg/dL or higher: Diabetes
RESTECG (Resting Electrocardiographic Results):
Value 0: Normal
Value 1: ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
Value 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
THALACH: Maximum heart rate achieved.
EXANG: Exercise induced angina (1 = yes; 0 = no).
OLDPEAK: ST depression induced by exercise relative to rest.
SLOPE (The slope of the peak exercise ST segment):
Value 0: Upsloping
Value 1: Flat
Value 2: Downsloping
CA: Number of major vessels (0-3) colored by fluoroscopy.
THAL:
Value 0: Normal
Value 1: Fixed defect
Value 2: Reversible defect
How It Works
Sign Up: Users create an account by providing a username, email, and password.
Log In: Registered users log in to access the heart attack risk prediction tool.
Input Data: Users fill out a form with the required health metrics.
Prediction: The machine learning model processes the input data and provides a prediction indicating the likelihood of a heart attack.
Result: The prediction result is displayed on the screen.
Technology Stack
Frontend: React.js for building the user interface.
Backend: Node.js and Express for handling user authentication and serving the machine learning model.
Machine Learning Model: A Decision Tree model trained in Python using scikit-learn.
Database: MongoDB for storing user credentials and prediction logs.
