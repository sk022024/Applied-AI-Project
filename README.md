# Applied-AI-Project-Predicting the energy efficiency of buildings

## Project Overview
This project analyzes energy consumption in buildings and provides actionable business recommendations based on predictive modeling. The analysis focuses on heating and cooling loads and identifies the key drivers affecting energy demand.  

The project leverages:
- Random Forest modeling
- Exploratory Data Analysis (EDA)
- Data-driven business recommendations for energy-efficient building design

# Dataset Card: Energy Efficiency Dataset

## Dataset Name
Energy Efficiency Dataset

## Source
The dataset is publicly available from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency).

## Dataset Structure
- Total records: 768
- Features:

| Column                     | Type    | Description                                              |
|-----------------------------|---------|----------------------------------------------------------|
| Relative Compactness        | float64 | Ratio indicating building compactness                   |
| Surface Area                | float64 | Total surface area of the building                      |
| Wall Area                   | float64 | Total wall area                                         |
| Roof Area                   | float64 | Total roof area                                         |
| Overall Height              | float64 | Building height                                         |
| Orientation                 | int64   | Orientation of the building (numeric code)             |
| Glazing Area                | float64 | Total glazing area                                      |
| Glazing Area Distribution   | int64   | Distribution code of the glazing area                  |
| Heating Load                | float64 | Target variable: heating load (kWh/m²)                 |
| Cooling Load                | float64 | Target variable: cooling load (kWh/m²)                 |

