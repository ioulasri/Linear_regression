# Car Price Prediction using Linear Regression

## Overview
This project implements a **linear regression model** to predict car prices based on mileage. The dataset consists of **250 data points**, where each entry includes:
- **Mileage** (in kilometers, formatted as `xx,xxx km`)
- **Price** (in dollars)

The project involves **data preprocessing, feature scaling, training a regression model using gradient descent, and evaluating performance**.

## Features
- **Data Preprocessing:** Stripping `km` from mileage, removing commas, and converting to integers.
- **Feature Scaling:** Min-Max normalization for mileage and price.
- **Model Training:** Gradient Descent for optimizing `m` (slope) and `b` (intercept).
- **Performance Evaluation:** Using **R² score** and **Mean Absolute Error (MAE)**.
- **Visualization:** Scatter plot comparing actual vs. predicted prices.

## Dataset
- The dataset (`data.csv`) contains 250 car entries.
- Mileage values range from **10,000 km to 250,000 km**.
- Prices are **correlated** with mileage but include some noise for realism.

## Results
- **R² Score:** `0.89` (~89% variance explained)
- **MAE:** `$388` (average price prediction error)
- **Visualizations:** Scatter plot showing actual vs. predicted prices.

## How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
   ```
2. Install dependencies:
   ```sh
   pip install numpy pandas matplotlib
   ```
3. Run the Jupyter Notebook (`main.ipynb`) or execute the Python script.
4. View the generated **scatter plot** and **model evaluation metrics**.

## Future Improvements
- Implement **Polynomial Regression** to capture nonlinearity.
- Include additional features (**car age, brand, fuel type**).
- Train on a larger dataset for better generalization.

## License
This project is open-source under the **MIT License**.

---
Feel free to contribute by improving the model, adding new features, or optimizing the training process! 🚀