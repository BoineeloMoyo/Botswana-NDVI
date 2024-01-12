# NDVI Time Series Analysis - Botswana
This repository contains a script for conducting an annual animated NDVI (Normalized Difference Vegetation Index) analysis in Botswana using Google Earth Engine (GEE) using the [MODIS Terra Vegetation Indices 16-Day Global 1km dataset](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD13A2). NDVI is a key indicator of vegetation health and can provide valuable insights into environmental changes over time

![ndviBW](https://github.com/BoineeloMoyo/-30DayMapChallenge_2023/blob/main/Challenge_Material/Day-26_Minimal/NDVI.gif)

## What you will need first

### 1. Define Area of Interest (AOI):
To initiate the analysis, it is imperative to accurately delineate the Area of Interest (AOI) or study area. The recommended method for country-level analysis involves the upload of a boundary shapefile into Google Earth Engine

### 2. Define Geometry Level Point:
Establishing a geometry level point is crucial for serving as the spatial reference point for animated monthly information.
Example:
```
var geometryLabel: Point (23.52,-17.30)
type: Point
coordinates: [23.524982828900136,-17.309520044478152]
```

### 3. Define Geometry Gradient Bar:
To enhance the visual representation of the analysis, specify a geometry gradient bar. This serves both as a spatial reference point and determines the size of the gradient legend.

Example snippet:
```
var geomeyGradientBar: Polygon, 4 vertices
type: Polygon
coordinates: List (1 element)
0: List (5 elements)
0: [22.87678946952514,-26.500852964941146]
1: [27.073566813275136,-26.500852964941146]
2: [27.073566813275136,-26.02795337316033]
3: [22.87678946952514,-26.02795337316033]
4: [22.87678946952514,-26.500852964941146]
```


### Contributing
Contributions to this project are welcomed

### License
This project is licensed under the MIT License. Refer to the LICENSE file for details.

### Acknowledgments
Massive gratitude to Google Earth Engine for providing powerful geospatial analysis tools.
