# Socio-Demographic Data Analysis and Health Resources in the U.S.

This repository contains a data analysis project that investigates the relationship between health resources and socio-demographic data at the county level in the United States (2018-2019).

## Project Description

The main objective is to determine whether there is a relationship between health resources and socio-demographic factors in U.S. counties. To achieve this, a dataset containing various variables—both demographic and health-related—has been utilized.

The project workflow is structured in the following steps:

### Data Loading
- The dataset used is `demographic_health_data.csv`, available at:  
  [https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/demographic_health_data.csv](https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/demographic_health_data.csv)
- The necessary code to load and read the data is included.

### Exploratory Data Analysis (EDA)
- A comprehensive exploratory data analysis is performed to identify relevant variables and discard those that do not provide useful information.
- Data cleaning and visualization techniques are applied, along with an appropriate train-test split of the dataset.

### Regression Model Construction
- A linear regression model is implemented initially.
- Subsequently, a Lasso model is built using the same data and default attributes.
- The results of both models are compared, with special emphasis on how the R² coefficient evolves as the Lasso hyperparameter changes (testing values from 0.0 up to 20).

### Model Optimization
- If the results of the Lasso model are not satisfactory, optimization techniques covered in the course are applied to improve the model’s performance.

## Prerequisites

- **Python:** 3.11 or higher.
- **Pip:** For installing packages.

## Installation

1. **Clone the repository** to your local machine:
   ```bash
   git clone <repository-URL>
