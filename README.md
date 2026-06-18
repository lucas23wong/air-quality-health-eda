# Exploratory Data Analysis on BreathWatch Air Quality and Human Health: 2015-2024

## Project Overview 
This project analyzes the BreathWatch Air Quality & Health 2015-2024 dataset to identify the drivers to respiratory illnesses such as asthma, COPD, lung cancer, etc.

## Project Structure
- data/ -> stores CSV file of dataset as well as cleaned data ready for analysis 
- notebooks/ -> stores jupyter notebooks used for data cleaning, analysis, and visualization 


## Tech Stack 
- Python 3.12
- Pandas, numpy - data manipulation 
- Matplotlib, seaborn - visualization 
- Scipy - statistical testing 
- Jupyter - notebooks

## Data 
- The CSV data for this project was downloaded from Kaggle: https://www.kaggle.com/datasets/aliyasaly1231/breathwatch-air-quality-and-health-2015-2024. 
- The dataset contains 6,000 records (2015-2024) spanning over 30 countries and 100+ cities. It tracks 12 key atmospheric pollutants (PM2.5, NO2, etc.) as well as other health, environmental, and demographic data. 

## Jupyter Notebooks 
| Notebook | Purpose | 
| --- | --- | 
| 01_data_cleaning.ipynb | Orders data by date and season, filters through records with NaN entries, and continent column is added. |
| 02_eda.ipynb | Explores the cleaned dataset through univariate and multivariate visualizations. |
| 03_statistical_analysis | Hypothesis testing on key correlations between air pollutants and health risks. | 








