1. What this project does:

It contains an ArcGIS notebook (.ipynb file) with 2 input shape files for running a spatial analysis to investigate historical changes over time in 2 indices of spectral reflectance in the Peel-Harvey estuary, Western Australia. It does not include the input raster files, however these can be obtained online if desired. The raster files are raw satellite images captured by Landsat 5 TM in March, July, September, and December of 1988 and 1996 (Bands 1-4).

The script can also (perhaps more conveniently) be viewed in the PDF file.

2. Why this project is useful (PURPOSE):

I've prepared this material for a student assignment, and these files are required to be accessible for assessment purposes. The main document for the assignment is an ESRI StoryMap. 
I provided an embedded link within that StoryMap to this GitHub content. 
The StoryMap presentation can be viewed at this URL: https://storymaps.arcgis.com/stories/7132fdded9de4d5e8e31a061d0f0051c

I wanted to investigate if a specific intervention (man-made channel) done to address water quality issues in an estuary actually impacted water quality, and how so. The channel was constructed over the period 1990-1994. I looked at images at time points (in March, July, September, December) before (1988) and after (1996) this period to assess change. 
This is somewhat of a simplistic analysis, does not include ground-truth validation, and has been limited by the time constraints available to do this desktop study. 

Importantly, this analysis is of spectral reflectance imagery only, done for the purposes of a student assignment, which has not been peer-reviewed or subject to ground-truth validation, so results must be treated with caution.

3. This repository contains:

1) an ArcGIS notebook containing Python code (with file extension .ipynb) 
2) a PDF file, which is an electronic printed copy of the notebook script
3) a shapefile, including the polygon area of interest (AOI.shp)
4) a shapefile, including the 100 points randomly selected within that AOI (randompts.shp).

The shapefiles are each comprised of several separate files, and all need to be saved together in the same directory in order to be available to the GIS software (ArcGIS Pro). You will need to have a license to access ArcGIS Pro software.

4. Additional information.

These materials are for a student project that I completed for my postgraduate studies at the University of Western Australia in October, 2024.
This material is intended to provide access to the Python script when viewing the StoryMap presentation. 

The project is titled "Historical impacts of a channel on estuarine water quality".

Ross Marriott.

email: ross.marriott@iinet.net.au
