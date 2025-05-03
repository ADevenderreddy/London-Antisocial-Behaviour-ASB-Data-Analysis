# 🚨 London Antisocial Behaviour (ASB) Data Analysis

This project investigates antisocial behaviour (ASB) incidents across London using open-source crime data. The goal is to understand spatial and temporal patterns of ASB reports to inform community safety initiatives and resource allocation.

## 📊 Project Overview

This notebook-based project performs an exploratory data analysis (EDA) and geospatial visualization of ASB incidents in London, aiming to identify boroughs with higher incident rates, seasonal trends, and overall patterns in reported antisocial behaviour.

## 📁 Dataset

The data used is sourced from:

* **Metropolitan Police Crime Data**: Contains monthly crime reports per London borough, including categories like ASB, burglary, and more.

### Key Features:

* Borough-level ASB incident data
* Monthly granularity
* Covers Greater London
* CSV format

## 🧪 Analysis Conducted

* **Data Cleaning & Preprocessing**: Handling missing values, date conversion, renaming columns.
* **EDA**: Borough-wise counts, monthly distribution, high-frequency areas.
* **Time-Series Analysis**: Temporal trend evaluation of ASB incidents.
* **Visualization**:

  * Bar charts for borough comparisons
  * Line plots for monthly trends
  * Heatmaps for borough vs. month intensity
* **Insights Derived**:

  * Westminster and Camden reported the highest ASB levels.
  * Peaks in summer months and during lockdown phases.
  * Inner-city boroughs tend to have consistently higher ASB rates.

## 📍 Tools & Technologies

* Python 3
* Pandas
* Matplotlib & Seaborn
* Jupyter Notebook

## 📌 Key Findings

* **Spatial Insight**: Central London boroughs like Westminster show consistently high ASB levels.
* **Temporal Insight**: Seasonal patterns suggest increased ASB during summer months.
* **Trend**: General decline in ASB since peak COVID periods.
