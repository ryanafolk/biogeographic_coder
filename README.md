# Biogeographic Coder
This code was written as a solution to address some inefficient and inflexible code I encountered in 2017 when designing a biogeographic study. The code is designed to be high-throughput for thousands of species each with hundreds or thousands of occurrences, and to efficiently load shape files of arbitrary complexity.

To those planning to use the script: The output is unformatted shapefile metadata. You will need to use some simple search-and-replace functions to turn these into a neater alphanumeric coding.

For input data, both occurrence records and shapefiles should already be ESRI shapefiles. Conversion can be done with GDAL tools. The script is for Python3 and uses the following dependences:
#ogr
#fiona 
#shapely
#rtree
