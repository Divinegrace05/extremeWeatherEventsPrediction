# Nairobi Extreme Weather Events Detection

This project focuses on predicting extreme weather events in Nairobi, Kenya, using machine learning techniques. The repository contains code to load, clean, preprocess, and analyze weather data specific to Nairobi, as well as train and evaluate various machine learning models for predicting extreme weather events.

## Overview

Extreme weather events can have significant impacts on Nairobi's residents, infrastructure, and economy. Accurate prediction of these events is crucial for disaster preparedness and response efforts. In this project, we leverage historical weather data from Nairobi to develop machine learning models capable of identifying extreme weather patterns unique to the region.

## Data

The project utilizes historical weather data sourced from the Kenya Meteorological Department. Due to data sharing restrictions, the raw data cannot be uploaded to GitHub. However, instructions are provided for acquiring and preprocessing the data locally. The data includes precipitation records spanning a specific timeframe, which serve as the basis for predicting extreme weather events.

## Extreme Events Definition

Extreme events in Nairobi are defined based on predefined thresholds, such as percentiles, tailored to the local climate and geography. These thresholds help categorize weather events as either normal or extreme, providing valuable insights into the frequency and intensity of extreme weather phenomena in Nairobi.

## Model Training and Evaluation

Several machine learning models, including Random Forest, Logistic Regression, Support Vector Machines (SVM), and K-Nearest Neighbors (KNN), are trained and evaluated for their predictive performance using Nairobi weather data. Model evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess the models' effectiveness in predicting extreme weather events specific to Nairobi's climate.

## Conclusion

The project concludes with insights into the performance of each model and recommendations for leveraging predictive modeling techniques to enhance Nairobi's resilience to extreme weather events. By understanding and predicting these events more accurately, stakeholders can develop proactive measures and strategies to mitigate their impact on various sectors, including agriculture, infrastructure, and public safety.

## Usage

To use the provided code:

1. Acquire the Nairobi weather data from the Kenya Meteorological Department or another reliable source.
2. Preprocess the data locally, adhering to data sharing regulations and privacy policies.
3. Install the required dependencies listed in the `requirements.txt` file.
4. Run the Jupyter notebooks or Python scripts provided in the repository to execute various steps of the project pipeline.
5. Explore the trained models and their performance metrics specific to Nairobi's weather patterns.

## Future Work

Future enhancements to the project could include:

- Incorporating additional weather variables specific to Nairobi for more comprehensive analysis.
- Fine-tuning model hyperparameters to improve predictive performance in the local context.
- Collaborating with local meteorological experts to refine model interpretations and recommendations.
- Exploring the integration of real-time weather data streams for continuous model updating and monitoring.
