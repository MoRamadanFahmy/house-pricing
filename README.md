# house-pricing🏡💰
## 📊 Project Overview
This repository contains a machine learning project focused on predicting house prices in Bengaluru based on various features such as location, size, number of bathrooms, and more. The project involves data cleaning, feature engineering, and applying machine learning algorithms to build a model that can predict house prices.

## 📂 Dataset used
The dataset used in this project is a collection of house prices in Bengaluru. It includes the following columns:
* area_type: The type of area (Super built-up Area, Plot Area, Built-up Area, Carpet Area)
* availability: Availability status (Ready To Move, etc.)
* location: The location where the property is situated
* size: Size of the house (e.g., 2 BHK, 3 BHK, etc.)
* society: The society name (if applicable)
* total_sqft: Total square footage of the house
* bath: Number of bathrooms
* balcony: Number of balconies
* price: Price of the house (in lakhs)
- <a href="dataset.csv">Dataset</a>

## 🧹Data Cleaning
The project involved several steps to clean and preprocess the data, including:
1. Removing irrelevant columns: We removed columns such as 'area_type', 'society', 'balcony', and 'availability' that were not useful for price prediction.
2. Handling missing values: We dropped rows with missing values in the relevant columns.
3. Feature Engineering: We created new features such as 'bhk' (number of bedrooms) and 'price_per_sqft' (price per square foot) to provide more insights for the model.
4. Outlier Removal: We handled outliers by filtering out unreasonable values based on price per square foot and square footage.

## 🤖Model
The model used in this project involves training a regression algorithm to predict the house prices. We removed outliers from the dataset to ensure the model's predictions are more accurate and reliable.


## 🔗Notebbook
- <a href="source.ipynb">Dashboard</a>
