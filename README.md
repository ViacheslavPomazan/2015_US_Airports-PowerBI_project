# 2015_US_Airports-PowerBI_project 🚀

## 📌 Project Overview
This project provides a comprehensive analysis of the **2015 US Flight Delays and Cancellations** dataset. Using Power BI, I developed an interactive multi-page dashboard to explore performance metrics across 5.8 million flights. The report provides both a high-level overview of all US airports and detailed airport-level analysis, with separate Departure and Arrival perspectives. It also explores how delays and cancellations depend on different factors and segments.

## 🎯 Key Objectives
*   **Identify Trends:** Analyze seasonal and monthly patterns in flight delays and cancellations.
*   **Root Cause Analysis:** Categorize delays and cancellatios by Weather, NAS (National Airspace System), Security, and Airline factors.
*   **Geospatial Insights:** Visualize flight performance across the United States using interactive maps.
*   **Comparative Analysis:** Compare performance between "Mega Hubs," "Major Hubs," "Regional," and "Small" airports.
*   **Statistical Distribution:** Use box plots and correlation charts to understand the variance and relationship between different delay types.

## 🛢️ Data Source
*   **Dataset:** [2015 Flight Delays and Cancellations](https://www.kaggle.com/datasets/usdot/flight-delays) from Kaggle (provided by the U.S. Department of Transportation).
*   **Scale:** Over 5.8 million records covering departures and arrivals for the entire year of 2015.

## 🛠 Tech Stack
*   **Tool:** Power BI Desktop
*   **Data Processing:** Power Query (ETL, data cleaning, and transformation)
*   **Modeling:** DAX (Data Analysis Expressions) for complex measures such as *Moving Averages, Dynamic Tooltips, and Category-based Correlations*.
*   **Visualization:** Geospatial maps, Box-and-Whisker plots, Bubble charts, and Time-series line charts.

## 📊 Gallery

1. Main Page

![main page](image/airport_main1.png)

2. Selected Airport

![airport](image/airport_airport1.png)

3. Airport Analysis by Delays

![airport analysis1](image/airport_analysis11.png)

4. Airport Analysis by Cancellations

![airport analysis2](image/airport_analysis22.png) 

👉[Watch report video review](https://drive.google.com/file/d/1RxhG_Ym4iGBYK-Q6sVSc-CF2hckTfH1K/view?usp=sharing)


## 🚀 Main Features & Interactivity
1.  **Dynamic Mode Switching:** A single toggle allows users to switch the entire report between **Arrival** and **Departure** metrics.
2.  **Airports Analysis (Drill-through):** Deep-dive into specific airports (e.g., Nantucket Memorial Airport) to see localized on-time rates, cancellation reasons, and monthly trends.
3.  **Statistical Insights:**
    *   **Box Plots:** Show the distribution of delays by airport category to identify outliers.
    *   **Correlation Matrix:** Analyzes how different delay causes (Weather vs. Airline vs. NAS) correlate with airport size.
4.  **Advanced Filtering:** Filter by Date range, Airline, City, and specific Cancellation Reasons (A, B, C, D).
5.  **Tops 10 Dashboard:** Quick-view cards showing the most problematic airports by average delay and total cancellation count.

## 💡 Key Insights
*   **Hub Performance:** While "Mega Hubs" (like Chicago-ORD and Dallas-DFW) have the highest absolute number of cancellations, smaller regional airports (like Wilmington-ILG) often exhibit higher *average* departure delays.
*   **Cancellation Drivers:** The "Cancelled Part" analysis reveals that certain regions are significantly more susceptible to weather-related cancellations during winter months.
*   **NAS vs. Weather:** NAS delays are more consistent throughout the year, whereas weather delays show high volatility, peaking during specific seasonal events.
*   **Airline Efficiency:** Significant variance in "On-Time Departure Rates" was observed among different carriers, with some airlines maintaining higher efficiency even at congested hubs.

## 📁 Repository Structure
*   `2015 US Airports.pdf` — Static export of the dashboard pages.
*   `2015 US Airports.mp4` — A screen recording demonstrating the interactivity and navigation of the Power BI report.
  

---
**Author:** Viacheslav Pomazan  
**Role:** Data Analyst  
**Links:** [LinkedIn](https://www.linkedin.com/in/viacheslav-pomazan) | [GitHub](https://github.com/ViacheslavPomazan)


