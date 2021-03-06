
## Datasets

This folder lists datasets needed to analyze the parking situation in the district of Friedrichshain-Kreuzberg. 


### Main Files

- **Berlin Street Network** All of Berlins streets, too big to share on Github: https://we.tl/t-2XhwpoDkvu (please report of the link doesn't work)

- **lor-districts.geojson** The official file of mutlipolygons delimiting LOR-Bezirke, still needs to be filtered for Friedrichshain-Kreuberg.

- **counted_cars_cartagger_project.geojson** Point coordinates of motionless and in motion vehicles at a point in time (unknown), as part of the Cartagger-project founded by Hans Hack.In case to be used, unparked cars ("1") need to be filtered out as well.

- **counted_parking-fk.geojson** Line coordinates (length in m) containing parking count. (**KLASSE?**) provided by the district Friedrichshain-Kreuzberg.

- **demographics_berlin_by_lor.xlsx** Demographics in Berlin file from the official website, structured by each LOR districs (needs to be filtered)

## Secondary files

- **vehicle_registration_F_FK.xlsx** Vehicle registration numbers in Friedrichshain-Kreuzberg

- **Detektoren_Brandenburg.json** National road car detectors in Brandenburg.

- **differenztest.json** Line coordinates (**NOT SURE WITH WHAT INFO**)

- **inrix_offstreet_parking_berlin.json** Point coordinates of parking spaces (public, park & ride, events, hotels, airport) all over Berlin. It contains street names and number, parking count within parking space. (**TODO**: match street to Bezirk, filter in only Bezirk FK).

- **parking_spaces_disabled_persons.json** (ALSO CSV) Point coordinates of parking spaces for disabled persons in FK. Includes full adresses. (**ISSUES RENDERING MAP**)

- **parkraumbewirtschaftung_parking_zones.geojson** The official paid parking areas in Berlin as GEOJSON

- **parkzones_hours_pricing.csv** Paid parking (no geospatial info). Most reference links don't work. In [this website](https://parkeninkreuzberg.de) one can find the _"Standorte der Parkscheinautomaten"_ but in pdf and with no possibility to match PARKRAUM_ID index or any other ID column.

- **registered_cars_per_lor.geojson** Polygons delimiting LORS all over Berlin containing info about car registration and demographics from 2018. The data is provided online https://www.berlin.de/sen/uvk/verkehr/verkehrsdaten/zahlen-und-fakten/mobilitaet-in-staedten-srv-2018/ and was recommended by Simon Stock.

- **sharenow_rental_cars.geojson** Point coordinates of ShareNow car rental spots all over Berlin. Includes full addresses (**TODO**: match street to Bezirk, filter in only Bezirk FK).

- **qgis-parking-data-with-database/parken_gesamt.geojson** Same geospatial info as `counted_cars_fr-k.geojson` but with no metadata. (**CHECK THIS!**)
