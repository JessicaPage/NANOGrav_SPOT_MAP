# NANOGrav_SPOT_MAP

The google map shown here: https://www.google.com/maps/d/u/0/viewer?mid=1U2eLXZ1GaEbHE5q_BGlJsoYeo_Q&ll=31.10647602832346%2C-100.28084975000002&z=4  
is an example of what we're trying to do. 
We want a circular placemarker for each location where a presentation was given, 
with the radius corresponding to how many students were reached at that location.

Circles.html is the progress made so far. It is not even close to correct. 

locations.csv is the data, with 'mag' being the number of people reached for that location.

locations.geojson is an attempt to put that data into a more html friendly format.

I have the google maps api key stored locally . We can just replace that variable with another.

ALTERNATIVELY, 

If you know php, I've included an example of how the varying radius was implemented in the given map example. 
I'm not sure how to use it or how to import the data in this language. It creates a kml file (similar to xml) that can be simply uploaded to 
a google map.

Here's what I manually made in google maps that does not vary the circle radius, but includes the NANOGrav institutions. 
https://www.google.com/maps/d/edit?mid=17TA2ZQHsYLSJNLbOYb0e9hgUAt4&ll=14.892277280221354%2C-100.39199239999994&z=3
The kml file generated from that can be downloaded there

We would eventually want to update the map every time we have a new presentation, 
but the map generation should be enough for now.

If there's any confusion my email is jp0089@uah.edu
