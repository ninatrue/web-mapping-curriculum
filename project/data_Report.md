1.	Problem: Non-local Homebuyers and renters in Austin, Texas do not know about neighborhood pricing distributions or local amenities. These factors are important for making a living decision buyers and renters can be happy with long-term. 

2.	Objective: Provide an interactive map for home buyers and renters in Austin, TX. This map will provide both an overview of Austin neighborhood pricing distribution and local amenities clusters as well as detailed information about amenities near a specific address. This map will help people choose neighborhoods that fit their budget and lifestyle and see if specific addresses fit their requirements.   

3.	Data


Austin Neighborhoods: 

Aquired from Zillow 

This data includes shapefiles of neighborhoods. It is joined with Zillow Estimated Home Values. This will aid in displaying 
      the most expensive neighborhoods in Austin. When displayed as a chloropleth map, the user can quickly see where the most         expensive neighborhoods are in Austin. A legend will also help the user determine where neighborhoods are in their price
      range. 


Breweries:

Download and filtered from OSM data using QGIS Plugin 

Data was clipped to Travis and Round Rock County 


Farmers Markets: 

download and filtered from OSM data using QGIS Plugin

Data was clipped to Travis and Round Rock County 


Ultimate Frisbee Leagues: 

frisbee leagues researched and locatiosn converted to geojson in QGIS 
 

Climbing Gyms:
  




4. Methodology: 

Austin neighborhoods need to be joined with neighborhood pricing data 

Neighborhoods will be displayed as a choropleth map 

When a neighborhood is selected, a popup will appear with name and average home price 

Breweries, Farmers Markets, and Frisbee Leagues can be selected from a layer pane 

When a layer is selected from the layer pane: 

When an individual amenity is clicked, the name of the amenity will appear as a popup 

A search bar will be included if a user is interested in finding a specific address 

When the address is located information will appear on how many amenities are withing a 5 mile radius 


