helbikes
========

A mobile-friendly map of bicycle shops in  in the greater Helsinki area. Click "Locate me" to zoom to where you are.

See the map:

 * http://bit.ly/helbikes

It uses:

 * [Leaflet](http://leafletjs.com)
 * [Leaflet GeoCSV plugin](https://github.com/joker-x/Leaflet.geoCSV), and the [bankia example](https://github.com/joker-x/Leaflet.geoCSV/tree/master/example)
 * Bike shop data originally from [Teemu Kalvas](http://www.s2.org/~chery/sport/cycling/bicycle-shops-greater-helsinki)

Corrections:

I made some updates to the bike shop list, but there will be some mistakes. Think of it as a guide. 
I got the latitude and longitude coordinates from each address using [GPS Visualizer](http://www.gpsvisualizer.com/geocoding.html). 
The map is made from [this .csv list of bike shops](https://github.com/hugovk/helbikes/blob/master/helbikes/bikeshops.csv), 
each with an address, optional notes, and latitude and longitude coordinates, each separated by a semicolon, like this:

    Action Factory;Tehtaankatu 25,00150 Helsinki;;60.157813;24.935847

If you spot a mistake, you can send a correction in one of these ways:

 * Update [bikeshops.csv](https://github.com/hugovk/helbikes/blob/master/helbikes/bikeshops.csv) and send a pull request;
 * Create a [new issue](https://github.com/hugovk/helbikes/issues); or
 * Tell me another way.
