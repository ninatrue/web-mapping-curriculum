1.	Problem: Non-local Homebuyers and renters in Austin, Texas do not know about neighborhood pricing distributions or local amenities. These factors are important for making a living decision buyers and renters can be happy with long-term. 

2.	Objective: Provide an interactive map for home buyers and renters in Austin, TX. This map will provide both an overview of Austin neighborhood pricing distribution and local amenities clusters as well as detailed information about amenities near a specific address. This map will help people choose neighborhoods that fit their budget and lifestyle and see if specific addresses fit their requirements.   

3.	Data


Austin Neighborhoods: 

Aquired from Zillow 

This data includes shapefiles of neighborhoods. It is joined with 2019 mean Zillow Estimated Home Values. 4 neighborhoods with no estimated home value for 2019 were deleted. This will aid in displaying 
      the most expensive neighborhoods in Austin. When displayed as a chloropleth map, the user can quickly see where the most         expensive neighborhoods are in Austin. A legend will also help the user determine where neighborhoods are in their price
      range. 


Breweries:

Download and filtered from OSM data using QGIS Plugin 

Data was clipped to Travis and Round Rock County 

This data will help potential home buyers visualize where points of interest are. 


Farmers Markets: 

download and filtered from OSM data using QGIS Plugin

Data was clipped to Travis and Round Rock County 

This data will help potential home buyers visualize where points of interest are. 


Ultimate Frisbee Leagues: 

frisbee leagues researched and locatiosn converted to geojson in QGIS 

This data will help potential home buyers visualize where points of interest are. 


Music Venues: 

Data from data.texas.gov. Filtered from a list of Arts and Cultural Facilities. Excel file was formatted with lat and long in seperate columns. Excel file uploaded onto QGIS and x,y fields assigned. 

Austin Airport: 

Marker placed at Ausin Airport Coordinates 
 
4. Methodology: 

Austin neighborhoods need to be joined with neighborhood pricing data. 

Neighborhoods will be displayed as a choropleth map. 

When a neighborhood is hovered over, a popup will appear with neighborhood name and average home price 

Breweries, Farmers Markets, Music Venues and Frisbee Leagues can be selected for display from a layer pane 

When a layer is selected from the layer pane: the ammentities will apear as clusters or individual points based on zoom level. 

When an individual amenity is clicked, the name of the amenity will appear as a popup 

A search bar will be included if a user is interested in finding a specific address 

The search bar will drop a pin at searched location 

When the address is located information will appear on how many amenities are withing a 5 mile radius. 


