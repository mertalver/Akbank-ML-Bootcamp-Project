# Project Overview

## Introduction

Are you interested in solving real-world problems using Machine Learning methods? If so, there's a project waiting for you. In this project, you will apply traditional Machine Learning techniques to address various problems. You'll be working with a dataset related to houses in Melbourne, Australia, and your goal is to evaluate this data using regression and tree-based methods. This project will enable you to gain valuable experience in data examination, data preparation for modeling, and exploratory data analysis. It's a valuable addition to your portfolio.

## Dataset

The dataset in question pertains to Melbourne, the capital and largest city of the Australian state of Victoria. This dataset contains a variety of attributes associated with houses in Melbourne, including their prices. Here are the variables present in the dataset:

- Suburb
- Address
- Rooms: Number of rooms
- Price: Price in Australian dollars (the target variable)
- Method: Property sale method (e.g., S, SP, PI, etc.)
- Type: Type of property (e.g., house, unit, townhouse)
- SellerG: Real Estate Agent
- Date: Date of sale
- Distance: Distance from CBD in kilometers
- Regionname: General region (e.g., West, North, North East)
- Propertycount: Number of properties in the suburb
- Bedroom2: Number of bedrooms (scraped from another source)
- Bathroom: Number of bathrooms
- Car: Number of carspots
- Landsize: Land size in square meters
- BuildingArea: Building size in square meters
- YearBuilt: Year the house was built
- CouncilArea: Governing council for the area
- Latitude
- Longitude

## Steps of the Project

### 1. Creating a Google Colaboratory File
- Ensure your project has a .ipynb extension.
- Include comment lines to explain project details.
- Submit the .ipynb file with cells that have been executed to display results.

### 2. Importing Required Libraries
- Import necessary libraries for data analysis, including NumPy, Pandas, Seaborn, and Matplotlib.
- Import libraries and modules for modeling and evaluating performance, such as sklearn.model_selection, sklearn.metrics, sklearn.ensemble, sklearn.linear_model, sklearn.tree, and sklearn.neighbors.

### 3. Project Definition
- Load the Melbourne Housing dataset and preprocess the data.
- Develop a predictive model for house price estimation.
- Analyze data to understand its quality and quantity.

### 4. Gathering and Observing Data
- Load the dataset using `read_csv()` and inspect the first 5 columns.
- Determine the dataset's shape, number of columns, and size.
- Display information about the dataset, including column labels, data types, memory usage, range index, and the number of non-null values in each column.

### 5. Exploratory Data Analysis
- Examine descriptive statistics of the dataset.
- Categorize variables as needed, especially those with object and categorical values.
- Check for duplicate data and remove duplicates.
- Address outlier data, particularly in "Landsize" and "BuildingArea" variables using the z-score method.
- Identify and handle missing values, particularly in the "Bathroom" and "Car" variables, using the mode method.
- Visualize data through histograms, pair plots, and correlation matrices.

### 6. Model Selection
- Select appropriate features (x) and target variable (y) for house price estimation.
- Split the data into training and testing sets to enhance model performance.
- Train models using preprocessed data, including models like Lasso, LinearRegression, Ridge, ElasticNet, KNeighborsRegressor, RandomForestRegressor, GradientBoostingRegressor, and AdaBoostRegressor.

### 7. Model Evaluation
- Compare model performance using evaluation metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).
- Choose the best performing model based on these evaluation metrics.
