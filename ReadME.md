# Soil Organic Carbon (SOC) Prediction for Matto Grosso, Brazil
This project focuses on predicting Soil Organic Carbon (SOC) values through spatial data analysis and machine learning techniques. The workflow encompasses data preprocessing, exploratory data analysis (EDA), ordinary least squares (OLS) regression, and random forest regression.


## Overview
This project is a journey through data-driven discovery and predictive modeling. By seamlessly integrating data preprocessing, exploratory data analysis (EDA), ordinary least squares (OLS) regression, and random forest regression, we aim to construct a robust model that captures the essence of SOC dynamics within this diverse and vital ecosystem.

## Usage
The heart of the project lies in the Jupyter Notebook `soc_prediction_v2.ipynb`. Dive into the notebook, where each step unfolds the secrets hidden in the data. From loading spatial data to conducting EDA, OLS regression, and training machine learning models, every section is a window into the fascinating world of soil science and data-driven insights.

Evaluate the model using metrics such as R-squared, RMSE, and MAE, gaining a comprehensive understanding of its predictive capabilities. Witness the power of machine learning as you predict SOC values for new locations, using the knowledge gleaned from the trained model.

## Data
Our dataset is a rich collection of spatial information, including:
- `sampling_points.shp`: A shapefile containing sampling points with associated SOC values.
- `Matto_Grosso.shp`: A shapefile delineating the study area boundary.
- `predictive_dataset_label.shp`: A shapefile equipped with features crucial for predicting SOC values.

## Results
The culmination of our efforts reveals compelling insights:
- The trained random forest regression model stands out with its high accuracy in predicting SOC values.
- A deep dive into feature importance analysis sheds light on the key predictors driving SOC dynamics.

## Predictions
Take the model beyond its training grounds and apply it to new locations (`predictive_dataset_label.shp`). Watch as the predictions unfold, with results neatly organized in `predicted_data.csv` and visually brought to life in `soc_pred.geojson`.

## Clone the Repository
Ready to explore further? Clone the repository using the following command:

```bash
git clone https://github.com/your-username/your-repository.git
```

## Acknowledgments
This project draws inspiration from the insightful [Hydroinformatics blog post](https://medium.com/hydroinformatics/towards-urban-flood-susceptibility-mapping-using-machine-and-deep-learning-models-3-random-9fe4e1279f3b).
