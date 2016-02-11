#Election Stats and Map

Repo for Ipython notebook recreating election stats including DPI and Dem base similar to data from NCEC.  Created using election returns from MN SOS.

The results map shows steps to create a heatmap in the notebook using the returns from 2014.

TO DO:
Add pop-up to map districts - this will need to be done in the HTML since folium cannot create popups for the polygons in the shapefile.
Create a sql database for the final results dataframe and the results for each year
Try using LeafletR to create an interactive map for the results