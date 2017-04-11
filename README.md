## GBIF API Search

A web tool to search for occurrence records and time from GBIF by using the RESTFUL JSON based API (http://api.gbif.org/v1/)

## Getting Started

More information about the map API on http://www.gbif.org/developer/maps

```
var gbif = L.tileLayer('http://api.gbif.org/v1/map/density/tile?x={x}&y={y}&z={z}&type=TAXON&key=1&layer=OBS_NO_YEAR&layer=SP_NO_YEAR&layer=OTH_NO_YEAR&layer=OBS_1900_1910&layer=SP_1900_1910&layer=OTH_1900_1910&layer=OBS_1910_1920&layer=SP_1910_1920&layer=OTH_1910_1920&layer=OBS_1920_1930&layer=SP_1920_1930&layer=OTH_1920_1930&layer=OBS_1930_1940&layer=SP_1930_1940&layer=OTH_1930_1940&layer=OBS_1940_1950&layer=SP_1940_1950&layer=OTH_1940_1950&layer=OBS_1950_1960&layer=SP_1950_1960&layer=OTH_1950_1960&layer=OBS_1960_1970&layer=SP_1960_1970&layer=OTH_1960_1970&layer=OBS_1970_1980&layer=SP_1970_1980&layer=OTH_1970_1980&layer=OBS_1980_1990&layer=SP_1980_1990&layer=OTH_1980_1990&layer=OBS_1990_2000&layer=SP_1990_2000&layer=OTH_1990_2000&layer=OBS_2000_2010&layer=SP_2000_2010&layer=OTH_2000_2010&layer=OBS_2010_2020&layer=SP_2010_2020&layer=OTH_2010_2020&layer=LIVING&layer=FOSSIL&palette=yellows_reds');

```

More information about the occurrence search on http://www.gbif.org/developer/occurrence

```

http://api.gbif.org/v1/occurrence/search?year=1800,1899

```

## What is GBIF

A short description of the Global Biodiversity Information Facility (GBIF) from the official webpage http://www.gbif.org

```
The Global Biodiversity Information Facility (GBIF) is an international 
open data infrastructure, funded by governments.

It allows anyone, anywhere to access data about all types of life on Earth, 
shared across national boundaries via the Internet.

By encouraging and helping institutions to publish data according to common standards, 
GBIF enables research not possible before, and informs better decisions to conserve 
and sustainably use the biological resources of the planet.

GBIF operates through a network of nodes, coordinating the biodiversity information 
facilities of Participant countries and organizations, collaborating with each other 
and the Secretariat to share skills, experiences and technical capacity.

```

## Built With

* [GBIF API](http://www.gbif.org/developer/summary) - GBIF Webservice API v1
* [Leaflet JS](http://leafletjs.com/) - Leaflet JS
* [Mapbox JS API](https://www.mapbox.com/mapbox-gl-js/example/mapbox-gl-geocoder/) - Mapbox Geocoding API
* [Bootstrap](http://getbootstrap.com/) - HTML, CSS, JS web framework

## Demo

See a [Demo](http://rawgit.com/ChristianLanger/GBIF-API/master/index.html) for details

