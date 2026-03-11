# Weather Data Analysis and Visualization

## Project Overview

This project focuses on analyzing **10 years of daily weather data** to understand climate patterns, seasonal variations, and relationships between meteorological variables. Using Python-based data analysis tools, the project explores how **temperature, rainfall, humidity, and wind speed** behave over time.

The goal of the project is to transform raw weather data into meaningful insights using **exploratory data analysis (EDA)** and visualization techniques.

---

## Objectives

The main objectives of this project are:

* Analyze **temperature patterns and seasonal trends**
* Study **rainfall distribution and rainy vs clear days**
* Examine **wind speed behavior and its seasonal variation**
* Explore relationships between **temperature, humidity, rainfall, and wind**
* Detect **extreme weather conditions**
* Identify **long-term climate trends across 10 years**
* Visualize weather patterns using statistical and graphical techniques

---

## Dataset Description

The dataset contains **daily weather observations** with multiple meteorological attributes.

### Features in the Dataset

| Column         | Description                                |
| -------------- | ------------------------------------------ |
| date           | Date of the observation                    |
| temp_max       | Maximum daily temperature                  |
| temp_min       | Minimum daily temperature                  |
| temp_mean      | Mean daily temperature                     |
| humidity       | Humidity level                             |
| rain           | Rainfall amount                            |
| wind_speed_max | Maximum wind speed                         |
| rainflag       | Indicates whether rainfall occurred        |
| temp_range     | Difference between max and min temperature |
| temp_avg       | Average temperature                        |
| month          | Month of observation                       |
| season         | Seasonal category                          |
| year           | Year of observation                        |
| weekday        | Day index of the week                      |
| day            | Day of the month                           |
| dayname        | Name of the weekday                        |

The dataset spans **10 years of daily observations**, enabling long-term climate analysis.

---

## Technologies Used

* **Python**
* **Pandas** – data manipulation and preprocessing
* **Matplotlib** – data visualization
* **Seaborn** – statistical visualization
* **SciPy** – statistical analysis

---

## Exploratory Data Analysis (EDA)

The project includes multiple types of analysis:

### Temperature Analysis

* Distribution of average temperature
* Monthly temperature variation
* Relationship between minimum and maximum temperature
* Seasonal temperature patterns
* Temperature trends over time
* Regression and residual analysis

### Rainfall Analysis

* Rainy vs clear days comparison
* Rainfall distribution
* Monthly rainfall trends
* Seasonal rainfall patterns
* Cumulative rainfall distribution (ECDF)

### Wind Analysis

* Wind speed distribution
* Temperature vs wind relationship
* Seasonal wind behavior

### Humidity Analysis

* Humidity distribution
* Joint distribution of temperature and humidity

### Temporal Analysis

* Weather trends over time
* Temperature anomaly detection
* Long-term climate pattern analysis

### Yearly Climate Analysis

* Average temperature by year
* Rainfall variation by year
* Wind speed variation across years

### Advanced Visualizations

* Correlation heatmap
* Pairwise variable analysis
* Calendar heatmap of temperature over 10 years
* Extreme weather detection visualization

---

## Key Insights

Some important insights obtained from the analysis include:

* The climate in the dataset is **generally warm**, with most temperatures ranging between **24°C and 28°C**.
* **Summer months show the highest temperatures**, while winter months are cooler.
* Rainfall is **highly seasonal**, with most precipitation occurring during the **monsoon period**.
* Wind speeds remain **moderate on most days**, with occasional higher speeds during rainy seasons.
* Temperature variables show **strong correlations**, particularly between mean and maximum temperature.
* Extreme weather events occur **infrequently but are identifiable through combined temperature and wind thresholds**.

---

## Project Structure

```
Weather-Data-Analysis
│
├── data/
│   └── weather_dataset.csv
│
├── notebooks/
│   └── weather_analysis.ipynb
│
├── visualizations/
│   └── generated_plots
│
├── README.md
└── requirements.txt
```

---

## Future Improvements

Possible future enhancements include:

* Building **predictive models for weather forecasting**
* Detecting **anomalies and climate change indicators**
* Adding **geographical weather comparisons**
* Creating an **interactive dashboard using Power BI or Plotly**
* Integrating additional meteorological variables such as atmospheric pressure and solar radiation

---

## Conclusion

This project demonstrates how **exploratory data analysis and visualization** can be used to uncover patterns in environmental data. By analyzing multiple weather variables across a decade, the project highlights the value of data visualization in understanding **seasonal trends, climate behavior, and extreme weather conditions**.

---

## Author

Siddhartha Kumar Raju Nadimpalli,Sai Vivek Kamanuru

