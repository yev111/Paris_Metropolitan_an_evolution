# Paris Metropolitan, an evolution
## Introduction
This page contains the different components, from original maps to python notebooks, that enabled to achieve the project 'Paris Metropolitan, an evolution' made in the context of the course 'Foundation to Digital Humanities' at the EPFL.
The goal of this project was to extract information from three old maps displaying the Metropolitan of Paris at three different years, 1908, 1915 and 1950. See more info about the project on http://fdh.epfl.ch/index.php/Paris_Metropolitan,_an_evolution

## The different components
### Maps
The folder contains the three source maps in .png format we have used for this project. All maps belongs to BnF.
  * `1908 - Paris Metro Map.png [One of the first Paris Metropolitan Maps after the construction of the first six lines]`
  * `1915 - Paris Metro Map.png [Map displaying all Metropolitan stations up until 1915]`
  * `1950 - Paris Metro Map.png [Map displaying the evolution of the Paris Metropolitan after going through WWI and WWII]`

### Database
The folder contains the database generated from the extracted information of the three maps. The database is available in three formats: .geojson, .csv, .xlsx. For more information on how the database can be used, see http://fdh.epfl.ch/index.php/Paris_Metropolitan,_an_evolution#Creation_of_a_database
  * `paris_metropolitan_an_evolution_lines.geojson [Database in GeoJSON format of all the Paris Metropolitan lines until 1950]`
  * `paris_metropolitan_evolution_db.geojson [Database in GeoJSON format of all the Paris Metropolitan stations up until 1950]`
  * `paris_metropolitan_evolution_db_updated.geojson [Database in GeoJSON format of all the Paris Metropolitan stations up until 1950 with historical information added to specific Metro stations]`

### Notebooks
The following Jupyter notebooks contributed as helpers to extract information from external sources, create the new database, and input the database into the website.
  * `Paris Metropolitan GeoJSON functions.ipynb [Helper notebook to extract information from the RATP GeoJSON and insert it into the database]`
  * `maps_generator.ipynb [Helper notebook to generate two from the three maps that were used for the website]`
  * `geojson_to_csv.ipynb [Helper notebook to include changes made on the geojson format database to the csv one]`

### QGIS
The folder contains the main .gqz file and other shapefiles and .tiff rasters used for the project. However, it was not possible to upload all files due to their big size.

### Website
The folder contains the different .html, .css and .js files that were generated to create the following website that displays the work done based on the database: http://valentinebernasconi.ch/paris_metropolitan/index.html

### External sources
External sources that contributed to the project's making and its database.
  * `positions-geographiques-des-stations-du-reseau-ratp.geojson [The official GeoJSON database from RATP with the current public transportation system of Paris, including Metro, Bus, and RER]`
  * `emplacement-des-gares-idf.geojson [The official GeoJSON database from the Région Île-de-France departement with the curent geolocation of metropolitan stations]`
  * `Paris_Plan_Metro.pdf [Current Map of the Parisian public transportation system]`

## Authors
  * Valentine Bernasconi - valentine.bernasconi@epfl.ch
  * Evgeniy Chervonenko - evgeniy.chervonenko@epfl.ch
