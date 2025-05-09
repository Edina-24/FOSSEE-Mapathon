### Delhi AQI Heatmap
## Overview
This project is developed as part of the IIT Bombay FOSSEE Mapathon, with the goal of creating a high-precision Delhi Air Quality Index (AQI) Heatmap. The heatmap visually represents areas in Delhi with high, moderate, and low AQI values, using Inverse Distance Weighting (IDW) interpolation for accurate spatial analysis.

## Key Features:
Geospatial Analysis: Utilized QGIS for advanced geospatial data visualization and analysis.

IDW Interpolation: Applied IDW interpolation to predict AQI values at unsampled locations.

Air Quality Visualization: The heatmap helps visualize air quality across different parts of Delhi, enabling the identification of high-pollution zones.

## Tools & Technologies
QGIS: A powerful open-source geographic information system for mapping and spatial analysis.

IDW (Inverse Distance Weighting): A method used for interpolating AQI values based on distances from known data points.

Python: For data preprocessing and automation tasks (e.g., cleaning, formatting, and transforming AQI data).

GIS Data: Includes geographic information of Delhi with AQI readings from various monitoring stations.

## Installation
Install QGIS from QGIS Official Site.

Download the project files (you should receive a ZIP file or access to the repository with GIS data).

Open QGIS and load the dataset containing AQI readings from various locations in Delhi.

Use the provided QGIS project file (.qgs) to view the AQI heatmap.

If needed, you can run additional Python scripts (included in the repository) to preprocess the AQI data or perform specific spatial analyses.

## How to Use
Load the Dataset: Import the AQI data into QGIS (either in CSV format or other GIS-compatible formats).

Apply IDW Interpolation:

Use the IDW interpolation tool in QGIS to generate AQI values at unsampled locations based on the known data points.

Set the necessary parameters, including the search radius and power value.

Visualize the Heatmap:

After interpolation, display the data in a heatmap format with color-coded zones to represent low, moderate, and high AQI values.

Analyze the Results: Review the heatmap to identify areas with the most significant pollution and evaluate the air quality distribution across the city.

## Results
The AQI Heatmap helps visualize the air quality in different areas of Delhi.

High AQI Zones: Areas with poor air quality are highlighted in red, indicating unhealthy air conditions.

Moderate AQI Zones: Areas with moderate pollution are displayed in yellow or orange.

Low AQI Zones: Clean air areas are shown in green or blue.

## Future Improvements
Real-time Data: Integrate real-time AQI data for live updates on air quality across Delhi.

Mobile Accessibility: Develop a mobile-friendly application or web-based interface to allow users to easily view the AQI heatmap.

Advanced Modeling: Explore the use of machine learning models to predict AQI based on additional features like weather data, traffic density, and industrial activities.
