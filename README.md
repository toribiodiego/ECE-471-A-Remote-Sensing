

> This repository contains the code for **ECE471: Remote Sensing**, a course offered in Spring 2025 at The Cooper Union for the Advancement of Science and Art, providing practical experience in geospatial data analysis using GDAL, QGIS, Google Earth Engine, and Python.

## Remote Sensing
**Course, Spring 2025**  
**Instructor:** Professor Krishna Karra


### Overview
This course provides a practical introduction to remote sensing and Earth observation. Through focused study of key geospatial datasets and interactive programming assignments, students gain both the theoretical background and practical skills required to analyze satellite imagery and other remotely sensed data using GDAL, QGIS, Google Earth Engine, and essential Python libraries.

### Repository Structure

- **P01.ipynb** – *Satellite Imagery Analysis*  
  This project simulates a real-world consulting scenario for New Mexico by analyzing Sentinel-2 imagery over the greater Santa Fe area. The assignment includes exploring the dataset, creating visualizations, processing images for consistent spatial properties, and generating composite images. It also features tasks such as developing cloud masks and analyzing pixel value distributions—all aimed at building a comprehensive understanding of geospatial data processing.

- **P02.ipynb** – *Crop Prediction and Seasonal Analysis*  
  This assignment focuses on using the Cropland Data Layer and Landsat imagery to predict crop types in Iowa and Illinois. It begins with ranking crop prevalence using acreage data, followed by an exploration of seasonal vegetation patterns through NDVI time series analysis. The project culminates in the development, testing, and deployment of a crop classification model designed to produce accurate in-season predictions by integrating geospatial analysis with machine learning techniques.



- **Final Project** – *Drought Forecasting in California’s Central Valley*

### Final Project

The project, *Drought Forecasting in California’s Central Valley*, uses remote sensing and machine learning to predict drought conditions up to 12 weeks ahead. The approach begins by replicating the [*DroughtCast*](https://www.frontiersin.org/journals/big-data/articles/10.3389/fdata.2021.773478/full) framework to build a baseline dataset, which is then enhanced with additional features. Google Earth Engine processes and aligns various data sources—such as satellite imagery, soil moisture, weather observations, and water storage measurements. A sequence-to-sequence model based on gated recurrent units (GRUs) is trained on the curated dataset and validated through both spatial and temporal tests. The goal is to deliver early drought warnings that support better decision-making in agriculture, water management, and environmental planning.