# Delhi_Metro_Network_Analysis

This project involves an in-depth analysis of the Delhi Metro network using various data visualization and geospatial tools. The dataset includes information about metro stations, such as station IDs, names, distances from the start, lines, opening days, layouts, and geographic coordinates.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis](#analysis)
  - [Map Visualization](#map-visualization)
  - [Stations Opened Per Year](#stations-opened-per-year)
  - [Stations Per Line](#stations-per-line)
  - [Station Layout Distribution](#station-layout-distribution)
  - [Station Density Heatmap](#station-density-heatmap)
- [Conclusion](#conclusion)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Usage](#usage)

## Introduction
The Delhi Metro is a rapid transit system serving Delhi and its satellite cities. This project aims to analyze the metro network's expansion, station distribution, and various other aspects using Python libraries such as `pandas`, `matplotlib`, `seaborn`, `plotly`, and `folium`.

## Dataset
The dataset contains the following columns:
- `Station ID`
- `Station Name`
- `Distance from start`
- `Line`
- `Opening date`
- `Station Layout`
- `Latitude`
- `Longitude`

## Analysis
### Map Visualization
A Delhi map with metro lines and tooltips for station information has been plotted using Folium.

### Stations Opened Per Year
A bar chart showing the number of metro stations opened each year, highlighting the growth of the metro network over time.

### Stations Per Line
A bar chart depicting the number of stations on each metro line.

### Station Layout Distribution
A distribution plot showing the different layouts of metro stations.

### Station Density Heatmap
A heatmap illustrating the density of metro stations across Delhi.

## Conclusion
The analysis of the Delhi Metro network provides insights into its structure, growth, and distribution. The network is strategically spread across Delhi, enhancing connectivity and accessibility. The continuous expansion reflects efforts to improve urban mobility and reduce congestion.

## Getting Started
To get a local copy up and running, follow these steps.

### Requirements
- Python 3.10
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`
- `folium`

### Usage
1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/delhi-metro-network-analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd delhi-metro-network-analysis
    ```
3. Install the required libraries:
    ```sh
    pip install pandas matplotlib seaborn plotly folium
    ```
4. Run the analysis script:
    ```sh
    python analysis.py
    ```
