# Create Lidar Derived Contours from USGS Lidar Data in ArcGIS Pro
Author: Langdon Sanders | GIS@dublin.oh.us December, 2023

Some template framework steps for common operations in creating lidar-derived contours from many .laz tiles downloaded from USGS site.  

You will need a data.txt file from USGS from your cart of lidar data as a starting point.  

This also uses our project level settings for the GIS products, i.e. 1ft contours; you'll need to adjust the last few steps for your needs, such as coordinate system, cell size for DEM, and contour interval.  



# Sections
* Download .laz files from a list of URLS (your cart from the USGS site)
* Convert them to .las
* Create a Las Dataset
* Create a Filter for Ground Only Points
* Create a Digital Elevation Model (DEM)
* Create Contours from DEM
* Export Contours as Shapefile
