# Covid-19-Time-series-Prediction

# Project Overview
This project focuses on predicting the future trends of COVID-19 cases using time series analysis and machine learning techniques. By analyzing historical case data, we aim to forecast future case numbers, helping authorities and researchers in decision-making.

# Dataset
The dataset sourced from:
* Johns Hopkins University COVID-19 Data Repository
* World Health Organization (WHO)
As it consist of data such as
* Province/State: Specific State of the the country
* Country/Region: Country of the covid-19 patients
* Lat : Latitude of the area
* Long : Longitude of the area
* Date : Date of the Patient to be found
* Confirmed : Confirm cases of covid-19
* Deaths : Deaths cases on the particular date
* Recovered : Recovered cases
* Active	: Active cases upto particular Date
* WHO Region : Which WHO region the country/state comes under

# Problem Statement
* Analyze past trends of COVID-19 cases.
* Build predictive models to forecast future cases.
* Evaluate model performance using appropriate metrics.

# Technologies & Libraries Used
* Python
* Pandas, NumPy (Data preprocessing)
* Matplotlib, Seaborn (Visualization)
* Scikit-learn (Machine learning models)
* Facebook Prophet (Time series forecasting)

# Steps Involved
1. Data Collection & Preprocessing
 * Cleaning missing values
 * Aggregating data for time series analysis
2. Exploratory Data Analysis (EDA)
 * Trends, seasonality, and patterns in COVID-19 cases
 * Time series decomposition
3. Model Selection & Training
 * Traditional models: Facebook Prophet

# Result
 Succesfully predicted the Confirmed, Active, Deaths, Recovered Patients in the world for next 7 days Dated from -

