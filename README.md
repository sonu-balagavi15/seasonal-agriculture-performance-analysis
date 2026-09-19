# Seasonal Agriculture Performance Analysis and Profit Prediction

## Project Overview

This project analyzes agricultural performance across different crops and seasons using Python, Exploratory Data Analysis (EDA), data visualization, and Machine Learning.

The main objective is to identify meaningful patterns, trends, relationships, and variations in agricultural performance and to develop a machine learning model for profit prediction.

## Problem Statement

Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability, and market conditions. As a result, agricultural performance may differ from one season to another.

However, raw agricultural data does not clearly explain how agricultural performance changes across seasons or what patterns can be observed under different seasonal conditions.

The problem is to analyze the given agricultural dataset and investigate seasonal differences in agricultural performance by identifying meaningful patterns, trends, relationships, and variations within the available data.

## Objectives

- Analyze agricultural performance across different crops and seasons.
- Study yield, revenue, cost, profit, and profit margin.
- Identify relationships between important agricultural variables.
- Detect variations and outliers in the dataset.
- Compare crop-wise and season-wise performance.
- Visualize important agricultural patterns.
- Build machine learning models for profit prediction.
- Compare different regression models.
- Identify important features influencing predicted profit.

## Dataset

The dataset contains the following variables:

- Crop
- Season
- Farm_Area_Hectares
- Production_Tonnes
- Yield_Tonnes_Ha
- Revenue_INR
- Profit_INR
- Profit_Margin
- Total_Cost_INR

## Exploratory Data Analysis

The project includes:

- Dataset inspection
- Missing value analysis
- Duplicate analysis
- Descriptive statistics
- Crop-wise analysis
- Season-wise analysis
- Crop and season comparison
- Yield analysis
- Revenue analysis
- Cost analysis
- Profit analysis
- Profit margin analysis
- Outlier analysis
- Correlation analysis
- Data visualization

## Key Findings

### Average Yield by Crop

| Crop | Average Yield |
|---|---:|
| Sugarcane | 46.64 |
| Maize | 2.71 |
| Rice | 2.43 |
| Wheat | 2.11 |
| Chilli | 1.54 |
| Groundnut | 1.32 |
| Cotton | 1.23 |
| Pulses | 0.92 |

### Average Profit by Crop

| Crop | Average Profit (INR) |
|---|---:|
| Sugarcane | 817187.99 |
| Chilli | 750878.34 |
| Cotton | 124546.92 |
| Groundnut | 44858.12 |
| Pulses | -4238.05 |
| Maize | -83978.33 |
| Rice | -102213.50 |
| Wheat | -123398.34 |

### Average Profit Margin by Crop

| Crop | Average Profit Margin |
|---|---:|
| Chilli | 33.78% |
| Sugarcane | 27.35% |
| Cotton | -8.23% |
| Groundnut | -28.66% |
| Pulses | -36.48% |
| Maize | -81.54% |
| Wheat | -91.70% |
| Rice | -99.37% |

## Correlation Analysis

Important observed correlations:

- Farm Area vs Revenue: 0.5434
- Production vs Revenue: 0.5635
- Farm Area vs Profit: 0.1152

These relationships were analyzed to understand the association between farm size, production, revenue, and profit.

## Machine Learning

The target variable is:

`Profit_INR`

### Features Used

- Crop
- Season
- Farm Area
- Production
- Yield
- Revenue
- Total Cost

Categorical variables such as Crop and Season were converted using one-hot encoding.

### Models Used

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor

### Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The models were compared and the best-performing model was selected based on the observed R² score.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning
- Data Visualization

## Project Files

- `Seasonal_Agriculture_Analysis.ipynb`
- `README.md`

## How to Run

1. Open `Seasonal_Agriculture_Analysis.ipynb`.
2. Open it using Google Colab or Jupyter Notebook.
3. Upload the required dataset when requested.
4. Run the notebook cells sequentially.

## Future Scope

- Include real-time agricultural and market data.
- Add weather and environmental parameters.
- Integrate real-time crop price information.
- Develop a web-based agricultural decision-support system.
- Improve profit prediction using additional features.
- Deploy the machine learning model as a web application.
- Provide crop and season recommendations based on historical data.

## Author

**Sonu Parashuram Balagavi**

B.E. Computer Science Engineering  
AGM Rural College of Engineering and Technology

### Links

- GitHub: https://github.com/sonu-balagavi15
- LinkedIn: https://www.linkedin.com/in/sonu-balagavi

## Project

**Seasonal Agriculture Performance Analysis and Profit Prediction**

This project was developed as part of academic project work.
