# NYC Flights Analysis System 🛫

An interactive command-line data analysis system built to explore and query
flight data from New York City's three major airports: JFK, LaGuardia (LGA),
and Newark Liberty (EWR) — covering over 300,000 flights from 2013.

## 🔍 What It Does

- Merges flight data from 3 airports into a single unified dataset
- User authentication system with login, signup, and attempt limits
- Interactive menu with 7 analysis modules:
  - **a)** Flight count by origin and destination
  - **b)** Total flights by origin and date
  - **c)** Statistical summary (distance, air time) by airport
  - **d)** Delay status breakdown by origin airport
  - **e)** Summary by criteria and date
  - **f)** Flight count by tail number and airport
  - **g)** Bar chart of delayed flights per month per airport

## 📊 Key Features

- Data wrangling: unit conversions (miles → km, minutes → hours), month translation, delay status classification
- Airport name mapping for all US destinations
- Matplotlib visualizations comparing delay trends across all 3 airports

## 🛠 Tech Stack

Python · Pandas · Matplotlib · NumPy

## 📁 Data Sources

Flight data pulled from public CSV files covering JFK, EWR, and LGA airports (2013).

## ▶️ How to Run
```bash
pip install pandas matplotlib numpy
```

Open `nyc_flight_analysis.ipynb` in Jupyter Notebook or Google Colab and run all cells.
