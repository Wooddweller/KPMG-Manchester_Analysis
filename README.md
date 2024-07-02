# KPMG-Manchester_Analysis(Capstone Project)

## Overview

This project investigates the impact of bus transit accessibility on rental prices in Manchester, analyzing how proximity to bus stops and frequency of service affect the rental market. By examining spatial and temporal data, we aim to provide insights into the relationship between public transportation and housing affordability to aid urban planners and policymakers in making informed decisions.

## Objectives

1. **Impact of Public Transit on Rental Prices**: Assess how accessibility to bus services influences rental prices in Manchester.
2. **Correlation between Deprivation and Bus Coverage**: Analyze whether areas with higher deprivation levels have lower bus coverage.
3. **Traffic and NO2 Emissions**: Examine the influence of bus and car traffic on NO2 emission levels in Manchester.
4. **Connectivity to Essential Services**: Evaluate the connectivity of bus services to essential services and identify underserved areas.

## Methodology

1. **Data Collection**:
   - **Bus Timetable Data**: Collected detailed bus routes, schedules, and stop locations for Manchester.
   - **Rental Listings**: Scraped rental listings from SpareRoom to gather rental price data, including geographical coordinates.
   - **Points of Interest (POI) Data**: Used Google Places API to fetch distances to amenities like grocery stores, hospitals, parks, and leisure facilities.

2. **Data Integration**:
   - Matched rental listings with bus stop buffer zones (100, 300, and 500 meters) to create variables indicating proximity to bus stops.
   - Integrated POI data to enrich the dataset and provide context on amenities near rental properties.

3. **Analysis**:
   - **Geospatial Analysis**: Created buffer zones around bus stops and matched rental listings to these zones.
   - **Regression Models**: Used Random Forest Regression to model the relationship between bus accessibility and rental prices.
   - **Predictive Models**: Developed models to predict deprivation index and unique bus routes.
   - **Comparative Analysis**: Compared traffic data with NO2 emission levels to assess environmental impacts.

## Results

1. **Rental Prices**:
   - Proximity to bus stops and frequency of service significantly influence rental prices, with higher accessibility leading to increased rental values.
   
2. **Deprivation and Bus Coverage**:
   - Areas with higher deprivation levels tend to have lower bus coverage, indicating a need for improved public transit in these regions.

3. **Traffic and NO2 Emissions**:
   - Increased traffic, especially from buses and cars, correlates with higher NO2 emission levels, highlighting the environmental impact of urban traffic.

4. **Connectivity to Essential Services**:
   - Identified several underserved areas with poor connectivity to essential services, suggesting targeted improvements in bus services are necessary.

## Conclusion

This study underscores the importance of accessible public transportation in urban planning and housing affordability. The findings suggest that enhancing bus services can lead to better living conditions and reduced environmental impact in Manchester.

---

For more detailed insights and data visualizations, please refer to the full project report.
