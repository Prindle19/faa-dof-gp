faa-dof-gp
==========

This library provides the ability to read the [Federal Aviation Administration (FAA) Terrain and Obstacles Data (TOD) Team - Digital Obstacle File (DOF) files](http://tod.faa.gov/tod/public/TOD_DOF.html).

## Dependencies ##

* ArcGIS Desktop must be installed on computer.  (Having just ArcGIS Server instead of ArcGIS Desktop may also work, but has not been tested.)
* ArcView license level should be sufficient.

## Modules ##

### faadof.py ###
Provides utilities for importing FAA DOF data into a geodatabase.

### remotezip.py ###
Reads remote ZIP files using HTTP range requests.
Code [posted on StackOverflow](http://stackoverflow.com/a/7843535) by [Jo�o Pinto](http://stackoverflow.com/users/401041/joao-pinto).


## Licensing ##
Licensed under the [CC BY-SA 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/).