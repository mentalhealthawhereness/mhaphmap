# MHAPh: Mental Health AWHEREness PH

Mental Health AWHEREness PH (MHAPh) is a volunteer-organized online platform and map that shows the locations of mental health facilities and services that offer help to people with their mental health within the Philippines.

Through this map, we hope that more people who are dealing with mental health issues would be encouraged to reach out and seek help.

### Project by:
- <a href="https://mentalhealthawhereness.com" target="_blank">Mental Health A-WHERE-ness PH, a non-profit, non-stock organization in the Philippines.</a>

Libraries used
-

* <a href="https://leafletjs.com" target="_blank">leaflet.js v1.4</a>
* <a href="https://www.mapbox.com/mapbox-studio/" target="_blank">Mapbox Studio</a>
* <a href="https://jquery.com" target="_blank">jquery.js v3.2.1</a>

Add or Update Mental Health Services on the Map
-

<a href="https://forms.gle/p1cNjNtF7ffg1mbu9" target="_blank">MHAPh form</a>

[![preview screenshot](/assets/guide.png)](https://)  
 <a href="https://mentalhealthawhereness.github.io/mhaph/assets/guide.png" target="blank">Uploading Guide</a> 

Database structure `places.json`
-

`id`: The exact filename of the MH service in <a href="https://en.wikipedia.org/wiki/Camel_case " target="_blank">CamelCase</a>.

`url / locationshare`: The url to the location on the map. This url will appear when the user zooms in to the location in the map and drops the locationshare pin on it then clicking "get url". When adding or updating a mental health service on the map, a contributor will be asked to provide this url.
[![locationshare](/assets/locationshare.png)](https://mentalhealthawhereness.github.io/mhaph/) 

`x`:   Latitude coordinate in decimal number

`y`:   Longitude coordinate in decimal number

`type`: The mh service types will be free or paid:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
