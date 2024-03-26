# CB_2166-NEET-2-Congenital-Abnormality

This repository contains work on using data analytics to inform the prevention of NEET (Not in Education, Employment, or Training) with congenital anomalies considered as a risk factor. The analysis aims to understand the association between congenital heart defects (CHD) and NEET status, explore spatial relationships between various geographic units and NEET status, and look into the educational aspects related to NEET.

Notebooks Overview
1. data_ingestion.ipynb
This notebook focuses on ingesting data from source datasets, cleaning it, and creating two new datasets: the NEET-CHD dataset and the other_covariates dataset which is used for further analysis

2. data_exploration.ipynb
In this notebook, we look into the NEET-CHD dataset and other_covariates dataset. Visualizations are created to understand the data and identify patterns.

3. statistical_analysis.ipynb
This notebook performs logistic regression to analyze the association between congenital heart defects (CHD) and NEET status.

4. home_lsoa_analysis.ipynb
Exploring the spatial relationship between home LSOA (Lower Layer Super Output Area) and NEET status is the focus of this notebook.

5. ward_analysis.ipynb
Here, we examine the spatial relationship between ward and NEET status on a ward level. Additionally, trend analysis of NEET status over 9 academic years is conducted.

6. school_based_analysis.ipynb
This notebook delves into the educational underpinnings of NEET, focusing on school-based analysis.

How to Use
Each notebook contains detailed explanations and code to replicate the analyses performed. The notebooks are self-contained and can be run sequentially for a comprehensive understanding of the project.

Requirements
Python 3
Jupyter Notebooks
Required libraries: numpy, pandas, matplotlib, seaborn, statsmodels, sklearn, folium, geopandas, etc.
