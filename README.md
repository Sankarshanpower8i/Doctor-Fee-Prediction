Doctor-Fee-Prediction



 Overview
The Doctor's Fee Prediction project focuses on predicting consultation fees for doctors based on attributes such as specialty, experience, location, and more. The project involves data extraction, preprocessing, model building, and an interactive web application.


 User's Manual
Files/Folder	Description
Python Files	Review the data extraction process and preprocessing steps
Python Files/ML_Models.ipynb	Understand the machine learning model creation
DATA	Explore the raw and cleaned data
Web Application	Run the web application using the provided code
 Table of Contents
Project Details
Data Extraction
Data Preprocessing
Machine Learning Modeling
Web Application
Presentation
Acknowledgments

 Project Details
This project utilizes Python libraries such as NumPy and Pandas for data cleaning and preprocessing purposes. Matplotlib and Seaborn are used for data analysis and visualization. Scikit-learn (sklearn) is employed for building the machine learning model. Flask, HTML, and CSS are used to build an interactive website.

The main objective is to predict doctor consultation fees based on the following attributes:

Coding

speciality_of_doctor: Specialty of the doctor
degree_type: Type of degree (e.g., MBBS, MD, BDS)
year_of_experience: Total years of experience
Location: Clinic location
city: City of the clinic
dp_score: Doctor-patient experience score
npv_: Number of people's votes

 Python Files
Data Extraction
The data extraction phase involves collecting raw doctor information from the online medical consultancy booking site Practo. This is achieved using the Jupyter Notebook Scrapping code.ipynb.
Data Preprocessing
In the preprocessing phase data is cleaned, missing values are handled, and exploratory data analysis is performed. The Jupyter Notebook Preprocessing_EDA.ipynb includes the cleaning and visualization code.
Machine Learning Modeling
The machine learning model is built using Scikit-learn and is implemented in the Jupyter Notebook ML_Models.ipynb. This model predicts the consultation fee for doctors based on the provided attributes.

 Data
Raw Data
The collected data is stored in raw_practo.csv.
Cleaned Data
The cleaned data is saved in clean_practo.csv.

 Web Application
The project includes an interactive web application developed with Flask. The application allows users to input values for speciality_of_doctor, degree_type, year_of_experience, Location, city, dp_score, and npv_ to obtain a predicted consultation fee for doctors. The machine learning model, stored as model.pkl, is integrated into the web application.

Directory Structure for Web Application
app.py: Flask application handling user inputs and serving the web page.
model.pkl: Trained machine learning model for predicting consultation fees.
templates/: Directory containing the HTML template for the interactive web application.
index.html: HTML template allowing users to input attributes and get predicted fees.

Coding

 Presentation
Doctor Fee Prediction.pdf: Presentation showcasing project details and insights.

README.md: Overview of the project, its structure, and usage instructions.


 Acknowledgments
We extend our appreciation to the mentors and faculty members for their guidance and support throughout the project.