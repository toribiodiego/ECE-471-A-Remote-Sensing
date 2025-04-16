

> This repository contains the code for **ECE471: Remote Sensing**, a course offered in Spring 2025 at The Cooper Union for the Advancement of Science and Art, providing practical experience in geospatial data analysis using GDAL, QGIS, Google Earth Engine, and Python.

## Remote Sensing
**Course, Spring 2025**  
**Instructor:** Professor Krishna Karra


### Overview
This course provides a practical introduction to remote sensing and Earth observation. Through focused study of key geospatial datasets and interactive programming assignments, students gain both the theoretical background and practical skills required to analyze satellite imagery and other remotely sensed data using GDAL, QGIS, Google Earth Engine, and essential Python libraries.

### Repository Structure

```
.
├── Final_Project
│   └── README.md
├── P01
│   └── P01.ipynb
├── P02
│   ├── P02.ipynb
│   └── artifacts
│       └── Iowa_Illinois_top20_crops.csv
└── README.md

```

- **`Final_Project.ipynb`** – *Drought Forecasting:*  
  Builds on the *DroughtCast* approach, augmenting baseline satellite and ground data with additional features. The final sequence-to-sequence model aims to provide early drought warnings in California’s Central Valley.

- **`P01.ipynb`** – Satellite Imagery Analysis:**  
  Examines Sentinel-2 imagery around Santa Fe, covering data loading, visualization, spatial normalization, and techniques like cloud masking and pixel distribution analysis.

- **`P02.ipynb`** – *Crop Prediction and Seasonal Analysis*  
  Investigates crop types in Iowa and Illinois with a Cropland Data Layer and NDVI time series, culminating in a classification model that leverages geospatial data for accurate in-season crop predictions.


### Final Project

The project, *Drought Forecasting in California’s Central Valley*, uses remote sensing and machine learning to predict drought conditions up to 12 weeks ahead. The approach begins by replicating the [*DroughtCast*](https://www.frontiersin.org/journals/big-data/articles/10.3389/fdata.2021.773478/full) framework to build a baseline dataset, which is then enhanced with additional features. Google Earth Engine processes and aligns various data sources—such as satellite imagery, soil moisture, weather observations, and water storage measurements. A sequence-to-sequence model based on gated recurrent units (GRUs) is trained on the curated dataset and validated through both spatial and temporal tests. The goal is to deliver early drought warnings that support better decision-making in agriculture, water management, and environmental planning.