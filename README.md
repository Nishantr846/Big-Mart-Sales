# Big Mart Sales Prediction

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Setup and Usage](#setup-and-usage)
  - [Clone the Repository](#1-clone-the-repository)
  - [Install Dependencies](#2-install-dependencies)
  - [Run the Script](#3-run-the-script)
  - [Test the Predictive System](#4-test-the-predictive-system)
- [Project Workflow](#project-workflow)
- [License](#license)

---

## Overview
Big Mart Sales Prediction is a machine learning project designed to predict the sales of items in Big Mart outlets. By analyzing item and outlet characteristics, the system forecasts sales, enabling better decision-making in inventory management and sales strategies.

---

## Features
- Automatically handles missing values in the dataset.
- Standardizes categorical and numerical data for model compatibility.
- Leverages the **XGBoost Regressor**, a robust machine learning model for high accuracy.
- Includes a predictive system function for real-world usability.

---

## Technologies Used
- **Programming Language**: Python  
- **Libraries**:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `xgboost`

---

## Dataset
The dataset includes:
- Item attributes (e.g., weight, visibility, type, MRP).
- Outlet attributes (e.g., size, location type, establishment year).
- Target variable: `Item_Outlet_Sales`.

Ensure the dataset file (`Data.csv`) is placed in the project directory before running the code.
