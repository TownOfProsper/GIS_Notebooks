# GIS_Notebooks
A collection of Jupyter Notebooks for GIS processing tasks

* Contour_Enrichment.ipynb - This notebook takes a number of featureclasses created as a result of the spatial analyst Contour geoprocessing tool, enriches it using supplemental data, and performs a series of splits to segment the geometry by the geometry of the supplemental areas. Performs the operations using the "memory" workspace. Processing time depends on Contour density and area. 
    - Requires prerequisite data from the US National Grid (USNG) and the US Hydrological Unit Codes (HUC)
    - Requires the ArcPy library 
