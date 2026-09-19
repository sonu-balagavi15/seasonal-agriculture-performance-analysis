# Seasonal Agriculture Performance Analysis and Profit Prediction

## 📌 Project Overview

This project analyzes agricultural performance across different crops and seasons using Python, Exploratory Data Analysis (EDA), data visualization, and Machine Learning.

The main objective is to identify meaningful patterns, trends, relationships, and variations in agricultural performance and to develop a machine learning model for profit prediction.

---

## 🎯 Problem Statement

Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability, and market conditions. As a result, agricultural performance may differ from one season to another.

However, raw agricultural data does not clearly explain how agricultural performance changes across seasons or what patterns can be observed under different seasonal conditions.

The problem is to analyze the given agricultural dataset and investigate seasonal differences in agricultural performance by identifying meaningful patterns, trends, relationships, and variations within the available data.

---

## 🎯 Objectives

- Analyze agricultural performance across different crops and seasons.
- Study yield, revenue, cost, profit, and profit margin.
- Identify relationships between important agricultural variables.
- Detect variations and outliers in the dataset.
- Compare crop-wise and season-wise performance.
- Visualize important agricultural patterns.
- Build machine learning models for profit prediction.
- Compare different regression models.
- Identify important features influencing predicted profit.

---

## 📊 Dataset

The dataset contains agricultural performance information with the following variables:

- `Crop`
- `Season`
- `Farm_Area_Hectares`
- `Production_Tonnes`
- `Yield_Tonnes_Ha`
- `Revenue_INR`
- `Profit_INR`
- `Profit_Margin`
- `Total_Cost_INR`

---

## 🔍 Exploratory Data Analysis

The project includes analysis of:

- Dataset structure and information
- Missing values
- Duplicate records
- Descriptive statistics
- Crop-wise performance
- Season-wise performance
- Crop and season comparison
- Yield analysis
- Revenue analysis
- Cost analysis
- Profit analysis
- Profit margin analysis
- Outlier analysis
- Correlation analysis
- Data visualization

---

## 📈 Key Findings

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
| Sugarcane | 817,187.99 |
| Chilli | 750,878.34 |
| Cotton | 124,546.92 |
| Groundnut | 44,858.12 |
| Pulses | -4,238.05 |
| Maize | -83,978.33 |
| Rice | -102,213.50 |
| Wheat | -123,398.34 |

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

---

## 🔗 Correlation Analysis

Important observed relationships include:

- Farm Area vs Revenue: **0.5434**
- Production vs Revenue: **0.5635**
- Farm Area vs Profit: **0.1152**

These correlations were analyzed to understand relationships between farm size, production, revenue, and profit.

---

## 🤖 Machine Learning

The target variable for machine learning is:

```text
Profit_INR
