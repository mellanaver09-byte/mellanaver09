# Soil Property Classification with Terrain-Derived Features

## Overview
Classified key soil properties — organic matter (SOM), cation exchange 
capacity, and soil texture — using terrain covariates derived from a 
Digital Elevation Model (DEM), combined with field soil sample data.

## Methodology
- Derived slope, aspect, and Topographic Wetness Index (TWI) from a DEM
- Reprojected soil sample data to match the raster coordinate reference system
- Trained and compared Random Forest and Support Vector Machine (SVM) 
  regression models to predict SOM
- Implemented in R using terra, sf, sp, and raster packages

## Results
- Random Forest achieved lower prediction error than SVM for SOM, with an 
  RMSE of 0.477 versus 0.6 for SVM
- R² values indicated that neither model explained SOM variance well, 
  suggesting terrain-derived covariates alone are limited predictors of 
  SOM in this dataset
- Comparing model-generated SOM maps to reference maps showed a weak 
  correlation (-0.34), with a 33% shift in the spatial relationship 
  between predicted and observed values
- Despite limited overall model fit, a meaningful ecological pattern held: 
  high SOM correlated with high elevation, consistent with prior research 
  (Lv et al., 2022)

## Takeaways
Terrain-derived features alone were insufficient to reliably predict SOM 
in this dataset, though the elevation–SOM relationship aligned with 
published literature — suggesting additional covariates (e.g., land 
cover, climate variables, or soil parent material) may be needed to 
improve predictive performance in future iterations.

## Tech Stack
R · terra · sf · sp · raster · Random Forest · SVM
