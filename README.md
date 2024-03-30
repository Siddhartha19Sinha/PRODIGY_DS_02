# PRODIGY_DS_02
# Stellar Classification Exploratory Data Analysis (EDA) Project 🌟🔭

Welcome to the Stellar Classification Exploratory Data Analysis (EDA) Project! This repository contains an in-depth analysis of stellar data, focusing on classifying stars, galaxies, and quasars based on their spectral characteristics.

## Overview ℹ️

In this project, we explore a dataset comprising 100,000 observations of space taken by the SDSS (Sloan Digital Sky Survey). Each observation is described by 17 feature columns and 1 class column, identifying it as a star, galaxy, or quasar.

## Dataset Details 📄

- **Source:** [Insert dataset source/link]
- **Description:** The dataset includes information about various stellar attributes such as spectral type, magnitude, color index, luminosity, and more, collected from astronomical observations and surveys.

## Project Structure 📁

The repository is organized as follows:

- **Data:** Contains the stellar datasets used for analysis.
- **Notebooks:** Jupyter Notebooks (.ipynb) files containing the EDA process.
- **Visualizations:** Visualizations generated during the analysis.
- **README.md:** You are here!

## Data Exploration 🚀

- **Data Cleaning:** Handled missing values and duplicates.
- **Understanding Data Distribution:** Explored various stellar metrics such as right ascension angle, declination angle, and redshift values.
- **Exploratory Visualization:** Visualized data distribution using histograms, box plots, violin plots, and pair plots.
- **Feature Engineering:** Calculated color indices, extracted temporal features, performed one-hot encoding, and binned red-shift values.

## Statistical Analysis 📊

- **t Test:** Compared redshift values between galaxies and stars.
- **ANOVA:** Analyzed the redshift values across different classes.
- **Chi-Square Test:** Tested the independence between class and redshift category.

## Modeling 🧠

- **Linear Regression:** Predicted redshift values based on photometric filters (u, g, r, z).
- **Logistic Regression:** Classified stellar objects into stars, galaxies, or quasars.
- **Principal Component Analysis (PCA):** Reduced dimensionality for visualization.

## Advanced Visualization 📊

- **Interactive Visualization with Plotly:** Created interactive scatter plots.
- **Hierarchical Visualization with Dendrogram:** Plotted hierarchical clustering dendrogram.
- **Confusion Matrix:** Evaluated classification performance using a confusion matrix.
- **ROC Curve:** Visualized the Receiver Operating Characteristic (ROC) curve for logistic regression.

## Usage 📝

To replicate or explore the analysis:

1. Clone this repository:

   ```bash
   https://github.com/Siddhartha19Sinha/PRODIGY_DS_02.git

2. Navigate to the cloned directory.

3. Open the Jupyter Notebooks in the Notebooks directory to view the analysis.
