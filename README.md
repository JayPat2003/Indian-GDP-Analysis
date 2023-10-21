# GDP Prediction with Time Series Analysis

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)

## Overview

This project aims to forecast India's Gross Domestic Product (GDP) using time series analysis. GDP prediction is a critical aspect of economic planning and decision-making, and accurate forecasts are essential for government policies, business strategies, and investment decisions.

In this project, we explore various forecasting models, including ARIMA, Linear Regression, Random Forest, and XGBoost, to identify the most reliable predictor for India's economic growth.

## Project Highlights

### Model Performance

We evaluated the performance of different models using key metrics:

#### ARIMA Model
- Root Mean Squared Error (RMSE): 0.06
- Mean Absolute Error (MAE): 0.04
- Mean Absolute Percentage Error (MAPE): 5.93%

#### Linear Regression
- RMSE: 0.07
- MAE: 0.06
- MAPE: 101.70%

#### Random Forest
- RMSE: 0.17
- MAE: 0.17
- MAPE: 17.37%

#### XGBoost
- RMSE: 0.09
- MAE: 0.09
- MAPE: 9.45%

### Conclusion

After rigorous model exploration, the ARIMA model emerged as the most suitable choice for GDP prediction. Its consistent performance, with the lowest RMSE and MAPE, reflects its capability to deliver precise and dependable forecasts. The ARIMA model's emphasis on time series forecasting aligns perfectly with our project's objective of predicting future GDP trends in India.

## How to Use

1. Clone this repository to your local machine.
2. Install the required libraries and dependencies listed in the `requirements.txt` file.
3. Explore the project using the Jupyter Notebook `GDP_Prediction.ipynb`.
4. Customize models and features to adapt the project to your specific use case.
5. Deploy the selected model for real-time GDP forecasts.

## Data Source

We'd like to express our gratitude to the [Wikipedia](https://en.wikipedia.org/wiki/Economy_of_India) for providing the GDP dataset. This project would not have been possible without access to this valuable information.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

We extend our appreciation to the open-source community for their valuable contributions and insights that have enriched this project.

For a more comprehensive analysis and detailed exploration of the models, please refer to the [Jupyter Notebook](GDP_Prediction.ipynb) included in this repository.

Feel free to contribute and enhance the project, making it an even more powerful tool for GDP prediction.
