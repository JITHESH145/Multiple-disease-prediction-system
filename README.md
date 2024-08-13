
# Multiple Disease Prediction System

This project is a web-based application built using Streamlit that predicts the likelihood of a person having Diabetes, Heart Disease, or Parkinson's Disease. The predictions are made using pre-trained machine learning models.

## Features

- **Diabetes Prediction:** Predicts whether a person has diabetes based on input parameters like glucose level, blood pressure, BMI, etc.
- **Heart Disease Prediction:** Predicts the presence of heart disease using parameters such as age, cholesterol levels, chest pain types, etc.
- **Parkinson's Disease Prediction:** Predicts whether a person has Parkinson's disease based on voice measurements like jitter, shimmer, and others.

## Installation

To run this application locally, follow these steps:

1. Clone the repository:



2. Install the required Python packages:


3. Change the paths of the sav files with the paths in which it is stored in your local system
  

4. Run the Streamlit application:

   
   streamlit run app.py

## Usage

1. Navigate to the appropriate disease prediction section via the sidebar.
2. Input the required health parameters.
3. Click on the "Test Result" button to see the prediction outcome.

## Project Structure

```plaintext
multiple-disease-prediction-system/
├── diabetes_model.sav            # Pre-trained model for diabetes prediction
├── heart_disease_model.sav       # Pre-trained model for heart disease prediction
├── parkinsons_model.sav          # Pre-trained model for Parkinson's disease prediction
├── app.py                        # Main Streamlit application code
├── requirements.txt              # List of dependencies
└── README.md                     # This file
```

## Models

- **Diabetes Model:** Predicts diabetes using features such as pregnancies, glucose, blood pressure, etc.
- **Heart Disease Model:** Predicts heart disease based on features like age, sex, cholesterol, etc.
- **Parkinson's Disease Model:** Predicts Parkinson's disease using features derived from voice measurements.

## License

This project is licensed under the MIT License.

---

This README gives a clear overview of your project, including installation instructions, usage guidelines, and a brief explanation of each disease prediction model.
