# EDA Process with Feature Selection on Boston Housing Dataset

## Overview

This notebook demonstrates the process of exploratory data analysis (EDA) and feature selection using the Boston Housing Dataset. The primary goal is to explore the dataset, handle missing values, identify and treat outliers, perform univariate and bivariate analysis, and use linear regression for feature selection.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Loading and Initial Exploration](#data-loading-and-initial-exploration)
3. [Data Exploration](#data-exploration)
4. [Handling Missing Values](#handling-missing-values)
5. [Outlier Analysis and Treatment](#outlier-analysis-and-treatment)
6. [Univariate Analysis](#univariate-analysis)
7. [Bivariate Analysis](#bivariate-analysis)
8. [Feature Selection](#feature-selection)
9. [Modeling](#modeling)
10. [Key Techniques and Libraries](#key-techniques-and-libraries)
11. [Results](#results)
12. [Conclusion](#conclusion)

## Introduction

- Overview of the Boston Housing Dataset.
- Description of the SEMMA (Sample, Explore, Modify, Model, Assess) process used for data analysis.

## Data Loading and Initial Exploration

- Loading the dataset into a pandas DataFrame.
- Adding column names to the dataset.
- Displaying the first few rows and the shape of the dataset.

## Data Exploration

- Checking for missing values.
- Exploring dataset variables using statistical summaries and data types.
- Visualizing data distributions using histograms and boxplots.

## Handling Missing Values

- Strategies for dealing with missing data, including removal and imputation.

## Outlier Analysis and Treatment

- Identifying outliers using boxplots.
- Discussing strategies for handling outliers, such as removal or imputation.

## Univariate Analysis

- Detailed examination of each variable, including count, mean, standard deviation, minimum, and maximum values.

## Bivariate Analysis

- Creating a correlation matrix to understand relationships between variables.
- Visualizing relationships using heatmaps and scatter plots.

## Feature Selection

- Discussion of the curse of dimensionality and the importance of feature selection.
- Using linear regression to identify important features.
- Reducing the dataset's dimensionality from 14 to 7 features.

## Modeling

- Building a linear regression model using the selected features.
- Predicting house prices and calculating residuals.
- Assessing the model’s performance.

## Key Techniques and Libraries

- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.
- **Scikit-learn**: For machine learning and feature selection.

## Results

- Successfully reduced the dataset from 14 to 7 features using linear regression for feature selection.
- Built a linear regression model to predict house prices.
- Analyzed model performance using residuals and correlation metrics.

## Conclusion

This notebook provides a comprehensive guide to performing EDA and feature selection on the Boston Housing Dataset. It highlights the importance of thorough data exploration and the impact of feature selection on model performance.
