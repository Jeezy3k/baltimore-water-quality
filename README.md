# Baltimore Stream Water Quality Analysis

An exploratory data analysis of water quality in Baltimore's streams from 1995-2020, examining contamination levels and trends over time.

## Motivation

As someone interested in public health and environmental issues, I wanted to understand the quality of water in Baltimore's streams. This analysis investigates key water quality indicators including coliform bacteria, lead levels, and dissolved oxygen to assess the health of the city's waterways.

## Key Findings

- **Coliform bacteria** levels showed significant improvement after 2008
- **Lead contamination** is present across many monitoring stations, with BRANCH AVE having the highest average levels
- **Dissolved oxygen** levels are generally healthy for aquatic life
- Correlation analysis reveals that related contaminants tend to occur together

## Dataset

**Source:** Baltimore Open Data - Surface Water Quality Data Since 1995

The dataset contains ~350,000+ water quality measurements from monitoring stations across Baltimore City, including:
- pH levels
- Coliform bacteria counts (Total and Fecal)
- Lead measurements (Total and Dissolved)
- Dissolved oxygen
- And many other water quality parameters

**Download:** Visit [Baltimore Open Data](https://data.baltimorecity.gov/) and search for "Surface Water Quality Data"

## Tools Used

- Python
- pandas
- matplotlib
- seaborn

## Analysis Includes

1. Data cleaning and handling missing values
2. Time series analysis by year
3. Station-level comparisons
4. Categorical classification of contamination levels
5. Correlation analysis between water quality parameters
6. Data visualization with seaborn

## Files

- `baltimore_water_quality.ipynb` - Main analysis notebook
- `stream_water_quality.csv` - Dataset (download from Baltimore Open Data)

## How to Run

1. Download the dataset from Baltimore Open Data
2. Save as `stream_water_quality.csv` in the same directory
3. Open the notebook in Jupyter
4. Run all cells
