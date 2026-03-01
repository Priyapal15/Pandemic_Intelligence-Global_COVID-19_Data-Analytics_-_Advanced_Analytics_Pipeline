# Pandemic_Intelligence-Global_COVID-19_Data-Analytics_-_Advanced_Analytics_Pipeline

A comprehensive end-to-end data analytics project focused on global COVID-19 data processing, feature engineering, exploratory analysis, mortality modeling, and visualization using Python.

This project goes beyond basic EDA and implements a structured data engineering pipeline with automated feature creation, testing, and analytical reporting.



**📌 Project Objective**

The goal of this project is to:

Collect and preprocess global COVID-19 data

Engineer meaningful analytical features

Analyze global case trends and mortality

Study socioeconomic impact correlations

Build reusable feature pipelines

Generate high-quality visualizations

Apply statistical reasoning for insights

This project simulates a real-world data analytics workflow used in public health intelligence and data science teams.

Data Pipeline Overview


1️⃣ Data Collection

Automated dataset downloading using download_data.py

Structured ingestion of global COVID case data

Integration with World Bank socioeconomic indicators


2️⃣ Feature Engineering

The features/ directory contains modular feature creation scripts:

Script Purpose

| Script                     | Purpose                                   |
| -------------------------- | ----------------------------------------- |
| make_cases.py              | Total case calculations                   |
| make_cases_daily_change.py | Daily case growth                         |
| make_cases_since_t0.py     | Cases since first outbreak                |
| make_mortality.py          | Mortality rate computation                |
| make_country_stats.py      | Country-level aggregated metrics          |
| make_continents.py         | Continent-level grouping                  |
| make_world_bank.py         | Socioeconomic data integration            |
| make_coordinates.py        | Geo-coordinates mapping                   |
| make_all.py                | Central pipeline to generate all features |


This design mimics production-level data engineering pipelines, where feature generation is modular and reusable.



**📊 Exploratory Data Analysis (EDA)**

The notebooks cover:

🌎 Global Trend Analysis

Case growth over time

Continent-level comparisons

Growth curve visualization

☠️ Mortality Analysis

Death rate trends

Mortality comparison across regions

Outlier country identification

📈 Socioeconomic Impact Study

Correlation with GDP

Healthcare infrastructure influence

Population density comparisons

🎨 Advanced Visualizations

Custom styled plots

High-quality presentation charts

Publication-style visual outputs



**🤖 AI / Advanced Analytical Elements**

Although this is primarily an analytics and feature-engineering project, it includes elements commonly used in AI workflows:

Structured feature pipelines suitable for machine learning

Mortality rate modeling preparation

Statistical distribution analysis

Residual-style evaluation concepts

Automated transformation utilities

Testing framework (tests/test.py) for pipeline validation

The modular feature system is fully compatible with:

Predictive modeling

Time-series forecasting

Classification models

Clustering analysis

This makes the project extendable into a full AI-based pandemic prediction system.



**🛠️ Technologies Used**

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Custom Feature Engineering Modules

Basic Testing Framework



**🧠 Key Skills Demonstrated**

✔ Data Wrangling 
✔ Data Cleaning & Transformation 
✔ Feature Engineering 
✔ Statistical Analysis 
✔ Mortality Rate Computation 
✔ Socioeconomic Data Integration 
✔ Visualization Engineering 
✔ Modular Code Architecture 
✔ Reproducible Data Pipelines 
✔ Analytical Thinking



**📈 Sample Insights Generated**

Mortality rates vary significantly by continent

Socioeconomic indicators correlate with case outcomes

Early outbreak countries show distinct growth curves

Case growth stabilizes differently across regions
