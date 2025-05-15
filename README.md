# nyc_transport

# Project Title: NYC Transportation Barriers Research Project


# Project Description: 
This project analyzes barriers in NYC's multi-modal transportation system using data from the 2019 Citywide Mobility Survey. The research analyzes over 85,000 trip records and examines how journey characteristics vary across different NYC zones. The analysis investigates spatial and temporal movement patterns throughout NYC, identifies key origin-destination flows, analyzes transportation mode distribution by neighborhood, and investigates how multi-modal integration works. By creating a comprehensive understanding of mobility patterns that reveals relationships between location, modes, accessibility, and trip purposes, the project offers insights for targeted interventions to improve mobility across the five boroughs and create more inclusive mobility solutions.


# Rationale Statement: 
This project was motivated by my daily Brooklyn-to-Manhattan commute frustrations—waiting for delayed trains, navigating crowded transfers, and watching buses crawl through congestion. What struck me was how dramatically these challenges varied depending on where I was in the city. People in some neighborhoods consistently enjoy efficient trips, while others face what I began to call a daily "time tax" for living in poorly connected areas. These aren't just inconveniences but quality-of-life barriers that accumulated over time, adding up to days of lost life annually for some New Yorkers. Beyond the personal impact, I recognize these disparities as fundamental equity issues, which are invisible to traditional transit metrics but painfully real for residents. By quantifying these experiences and uncovering the patterns behind them, this research aims to give voice to the lived transportation realities of New Yorkers and provide evidence for more equitable, responsive interventions that acknowledge how people actually move through their city.


# Workflow: 
  Libraries Used:
  1. Data manipulation: pandas, numpy, datetime
  2. Spatial analysis: geopandas
  3. Network analysis: networkx
  4. Visualization: matplotlib, seaborn, plotly.express, plotly.graph_objects, plotly.subplots, folium

 Key Analytical Steps:
  1. Data Exploration and Cleaning: Processed the Citywide Mobility Survey Trip 2019 dataset from NYC Open Data, containing 85,000+ trip records across all five boroughs.
  2. Spatial Analysis: Examined trip durations, distances, and speeds by origin/destination zones to identify geographic disparities in transportation efficiency.
  3. Flow Analysis: Mapped origin-destination pairs to identify major movement corridors and connectivity gaps.
  4. Modal Distribution Analysis: Assessed transportation mode availability and preferences by neighborhood, creating a Modal Diversity Index.
  5. Multi-Modal Journey Analysis: Examined how travelers combine different modes and identified critical transfer points.
  6. Temporal and Purpose Analysis: Analyzed how trip purpose influences transportation patterns.
  7. Transportation Barrier Index Development: Created a composite measure that quantifies mobility challenges across neighborhoods.


# Further Uses: 
  1. Transit Service Optimization: Apply findings to align transit service with actual movement patterns. Use origin-destination flows for route planning, trip purpose data for schedule adjustments, and modal integration insights to redesign transfer points for better multi-modal connectivity.
  2. Dynamic Applications: Extend the approach with real-time data integration, demographic analysis, or interactive tools that help residents visualize transportation options in their neighborhoods.
  3. Policy and Equity Applications: Use this framework to identify neighborhood-level disparities, develop equity-focused interventions, and prioritize improvements in underserved areas.


# Files List: 
  1. nyc_transport_analysis_notebook.ipynb: Main Jupyter notebook containing the full analysis workflow, from data cleaning to visualization and findings synthesis.
  2. 664_Citywide_Mobility_Survey_Trip_2019.csv: Primary dataset from NYC Open Data containing trip records with origin/destination, mode, purpose, and timing information.
