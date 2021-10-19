## Datasets

### Main Files

- **lor-districts.geojson** Mutlipolygons delimiting LOR-Bezirke.

- **counted_cars_cartagger_project.geojson** Point coordinates of motionless and in motion vehicles at a point in time (unknown)

- **counted_parking-fk.geojson** Line coordinates (length in m) containing parking count. (**KLASSE?**)

## Secondary files

- **Detektoren_Brandenburg.json** National road car detectors in Brandenburg.

- **differenztest.json** Line coordinates (**NOT SURE WITH WHAT INFO**)

- **inrix_offstreet_parking_berlin.json** Point coordinates of parking spaces (public, park & ride, events, hotels, airport) all over Berlin. It contains street names and number, parking count within parking space. (**TODO**: match street to Bezirk, filter in only Bezirk FK).

- **parking_spaces_disabled_persons.json** (ALSO CSV) Point coordinates of parking spaces for disabled persons in FK. Includes full adresses. (**ISSUES RENDERING MAP**)

- **parkzones_hours_pricing.csv** Paid parking (no geospatial info). Most reference links don't work. In [this website](https://parkeninkreuzberg.de) one can find the _"Standorte der Parkscheinautomaten"_ but in pdf and with no possibility to match PARKRAUM_ID index or any other ID column.

- **registered_cars_per_lor.geojson** Polygons delimiting LORS all over Berlin containing info about car registration and demographics.

- **sharenow_rental_cars.geojson** Point coordinates of ShareNow car rental spots all over Berlin. Includes full addresses (**TODO**: match street to Bezirk, filter in only Bezirk FK).

- **qgis-parking-data-with-database/parken_gesamt.geojson** Same geospatial info as `counted_cars_fr-k.geojson` but with no metadata. (**CHECK THIS!**)
