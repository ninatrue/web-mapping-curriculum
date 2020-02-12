_Respond to writing prompts here..._
Objects recap

An object is a series of ____’s : ____’s

Objects are key value pairs. 

What kinds of things can be included in an object?

They can be anything like arrrays, variables, strings, or other objects. 


Intro to “client-side”

What does client-side rendering mean in the context of web maps?

Rendering maps in the browser (client-side rendering), rather than on the server, make it possible to change the map's style and the data it displays in response to user interaction. You can make interactive maps! In web apps using Mapbox GL JS, maps are rendered dynamically using by combining vector tiles with style rules. 

Why is it possible for Mapbox GL JS to place labels dynamically as you interact with the map?

Dynamic label placement is possible because of client-side rendering. It recomputes 60x per second. Crazy!


Jurisdiction finder recap For the following 3 prompts, reference the working file and README.md in the jurisdiction finder explanation folder in the main class repo.

Describe how feature gets to the makeFeatureLabel() function.

When a user clicks on the map, the list of features selected is looped through to get each feature's HTML formatted. 
Given a feature, the makeFeatureLabel() function translates bewteen a feature's corresponding map layer and returns a more readable name. 

What does the getDistrictNumber() function do?

Given a feature, this function translates between the corresponding map layer and the appropriate district id attribute name and returns the district's ID number. 

Looking at the callback to map.on('click',...), what is e and why do we need it?

THe e is an event object and contains event data. It is passed to the event handler. In this case, the clicked features are passed through the function. 

