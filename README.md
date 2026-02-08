# Harcourt Park – Refined Tributary Network

## This repository contains the refined tributary network and supporting geospatial data used to improve hydrological modelling for Harcourt Park, Ontario. The updated stream layers were created using DEM-based hydrological analysis and manual validation in QGIS.

 ### Contents
 
	•	hp_data/ — Original Harcourt Park datasets (boundary, wetlands, tributaries)
	•	refined_streams/ — DEM-derived and validated tributary network. 


 ### Project Summary


This work refines Harcourt Park’s existing tributary dataset by:

	•	Using a 10 m Ontario Integrated Hydrology DEM
  
	•	Applying sink filling, flow direction, and flow accumulation
  
	•	Extracting streams using accumulation thresholds
  
	•	Validating and correcting flow paths using orthophotos + wetland layer
  
	•	Preparing data for culvert risk assessment and watershed analysis

All files are projected to EPSG:2958 (NAD83 / UTM Zone 18N).

 ### Tools Used
 
	•	QGIS desktop
	•	GRASS GIS hydrology tools
	•	GeoPandas (Python) for basic spatial accuracy checks
	•	GeoPackage format for cross-platform consistency


  
