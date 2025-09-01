# Delany Solubility Prediction Using Machine Learning

## Overview
This project aims to predict the solubility of compounds using machine learning techniques, specifically Linear Regression and Random Forest Regression. The dataset used for this analysis is based on the Delany solubility data. The notebook provides a comprehensive analysis, including data preparation, model training, evaluation, and visualization of results.

## Table of Contents
- [Model](#model)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [License](#license)

## Model
The notebook implements two machine learning models to predict the log solubility (\(logS\)) of chemical compounds based on their features.You will find the following:
- [Load Data](#load-data)
  - [Data Preparation](#data-preparation)
  - [Data Separation as X and Y](#data-separation-as-x-and-y)
  - [Data Splitting](#data-splitting)
  - [Model Building](#model-building)
    - [Linear Regression](#linear-regression)
      - [Training the Model](#training-the-model)
      - [Applying the Model to Make Predictions](#applying-the-model-to-make-predictions)
      - [Evaluate Model Performance](#evaluate-model-performance)
    - [Random Forest](#random-forest)
      - [Training the Model](#training-the-model-1)
      - [Applying the Model to Make Predictions](#applying-the-model-to-make-predictions-1)
      - [Evaluate Model Performance](#evaluate-model-performance-1)
  - [Model Comparison](#model-comparison)
  - [Data Visualization of Predicted Results](#data-visualization-of-predicted-results)

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`

## How to Run
1. Clone the repository.
2. Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run the cells sequentially.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
