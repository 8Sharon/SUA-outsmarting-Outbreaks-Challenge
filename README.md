# SUA Outsmarting Outbreaks Challenge

## Overview

The **SUA Outsmarting Outbreaks Challenge** is a competition aimed at developing a machine learning model that can predict the outbreaks of climate-sensitive waterborne diseases. The model will leverage datasets that include information on water sources, toilet quality, waste management, health facilities, and climate data from 2019 to 2023.

The objective is to create a predictive system that will help governments and health organizations implement **timely and targeted interventions**. By doing so, resources can be allocated more efficiently, reducing disease incidence and strengthening public health resilience against waterborne outbreaks, especially in regions sensitive to climate change.

## Challenge Objective

Build a machine learning model that predicts the likelihood of outbreaks of climate-sensitive waterborne diseases using data from multiple sources, including:

- **Water sources** (availability and quality).
- **Toilet quality** (sanitation infrastructure).
- **Waste management** (handling and disposal practices).
- **Health facility data** (availability and access to healthcare).
- **Climate information** (weather patterns, temperature, rainfall).

This predictive capability will help organizations make informed decisions, optimizing resource distribution and ultimately enhancing public health outcomes.

## Requirements

The following libraries are required to run the code:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **faiss**: For similarity search and clustering.
- **lightgbm**: For training the LightGBM model (used as the base model in this challenge).
- **sklearn**: For machine learning utilities such as model selection, preprocessing, and evaluation.
- **matplotlib**: For data visualization.

## data prepocessing 
handling missing values and renaming of columns for clarity
## clustering
Utilized FAISS (Facebook AI Similarity Search) for efficient clustering, helping to identify patterns in the geographical distribution of the data. Clustering allowed for better handling of similar locations or regions, improving the model's ability to generalize.

## model training and evaluation
Trained the model using KFold evaluated using the Mean Absolute Error (MAE) metric. This metric was chosen as it provides a clear and interpretable measure of model accuracy.

## Data Visualization
The model also includes a data visualization function that allows for the display of geographical data related to the health, water, waste, and sanitation facilities. 
  
