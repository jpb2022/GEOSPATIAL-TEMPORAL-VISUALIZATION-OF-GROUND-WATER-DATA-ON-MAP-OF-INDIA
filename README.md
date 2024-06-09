# GEOSPATIAL--TEMPORAL-VISUALIZATION-OF-GROUND-WATER-DATA-ON-MAP-OF-INDIA

About Dataset:
water sample data collected across India from 2010 to 2018 by a government organization. It contains two main types of information. The first type includes geographical details such as site ID, state name, latitude and longitude values, district name, and block name. The second type encompasses water quality parameters, listing values for Total Dissolved Solids (TDS), sulphate, calcium, arsenic, fluoride, iron, and 17 other chemical components. This extensive dataset serves as a crucial resource for analyzing the water quality across different regions of India over the specified period, providing valuable insights for environmental monitoring and public health initiatives.


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
