## Toronto Crime Data Analysis

### Project Overview

This project analyzes Toronto crime data from 2013 onwards to uncover patterns, trends, and hotspots in criminal activity across the city. The goal is to provide actionable insights for law enforcement, policymakers, and urban researchers by leveraging data cleaning, feature engineering, statistical analysis, clustering, and predictive modeling.

The analysis combines exploratory data analysis (EDA), machine learning, and visualization techniques to reveal relationships between crime types, locations, and temporal patterns.

### Objectives

Clean and preprocess large datasets for analysis.

Explore crime patterns across different neighborhoods and time periods.

Identify crime hotspots using clustering algorithms.

Apply predictive modeling to understand key factors influencing crime occurrence.

Visualize findings through dashboards, heatmaps, bar charts, and trend plots for easy interpretation.

### Features

Data Cleaning & Preprocessing: Handling missing values, standardizing categorical variables, and preparing datasets for analysis.

Feature Engineering: Creating additional features such as crime counts by neighborhood, month, day of the week, and time of day.

Exploratory Data Analysis (EDA): Summary statistics, correlations, and trend visualization to understand the data.

Clustering (DBSCAN): Detecting crime hotspots and identifying spatial clusters of high crime activity.

Association Rule Mining (Apriori): Discovering relationships between crime types.

Predictive Modeling (Decision Trees): Modeling crime patterns and identifying strong predictors for criminal activity.

Visualization: Heatmaps, bar charts, line graphs, and interactive dashboards to communicate actionable insights.

### Dataset

Source: Toronto Police Service Open Data Portal

Records: Crime incidents from 2013 onward

Key columns: Occurrence Date, Crime Type, Neighbourhood, Latitude, Longitude, Outcome, etc.

Data size: ~hundreds of thousands of rows, covering multiple crime types and geographic areas

### Tools and Technologies

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn

Data Analysis Techniques: Clustering, association rule mining, predictive modeling

Visualization Tools: Heatmaps, bar charts, line plots, dashboards

Other Tools: Excel for initial data exploration

### Key Insights

Identified high-crime neighborhoods and temporal crime trends.

Detected patterns between different types of crimes using association rules.

Developed predictive models highlighting key factors contributing to crime likelihood.

Provided actionable visualizations to support city policing strategies and decision-making.

### How to Use

Clone this repository:

git clone <repo-url>


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook GroupReport_Global_Life_Expectancy.ipynb


Follow the notebook cells to explore data cleaning, EDA, clustering, predictive modeling, and visualizations.

### Future Improvements

Integrate real-time crime data to allow dynamic crime hotspot detection.

Apply advanced machine learning models like Random Forests or Gradient Boosting for more accurate prediction.

Build an interactive web dashboard for city officials to explore insights visually.

Include additional features such as socio-economic data or demographic information for deeper analysis.

### Author

Navdisha Bhakri
Software Engineering Student | Data Science & Machine Learning Enthusiast
