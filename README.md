# atl_energy
Atlanta efficiency data

"""
This notebook provides tools for extracting, cleaning amd geocoding
data that is publicly available on the Atlanta building efficiency website at
https://atlantabuildingefficiency.com/benchmarking-data/

The output is a CSV file wih latitude and longitudes for each building
in the database shown on that site

Note that the geocoding process can take several minutes and throw
several exceptions, but it will complete correctly as long as you have 
a proper API key for the geocoding service you are using

I welcome all help and suggestions for improvements.
Please send any to david@buildpayer.com

"""
