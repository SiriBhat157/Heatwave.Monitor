A desktop dashboard that analyzes monthly temperature data for 96 Indian cities (2020–2025) and highlights heat trends and heatwave-prone months. It is built as a tabbed GUI with interactive filters and embedded charts.

Features
Dashboard: Key statistics at a glance, including total records (6,912), cities (96), years covered (6), average max temperature (31.6 °C), months at or above 40 °C (223), and the highest recorded max temperature (44.0 °C, Amravati, May 2020). It also shows three charts: average max temperature by year, months ≥ 40 °C by year, and the heat level distribution.
City Data: Browse monthly records (average, min and max temperature, rainfall, pressure, heat level) for any city, filterable by year.
Heat Months: List all city-month records at or above a chosen heat level (Hot, Heatwave-prone, Severe heat), with a match count and year filter.
Summary: Per-city statistics (hottest month, months ≥ 40 °C, average max temperature, average rainfall), the top 5 hottest cities, and a monthly max temperature chart with a 40 °C reference line.
Charts: Additional visualizations of the dataset.
Heat Classification

Each month is labeled Normal, Hot, Heatwave-prone, or Severe heat based on its maximum temperature.

Tech Stack
Python
Tkinter
Pandas
Matplotlib
SQLite

Dataset

popular_cities_weather.csv: monthly weather records for popular Indian cities.
