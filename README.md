# AirBnB-Booking-Analysis

# Problem Statement
To analyze Airbnb booking data to uncover insights into customer behavior, property characteristics, pricing strategies, and market trends. 
This analysis aims to help hosts and decision-makers optimize their strategies for better performance and profitability.

# Dataset Information
   48,895 rows and 16 columns.
Key Features:
Property details (e.g., room_type, price, availability_365).
Host details (e.g., host_id, host_name).
Geographic information (e.g., neighbourhood_group, latitude, longitude).
Booking activity (e.g., minimum_nights, number_of_reviews, reviews_per_month).

# Methodology
Data Loading:Dataset read using pandas.Initial exploratory data analysis (EDA) performed to understand data structure.

Data Cleaning:Address missing values.Remove outliers and handle inconsistencies.

Exploratory Data Analysis (EDA):Distribution of key variables visualized using matplotlib and seaborn.
Analysis of room_type popularity, price distributions, and booking trends by neighbourhood_group.

Insights Extraction:Grouped data by various dimensions (room_type, neighbourhood, etc.). Identified top-performing locations and property types.

Visualization:Generated charts for key findings (e.g., bar plots, heatmaps).

# Key Results
Manhatten and Brooklyn have the highest demand for Airbnb rentals. This can be attactive areas for hosts to invest in properties. The price distribution is high in Manhattan and Brooklyn.

Room Type Analysis: Entire homes/apartments were the most popular choice among customers.

Neighborhood Trends: Certain neighborhoods had significantly higher prices and booking frequencies.Famous neighbourhood are Williamsburg (3732), Bedford-Stuyvesant (3638),Harlem (2585)

Price Distribution: Pricing varied widely by room_type and location, with some outliers in premium properties.

# Tools Used
Programming Language: Python
Libraries: pandas for data manipulation.matplotlib and seaborn for data visualization.numpy for numerical operations.
Notebook Environment: Jupyter Notebook
