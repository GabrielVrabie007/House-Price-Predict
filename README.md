# House Price Prediction AI 🏠

Welcome to the **House Price Prediction AI** project, a machine learning solution for predicting real estate prices. This project employs advanced regression techniques to provide accurate property valuations based on various features. 🎯

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Performance](#model-performance)
- [Contributing](#contributing)

## Overview

House Price Prediction AI analyzes various property features such as location, area, number of rooms, and amenities to predict market values. The project includes data preprocessing,handling outliers, feature engineering, model training. 📊

## Features

- **Data Analysis**: Comprehensive exploration and visualization of housing data 📈
- **Feature Engineering**: Advanced preprocessing and feature creation for better predictions 🔧
- **Best model in this case**: Implementation of XGBoost algorithm

- **Price Insights**: Detailed analysis of factors influencing house prices 💡

## Installation

1. **Clone the repository**:
   ```bash
   git clone "https://github.com/GabrielVrabie007/House-Price-Predict.git"
   ```

2. **Create a virtual environment**:

   For Windows:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

   For Unix or MacOS:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install poetry

   poetry install
   ```

## Usage

1. **Prepare your data**:
   ```python
   RUN file "house_price_pred.ipynb"
   ```


## Dataset

The project uses a comprehensive housing dataset containing:
- 1.Price: The price of the house.

- 2.Area: The total area of the house in square feet.

- 3.Bedrooms: The number of bedrooms in the house.

- 4.Bathrooms: The number of bathrooms in the house.

- 5.Stories: The number of stories in the house.

- 6.Mainroad: Whether the house is connected to the main road (Yes/- No).

- 7.Guestroom: Whether the house has a guest room (Yes/No).

- 8.Basement: Whether the house has a basement (Yes/No).

- 9.Hot water heating: Whether the house has a hot water heating  system (Yes/No).

- 10.Airconditioning: Whether the house has an air conditioning - system (Yes/No).

- 11.Parking: The number of parking spaces available within the - house.

- 12.Prefarea: Whether the house is located in a preferred area - (Yes/No).

- 13.Furnishing status: The furnishing status of the house (Fully Furnished, Semi-Furnished, Unfurnished).

You can download similar datasets from:
- [Kaggle Housing Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)


## Model Performance

Current model achieves:
- Mean Absolute Error (MAE): $823183.465625
- Mean Square Error (MSE): $1520740652576.1787
- R² Score: 0.631



## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.


---
Built with ❤️ using Python, Scikit-learn , Pandas and Numpy.
