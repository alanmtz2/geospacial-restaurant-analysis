# Geospatial Analysis of Restaurant Distribution in Mexico City

## Introduction

This project aims to analyze the spatial distribution of restaurants in Mexico City using geospatial data from OpenStreetMap. By examining the density and distribution patterns of restaurants, we can gain insights into urban planning, business opportunities, and accessibility within the city.

## Data Collection

- **Points of Interest (POI)**: Data on restaurants was collected from OpenStreetMap.
- **Street Network**: The road network of Mexico City was also obtained from OpenStreetMap to provide a comprehensive understanding of the urban layout.

## Exploratory Data Analysis (EDA)

- **Restaurant Distribution**: Visualized the geographic distribution of restaurants across the city.
- **Street Network Visualization**: Mapped the city's road network to contextualize the restaurant locations.

## Geospatial Analysis

- **Grid Creation**: Generated a grid over the city to perform a density analysis of restaurants.
- **Density Calculation**: Counted the number of restaurants within each grid cell to identify areas of high and low restaurant density.

## Interactive Visualization

- **Folium Map**: Created an interactive map using Folium to display the exact locations of restaurants and highlight density hotspots.
  - **Markers**: Each restaurant is marked on the map.
  - **Density Circles**: Visual representation of restaurant density using circle markers.

## Conclusions

- **High-Density Areas**: The city center exhibits a high density of restaurants, indicating a concentration of dining options.
- **Low-Density Areas**: Peripheral regions have fewer restaurants, suggesting less commercial activity or lower demand.

## Future Work

- **Other POIs**: Expand the analysis to include other points of interest such as hospitals, schools, and parks.
- **Mobility Data**: Incorporate mobility data to study accessibility and the relationship between restaurant locations and transportation networks.
