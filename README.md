# preprocess_matlab
This is a location for matlab code used to acquire and format data for a SnowModel run

1. GEE_to_snowmodel.m - this script will take output from Google Earth Engine and it will convert it to file formats needed for SnowModel. Please see the comments at the top of that file. 
2. arcgridwrite.m - this script is called by GEE_to_snowmodel.m for the purposes of writing out ESRI ASCII grids.
