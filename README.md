# occcube
to create an sqlite database from an occurrence cube file

An occupancy datacube for a country can be made using the R scripts in https://github.com/trias-project/occ-processing
This produces a text file of the data cube for each species, year and km2.
To efficiently query it in scripts it can be loaded into a SQLite database file (https://www.sqlite.org/index.html).
