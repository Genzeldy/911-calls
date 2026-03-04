# 911 Emergency Calls Analysis

## Project Overview

This project explores a dataset of **911 emergency calls** to identify patterns in emergency incidents across time, location, and type of emergency.

Using Python and data visualization techniques, the analysis examines how emergency calls vary by:

* type of emergency
* time of day
* day of the week
* monthly trends

The goal of this project is to demonstrate **exploratory data analysis (EDA), feature engineering, and data visualization** using Python.

---

## Dataset

The dataset contains records of 911 emergency calls with the following fields:

* Latitude and longitude
* Description of the emergency
* Zip code
* Township
* Timestamp of the call
* Emergency title

Dataset file:

```
data/911.csv
```

---

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Key Analysis Steps

The project includes the following analysis workflow:

1. Data loading and inspection
2. Exploratory data analysis (EDA)
3. Feature engineering (extracting emergency categories and time features)
4. Analysis of emergency call types
5. Time-based analysis (hour, day of week, and monthly trends)
6. Time series analysis of daily call volume
7. Heatmap visualization of emergency call patterns

---

## Repository Structure

```
911-calls
│
├── data
│   └── 911.csv
│
├── images
│   └── heatmap_calls_by_hour_day.png
│
├── 911_calls_data_analysis.ipynb
├── README.md
└── LICENSE
```

---

## Key Insights

Some patterns identified during the analysis include:

* Emergency Medical Services (EMS) calls represent the largest portion of emergency incidents.
* Emergency call volume varies significantly across different hours of the day.
* Weekly patterns show differences between weekday and weekend emergency activity.

These insights demonstrate how exploratory data analysis can reveal operational patterns in emergency response data.

---

## How to Run the Project

1. Clone the repository
2. Install the required Python libraries
3. Open the notebook:

```
911_calls_data_analysis.ipynb
```

4. Run the notebook cells to reproduce the analysis.
