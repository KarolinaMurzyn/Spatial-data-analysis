# Spatial Data Analysis - Exercises and Projects

This repository contains exercises and projects developed as part of the **Spatial Data Analysis** course at **AGH University of Krakow**. The primary language used for analysis is **R**. The exercises focus on using spatial statistics and clustering techniques to analyze, visualize, and interpret spatial datasets.

## Course Overview
The course introduces students to advanced methods for spatial data analysis, including:
- Generating and analyzing spatial point patterns.
- Modeling spatial processes (e.g., Poisson, Strauss, and Matern processes).
- Clustering spatial data using DBSCAN and HDBSCAN.
- Visualizing and interpreting results with R packages like `spatstat`, `sf`, and `ggplot2`.

## Highlights from Exercises

1. **Basic Point Pattern Analysis**
   - Generate and visualize random points in rectangular and circular regions.
   - Test the randomness of point distributions using spatial statistical methods.

2. **Geostatistics and Spatial Density Estimation**
   - Analyze geological datasets, such as gold deposits and faults, using quadrat counts and kernel density estimators.
   - Visualize geological features and assess clustering.

3. **Modeling Spatial Processes**
   - Simulate spatial processes such as:
     - **Poisson Process**: Homogeneous random distribution of points.
     - **Strauss Process**: Incorporating interaction between points.
     - **Matern Cluster Process**: Modeling clustering in spatial data.
   - Analyze nearest-neighbor distances and spatial functions like G and K.

4. **Clustering Spatial Data**
   - Implement clustering algorithms such as DBSCAN and HDBSCAN to group spatial points based on density and neighborhood.
   - Visualize clusters on maps and evaluate the impact of parameters on cluster formation.

5. **Real-world Application: Analyzing Kraków**
   - Perform spatial clustering of points representing locations in Kraków.
   - Evaluate clustering results to identify densely populated regions or areas with high activity.

## Tools and Libraries
The exercises make extensive use of the following R libraries:
- `spatstat`: For spatial statistics and point pattern analysis.
- `sf`: For handling spatial data in vector formats.
- `ggplot2`: For data visualization.
- `dbscan`: For density-based clustering.
- `dplyr`: For data manipulation.

## Getting Started
To reproduce the analyses:
1. Install the necessary R packages listed in the scripts.
2. Load the provided R scripts into your R environment.
3. Follow the code comments and modify parameters as needed.

## Example Visualizations
Some of the visualizations generated include:
- Kernel density estimations of geological data.
- Maps showing clustered points and regions.
- Histograms of nearest-neighbor distances.

---
