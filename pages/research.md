# Research & Data Science Projects

:::{admonition} Dissertation Focus
:class: tip
**Remote Sensing and Deep Learning for Environmental Public Health and Societal Outcomes.** Bridging transformer-based foundation models with physics-based constraints to simulate complex Earth processes.
:::

## Multimodal Fusion for High-Resolution Health Prediction
*The University of Texas at Dallas*

Architected a robust geospatial data pipeline observing **3,084 contiguous US counties from 2000 to 2019**, achieving a scale of **61,680 County-Year Observations**. 

* **Pipeline Architecture:** Integrated high-resolution remote sensing imagery with aggregated agricultural metrics via the Google Earth Engine API, utilizing a `tileScale=4` to manage heavy computational loads.
* **Robust Validation:** Engineered a rigorous 5-fold GroupKFold cross-validation strategy. Counties were grouped by FIPS to strictly prevent spatial leakage, ensuring true model generalizability.
* **Imputation Strategy:** Designed a localized intra-county missing-data imputation mechanism to preserve extreme local spatial fidelity across 20 years of data.

## Explainable AI (XAI) for Public Health & Climate Analysis
Developed and optimized a LightGBM machine learning model ($R^2 = 0.64$, $CV-RMSE = 1.46$) to analyze two decades of climate, environmental, and socioeconomic drivers.

* Extracted actionable insights using **SHAP feature importance** and ablation studies to uncover non-linear relationships between variables like tree canopy, soil health, and regional longevity.

## Select Publications & Preprints

> **Shrestha, S., Lary, D. J., Ruwali, S., Ahmad, F.** (April 2026). *The External Exposome and Life Expectancy: Formaldehyde as a Leading Predictor in U.S. Counties.* [Preprint].

> **Shrestha, S., Lary, D. J., Ruwali, S., Ahmad, F.** (March 2026). *Atmospheric Exposures and Cardiovascular Mortality in U.S. Counties: Formaldehyde and Wet-Bulb Temperature as Leading Predictors.* [Preprint].
