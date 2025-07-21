# Drought-Analysis-and-prediction

This project analyzes rainfall data to identify drought patterns and build a machine learning model that can predict drought conditions. The analysis and visualizations are done using R, and the prediction model uses the XGBoost algorithm.

## Project Description

- Analyzed historical rainfall data
- Visualized rainfall trends and drought distribution
- Created a drought classification label based on July rainfall
- Built a machine learning model to predict drought

## Dataset

The dataset includes:

- Rainfall records (e.g., 2010-07-01)
- Region or state (`STATE`)
- Average July rainfall (`Avg_Jul`)
- Derived drought labels based on `Avg_Jul`

**Source**:  
You can download similar datasets from the following platforms:

- [Government Open Data Portal (data.gov.in)](https://data.gov.in/)
- [DANS Data Station Physical and Technical Sciences](https://dans.knaw.nl/en/data-station/physical-and-technical-sciences/)

## Steps Performed

1. Loaded and cleaned the data
2. Created histograms and density plots for rainfall
3. Visualized drought count by state
4. Created pair plots to explore relationships between rainfall columns
5. Built a classification model using XGBoost
6. Predicted drought and no-drought conditions

## Technologies Used

- R
- ggplot2
- dplyr
- GGally
- xgboost

## Results

- The model classifies regions into **Drought** or **No Drought** based on rainfall
- Output shows the number of regions under each prediction

## How to Run

1. Open the R script or notebook
2. Install required R libraries if not already installed
3. Run the analysis and model code
