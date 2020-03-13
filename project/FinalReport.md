Project description: 
An interactive map to inform homebuyers in Austin, TX of housing price distributions and local amenities. 

Problem statement: 
Non-local Homebuyers and renters in Austin, Texas do not know about neighborhood pricing distributions or local amenities. These factors are important for making a living decision buyers and renters can be happy with long-term. Visualizing neighborhood pricing distributions can help narrow housing searches and information about local amenities can help gauge interest in locations without ever having visited the place. This map can also provide valuable information for Austin locals who can visualize houses nearness to their favorite spots throughout the city. 

Objectives: 
Provide an interactive map for home buyers and renters in Austin, TX. This map will provide both an overview of Austin neighborhood pricing distribution and local amenities clusters as well as detailed information about amenities near a specific address. This map will help people choose neighborhoods that fit their budget and lifestyle and see if specific addresses fit their requirements. 

Intended Audience: 
Potential Homebuyers in Austin, Texas 

Data Report: 
1.	Austin Neighborhoods shapefile: This data includes shapefiles of neighborhoods in Austin, Texas. It is joined with 2019 mean Zillow Estimated Home Values. 4 neighborhoods with no estimated home value for 2019 were deleted. This will aid in displaying neighborhood price distributions in Austin. When displayed as a choropleth map, the user can quickly see where the most expensive neighborhoods are in Austin. A legend will also help the user determine where neighborhoods are in their price range. 
2.	Austin Breweries: Download and filtered from OSM data using QGIS Plugin. Data was clipped to Travis and Round Rock County. Popup will display Brewery name, hours, and website. List of breweries within a 1-mile radius will pop up when an address is searched.
3. Farmers’ Markets: Download and filtered from OSM data using QGIS Plugin. Data was clipped to Travis and Round Rock County. Popup will display Market name and website. List of markets within a 1-mile radius will pop up when an address is searched.
4.	Music Venues: Data from data.texas.gov. Filtered from a list of Arts and Cultural Facilities. Excel file was formatted with lat and long in seperate columns. Excel file uploaded onto QGIS and x,y fields assigned. Popup will display venue name, hours, and website. List of venues within a 1-mile radius will pop up when an address is searched.

Methodology: 

1. 	Add and display data layers: 
  a. Neighborhoods will be displayed as a choropleth map 
  b. Amenities will be displayed with corresponding icons 

2. 	Create legend of housing price choropleth 

3. Create Informational popups 

4.	Add hover effect to display neighborhood name and 2019 housing price when mouse hovers over neighborhood polygon 

5. Add geocoder (change zoom level after address is searched) 

6. Create a function to generate a list of local amenities when an address is searched

7. Style a sidebar to house list of local amenities 

8. Write an if/else statement to Change map display on zoom:  
a. remove choropleth map and corresponding legend 
b.	Style traffic layer in MapBox Studio
c.	Add traffic layer on zoom 

Issues: Adding amenity data so that it can be queried and an amenities list generated 

