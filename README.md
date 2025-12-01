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

Hotspot analysis focuses on identifying areas with statistically significant concentrations of data.  
The aim of this thesis is to analyze spatiotemporal datasets and highlight regions that show unusually high activity across different time intervals.

Two hotspot detection methods were implemented:

- **90th-percentile method:** Detects high-density cells without considering information from neighboring cells.
- **Modified Getis-Ord Gi\***:** Calculates spatial autocorrelation using only neighboring cells within a user-defined distance, based on the Chebyshev distance.

The algorithm was implemented in **Python**, and an experimental evaluation was conducted to assess performance under various analysis parameters.  
The resulting hotspots were also visualized to support interpretation.

**Key terms:** hotspot analysis, spatiotemporal data, grid cells, 90th percentile, spatial autocorrelation, Getis-Ord Gi*


## Technologies Used

