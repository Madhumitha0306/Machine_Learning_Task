Overview

This project explores and analyzes restaurant data from Zomato to find useful insights and build basic machine learning models.
It includes data cleaning, visualization, cuisine prediction, and location-based analysis, all done step by step in Google Colab (Python).

Tasks Covered
Task 1 – Data Exploration
Goal: Understand the dataset and clean it for analysis.

Steps:
* Loaded the Zomato dataset using pandas.
* Removed missing and duplicate values.
* Checked data types and basic statistics.
* Explored popular cuisines, cost, and ratings.

Findings:
* Most restaurants are rated between 3.0 and 4.5.
* North Indian, Chinese, and Fast Food are the most common cuisines.

Task 2 – Data Visualization
Goal: Visualize data to identify patterns and relationships.

Steps:
* Plotted graphs for ratings, price range, and votes using Matplotlib and Seaborn.
* Created bar charts for top cuisines and cities.
* Used heatmaps to show correlations.
  
Findings:
* Restaurants with higher votes usually have better ratings.
* Metro cities have more high-rated restaurants.

Task 3 – Cuisine Classification
Goal: Build a model to predict a restaurant’s cuisine based on its details.

Steps:
* Encoded categorical data using LabelEncoder.
* Split data into training and testing sets.
* Trained models like Random Forest and Logistic Regression.
* Evaluated performance using accuracy, precision, and recall.

Results:

* Random Forest performed better than Logistic Regression.
* Accuracy improved after balancing classes and removing rare cuisines.
  
Task 4 – Location-Based Analysis
Goal: Study restaurant distribution by location.

Steps:
* Visualized latitude and longitude of restaurants on maps.
* Grouped data by city/locality to find the most popular food areas.
* Calculated average ratings and cost per city.

Findings:
* Cities like Delhi, Bangalore, and Mumbai have the most restaurants.
* Some areas show higher prices but better ratings.
  
Tools and Libraries Used
* Python
* Pandas, NumPy – Data cleaning and analysis
* Matplotlib, Seaborn, Plotly – Visualization
* Scikit-learn – Machine learning
* Google Colab – Development environment
  
