# 🌦 Weather Dashboard

A Python project for visualizing hourly weather trends using a dataset (CSV) or live weather data from the OpenWeather API. It highlights how temperature, apparent temperature, humidity, and wind speed change over time.

---

## 📊 Features

- 📅 **Date Parsing**: Converts and parses the `Formatted Date` column to datetime objects.
- 🌡 **Temperature Trends**: Visualizes Actual vs Apparent Temperature over time.
- 💧 **Extendable Metrics**: Easily extend to plot Humidity, Wind Speed, Pressure, etc.
- 🎨 **Beautiful Visuals**: Uses Matplotlib and Seaborn for clear and customizable plots.
- 📂 **File-Based Input**: Reads from a properly formatted CSV (`weather_data.csv`).

---

## Use openweather api key

The dataset should include the following columns:

- `Formatted Date`
- `Summary`
- `Precip Type`
- `Temperature (C)`
- `Apparent Temperature (C)`
- `Humidity`
- `Wind Speed (km/h)`
- `Wind Bearing (degrees)`
- `Visibility (km)`
- `Loud Cover`
- `Pressure (millibars)`
- `Daily Summary`

> 
