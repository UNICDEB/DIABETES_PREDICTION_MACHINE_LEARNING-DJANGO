# DIABETES_PREDICTION_MACHINE_LEARNING-DJANGO
Here we build a Django website for predicting diabetes using a machine learning algorithm.

This repository contains code for a diabetes prediction machine learning model built using Python and Django. The model is built using the scikit-learn library and is deployed as a web application using Django.

Installation
To run the web application, follow these steps:

Clone this repository
Navigate to the project directory: cd <repository>
Create a virtual environment: python -m venv env
Activate the virtual environment: source env/bin/activate
Install the required packages.
Run the web application: python manage.py runserver
Usage
Once the web application is running, navigate to http://localhost:8000/ in your web browser. You will see a form where you can input your health data such as age, weight, and blood sugar levels. Click the "Predict" button to get a prediction about your likelihood of developing diabetes.

Dataset
The dataset used to train the machine learning model is the Diabetes Database, which contains information about diabetes patients. The dataset is attached to this repository.

Model
The machine learning model is built using the LogisticRegression algorithm from the scikit-learn library. All of you can use any other machine learning model to train this dataset.

Web Application
The web application is built using Django and is deployed using the Django development server. The web application is located in the diabetes_pred directory and consists of several files including views, templates, and static files.
