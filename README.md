# Airbnb Listing Analysis 

## Project Overview
This project analyzes Airbnb listings in Paris to assess the impact of 2015 regulations on the market. The focus is on identifying factors that affect pricing and examining how these regulations have influenced the number of new hosts over time. This analysis provides valuable insights for Airbnb's leadership to inform strategic decisions.

## Aim
- To explore the impact of regulatory changes on Airbnb listings in Paris.
- To identify key factors influencing pricing and host behavior.

## Data Used
- **Dataset**: Airbnb Listings (CSV)
- **Key Columns**:
  - `host_since`
  - `neighbourhood`
  - `city` (filtered to Paris)
  - `accommodates`
  - `price`

## Techniques Used
- **Data Cleaning and Preparation**:
  - Date formatting and filtering specific to Paris.
  - Handling missing values and basic statistical analysis.
  
- **Data Aggregation and Grouping**:
  - Grouping by `neighbourhood` and `accommodates`.
  - Trend analysis by `host_since` year.

- **Visualization**:
  - Horizontal bar charts for pricing by neighborhood and accommodations.
  - Line charts for trends in new hosts and pricing over time.
  - Dual-axis charts to analyze host growth and pricing simultaneously.

## Key Findings
- **Neighborhood Disparities**: Élysée is the most expensive neighborhood, while Menilmontant and Buttes-Chaumont are among the cheapest.
- **Regulatory Impact**: The 2015 regulations significantly reduced the number of new hosts, leading to a stabilization and eventual increase in prices.
- **Price Trends**: Post-regulation, average prices increased due to reduced competition, with a notable decline during the COVID-19 pandemic.

## Conclusion
The project highlights the significant impact of regulations on Airbnb's market dynamics in Paris, providing insights that can help in strategic decision-making regarding host management and pricing strategies.

## Author : Vishwas Khandelwal
