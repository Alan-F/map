# map and data
> for [Museum Time Machine](https://github.com/amnh/HackTheStacks/wiki/Museum-Time-Machine) challenge. Slides: [here](https://docs.google.com/presentation/d/1Uzc0dj9mUH_LvWRbEHbbAUrSSGk0kKQcZj2ql3nLtsg/edit?usp=sharing) 

> Sources used: [PH_all_floors.csv](https://github.com/amnh/HackTheStacks/blob/master/challenges/Museum_Time_Machine/data/PH_all_floors.csv) , [Permanent-Halls_FINAL_floors-sections.xls](http://images.library.amnh.org/hiddencollections/resources/amnh-permanent-halls/)


### index.html
leaflet map of the data

### floorplan.tif 
geotiff of the floorplan 

### ./section 
shape files & geojson - rough outline of sections

| column name         | description          
| ------------- |:-------------:| 
| section | the section |  
| alias[1] | other names for that section | 

### arc.csv
recordId, Names used in AMNH publications, useDates

## merge.csv
geometry, section, year, floor, hall name
