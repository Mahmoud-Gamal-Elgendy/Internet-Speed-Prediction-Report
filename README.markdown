# Internet Speed Prediction Report

## Overview

This project is a college assignment for the "Analysis Web Based" course. It involves a Jupyter Notebook report that predicts internet download speeds from 2024 to 2030 using historical data from 2021 and 2023. The report includes:

- Data preprocessing and feature engineering.
- Training and evaluation of three machine learning models: Ridge Regression, Decision Tree, and Random Forest.
- Features used: year, bytes transferred, upload speed, and latency.
- Visualizations of actual vs. predicted speeds, residual analysis, and speed trends over time.
- Future predictions with confidence intervals.

All details, code, results, and visualizations are presented in the Jupyter Notebook file.

## Files

- `internet_speed_prediction_report.ipynb`: The main Jupyter Notebook file containing the full report, code, and visualizations.
- `data/`: Directory where the dataset files should be placed after downloading (e.g., `curr_httpgetmt6.csv`, `curr_httppostmt.csv`, etc.).

## Dataset

The dataset consists of historical internet performance data for 2021 and 2023. Download the required files using the links below and place them in the `data/` directory:

https://data.fcc.gov/download/measuring-broadband-america/2023/data-raw-2023-feb.tar.gz
https://data.fcc.gov/download/measuring-broadband-america/2021/data-raw-2021-feb.tar.gz

## Requirements

To run the notebook, you need the following:

- Python 3.x
- Jupyter Notebook
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib


## Author

- \[Mahmoud Youssef\]


## License

This project is licensed under the MIT License - see the LICENSE file for details.