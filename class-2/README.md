### Content for class 2. 

Class presentation materials are on [Google Drive here](https://docs.google.com/presentation/d/1nNNup7iSOsG-xhoxhEWfkNDnwiH74qQ1BbSGji2ql_4/edit#slide=id.g643643ac23_0_34)

__Homework__

For your class journal:

1. What is the difference between raster and vector data?

Rasters are like pictures, they are created and served on the browser. Vector data are points, lines, and polygons stored in x,y coordinates. Vector data can be converted into vector tiles and are combined with CartoCSS styles and stored on the server and are rendered as the final step- which makes loading super fast! 


2. Why do "slippy maps" exist?

Slippy maps make it easier to scroll around a location to see just what is outside of the viewer without loading a whole new page. This is made possible with map tiles. In slippy maps, only the tiles that are on your screen are loaded (and some right outside the screen for faster scrolling around). 

3. Why would you want to install a dedicated text editor?

Text editors provide a user interface to make coding easier. Text editors may use a color code for certain functions that could make trouble shooting and debugging easier and making code easier to follow along in general. 

4. What is Leaflet?

Leaflet is a JavaScript library used to build interactive maps.

5. How has web map rendering changed over the years?

Early web maps were static maps (not slippy!, they could not pan without loading a whole new web page). Tiling changed the user's ability to pan maps by selecting an extent and loading enough tiles to make the map (and some tiles just outside for easy panning). Finally, vector tiles separate data storage from map rendering by only storing data and how a how a map should look and rendering at the very end.

6. What is the basemap-overlay paradigm and how are GL maps different?

In most modern maps, basemaps are overlaid with data layers. This is being changed by vector tiles that are created from vector data. This allows maps to be rendered on the fly and allows for easy updating of map tiles. 


Exercises to do on your own:

1. Keep learning! Try one more of the Web apps tutorials on the [Mapbox help page](https://docs.mapbox.com/help/tutorials/#web-apps) and submit your completed tutorial to your GitHub project.

Submitted under projects 

2. Head to the [Mapbox GL JS examples page](https://docs.mapbox.com/mapbox-gl-js/examples/) and pick two examples under the user interactions section. What kind of interactions do you see? Why might you use each of those interactions?

 a)"Create draggable Marker" - user can drag a marker and get coordinates. Users might find this helpful when looking at a map of green space, wild lands, trails, natioanl parks, etc. where there are no addresss. 

b) "Filter symbols by text input" user can type in a feature class and only symbols of that feature class will be displayed. This is helpful if a user is looking for a certain type of attraction with a city. They can search "coffee shops" and the map will filter out everything but "coffee shops". 


3. If you didn’t finish the “code together” exercise, please do so before next week.


__Project__

Choose a project idea and open an issue in your GitHub repo describing what it is. Your description should include:

1. The topic you will focus on (one of: housing and homelessness, wildfires, or fracking.)
2. A description of your audience.
3. At least three questions you hope to be able to answer for your audience.

__Additional learning materials__
