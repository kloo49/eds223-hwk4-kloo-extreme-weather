# Identifying the impacts of extreme weather
EDS 223 Homework Assignment 4 

[Assignment Link](https://eds-223-geospatial.github.io/assignments/HW4.html)

Texas suffered three severe winter storms in 2021 on February 10-11, 13-17, and 15-20.

In this assignment, we evaluate impacts of the winter storms by estimating the number of homes and areas in the Houston metropolitan area that lost power. We use remotely-sensed night lights data from the Visible Infrared Imaging Radiometer Suite (VIIRS) on the Suomi satellite, distributed via NASA's **LAADS DAAC**. We use building and roads data from **OpenStreetMap**.

We have two datasets from VIIRS, one before the storm (Feb 7) and one after (Feb 16).

## Repo Structure

```
eds223-hwk4-kloo-extreme-weather  
├── .gitignore
│   └── data                                                       # folder for the raw data
│      ├── gis_osm_buildings_a_free_1.gpkg                         # EJ dataset
│      ├── gis_osm_roads_free_1.gpkg                               # Roads dataset
│      └── VNP46A1                                                 # VIIRS dataset
│            ├── VNP46A1.A2021038.h08v05.001.2021039064328.tif # tile h08v05, collected on 2021-02-07
│            ├── VNP46A1.A2021038.h08v06.001.2021039064329.tif # tile h08v06, collected on 2021-02-07

│            ├── VNP46A1.A2021047.h08v05.001.2021048091106.tif # tile h08v05, collected on 2021-02-16
│            └── VNP46A1.A2021047.h08v06.001.2021048091105.tif # tile h08v06, collected on 2021-02-16
├── texas-blackout.pdf                                             # pdf version of the assignment
├── texas-blackout.qmd                                             # quarto version of the assignment
└── README.md                                                      # readme documentation
```

## Contributors
Author: Kelly Loo\
Instructor: Annie Adams\
Teaching Assistant: Mary Salami