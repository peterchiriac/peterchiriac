# Hi, I’m Peter

Data analyst building practical projects in data quality, relational databases, spatial analytics and decision-support tools.

My work uses SQL, Python, PostgreSQL and geospatial tools to clean, structure, validate and interpret complex datasets.

## Focus

* Data analysis and reporting
* Data quality and validation
* Relational databases and SQL workflows
* Python and Pandas
* Spatial analytics
* Practical decision-support tools

## Current Projects

### Project FieldPulse — Agritech Sensor Data Quality Pipeline

A PostgreSQL data-quality pipeline for messy farm sensor telemetry.

The project imports simulated sensor readings, preserves the original telemetry, and creates a reusable clean view with diagnostic flags for:

- physically impossible soil moisture readings
- battery-related missingness
- frozen temperature sensor behaviour

The frozen-sensor rule uses temporal analysis to identify long consecutive runs of identical temperature readings.

This project focuses on sensor data quality, temporal anomaly detection, and reproducible SQL workflows.

### Farm Alpha — Soil Analysis and Management Recommendations

A field-level agritech workflow that transforms spatial and soil data into management recommendations.

Farm Alpha uses a subset of Irish LPIS parcels as the analysis unit and integrates SoilGrids data into field-level outputs through spatial data validation, field-level aggregation, and decision mapping.

Key outputs include:

- field boundary validation and spatial data QA
- soil pH classification
- soil organic carbon status
- clay-influenced soil structure notes
- recommended management action mapping

The main finding was that soil pH was consistently low across the farm, indicating a need for whole-farm liming, while soil organic carbon levels were generally moderate to high.

This project focuses on turning raw spatial and soil data into practical decision-support outputs.

### Precision Agriculture Advisory Tool

A portfolio project exploring soil- and weather-based agronomic recommendations using Python, Streamlit, and external data sources.

The project combines soil characteristics and weather signals to generate simple advisory outputs for field management.

### Farm Tracking Tool

A lightweight tool for tracking plantings and harvests in a city-farm context.

This project focuses on small-scale farm operations, structured records, and practical data capture.

## Technical Skills

- SQL
- PostgreSQL
- PostGIS
- Python
- Pandas
- QGIS
- CSV data workflows
- Spatial data QA
- Data cleaning
- Data validation
- Markdown documentation
- Git and GitHub

## Direction

I am developing my skills for data analyst and junior analytics engineering roles involving data quality, reporting and reliable data systems. Agriculture, sustainability and spatial analytics remain particular areas of interest.
