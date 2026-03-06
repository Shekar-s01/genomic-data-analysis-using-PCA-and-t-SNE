# genomic-data-analysis-using-PCA-and-t-SNE
# Genome Data Analysis

## Overview
This project performs exploratory and statistical analysis on genomic datasets. It includes data preprocessing, dimensionality reduction, and hypothesis testing to identify patterns and relationships in genetic data.

## Features
- Data loading and preprocessing using Pandas
- Missing value handling (mean imputation or row removal)
- Categorical feature encoding using One-Hot Encoding
- Feature standardization
- Dimensionality reduction using PCA and t-SNE
- Statistical tests including t-test, ANOVA, and Chi-square
- Visualization using Matplotlib and Seaborn

## Requirements

Install the required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn scipy

## Dataset

The project uses the dataset:

igsr_HG01350_undefined.csv

Place the dataset in the project directory before running the script.

## Usage

Run the analysis script:

python genome.py

The script performs preprocessing, statistical analysis, and generates visualization plots for PCA and t-SNE.

## Future Improvements
- Advanced missing value handling
- Optimization of PCA and t-SNE parameters
- Integration of machine learning models for genomic classification or clustering
