# GEOSPATIAL--TEMPORAL-VISUALIZATION-OF-GROUND-WATER-DATA-ON-MAP-OF-INDIA
Objective 
➢ Visualize groundwater data on the map of India indicating water quality by region.
➢ Ascertain if the physicochemical parameters fall within the prescribed range for drinking water standards according to BIS/WHO.
Approach 
➢ Libraries used: GeoPandas, pandas, NumPy, folium, matplotlib, re, shapely, GeoJSON.
➢ Used three different datasets for visualization: Water quality data, state boundaries, and district boundaries
➢ EDA: data cleaning, conversion of latitude and longitude coordinates in a standard format, create water geodata frame.
➢ Cluster formation by safe drinking levels (BIS/WHO) for different colors (green, yellow, blue, red…).
➢ For map of India, state, and district boundaries with different width and different colour.
➢ Visualize water quality clusters as Geospatial heatmap on map of India using BIS/WHO guidelines.
➢ Temporal variation plot, Google Maps plot for enhanced display
ResultS
➢ Results show high arsenic (Tripura, Assam, Arunachal Pradesh, Meghalaya etc.), high acidic (Kerala, Maharashtra, Tamil Nadu
etc.), high sodium (AP, Rajasthan, Gujarat), high fluoride (Rajasthan, Karnataka) We also identified high concentration regions
for other 19 physicochemical parameters, Google map displays drinkable status popup.
