# 🕵️ Crime Data Analysis

## 📋 Project Overview

This project focuses on analyzing crime data across different Indian cities. It provides a comprehensive exploration of various attributes such as victim demographics, crime types, weapons used, closure rates, and police deployment statistics. Additionally, it includes a machine learning model that predicts police deployment using linear regression.

## 🎯 Objectives

1. Analyze crime distribution across cities.
2. Identify the most frequent types of crimes.
3. Study victim demographics by age and gender.
4. Explore the usage of weapons in crimes.
5. Categorize crimes by domains (e.g., violent, property).
6. Investigate closure rates of reported crimes.
7. Observe trends in monthly and yearly crime occurrences.
8. Examine reported time patterns of crime.
9. Predict police deployment using linear regression.

## 🧹 Data Preprocessing

- Filled missing values using forward fill (`ffill`).
- Converted date fields to `datetime` objects.
- Extracted year and month from the occurrence date.
- Encoded categorical features using `OneHotEncoder`.
- Split data into training and testing sets (80-20 ratio).

## 📊 Exploratory Data Analysis (EDA)

Visualizations were created using Python libraries like `matplotlib` and `seaborn` to generate insights. Key charts include:

- **Crime Distribution by City and Type**  
- **Victim Age and Gender Distribution**  
- **Weapon Usage in Crimes**  
- **Closure Status of Reported Cases**  
- **Monthly and Yearly Crime Trends**  
- **Time of Crime Reporting Patterns**  
- **Police Deployment Comparison and Prediction**

## 🔮 Police Deployment Prediction (Overview)

A linear regression model was implemented to estimate the number of police officers deployed based on features like victim age, weapon used, crime type, city, and time details. This model provides an initial understanding of how certain factors influence police resource allocation.
