# Vector Atlas Project 
Tan Pei Hua (Hua)

## Overview
This project aims to understand the structure of spatial datasets from various sources and develop a detailed methodology for cleaning, filtering, and integrating the data. The goal is to analyse accessible online data, refine it into a complete dataset with a well-defined structure for further analysis, and ultimately generate a comprehensive map visualisation of the spatial distribution of vector species, with a primary focus on the Asian continent. This visualisation will be created using species occurrence data from multiple sources, including the Malaria Atlas R package, GBIF (Global Biodiversity Information Facility), and VectorBase.



## Table of contents
1. Project Guide
2. Data Sources
3. Data Cleaning Structure
4. Visualisation
5. Discussion


## Project Guide




## Data sources
- Malaria_Atlas_R (R packages) & RGBIF
- gbif_extracted_dataset.csv (GBIF Website)
- Samples.txt, Studies.txt, Collection_sites.txt (VectorBase)




## Data Cleaning structure
- Primary focus on leucosphyrus Anopheles and Dirus Anopheles
- Extract useful and common attributes between datasets for merging purposes
- Data standardisation (Decimal places, attribute's name, missing content, time & date)
- Remove NAs when necessary
- Use xtables to summarise categorical data




## Visualisation

1. Number of species collected from various sources and total number of occurrences  
![image](https://github.com/user-attachments/assets/6236460e-2b40-4f95-8cd9-b4add3dce555)

2. Spatial distribution for RGBIF data in the R package
![image](https://github.com/user-attachments/assets/0f2b6fc8-a3dc-4b40-97b3-1ccf4f821298)

3. Spatial distribution for GBIF data on the GBIF website
![image](https://github.com/user-attachments/assets/1f0da1cc-7fd0-44aa-bea8-511f1395102a)

4. Spatial distribution for VectorBase data 
![image](https://github.com/user-attachments/assets/0e413f22-3142-4ed2-8376-f5860870ac10)

5. Spatial distribution for combined data 
![image](https://github.com/user-attachments/assets/2cc585f0-b62a-4c1a-91a7-f2dd4e34e903)


Heatmap
![image](https://github.com/user-attachments/assets/7c054884-28e4-43c8-910a-b4ac9547fc66)


