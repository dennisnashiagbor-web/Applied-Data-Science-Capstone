# SpaceX Falcon 9 Launch Success Prediction

## Project Summary
This is an end-to-end data science project focused on analyzing historical SpaceX Falcon 9 launch data to predict first-stage booster landing success. The project applies statistical analysis, machine learning, and interactive visualization to support data-driven decision-making.

The goal is to identify the key factors that influence successful landings and build predictive models to support data-driven decision-making.

---

## Business Problem
SpaceX aims to reduce launch costs by reusing rocket boosters. Accurately predicting whether a booster will land successfully enables better mission planning, cost estimation, and operational decision-making.

---

## Project Objectives
- Collect launch data from public APIs and web sources
- Clean, transform, and structure the dataset
- Perform exploratory data analysis (EDA) using Python and SQL
- Visualize launch patterns and geographic trends
- Build and evaluate machine learning models
- Create an interactive dashboard for result exploration

---

## Project Workflow
1. Data Collection (API & Web Scraping)
2. Data Wrangling & Cleaning
3. Exploratory Data Analysis (EDA)
4. SQL-Based Analysis
5. Interactive Visualizations (Folium)
6. Interactive Dashboard (Plotly Dash)
7. Machine Learning Modeling

---

## Folder Structure
```text
applied-data-science-capstone/
├── notebooks/   # Jupyter notebooks for each project stage
├── app/         # Plotly Dash application
├── data/        # Processed datasets
├── assets/      # Images and visual outputs
```
---

## Notebooks Overview
| Order | Notebook | Description |
|------|---------|-------------|
| 01 | Data Collection (API) | Collects launch data using SpaceX REST API |
| 02 | Data Collection (Web Scraping) | Scrapes historical launch records |
| 03 | Data Wrangling | Cleans and prepares data for analysis |
| 04 | EDA with SQL | Performs SQL-based analysis using SQLite |
| 05 | EDA & Visualization | Explores trends using charts and plots |
| 06 | Folium Visualization | Creates interactive geospatial maps |
| 07 | Machine Learning Prediction | Trains and evaluates classification models |

---

## Tools & Technologies
- Python (Pandas, NumPy)
- SQL (SQLite)
- Data Visualization (Matplotlib, Seaborn, Folium)
- Machine Learning (Scikit-learn)
- Dashboarding (Plotly Dash)

---

## Key Results
- Launch site and orbit type significantly impact landing success
- Payload mass influences booster recovery probability
- Machine learning models achieved strong predictive performance

---

## Author
Dennis Ashiagbor
