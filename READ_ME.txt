1. What this project does:

It contains an ArcGIS notebook (.ipynb file) with 2 input shape files for running a spatial analysis to investigate historical changes over time in 2 indices of spectral reflectance in the Peel-Harvey estuary, Western Australia. It does not include the input raster files, however these can be obtained online if desired. The raster files are raw satellite images captured by Landsat 5 TM in March, July, September, and December of 1988 and 1996 (Bands 1-4).

The script can also (perhaps more conveniently) be viewed in the PDF file.

2. Why this project is useful (PURPOSE):

I've prepared this material for a student assignment, and these files are required to be accessible for assessment purposes. The main document for the assignment is an ESRI StoryMap, which I may decide to make publicly available, once it has been assessed. I will be providing an embedded link within that StoryMap to this GitHub content.

I wanted to investigate if a specific intervention (man-made channel) done to address water quality issues in an estuary actually impacted water quality, and how so. The channel was constructed over the period 1990-1994. I looked at images at time points (in March, July, September, December) before (1988) and after (1996) this period to assess change. This is very simplistic, and has been limited by the time constraints available to do this desktop study. 

Please note that this assignment has not been assessed yet, and that I am relatively new to ArcGIS Pro and GitHub, and still have much to learn about these topics.

Importantly, please also note that any observed changes in spectral reflectance are just that, and do not necessarily reflect historical changes in the water quality. One would need to have collected and assessed ground-truth information to determine to what extent changes in these satellite data did reflect actual changes in the water quality.

3. How users can get started:

Apologies, but I have not intended for this project to be used by others at this stage (except to those assessing my assignment).

4. This repository contains:

1) an ArcGIS notebook containing Python code (with file extension .ipynb) 
2) a PDF file, which is an electronic printed copy of the notebook script
3) a shapefile, including the polygon area of interest (AOI.shp)
4) a shapefile, including the 100 points randomly selected within that AOI (randompts.shp).

The shapefiles are each comprised of several separate files, and all need to be saved together in the same directory in order to be available to the GIS software (ArcGIS Pro). You will need to have a license to access ArcGIS Pro software.

5. Additional information.

These materials are for a student project that I have enrolled in at the University of Western Australia.
I wish to share these materials, to accompany those that I have submitted for a university assessment, which is primarily an ESRI StoryMap. 

The project is titled "Historical impacts of a channel on estuarine water quality".
I may decide to make the link to the StoryMap publicly available after this assignment has been assessed.

Ross Marriott.

email: ross.marriott@iinet.net.au