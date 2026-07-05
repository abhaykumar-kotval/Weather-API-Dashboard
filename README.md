# Live Weather & Air Quality Dashboard

A real-time, API-driven Power BI dashboard that monitors current weather conditions, a 5-day forecast, and air quality across multiple cities. The dashboard integrates directly with a live REST API, transforming nested JSON data into an interactive Business Intelligence solution.

---

## Project Overview

This project demonstrates how Power BI can be used with a live web API instead of static datasets. Weather and air quality information is retrieved in real time, transformed using Power Query, modeled into a relational data structure, and presented through an interactive dashboard for quick decision-making.

The dashboard currently monitors:

* Ahmedabad
* Bengaluru
* Delhi

The architecture is scalable and can be extended to additional locations with minimal changes.

---

## Features

* Live weather data using REST API integration
* Current weather conditions
* Five-day weather forecast
* Air quality monitoring
* Temperature trend analysis
* Rain probability analysis
* Sunrise and sunset information
* Environmental KPIs
* Multi-city selection
* Interactive Power BI report

---

## Technology Stack

| Technology       | Purpose                                                             |
| ---------------- | ------------------------------------------------------------------- |
| Power BI Desktop | Dashboard development and visualization                             |
| Power Query (M)  | API connection, JSON parsing, and data transformation               |
| REST API         | Live weather and air quality data source                            |
| DAX              | Custom measures and calculations                                    |
| Data Modeling    | Relational data model for current weather, forecasts, and locations |

---

## Data Source

The dashboard uses live JSON responses from a weather API rather than static CSV or Excel files.

The data model consists of:

* **Locations** – City lookup table
* **Current** – Current weather and air quality data
* **Forecast_Day** – Five-day weather forecast
* **Forecast_Hours** – Hourly forecast data
* **Measures** – DAX calculations

The solution is designed around real-time API responses and supports future expansion to additional cities.

---

## Dashboard Highlights

### Current Conditions

Displays the latest weather information, including:

* Temperature
* Weather condition
* Last refresh time
* City selection

### Five-Day Forecast

Provides:

* Daily temperature
* Weather conditions
* Rain probability
* Temperature trends

### Air Quality

Monitors:

* PM2.5
* PM10
* O₃
* CO
* NO₂
* SO₂

Includes health indicators and custom gauge-style visualizations created using DAX.

### Environmental Metrics

Additional KPIs include:

* Humidity
* Wind Speed
* Visibility
* Atmospheric Pressure
* UV Index
* Precipitation

---

## Business Problem

Weather and air quality information is often spread across multiple applications, making it difficult to obtain a complete operational view.

This dashboard consolidates weather forecasts and environmental data into a single report, enabling faster decision-making for weather-dependent operations.

---

## Business Value

* Centralized weather and air quality monitoring
* Faster operational decision-making
* Improved planning for outdoor activities
* Better environmental awareness
* Scalable multi-city monitoring solution

---

## Skills Demonstrated

* Power BI
* Power Query (M)
* REST API Integration
* JSON Transformation
* Data Modeling
* DAX
* Data Visualization
* Dashboard Design
* Business Intelligence
* Real-Time Analytics

---

## Future Enhancements

* Historical weather analysis
* Automated scheduled refresh
* Weather alerts and notifications
* Additional cities
* Mobile-optimized dashboard
* Geographic map visualization

---
