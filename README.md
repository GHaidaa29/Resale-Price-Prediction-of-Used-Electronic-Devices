# Resale-Price-Prediction-of-Used-Electronic-Devices
## Overview
This project aims to analyze the factors that influence the resale price of used electronic devices, particularly smartphones and tablets. By examining various specifications and features, the project seeks to determine which characteristics most significantly impact resale values in the second-hand market.

## Table of Contents
- [Introduction](#introduction)
- [Project Goals](#project-goals)
- [Data Description](#data-description)
- [Predictor Variables](#predictor-variables)
- [Analysis Methods](#analysis-methods)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The resale market for electronic devices has grown significantly as consumers look for cost-effective alternatives. Understanding the factors that influence resale prices is crucial for both consumers and businesses. This project addresses the gap in comprehensive analyses quantifying the impact of specific device features on resale prices.

## Project Goals
The primary research question guiding this study is:
- **What factors influence the resale price of used electronic devices?**

The project aims to:
- Analyze the impact of device specifications on resale prices.
- Create a predictive model to estimate resale values based on identified factors.
- Provide insights for consumers and businesses regarding the resale market.

## Data Description
The dataset includes information on multiple used devices, with each row representing a device and its attributes. The outcome variable is the resale price of the device, normalized for comparability. Summary statistics will be provided, including mean, median, and standard deviation.

## Predictor Variables
To effectively model the resale price, the following predictor variables will be utilized:
1. **Brand Name**: Reputation and resale value associated with different brands.
2. **Operating System**: User preference and market demand related to the OS.
3. **Screen Size**: The desirability of larger screens.
4. **4G/5G Capability**: Importance of connectivity features.
5. **Main Camera Megapixels**: Impact of camera quality on resale value.
6. **Selfie Camera Megapixels**: Appeal of selfie features to consumers.
7. **Internal Memory**: Effect of storage capacity on pricing.
8. **RAM**: Performance implications of higher RAM.
9. **Battery Capacity**: Selling point of longer battery life.
10. **Release Year**: Influence of model age on resale prices.

## Analysis Methods
The analysis will involve:
1. **Data Cleaning**: Handling missing values and ensuring appropriate data types.
2. **Exploratory Data Analysis (EDA)**: Identifying trends and relationships within the data.
3. **Feature Engineering**: Creating new features based on existing data.
4. **Model Selection**: Choosing the best-performing model based on metrics like R², RMSE, and MAE.
5. **Model Training and Evaluation**: Splitting data into training and testing sets to assess performance.

## Results
The project will evaluate model performance using metrics such as:
- **R² Score**: Indicates the proportion of variance explained by the model.
- **Mean Absolute Error (MAE)**: Measures the average magnitude of errors in predictions.
- **Root Mean Squared Error (RMSE)**: Provides insight into the standard deviation of prediction errors.
