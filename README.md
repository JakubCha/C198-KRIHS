# C198-KRIHS

## Description
This project contains models and tools for QGIS (v3.12.2) to import layers and tables into PostGIS from a geopackage 
and the ESRI xml Workspace definition.


## Data

### gpkg-specifications.xsd 
This is the schema defining the ESRI xml Workspace of a geodatabase

### CONP.xml
Workspace definition of the CONP geodatabase

### UNMAP.xml
Workspace definition of the UNMAP geodatabase


## Scripts
This folder contains the python scripts used to:
- create domains tables and load their data
- create feature classes with subtypes (via declarative partitioning in PG) and load their features

### import_domains.py


## Models
This folder contains the model (*.model3) to use to create database structure for:
- domains table
- feature class (with subtypes)



