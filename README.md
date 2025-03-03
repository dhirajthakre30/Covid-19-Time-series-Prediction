# Covid-19-Time-series-Prediction

# Problem Statement
The COVID-19 pandemic has significantly impacted global health and economies. Accurate forecasting of confirmed cases is crucial for governments and healthcare systems to plan resources, implement policies, and mitigate risks. This project aims to predict future COVID-19 case trends using Facebook Prophet, a time series forecasting model.

# Project Objective

The primary objective of this project is to:
* Analyze historical COVID-19 data
* Apply Facebook Prophet to forecast confirmed cases
* Evaluate the model's accuracy
* Provide insights that can aid decision-making for healthcare and policy planning

# Data Description
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

# Technologies & Libraries Used
* Python
* Pandas, NumPy (Data preprocessing)
* Matplotlib, Seaborn (Visualization)
* Scikit-learn (Machine learning models)
* Facebook Prophet (Time series forecasting)

# Data Pre-processing Steps and Inspiration

To prepare the data for forecasting, the following steps were taken:
* Convert the Date column to a datetime format
* Aggregate data at the country level or globally
* Handle missing values and inconsistencies
* Ensure a continuous time series with no gaps

**Choosing the Algorithm for the Project**
Facebook Prophet was selected due to its effectiveness in handling time series forecasting with trends, seasonality, and holidays.

**Motivation and Reasons For Choosing the Algorithm**

Prophet was chosen because:
* It efficiently models time series data with automatic trend and seasonality adjustments
* It handles missing data and outliers well
* It is simple to implement and interpret

**Future Possibilities of the Project**
* Incorporating additional factors like mobility data, vaccination rates, and policy changes
* Using hybrid models combining Prophet with deep learning for better accuracy
* Extending forecasting to regional levels for localized decision-making

# Result
 Succesfully predicted the Confirmed, Active, Deaths, Recovered Patients in the world for next 7 days Dated from - 27/07/2020 to 03/08/2020

