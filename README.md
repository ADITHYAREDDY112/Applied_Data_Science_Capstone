# Applied Data Science Capstone

This repository contains coursework for the IBM/Coursera Applied Data Science Capstone project. The notebooks and Dash app analyze SpaceX launch data through data collection, wrangling, exploratory analysis, visualization, SQL analysis, and machine learning.

## Files

- `Data Collection API.ipynb` - Collects launch data from the SpaceX API.
- `Data Collection with Web Scraping.ipynb` - Collects supplementary launch information from web pages.
- `Data Wrangling.ipynb` - Cleans and prepares the launch dataset.
- `EDA with Data Visualization.ipynb` - Explores launch outcomes with visualizations.
- `EDA with SQL.ipynb` - Performs exploratory analysis with SQL queries.
- `Interactive Visual Analytics with Folium.ipynb` - Builds interactive map visualizations.
- `Machine Learning Prediction.ipynb` - Trains and evaluates classification models.
- `spacex_dash_app.py` - Dash dashboard for launch site and payload analysis.

## Setup

Install the Python dependencies:

```bash
pip install -r requirements.txt
```

To run the Dash app, place `spacex_launch_dash.csv` in the repository root and run:

```bash
python spacex_dash_app.py
```

## Notes

The notebooks are kept as completed Coursera assignment files. Generated outputs are preserved where useful for reviewing the assignment work.
