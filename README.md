# A Project to Predict the Prices of Real Estate

## Introduction :
In today's dynamic real estate market, predicting house prices accurately is crucial for both buyers and sellers.
The House Price Prediction project aims to leverage advanced data analysis and machine learning techniques to create a model that can predict house prices based on various features.

Below data science concepts are used in this project:
 
* Data Loading and cleaning
* Outlier detection and removal
* Feature engineering
* analyse and visualise the data

Technology and tools used in this project:

* Python
* Numpy and Pandas for data cleaning
* Matplotlib and Seaborn for data visualization

# Steps :

* Step#1: Import the required libraries
* Step#2: Load the data
* Step#3: Understand the data
        -drop unnecessary columns
* Step#4: Data Cleaning
  
        * Check for na values
        * Verify unique values of each column
        * Make sure values are correct 
        * Feature Engineering
        * check for duplicates
        * Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
        * Outlier removal using standard eviation and mean
        * Using Ordinal and One Hot encoding to convert Categorical to Numerical
