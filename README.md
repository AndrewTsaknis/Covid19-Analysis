# COVID-19 Data Analysis 📊

## 📌 Project Summary
This project analyzes global COVID-19 time-series data to explore how confirmed cases and deaths evolved over time.  
The goal is to visualize long-term trends, identify major waves, and highlight how the pandemic progressed in a selected country.

The analysis includes loading time-series data (Johns Hopkins University), cleaning the dataset, and generating visualizations for confirmed cases and deaths.  
This project demonstrates practical data analysis, time-series handling, and visualization using Python and Matplotlib.

---

## 📂 Dataset Location

Place the following files in the same folder as the Jupyter notebook or Python script:

- `time_series_covid19_confirmed_global.csv`  
- `time_series_covid19_deaths_global.csv`

The project code is written to load these files directly from the project root directory.

---

## 🔗 Dataset Download

If you do not already have the datasets, you can download them here:

**Johns Hopkins CSSE COVID-19 Time Series (JHU):**  
https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series

---

## 📊 Key Insights

The following visualizations were created using Python (Pandas, Matplotlib):

---

### 1. Confirmed COVID-19 Cases Over Time

<img width="1489" height="590" alt="confirmed_cases" src="https://github.com/user-attachments/assets/3d141dc1-d538-412e-a5ca-d0ce86acdfa3" />


- Shows the cumulative number of confirmed cases from 2020 to 2023.  
- Clear waves and peaks highlight different phases of the pandemic.  
- Helps visualize how quickly cases increased during major outbreaks.

---

### 2. Confirmed COVID-19 Deaths Over Time

<img width="1389" height="590" alt="confirmed_deaths" src="https://github.com/user-attachments/assets/12f5f805-9a56-480a-acdf-ab11884b9150" />


- Displays the cumulative number of recorded deaths over time.  
- Allows comparison between case surges and fatality outcomes.  
- Useful for evaluating the severity of each wave.

---
### 3. Monthly New Cases Over Time

<img width="1527" height="589" alt="confirmed-new_cases_by_month" src="https://github.com/user-attachments/assets/60a623b7-e9e8-4801-a627-f73ccbe4dcda" />

- Shows the number of new reported cases each month.
- Peaks clearly highlight major COVID-19 waves.
- Useful for analyzing outbreak intensity and spread patterns.

---

### 4. Monthly New Deaths Over Time

<img width="1389" height="590" alt="daily_new_deaths_by_month" src="https://github.com/user-attachments/assets/6c7c6657-927d-4a61-bd1e-0a0dc04e3510" />

- Displays monthly new reported deaths.
- Helps identify the severity of each COVID wave.
- Often lags behind new cases, reflecting real-world disease progression.

---

## 🛠️ How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/AndrewTsaknis/Covid19-Analysis.git


Run the cells to generate the charts.
