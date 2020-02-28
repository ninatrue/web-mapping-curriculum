Data prep and analysis

Find at least two web mapping examples that allow for user analysis. For each example provide: 1) a link to the web map and 2) a description of the user analysis


1. https://www.whatismissing.net/timelines This is a global map and timeline of animal species around the world that have either become or are in danger of becoming extinct. This map includes both a global map and a timeline view of these animal species. In both the map and timeline view you can select any of the individual markers to learn more about the individual endangered or extinct animal species

2. https://mangomap.com/global-mapper-sample-maps/maps/96931/Salmon-Habitat# User can analyze salmon habitat in Maine. User can toggle between habitat mapping year. User can identify which townships have the best habitat during which year 


Give an example of static data you might include on a web map. How is your example different from dynamic data?

Static data could be boundaries like counties, states, or countries. They can help orient the map user. Dynamic data needs to be analyzed just in time. 


Under what circumstances might you want to do some data prep in desktop GIS before incorporating data into your web map? Give an example of the type of data that might apply here.


Super large data sets can be prepped in desktop GIS. The map maker can clip and filter data. They can also delete data fields that are not needed for analysis. 

What are some data characteristics that can impact rendering speed? How might you address these issues?

Too many data fields, too big data. Fix the data in a desktop GIS first. 

What is turf.js? Give an example of how you could apply a turf operation to a web map.

Turf.js is an open source JavaScript library used for spatial analysis. It can be used to make buffers or count points in polygon. 


Inline writing prompts

Describe where the centroids variable comes from. How is it possible for you to reference this variable when you didn't declare it?

The centroids variable is linked in another script. We called on this script at the top. 

Why might you want to create the 'centroids-selected' layer after you've created the 'centroids' layer?

Centroids selected is a layer that holds the centroids inside the buffer that is created when we click. Centroids selected is a subset of centroids. 

Should you set the marker's lngLat and add it to the map? Why or why not?

No, the marker's lng lat will be decided upon user's click. 

How did you know which arguments to pass to the pip() function?

The documentation. 

