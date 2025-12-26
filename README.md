# City Electricity Consumption – Hourly Analysis

## Project Overview
This project analyzes **city electricity consumption data on an hourly basis** using Python.  
The main goal is to understand **daily usage patterns**, identify **peak load hours**, and study **variations in electricity demand** throughout the day using data analysis and visualization techniques.

The project is suitable for **college minor projects**, **Pandas assignments**, and **data analysis portfolios**.

## Objectives
- Analyze hourly electricity consumption
- Detect peak load (maximum demand) hours
- Visualize consumption trends using graphs
- Study variance and distribution of electricity usage
- Understand consumption behavior during different time slots

## Technologies Used
- **Python**
- **Pandas** – Data handling and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization

## Dataset Description
- The dataset represents **hourly electricity consumption (in MW)** for a city over **30 days**.
- Data is generated programmatically to simulate realistic electricity usage.

### Columns Used
- **Timestamp** – Date and time (hourly)
- **Consumption_MW** – Electricity consumption in megawatts
- **Hour** – Extracted hour from timestamp
- **Date** – Extracted date
- **Time_Slot** – Categorized time of day (Morning, Afternoon, Evening, Night)

## Methodology
1. Generate hourly timestamps for 30 days
2. Create realistic electricity consumption values using NumPy
3. Preprocess data by extracting hour and date
4. Calculate:
   - Hourly average consumption
   - Hourly variance
5. Detect peak load hour
6. Visualize results using multiple plots
7. Generate statistical summary and final insights

## Visualizations Included
- **Line Plot:** Average hourly electricity consumption
- **Line Plot:** Daily electricity consumption trend
- **Line Plot:** Hourly variance in consumption
- **Pie Chart:** Electricity consumption by time slots
- **Histogram:** Distribution of electricity consumption

These visualizations help in clearly understanding demand patterns and variability.




