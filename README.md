# Discovering Urbanization Patterns through Unsupervised Learning
### A Geostatistical Approach for Mexico City

## Overview
This repository contains notebooks and resources for a geostatistical study of Mexico City using unsupervised learning techniques. The project applies clustering algorithms (K-Means, DBSCAN, Hierarchical Clustering) to demographic and economic entropy variables, aiming to uncover spatial patterns of urbanization.

## Methodology
- **Data Sources**: INEGI datasets (Population and Housing Census 2020, DENUE, Geostatistical Framework).
- **Pipeline**: Implemented in Databricks using a Medallion Architecture (Bronze, Silver, Gold layers).
- **Clustering Algorithms**:  
  - K-Means (partition-based)  
  - DBSCAN (density-based with noise detection)  
  - Hierarchical Clustering (Ward’s method)  
- **Validation**: Silhouette Score for structural consistency.

## Results
- **Urban Polygon Maps**: Visualization of territorial heterogeneity.  
- **Dendrograms**: Identification of compact vs. dispersed urban areas.  
- **PCA Comparisons**: Projection of clusters in principal component space.  
- **Relative Profiles**: Cluster differences across key variables (urban density, net density, economic entropy, adult population).

## Future Work
- Extend methodology to other metropolitan areas.  
- Incorporate temporal datasets to analyze dynamic urban growth.  

## Author
Jaime Alberto Suárez Moctezuma  
📧 suarezjaime2712@gmail.com  

## Acknowledgment
ChatGPT (OpenAI) was used to support language refinement and manuscript organization. All research design, methodology, data processing, analysis, and conclusions were developed solely by the author.
