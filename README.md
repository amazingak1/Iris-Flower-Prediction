# Iris Dataset Analysis and Classification

This project demonstrates a comprehensive analysis of the famous Iris dataset using Python, including exploratory data analysis (EDA), data visualization, and machine learning classification models.

## Overview

The project analyzes the Iris dataset, which contains measurements for three different species of iris flowers. It includes:
- Data exploration and statistical analysis
- Various visualization techniques using Seaborn and Matplotlib
- Implementation of multiple machine learning models for classification

## Technologies Used

- Python
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Features

1. **Exploratory Data Analysis**
   - Basic statistics and data summary
   - Group-wise analysis by species

2. **Data Visualization**
   - Scatter plots
   - Pair plots
   - Histograms
   - Heat maps for correlation analysis
   - Distribution plots

3. **Machine Learning Models**
   - K-Nearest Neighbors (KNN)
   - Logistic Regression
   - Support Vector Machine (SVM)

## Dataset

The dataset includes the following features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)
- Species (target variable)

## Setup and Usage

1. Ensure you have Python installed on your system
2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter notebook `sample.ipynb`

## File Structure

- `sample.ipynb`: Main Jupyter notebook containing all analysis and models
- `data/Iris.csv`: Dataset file (required for running the notebook)

## Results

The project implements various classification models with their respective accuracies:
- KNN Classifier
- Logistic Regression
- SVM with RBF kernel

Each model demonstrates effective classification of iris species based on the flower measurements.