# Patient Condition Classification Using Drug Reviews

## Project Overview
This project predicts a patient's medical condition using drug names and patient review text.

The model classifies reviews into three conditions:
- Depression
- Type 2 Diabetes
- High Blood Pressure

## Dataset
The dataset contains drug reviews collected from Drugs.com.

Features include:
- Drug Name
- Patient Review
- Medical Condition

## Machine Learning Pipeline
The model uses:
- Text preprocessing
- TF-IDF vectorization
- Support Vector Machine (SVM) classifier

## Model Performance
Accuracy: ~99%

## Application
A Streamlit web application allows users to enter:
- Drug name
- Patient review

The app then predicts the likely medical condition.

## How to Run the App

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app/app.py