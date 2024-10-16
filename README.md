# Predicting Startup Success with Machine Learning Models
### Shreeti Patel

## Project Description
In the dynamic world of startups, accurately predicting success can offer a substantial competitive edge. The ability to accurately forecast the trajectory of a new business affects decisions made by investors and entrepreneurs. This project's primary goal is to develop a machine-learning model designed to predict the success of startups. This project focuses on developing two machine learning models to predict startup success and estimate valuations. The project is divided into two parts: the first involves building a classification model to determine whether a startup will succeed based on its financial and operational data. Success is defined as achieving profitability through an IPO, merger, or acquisition. The second part focuses on creating a linear regression model to predict a startup's latest valuation. By analyzing different datasets and methodologies, this project strives to provide valuable insights and tools that enhance decision-making processes for investors and entrepreneurs in the startup ecosystem.

## Overview

This project is divided into two main parts: **Part 1 Crunchbase Data** and **Part 2 PrivCo Data**. Each part focuses on data analysis and model training using separate datasets. Both parts are organized as follows:

- **Part 1 Crunchbase Data:** Analysis and modeling on Crunchbase data.
- **Part 2 PrivCo Data:** Analysis and modeling on PrivCo data.

Each folder contains specific files that must be executed in a particular order to ensure the proper workflow.

### Getting Started

1. Clone this repository to your local machine.
2. Ensure that you have a Python environment with all necessary packages (e.g., pandas, scikit-learn, xgboost) installed. These can also be installed in the beginning of each jupyter notebook file. 

## Part 1: Crunchbase Data

### Project Workflow:
1. `startingEDA_CB.ipynb`
2. `ModelTraining_CB.ipynb`

### Files:

- `2014-crunchbase-data`  
  Contains raw Crunchbase data for 2014.

- `2015-crunchbase-data`  
  Contains raw Crunchbase data for 2015.

- `Cleaned_startup_data.pkl`  
  A serialized output in PKL format, generated by `startingEDA_CB.ipynb`.

- `KaggleDataset`  
  A directory containing additional datasets from Kaggle.

- `startingEDA_CB.ipynb`  
  An exploratory data analysis (EDA) notebook that processes raw Crunchbase data to produce `Cleaned_startup_data.pkl`.

- `ModelTraining_CB.ipynb`  
  A notebook that uses `Cleaned_startup_data.pkl` to train machine learning models.

## Part 2: PrivCo Data

### Project Workflow:
1. `EDA_privco.ipynb`
2. `feature_eng_privco.ipynb`
3. `model_training_privco.ipynb`

### Files:

- `EDA_cleaned_PrivCo_data.pkl`  
  A serialized output in PKL format, produced by `EDA_privco.ipynb`. (Omitted)

- `EDA_privco.ipynb`  
  An exploratory data analysis (EDA) notebook that processes raw PrivCo data to produce `EDA_cleaned_PrivCo_data.pkl`.

- `FE_cleaned_PrivCo_data.pkl`  
  A serialized output in PKL format, produced by `feature_eng_privco.ipynb`. (Omitted)

- `feature_eng_privco.ipynb`  
  A feature engineering notebook that processes EDA-cleaned data to produce `FE_cleaned_PrivCo_data.pkl`.

- `model_training_privco.ipynb`  
  A notebook that uses `FE_cleaned_PrivCo_data.pkl` to train machine learning models.

- `raw_PrivCo_data.csv`  
  A CSV file containing the raw PrivCo data that is the input to `EDA_privco.ipynb`. (Omitted)

### Important Note:

I obtained special permission to use data from PrivCo under a Non-Disclosure Agreement (NDA). Due to the confidentiality of this data, the original raw files (raw_PrivCo_data.csv) and processed outputs (.pkl files) have been omitted from this repository. However, the code provided demonstrates the full workflow I developed for data cleaning, feature engineering, and model training.