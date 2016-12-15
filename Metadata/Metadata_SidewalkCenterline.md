# Sidewalk Centerline
Filename: SIDEWALK_LINE<br>Geometry Type: polyline<br><br>![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Sidewalk_ln.png)

### Table of Contents<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**1. Identification**](#1-identification)<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**2. Data Quality and Specifications**](#2-data-quality-and-specifications)<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**3. Attribute Information**](#3-attribute-information)<br><br>
## 1. Identification
---------------------------------------------
|     |     |
| --- | --- |
**Purpose** |This feature class is part of the planimetrics database used by the NYC DOITT GIS group to maintain and distribute an accurate 'basemap' for NYC. The basemap provides the foundation upon virtually all other geospatial data with New York. Digital planimetrics are derived using the imagery products delivered with the 2014 New York Statewide Flyover (see Summary for specific flight dates), which includes raw imagery collected to support the generation of 0.5 Ft Ground Sample Distance (GSD) natural color imagery. 
**Description** |This feature class contains Interior sidewalk centerlines for all interior sidewalk polygon features but not the ROW-Sidewalk. The business use of this feature is to identify potential areas, outside of the public Right of Way (ROW), that could permit emergency vehicles through travel.
**Source(s)** |Current imagery and previous planimetric database
**Publication Dates** |**Data**: 03/14/16<br>**Last Update**: 08/27/16<br>**Metadata**: 12/02/16<br>**Update Frequency**: As needed
**Available Formats** |File Geodatabase Feature Class as part of the Planimetrics geodatabase and individual shapefile on the [NYC Open Data Portal](https://data.cityofnewyork.us/dataset/Sidewalk-Centerline/a9xv-vek9)
**Use Limitations** |Open Data policies and restrictions apply. See [Terms of Use](http://www.nyc.gov/html/data/terms.html)
**Access Rights** |Public
**Contact Information** |**Name**: Colin Reilly, Director GIS Division, Department of Information Technology and Telecommunication (DOITT)<br>**Email**: creilly@doitt.nyc.gov
**Links** |https://data.cityofnewyork.us/dataset/Sidewalk-Centerline/a9xv-vek9
**Tags** |structure, Planimetric, Sidewalk, Basemap, Interior Sidewalk Centerline, imageryBaseMapsEarthCover, Landbase, transportation, NYCMap
## 2. Data Quality and Specifications
---------------------------------------------
|     |     |
| --- | --- |
**Horizontal Coordinate System** |New York State Plane Coordinates, Long Island East Zone, NAD83, US foot
**Resolution** |NA
**Spatial Coverage** |New York City, NY
**Temporal Coverage** |For this dataset, the source imagery was captured on the following dates:<br>Manhattan - June 24, 2014<br>The Bronx, Brooklyn, Queens and Staten Island  - April 1st through April 25th, 2014<br>Final delivery of all imagery - April 10, 2015<br>Using this orthoimagery, the planimetric base layers were updated citywide starting in March 2015 and were completed in February 2016.
**Positional Accuracy** |
**Features Captured** |These features represent interior sidewalk centerlines for all interior sidewalk polygon features (not for the ROW Sidewalk).
**Features Excluded** |Row sidewalks were excluded. 
**Capture and Update Notes** |The business use of this feature is to identify potential areas, outside of the public Right of Way (ROW), that could permit emergency vehicles through travel. Interior Sidewalk Centerlines were extended beyond the Interior Sidewalk Polygons when connecting to a CSCL feature.
## 3. Attribute Information
---------------------------------------------
| Attribute | Description | Field Type | Sensitive Field (Y/N) | Notes| 
|------------ | ------------- | -------- | ----------- | ----------|
| SOURCE_ID | Unique Feature Identification Number. | double | No
| FEATURE_CODE | Type of feature.<br>3810 = Interior Sidewalk Centerline | integer | No
| SUB_FEATURE_CODE | A subset of features within a given Feature_Code set:<br>381000 = Interior Sidewalk Centerline | integer | No
| STATUS | Field indicating the feature status as it fits into one of the following categories:<br>NEW = A feature captured for the first time during the 2014 planimetrics update project.<br>UPDATED = The feature existed previously but has been updated during the 2014 planimetrics update project.<br>UNCHANGED = The feature is unchanged from the source planimetrics database. | text | No