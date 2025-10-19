# Melbourne Housing Price Analysis

This project analyzes Melbourne housing prices using interactive maps and data visualization techniques.

## Files

- `A2.Rmd` - Main R Markdown analysis file
- `A2.html` - Rendered HTML report
- `Melbourne_housing_FULL.csv` - Housing dataset

## Required Data

To run the analysis, you need to download the Melbourne suburb shapefile:

1. Visit [Australian Bureau of Statistics](https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs-edition-3/jul2021-jun2026/access-and-downloads/digital-boundary-files)
2. Download "Statistical Area Level 1 (SA1) ASGS Edition 3" for Victoria
3. Extract the files to a `shapefile/` folder in this directory
4. The main file should be named `SAL_2021_AUST_GDA94.shp`

## Features

- **Individual House Price Scatter Plot**: Shows each house location with price-based coloring
- **Interactive Suburb Map**: Clickable map showing average prices by suburb
- **Data Cleaning**: Comprehensive data preprocessing and imputation
- **Statistical Analysis**: Price statistics and top expensive/cheapest houses

## Requirements

- R 4.4.2+
- Required R packages: dplyr, ggplot2, sf, leaflet, viridis, scales, zoo, tidyr, naniar, mice, lubridate, forcats

## Usage

1. Open `A2.Rmd` in RStudio
2. Install required packages if not already installed
3. Run the R Markdown file (Ctrl + Shift + K)
4. View the generated `A2.html` for the complete analysis

## Data Source

Melbourne Housing Dataset with geographic coordinates and suburb boundaries from Australian Bureau of Statistics (SAL 2021).
