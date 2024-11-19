Project Description:
This project involves creating an interactive dashboard to monitor and visualize the spread of an invasive insect species across multiple forest types. 
The dashboard integrates data from drone imagery, GPS-tagged field observations, and satellite data to provide real-time insights into affected areas. 
It is designed analyze pest density, spread trends, and other critical metrics.

Features:
Geospatial Visualization:
Displays pest density and affected regions on an interactive map using ArcGIS Maps for Power BI.
Data Breakdown:
Detailed analysis of insect counts by forest type and data source through bar charts and tables.
Real-Time Updates:
Supports real-time data streaming for live updates from field observations and telemetry.
Filter and Drill-Down:
Filters by date, forest type, and data source for focused analysis.
Heat Maps:
Visual representation of pest density hotspots across forest regions.
Data Sources:
Drone Imagery:
High-resolution images with geospatial data.
GPS-Tagged Field Observations:
Direct field data, including timestamps and coordinates.
Satellite Data:
Large-scale coverage of affected areas for historical and real-time analysis.
Tools and Technologies:
Power BI:
Used for data integration, visualization, and dashboard creation.
Features: Power Query Editor, ArcGIS Maps, Shape Map, and streaming datasets.
ArcGIS Maps for Power BI:
Enables advanced geospatial visualizations and mapping capabilities.
Data Storage:
CSV files for static data and streaming datasets for real-time inputs.
Supporting Tools:
Microsoft Power Automate: Automates data refresh processes.
Python (Optional): For preprocessing large or complex datasets.
Steps to Run the Project:
Data Preparation:

Ensure all data sources are formatted correctly (e.g., CSV files with clean and standardized fields).
Confirm GPS coordinates are valid and consistent (decimal format).
Load Data into Power BI:

Open Power BI Desktop and import the data from the provided CSV file (Invasive_Insect_Data.csv).
Use Power Query Editor to clean and transform the data if necessary.
Create Visualizations:

Map Visualization: Plot GPS_Latitude, GPS_Longitude, and Insect_Count.
Bar Chart: Use Forest_Type and Insect_Count for comparison.
Table: Display Source, Date, Forest_Type, Insect_Count, and Observation_Note.
Add Slicers and Filters:

Include slicers for Date and Source to filter data dynamically.
Configure Real-Time Data:

Set up streaming datasets for live updates (if required).
Use Power Automate to connect live feeds from field teams or telemetry data.
Publish the Dashboard:

Publish the dashboard to Power BI Service for web-based access.
Share the dashboard with the research team, ensuring appropriate access permissions.
