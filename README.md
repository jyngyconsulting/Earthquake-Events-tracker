# World Earthquake Events
USGS inspired report of earthquake events in the world

This is a data engineering project using Microsoft Fabric unified platform.

## Project components and tasks

### Components
Notebook: Ingestion, Transformation, business modelling
Lakehouse: For data storage, data management and processing
Data Factory: Pipeline for batch loads and refresh
Power BI: visualization and analytics


### Tasks
1. Create Project in "My workspace"
2. Add lakehouse for storage and cataloging
3. PySpark to Ingest data from source api: https://earthquake.usgs.gov/fdsnws/event/1/ for a specific earthquake range
4. Store raw data in bronze layer
5. Process the data into structured dataframe, convert time from unix timestamp to standard timestamp
6. Store processed standardized data in a table in silver layer
7. Apply business logic to help analyse the data by location, and significance
8. Create a semantic model for fast direct data performance, keep the data in sync.
9. Develop Power BI report
10. The purpose of the report is to view the earthquake events by latitude and longitude location categorized by significance.

## Power BI Report

<iframe title="Earthquakes" width="1140" height="541.25" src="https://app.fabric.microsoft.com/reportEmbed?reportId=2407399c-0cac-4c7a-81eb-06c37040ef45&autoAuth=true&ctid=303ee47d-8b16-43a3-8a48-aef5a55b31c0" frameborder="0" allowFullScreen="true"></iframe>
