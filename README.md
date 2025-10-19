# Melbourne Housing Price Analysis

This project analyzes Melbourne housing prices using interactive maps and data visualization techniques.

## Files

- `A2.Rmd` - Main R Markdown analysis file
- `A2.html` - Rendered HTML report
- `Melbourne_housing_FULL.csv` - Housing dataset
- `shapefile/` - Geographic boundary data for Melbourne suburbs

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
