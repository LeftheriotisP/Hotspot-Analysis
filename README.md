# Hotspot Analysis with spatiotemporal data

Thesis topic: "Hotspot Analysis with spatiotemporal data"

## Author
Panagiotis Leftheriotis

## Contact
p.leftheriotis@gmail.com

## Contents
- [Summary](#summary)
- [Technologies Used](#technologies-used)
- [File Description](#file-description)
- [How to Run](#how-to-run)
- [User Manual](#user-manual)
- [References](#references)


## Summary
Hotspot analysis concerns the problem of identifying statistically significant data concentrations. The aim of this thesis is to study spatiotemporal data to highlight areas with significant concentration for different time intervals.
Two methods were used to detect hotspots. The first is the 90th-percentile method, which identifies cells with significant data concentrations without taking into account information from neighboring cells. The second method used the modified Getis Ord Gi* statistical method, where the spatial autocorrelation index is calculated by taking into account only the information from neighboring cells within a user-defined distance. The proximity relationship used to calculate the Gi* z-score uses the Chebyshev distance to calculate the distance between cells in the grid. The algorithm was implemented in the Python programming language. In the experimental evaluation of the algorithm, conclusions are drawn regarding its effectiveness for various analysis parameters and the results of the hotspot analysis are visualized.
Key terms: data analysis, hotspots, grid, 90th percentile, cells, spatiotemporal data, spatial autocorrelation

## Technologies Used

