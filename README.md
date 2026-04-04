# ARTI406-EDA-Project
ARTI406 - Assignment 1: Exploratory Data Analysis (EDA)   Project Overview 
ARTI406 - Assignment 1: Exploratory Data Analysis (EDA)

 Project Overview
This project performs a comprehensive Exploratory Data Analysis on a car market dataset. The goal is to clean the data, visualize key trends, and understand the factors affecting car prices.

Dataset Description
- Source: European Car Market Dataset (final_scout_not_dummy.csv).
- Size:15,915 rows and 13 columns.
- Key Features:
    - `make_model`: Brand and model of the car.
    - `price`: Selling price.
    - `km`: Total kilometers driven.
    - `Fuel`: Type of fuel used.
    - `body_type`: Category of the car (Sedan, SUV, etc.).

## Data Cleaning Steps
1. Column Standardization: Fixed issues with whitespace and incorrect naming (e.g., KeyError: 'Date').
2. Missing Values: Removed rows with null values to maintain data accuracy.
3. Data Types: Converted price and km to numeric types for analysis.

Key Insights
- Price Distribution: Most cars are priced between 10,000 and 20,000 Euro.
- Mileage Impact: A clear negative correlation exists between mileage (km) and price.
- Top Models: Renault Espace and Audi models command the highest average prices.
