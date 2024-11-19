# CIND820_TorontoCrime
CIND820 - Data Analytics, Big Data, and Predictive Analytics  - Capstone Project
## Overview
This project is part of the CIND820 capstone course for the Data Analytics, Big Data, and Predictive Analytics certification program at Toronto Metropolitan University. The primary goal is to apply data analysis and machine learning techniques to understand crime patterns in Toronto and create predictive models that can help improve public safety measures.

This repository contains all project-related files, including data processing scripts, machine learning implementations, visual analysis, and reports documenting findings and results.

## Research Objectives
The project focuses on three main objectives:
1. **Identify and visualize crime hotspots**: We explore which neighborhoods and geographical areas in Toronto exhibit specific types of crime, utilizing clustering and geospatial data analysis. (STILL TO BE COMPLETED)
2. **Analyze crime trends**: We investigate trends in crime types over time, identifying locations and premises increasingly susceptible to different crimes. (STILL TO BE COMPLETED)
3. **Develop predictive models**: Using machine learning, we aim to predict potential criminal activity patterns and evaluate the influence of various attributes, including premises type, location, and time. (STILL TO BE COMPLETED)


## Dataset
The datasets used in this project are publicly available data from the Toronto Police Service:
1. **Homicide Data**: Data on reported homicide incidents in Toronto, including attributes like date, neighborhood, geographical coordinates, and type of homicide. Data included from 2004 to mid-2024
2. **Non-Homicide Data**: Major Crime Indicators (MCI) dataset covering various crimes, such as assault, theft, break and enter, and robbery. Key attributes include occurrence date, neighborhood, premises type, and location type. Data included from 2014 to mid-2024


## Project Structure
The project is structured into multiple stages, including exploratory data analysis, model development, and evaluation. Below is a summary of the key content:

### Main Files
- **README.md**: Project overview (this file).
- **CIND820_TorontoCrime.ipynb**: Main Jupyter Notebook for data analysis and modeling.
- **requirements.txt**: A list of Python libraries used in the project for easy setup. (STILL TOBE COMPLETED)

## Methodology
- **Data Preprocessing**: Datasets were cleaned, and necessary columns were transformed using techniques like one-hot encoding. 
- **Exploratory Data Analysis**: Visualizations like bar charts and geospatial plots were generated to identify patterns and trends.
- **Machine Learning Models**:
  - **Logistic Regression**: Applied for crime prediction based on features like neighborhood, premises type, and time.
  - **Decision Tree Classifier**: Used to classify different crime categories.
  - **Random Forest Classifier**: An ensemble approach to improve classification accuracy.
  - **Clustering**: Used K-means and DBSCAN methods to identify crime hotspots. (STILL TO BE COMPLETED)
 
## Results (PRELIMINARY)
- **Homicide Analysis**: Visualizations and model predictions were used to understand the relationship between different factors and crime occurrence.
- **Non-Homicide Analysis**: Visualizations and model predictions were used to understand the relationship between different factors and crime occurrence.
- **Model Performance**: The performance of logistic regression, decision tree, and random forest models was compared using metrics like accuracy, precision, and recall.
 

## Authors
- Syed Muzaffar Hasan kazmi - Data Analysis and Machine Learning Implementation

## Acknowledgments
- Toronto Police Service for providing the crime datasets.
- Toronto Metropolitan University for guidance and supervision during the course.
