# Philadelphia Food Access Analysis

This project analyzes food accessibility in Philadelphia, focusing on food deserts, fast food clustering, and their correlation. We used census data, OpenStreetMap (OSM) data, and city-provided spatial layers to investigate patterns of food vulnerability.

## Research Questions

1. Where are food deserts located in Philadelphia?  
2. Where are fast food restaurants clustered?  
3. Is there a correlation between fast food density and food deserts?

## Methods

- **Data Sources**: Census API, OSM, City of Philadelphia GIS data.  
- **Cleaning**: KNN imputation for missing census values, filtering non-chain food stores.  
- **Analysis**:
  - Multi-Criteria Evaluation (MCE) with weighted variables: median income, age, poverty, vehicle access, and store proximity.
  - Kernel Density Estimation (KDE) and DBSCAN to identify fast food clusters.
  - Bivariate OLS regression to quantify the relationship between food access and fast food density.

## Key Finding

Higher fast food density is positively associated with greater food access vulnerability.

## Authors
Stella Meserve & Maryana Shnitser
