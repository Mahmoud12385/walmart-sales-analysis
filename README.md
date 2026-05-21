# Walmart Sales Analysis & Forecasting

A complete end-to-end data analysis and machine learning project focused on Walmart sales data.
This project covers data preprocessing, exploratory data analysis (EDA), regression modeling, and time series forecasting using ARIMA and Prophet.

---

## Project Overview

The goal of this project is to analyze Walmart sales data, identify business insights, predict sales using machine learning models, and forecast future sales trends using time series analysis.

The project includes:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Outlier Detection & Treatment
* Feature Engineering
* Machine Learning Regression Models
* Time Series Forecasting
* Business Insights Visualization

---

## Technologies & Libraries

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* Prophet

---

## Project Structure

```text
walmart-sales-analysis/
│
├── data/
│   └── Walmart Dataset.csv
│
├── notebooks/
│   └── walmart_analysis.ipynb
│
├── src/
│
├── dashboard/
│
├── images/
│
├── presentation/
│   └── walmart_presentation.pptx
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Data Preprocessing

The preprocessing phase included:

* Handling missing values
* Removing duplicate records
* Converting date columns
* Outlier detection using IQR
* Outlier treatment using clipping
* Filtering invalid discount values
* Feature encoding using One-Hot Encoding

---

## Exploratory Data Analysis (EDA)

The analysis explored:

* Sales distribution
* Profit distribution
* Sales by category
* Sales by customer segment
* Regional sales and profit analysis
* Correlation analysis
* Relationships between:

  * Sales and Profit
  * Discount and Profit

Visualizations were created using Matplotlib and Seaborn.

---

## Machine Learning Models

### 1. Linear Regression

Used for predicting Walmart sales based on:

* Product category
* Region
* Segment
* Quantity
* Discount
* Profit

### 2. Random Forest Regressor

Used to improve prediction accuracy and capture non-linear relationships.

### Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## Time Series Forecasting

Monthly sales were aggregated and analyzed as a time series.

### Techniques Used

* Stationarity Testing using ADF Test
* First Differencing
* Seasonal Differencing
* ACF & PACF Analysis
* ARIMA Forecasting
* Prophet Forecasting

---

## Business Questions Answered

The project answers important business questions such as:

* Which product category generates the highest sales?
* Which customer segment contributes most to revenue?
* Which regions generate the highest sales and profit?
* How do discount and profit affect each other?
* What are the future sales trends?

---

## Results

The project successfully:

* Cleaned and analyzed Walmart sales data
* Built predictive machine learning models
* Forecasted future sales trends
* Generated business insights through visualizations

---

## Future Improvements

Possible future enhancements:

* Deploying an interactive dashboard using Streamlit
* Adding more advanced forecasting models
* Hyperparameter tuning
* Feature importance analysis
* Real-time dashboard integration

---

## How to Run the Project

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/walmart-sales-analysis.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```text
notebooks/walmart_analysis.ipynb
```

---

## Dashboard

The project can be extended with:

* Streamlit Dashboard
* Power BI Dashboard
* Tableau Dashboard

---

## Presentation

The project presentation is available in the `presentation` folder.

---

## Author

Mahmoud

---

## License

This project is for educational and learning purposes.
