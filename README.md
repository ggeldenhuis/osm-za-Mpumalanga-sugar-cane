osm-za-Mpumalanga-sugar-cane
============================

Sugar Cane Farms

The primary aim of this repository is to enable collaboration between interested parties for importing sugar cane farming data from Mpumalanga into OpenStreetMap.
The secondary aim is to facilitate and document the data transformation process and importing steps for inclusion into OSM

Pre-requisite reading
* http://wiki.openstreetmap.org/wiki/Import/Guidelines

Current interested parties
* Gerhardus Geldenhuis (GG)
* Grant Slater (GS)
* Christoff Pretorius (CP)

List of things to do in no particular order:
* Analyse data for consistancy and any possible problems.
* Write conversion script to convert shp to josm file.
* Determine fields we want to keep.
* Determine a uniqueid to indentify data with to allow us to find and update existing data in OSM.
* Determine tags we want to use for importing the data.
* Create OSM import account.
* Once data is imported update this page: http://wiki.openstreetmap.org/wiki/Import/Catalogue
* Obtain permission from data source in writing and forward email to OSM-ZA mailing list.
* Update http://wiki.openstreetmap.org/wiki/Contributors once data is imported if the data provider is willing.
* Make raw data available to a wider audience.
* Investigate custom rendering to display sugar cane as a crop distinctly.

Preliminary data analysis
* There is some strange artifacts when zoomed in on the data. Do we feed this back to the supplier or fix and move on?
* There is a number of "bridges" between pieces of land. This seems a bit abritary. Why? and dow we keep it?

Considerations for data inclusion
* Needs to be easily maintainable by other OSM users.

Tags
* landuse=farmland ( In favour of landuse=farm )
* crop=sugarcane

Import steps
* Convert to OSM.
* Simplify straight lines. Currently there is a large amount of additional nodes for straight lines.
