# WATER-DETECTION-USING-GEE
Google Earth Engine (GEE) is a powerful cloud-based platform that allows for the analysis of large geospatial datasets. One of the applications of GEE is water detection, which can be achieved using different techniques and satellite imagery.
# Water Detection Using NDWI 
Using Sentinel-2 multispectral optical images and Google Earth Engine to detect water The Normalized Difference Water Index¹ or NDWI is a method that helps us delineate open water and enhance its presence in remotely-sensed images. It achieves this by using the near-infrared (NIR) and green spectral bands. We can calculate NDWI as follows:

![image](https://user-images.githubusercontent.com/97274882/230666582-1453aa8f-3cff-4d51-85d3-9a1befb96d32.png)
 
NDWI helps us differentiate between open water and soil based on the three facts:
Water reflects the green light.
Water has low reflectance of NIR light.
Terrestrial vegetation and soil have a high reflectance of NIR.
The results of the NDWI index will range from -1 to +1. Water features will have positive values, while soil and terrestrial vegetation have zero or negative values because they typically have a higher reflectance of NIR than green light.
