# kuje-precision-agriculture-gis
A remote sensing and GIS project for precision agriculture among small-scale farmers in Kuje Area Council, FCT, Abuja, Nigeria.
# Precision Agriculture Using Remote Sensing and GIS in Kuje Area Council, FCT, Abuja

## 1. Project Overview

This project explores how remote sensing and Geographic Information Systems (GIS) can support precision agriculture for small-scale farmers in Kuje Area Council, Federal Capital Territory, Abuja, Nigeria. It uses open-source geospatial datasets and satellite imagery to assess vegetation conditions, map agricultural areas and provide spatial information to support agricultural planning.

## 2. Spatial Research Question

How can remote sensing and GIS be used to identify and map agricultural areas and assess vegetation conditions to support precision agriculture for small-scale farmers in Kuje Area Council, FCT, Abuja?

## 3. Study Area

The study area is Kuje Area Council, located in the Federal Capital Territory, Abuja, Nigeria. The project focuses on agricultural land, vegetation conditions, accessibility and the surrounding population.

## 4. Project Objectives

* Map the study area using administrative boundary data.
* Use satellite imagery to assess vegetation conditions.
* Identify and map relevant agricultural areas.
* Examine the spatial distribution of roads, settlements and population.
* Demonstrate how GIS-based information can support agricultural planning.

## 5. Datasets and Sources

| Dataset                             | Purpose                                    | Source                                            |
| ----------------------------------- | ------------------------------------------ | ------------------------------------------------- |
| Kuje administrative boundary        | Delineation of the study area              | https://www.geoboundaries.org/                    |
| Sentinel-2 satellite imagery        | Vegetation assessment and land observation | https://dataspace.copernicus.eu/                  |
| OpenStreetMap roads and settlements | Accessibility and settlement mapping       | https://download.geofabrik.de/africa/nigeria.html |
| WorldPop population data            | Population distribution analysis           | https://www.worldpop.org/                         |

All datasets will be checked for spatial coverage, date, coordinate reference system, resolution and licensing before analysis.

## 6. Methodology

1. Acquire the required open-source geospatial datasets.
2. Review dataset metadata and assess data quality.
3. Load the datasets into QGIS.
4. Reproject the datasets to a suitable coordinate reference system.
5. Clip the relevant spatial layers to the Kuje study boundary.
6. Process Sentinel-2 imagery and calculate the Normalized Difference Vegetation Index (NDVI).
7. Integrate the vegetation results with roads, settlements and population data.
8. Prepare maps and interpret the results in relation to precision agriculture.

## 7. Software and Tools

* QGIS
* QuickOSM plugin
* Copernicus Data Space
* Open-source geospatial datasets

## 8. Expected Outputs

* Study area location map
* Vegetation condition map
* Roads and settlements map
* Population distribution map
* GIS project files and a brief spatial analysis

## 9. Coordinate Reference System

WGS 84 / UTM zone 32N (EPSG:32632) will be used for suitable projected spatial analysis, subject to checking the source datasets and study area coverage.

## 10. Limitations

Satellite-derived vegetation indices do not independently confirm crop type, yield or farm ownership. Results will depend on image dates, cloud cover, spatial resolution and the quality and coverage of the available datasets. Field validation would be required for stronger conclusions about specific farms.

## 11. Project Status

This repository contains the project brief, dataset sources and documentation. GIS processing and map outputs will be added as the project progresses.

## 12. Author

Hauwa Saleh Hassan
Agricultural Applications and Spatial Data Analyst
National Space Research and Development Agency (NASRDA), Abuja, Nigeria
