# Paris Metropolitan, an evolution
## Introduction
This page contains the different components, from original maps to python notebooks, that enabled to achieve the project 'Paris Metropolitan, an evolution' made in the context of the course 'Foundation to Digital Humanities' at the EPFL.
The goal of this project was to extract information from three old maps displaying the Metropolitan of Paris at three different years, 1908, 1915 and 1950. See more info about the project on http://fdh.epfl.ch/index.php/Paris_Metropolitan,_an_evolution

## The different components
### Maps
The folder contains the three source maps in .png format we have used for this project. All maps belongs to BnF.
### Database
The folder contains the database generated from the extracted information of the three maps. The database is available in three format: .geojson, .csv, .xlsx. For more information on how the database can be used, see http://fdh.epfl.ch/index.php/Paris_Metropolitan,_an_evolution#Creation_of_a_database
### Notebooks
The following Jupyter notebooks contributed as helpers to extract information from external sources, create the new database, and input the database into the website.
  * #### Paris Metropolitan GeoJSON functions.ipynb
  	* `Helper notebook to extract information from the RATP GeoJSON and insert it into the database`

### QGIS
The folder contains the main .gqz file and other shapefiles and .tiff rasters used for the project. However, it was not possible to upload all files due to their big size.

### Website
The folder contains the different .html, .css and .js files that were generated to create the following website that displays the work done based on the database: http://valentinebernasconi.ch/paris_metropolitan/index.html
