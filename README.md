# Diabetes-prediction-
Diabetes Predictor
The Diabetes Predictor is an innovative machine learning application that harnesses the
ower of data science to provide insightful predictions about an individual's potential risk of developing diabetes. This project is designed to empower both individuals and healthcare professionals with a tool that facilitates informed decision-making and proactive health management.

# App Screenshot

![Screenshot (25)](https://github.com/Praveen9131/Diabetes-prediction-/assets/121826658/99a707ce-d5f4-4a0f-a2ce-0338b31d36e7)

Project Overview
Diabetes is a prevalent chronic health condition that affects millions of people worldwide. Early detection and proactive management are crucial in preventing complications and ensuring a high quality of life for individuals with diabetes. The Diabetes Predictor aims to address this need by offering a user-friendly platform that leverages advanced machine learning algorithms to analyze a range of health parameters and provide personalized risk predictions.


# Key Features
Comprehensive Health Assessment: Users can input a set of health parameters, including factors like pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age.

Accurate Risk Assessment: The application employs a robust machine learning model trained on extensive datasets to generate accurate predictions about an individual's likelihood of developing diabetes.

User-Friendly Interface: The intuitive web interface ensures a seamless and straightforward experience for users, making it easy to input data, obtain predictions, and interpret results.

# Getting Started
Follow these steps to set up and run the Diabetes Predictor on your local machine.

# Prerequisites
Python 3.x: Ensure you have Python 3.x installed on your system. If not, you can download it from the official website: Python Downloads

Gradiologo Framework: The Diabetes Predictor is built using the Gradiologo framework. You can find detailed installation instructions in the Gradiologo Documentation.

Installation
Clone the Repository: Clone the Diabetes Predictor repository to your local machine:

# bash
# Copy code
git clone https://github.com/Praveen9131/Diabetes-Prediction.git
Navigate to the Project Directory: Move into the project directory:

# bash
# Copy code
cd Diabetes-Predictor
Install Dependencies: Install the necessary dependencies:

# Copy code
pip install -r requirements.txt
Usage
Run the Application: Launch the application:

# Copy code
python app.py
Access the Web Interface: Open your web browser and go to:

http://localhost:5000

Here, you can input health parameters and receive instant predictions.

# API Usage
The Diabetes Predictor also provides an API for programmatic access to its prediction capabilities.

Send a POST Request: Make a POST request to:

#bash
 # Copy code
http://localhost:/api/predict
Include Parameters: Include health parameters in the request payload, similar to the following JSON structure:

# json
 # Copy code
{
  "Pregnancies": 6,
  "Glucose": 148,
  "BloodPressure": 72,
  "SkinThickness": 35,
  "Insulin": 0,
  "BMI": 33.6,
  "DiabetesPedigreeFunction": 0.627,
  "Age": 50
}

## Receive a Prediction: The API will respond with a prediction result.
