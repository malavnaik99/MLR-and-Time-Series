# Comprehensive Analysis of Multiple Linear Regression and Time Series Forecasting

## Introduction
This project demonstrates the applications of **Multiple Linear Regression (MLR)** and **Time Series Forecasting** using SARIMA models. The repository showcases practical approaches to predictive modeling, emphasizing statistical rigor and interpretability.

## Features
- **Multiple Linear Regression (MLR)**: 
  - Predicts target variables using multiple independent features.
  - Includes steps like data preprocessing, encoding, model evaluation, and interpretation.
  - Metrics used: R-squared (R²) and Mean Squared Error (MSE).

- **Time Series Forecasting**:
  - Implements SARIMA modeling for seasonal and trend analysis.
  - Optimizes parameters using Auto ARIMA.
  - Evaluates performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Techniques and Methodologies
1. **Data Preparation**:
   - Handling missing values with mean/mode imputation.
   - One-hot encoding categorical variables.
   - Detecting and managing outliers using capping and flooring techniques.
   - Splitting the dataset into training and testing subsets.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizations: Histograms, Scatter Plots, Box Plots, Correlation Matrix.
   - Insights into trends, outliers, and correlations.

3. **Model Development**:
   - MLR: Fitted models, handled multicollinearity, and evaluated coefficients' significance.
   - Time Series: Addressed stationarity through log transformations and differencing.

4. **Model Validation**:
   - Residual analysis to confirm model assumptions.
   - Performance metrics on test datasets.

## Highlights
- Achieved an R² value of **0.699** in MLR, indicating strong predictive power.
- SARIMA forecasts were validated with low residual autocorrelation and high accuracy metrics (e.g., RMSE: 2.82).

## Repository Structure
- `MLR.ipynb`: Notebook detailing the Multiple Linear Regression implementation.
- `Time_Series.ipynb`: Notebook covering Time Series Forecasting with SARIMA.
- `x23271779.pdf`: Detailed project documentation.

## Tools and Libraries
- Python (Pandas, NumPy, Scikit-learn)
- Visualization (Matplotlib, Seaborn)
- Statsmodels (SARIMA modeling)
- Auto ARIMA

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/project-name.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebooks:
   - MLR: `MLR.ipynb`
   - Time Series: `Time_Series.ipynb`

## Results
Both models demonstrated robust performance on test datasets, validating their reliability for predictive analytics and decision-making.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

