i# Sustainable Urban Mobility Analytics

### Big Data Analysis and Machine Learning-Based Transportation Demand Forecasting

## Project Overview

Sustainable Urban Mobility Analytics is a Big Data analytics project that analyses New York City For-Hire Vehicle (FHV) trip data from January to March 2024.

The project uses Python, PySpark, Apache Spark, Machine Learning, and Power BI to process large-scale transportation data, identify travel demand patterns, and forecast future transportation demand.

The main objective is to understand when and where transportation demand is highest and use historical trip patterns to predict upcoming demand.

## Objectives

- Process and analyse large-scale transportation data.
- Identify daily and hourly transportation demand patterns.
- Analyse high-demand pickup locations.
- Explore trip distance and duration patterns.
- Develop a Machine Learning model for demand forecasting.
- Build an interactive Power BI dashboard for visual analysis.

## Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Big Data Processing | Apache Spark, PySpark |
| Data Analysis | Pandas, NumPy |
| Machine Learning | Random Forest Regression |
| Data Visualisation | Matplotlib, Power BI |
| Development Environment | Jupyter Notebook |

## Project Workflow

1. **Data Collection:** Used NYC For-Hire Vehicle trip records for January, February, and March 2024.

2. **Data Processing:** Processed approximately 60.3 million records using PySpark.

3. **Exploratory Data Analysis:** Analysed transportation demand based on dates, hours, pickup locations, trip distance, and duration.

4. **Feature Engineering:** Prepared historical demand features for Machine Learning.

5. **Model Development:** Developed a Random Forest Regression model to forecast transportation demand for the next seven days.

6. **Model Evaluation:** Evaluated model performance using MAE, RMSE, and R².

7. **Dashboard Development:** Created an interactive Power BI dashboard to present transportation demand insights and forecast results.

## Machine Learning Model Performance

The Random Forest Regression model was evaluated using the following metrics:

| Evaluation Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 21,576.49 |
| Root Mean Squared Error (RMSE) | 29,281.43 |
| R² Score | 0.8639 |

The model recorded approximately 31.3% lower MAE compared with the 7-day historical baseline on the test set.

**Note:** The test set contained 17 days of observations. Further validation on a longer test period would help assess the model's generalisation performance.

## Power BI Dashboard

The interactive dashboard includes:

- Total Trips and Average Daily Trips.
- Average Trip Distance and Duration.
- Daily Transportation Demand Trends.
- Hourly Transportation Demand Distribution.
- Top 10 Pickup Locations.
- Seven-Day Transportation Demand Forecast.
- Interactive Date Slicer.

## Project Structure

```text
Sustainable-Urban-Mobility-Analytics/
│
├── dashboard/
│   ├── Sustainable_Urban_Mobility_Dashboard.pbix
│   └── dashboard_screenshot.png
│
├── notebooks/
│   └── Sustainable_Urban_Mobility_Analytics.ipynb
│
├── outputs/
│   ├── daily_summary.csv
│   ├── demand_forecast.csv
│   ├── hourly_summary.csv
│   ├── pickup_location_summary.csv
│   └── pickup_location_by_date.csv
│
└── README.md
```

## Key Findings

- Processed approximately 60.3 million transportation trip records.
- Identified daily and hourly variations in transportation demand.
- Analysed pickup locations with high trip volumes.
- Developed a Random Forest model for seven-day demand forecasting.
- Presented analytical findings through an interactive Power BI dashboard.

## Future Improvements

- Validate forecasting performance over a longer test period.
- Explore additional Machine Learning algorithms.
- Incorporate real-time transportation data.
- Investigate traffic congestion and environmental indicators using additional datasets.

## Author

**Aarushi**

MCA Student | Thapar Institute of Engineering and Technology

---

*This project was developed as part of Big Data Analytics to demonstrate large-scale data processing, Machine Learning, and interactive data visualisation.*