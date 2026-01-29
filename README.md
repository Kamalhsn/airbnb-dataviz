# Airbnb Data Visualization  
**Transforming EDA Insights into Interactive Dashboards**

---

## Project Overview

This project is part of the **Data Visualization Challenge**, which focuses on transforming insights derived from Exploratory Data Analysis (EDA) into interactive and insightful dashboards. The objective is to demonstrate the ability to clean, analyze, and visualize real-world data using industry-standard tools.

In this project, Airbnb listings data is analyzed and visualized to compare patterns, trends, and differences between two major global cities: **Berlin** and **Bangkok**. The final outcome is an interactive Power BI dashboard designed to support data-driven decision-making.

---

## Problem Statement

How can data visualization tools be used to perform a comparative analysis of Airbnb operations across two diverse urban environments?

This project aims to leverage visual analytics to:
- Identify similarities and differences in Airbnb listings between Berlin and Bangkok
- Analyze neighbourhood-level patterns, pricing behavior, property types, and host activity
- Present insights in a clear and accessible manner for a broad audience

---

## Cities Covered

- **Berlin, Germany**
- **Bangkok, Thailand**

These cities were selected due to their contrasting tourism profiles, urban structure, and Airbnb market dynamics, making them ideal for comparative analysis.

---

## Data Sources

- **Dataset Name:** Airbnb Listings Data  
- **Source:** https://insideairbnb.com/get-the-data/  
- **Data Type:** Publicly available Airbnb listings data  

### Key Files Used
- Listings data (cleaned and feature-engineered)
- Neighbourhood-level aggregated metrics

The datasets include information such as:
- Listing identifiers and host details  
- Neighbourhood and location information  
- Room and property types  
- Pricing and availability  
- Review-related metrics  

---

## Tools & Technologies

- **Python**
  - Data cleaning
  - Exploratory Data Analysis (EDA)
  - Feature engineering
- **Pandas & NumPy**
  - Data manipulation and transformation
- **Excel**
  - Staging layer to preserve clean schemas and data types for visualization
- **Power BI**
  - Interactive dashboard creation
  - Data modeling and visualization
- **Git & GitHub**
  - Version control
  - Project documentation and reproducibility
 
## Project Structure

```text
airbnb-dataviz/
├── data/
│   ├── berlin/
│   └── bangkok/
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   └── 04_feature_engineering.ipynb
├── dashboards/
│   └── airbnb_berlin_bangkok.pbix
├── requirements.txt
└── README.md
```



## Methodology

### 1. Data Understanding
- Reviewed dataset structure and attributes
- Assessed data completeness and consistency
- Identified key variables relevant to analysis and visualization

### 2. Data Cleaning
- Removed duplicate records
- Handled missing and invalid values
- Standardized categorical fields (e.g., room type, host type)
- Validated and capped extreme price outliers

### 3. Exploratory Data Analysis (EDA)
- Analyzed listing distribution across neighbourhoods
- Examined room type and property composition
- Compared pricing, availability, and review patterns between cities

### 4. Feature Engineering
- Created price categories for easier comparison
- Classified hosts into single-listing and multi-listing types
- Generated neighbourhood-level aggregated metrics for dashboards

### 5. Dashboard Development
- Built an interactive Power BI dashboard
- Ensured clean data modeling and relationships
- Focused on clarity, usability, and insight-driven design

---

## Dashboard Plan

### Dashboard Pages
1. **Overview**  
   High-level KPIs comparing Berlin and Bangkok
2. **Property Analysis**  
   Distribution of room types and price categories
3. **Pricing Analysis**  
   Price behavior by room type and neighbourhood
4. **Host Analysis**  
   Host composition and its impact on supply and pricing

---

### Key KPIs
- Total Listings  
- Average Price  
- Median Price  
- Total Hosts  
- Average Availability (365 days)

---

### Filters & Interactivity
- Neighbourhood  
- Room Type  
- Price Category  
- Host Type  

Filters are applied selectively on analysis pages to ensure meaningful and accurate insights without over-filtering summary KPIs.

---

## Deliverables

- **Power BI Dashboard (.pbix file)**  
- **GitHub Repository** containing:
  - Cleaned and processed datasets
  - Python notebooks
  - Project documentation (README)
- **Presentation Video** (15+ minutes) explaining:
  - Project objectives
  - Data preparation
  - Dashboard design
  - Key insights and conclusions

---

## Conclusion

This project demonstrates the complete workflow of transforming raw Airbnb data into an interactive dashboard, from data cleaning and analysis to visualization and storytelling. The final dashboard provides actionable insights into Airbnb market dynamics across Berlin and Bangkok.

