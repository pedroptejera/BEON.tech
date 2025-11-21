# ✈️ NYC Flights Data Analysis

**Author:** Pedro Tejera
**Context:** Technical Assessment - Data Analyst Position

---

## 🎯 Project Objective
This project aims to analyze the **NYC Flights 2013 dataset** to identify operational bottlenecks and efficiency opportunities. The analysis focuses on three core pillars:
1.  **Traffic & Connectivity:** Understanding flight volume and destination spread.
2.  **Operational Efficiency:** Diagnosing departure delays and their correlation with weather conditions.
3.  **Fleet & Carrier Analysis:** Evaluating airline capacity and fleet composition.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas (Data Manipulation), Seaborn/Matplotlib (Visualization), NumPy.
* **Environment:** Jupyter Notebook.

## 📂 Repository Structure
| File | Description |
| :--- | :--- |
| `BEONtech.ipynb` | **Main Analysis Notebook.** Contains all the Python code, visualizations, and business insights. |
| `nyc_flights_fixed.csv` | Main dataset containing flight schedules and delay information. |
| `nyc_weather.csv` | Hourly weather data used for correlation analysis. |
| `nyc_airlines.csv` | Lookup table for Airline full names. |
| `nyc_planes.csv` | Metadata about the aircraft fleet (manufacturer, seats, etc.). |
| `nyc_airports.csv` | Metadata about airport locations and names. |

## 💡 Key Findings 
Based on the analysis performed in `BEONtech.ipynb`:

* **Hub Connectivity:** The airport acts as a significant hub, connecting passengers to **100 distinct destinations**.
* **Daily Consistency:** On average, the operation services **81 unique destinations per day**, demonstrating high route consistency.
* **Weekly Pattern:** **Sunday** is the day with the widest variety of connections (83 destinations on average), while Saturday sees the lowest (77), reflecting typical leisure and business travel cycles.
* **Peak Seasonality:** **August** stands out as the busiest month with over **24,290 flights**, marking the peak of the summer travel season.

## 🚀 How to Run
1.  Clone this repository.
2.  Ensure all CSV files are in the same directory as the notebook.
3.  Run the `BEONtech.ipynb` cells sequentially.

---
*2025*
