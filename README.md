# README

## Overview
This project involves analyzing two datasets related to drone and UFO sightings and a Jupyter Notebook that processes these datasets.

## Files

### `drone_reports.csv`
- Contains **347** drone sighting reports.
- Fields include:
  - `Link`: Reference to the original report.
  - `Occurred`: Date and time of the sighting.
  - `City`, `State`, `Country`: Location details.
  - `Shape`: The shape of the sighted object.
  - `Summary`: Brief description of the sighting.
  - `Media`: Whether media evidence is available.
  - `Explanation`: Possible explanation for the sighting.

### `ufo_reports_2023_to_2025.csv`
- Contains **2626** UFO sighting reports from 2023 to 2025.
- Fields include:
  - `Month-Year`: Time period of the sighting.
  - `Occurred`: Exact date and time of the event.
  - `City`, `State`, `Country`: Location of the sighting.
  - `Shape`: The shape of the object.
  - `Summary`: Brief narrative of the event.
  - `Reported`: Whether the report has been confirmed.
  - `Media`: Indicates possible sources like "Aircraft" or "Drone."
  - `Explanation`: Currently missing data.

### `phase1.ipynb`
- Jupyter Notebook containing preprocessing and analysis scripts.
- Key operations:
  - Installs necessary libraries (`torch`, `wordcloud`, `transformers`, `selenium`).
  - Scrapes drone-exclusive data from NuForc.
  - Cleans and filters the datasets to remove incorrect data points.
  - Future parts involve additional data processing.

## Purpose
- The goal is to analyze and distinguish between drone and UFO reports.
- The notebook facilitates automated data collection, processing, and visualization.
- Future work may involve machine learning for classification.

## Usage
1. Open `phase1.ipynb` in Jupyter Notebook.
2. Run the provided scripts to process and analyze the datasets.
3. Use the cleaned data for further study or visualization.

---
