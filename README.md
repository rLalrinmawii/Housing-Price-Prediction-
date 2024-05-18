# Housing Price Prediction using Multiple Linear Regression

This project aims to predict housing prices based on various features using multiple linear regression. The analysis is conducted on the "USA_Housing.csv" dataset, which includes information such as average area income, house age, number of rooms, number of bedrooms, population, and house price.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Analysis Steps](#analysis-steps)
- [Interpretations](#interpretations)
- [Files Included](#files-included)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Multiple linear regression is a statistical technique used to understand the relationship between one dependent variable and several independent variables. In this project, we utilize multiple linear regression to predict housing prices based on various features extracted from the "USA_Housing.csv" dataset.

## Dataset Description

The dataset comprises the following columns:

- **Avg. Area Income**: Average income of residents in the area.
- **Avg. Area House Age**: Average age of houses in the area.
- **Avg. Area Number of Rooms**: Average number of rooms in houses in the area.
- **Avg. Area Number of Bedrooms**: Average number of bedrooms in houses in the area.
- **Area Population**: Population of the area.
- **Price**: Price of the house.

## Analysis Steps

The analysis includes the following steps:

1. Data exploration and visualization
2. Preprocessing and cleaning
3. Model training using multiple linear regression
4. Model evaluation
5. Checking assumptions of linear regression
6. Binary classification metrics (if applicable)

## Interpretations

The model achieved an R-squared value of 0.918, indicating that approximately 92% of the variance in housing prices can be explained by the features in the dataset. The root mean squared error (RMSE) was 100,444.06, suggesting a good fit. The analysis also includes error analysis, checking assumptions of linear regression, and binary classification metrics (if applicable).

## Files Included

- `USA_Housing.csv`: Dataset used for analysis
- `housing_price_prediction.ipynb`: Jupyter Notebook containing the Python code for the analysis
- `README.md`: This README file

## Getting Started

To get started with this project, clone the repository to your local machine.

```bash
git clone https://github.com/yourusername/housing-price-prediction.git
```

## Dependencies

The following Python libraries are required to run the analysis:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## Usage

Open the `housing_price_prediction.ipynb` notebook in Jupyter Notebook or JupyterLab to view the analysis and execute the code cells.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
