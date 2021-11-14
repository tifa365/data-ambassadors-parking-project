## Available Datasets
_** Note: All datasets contain information solely from the District of Friedrichshain-Kreuzberg in Berlin, unless specified otherwise._

### General
* [ ] [`lor_friedrichshain_kreuzberg.geojson`] Living Areas (LOR, in German) in the District of Friedrichshain-Kreuzberg 
### Parking
* [ ] [`counted_parked_cars_by_district_office.geojson`] Official Parking Spot Count - Incomplete (kindly provided by the Distric Office of Friedrichshain-Kreuzberg) 
* [ ] [`parking_spaces_for_disabled_persons.geojson`] Official Parking Spots for Disabled Persons - Complete 
* [ ] [`paid_parking_zones.geojson`] Official Paid Parking Zones - Complete 
* [ ] [`estimated_parking_lanes.geojson`] Estimated Parking Lanes (w/ Parking Spot Count) based on OSM data - Complete 
* [ ] [`estimated_parking_spots_kfz.geojson`] Estimated Parking Spots based on OSM data - Complete 
* [ ] [`counted_cars_from_cartagger_project.geojson`] Vehicles (in motion | motionless) from Satellite Images Tagged by Volunteers ([The Cartagger Project](https://github.com/hanshack/car-tagging-data-berlin)) 

### Demographics
* [ ] [`demographics_age_of_inhabitants.csv`] Age of Inhabitants per LOR 
  - Bezirk,	Prognoseraum, Bezirksregion, Planungsrau: columns are number-coded based on `registered_cars.geojson`, is not obvious how to match these. 
* [ ] [`demographics_background_of_inhabitants.csv`] Ethnic Background of Inhabitants per LOR 
  - Bezirk,	Prognoseraum, Bezirksregion, Planungsrau: columns are number-coded based on `registered_cars.geojson`, is not obvious how to match these. 
* [X] [`registered_cars.geojson`] Registered cars per LOR 

### Extras
* [X] [`service_processed.geojson`] Driveways Lanes [[link](https://wiki.openstreetmap.org/wiki/Tag:highway%3Dservice)] 
* [X] [`drive_ways.geojson`] Driveways Entry Points (Intersection of Driveways and Streets) 
* [X] [`streets_processed.geojson`] Complete Street Network 
---

**GLOSSARY**:
- LOR: Lebensweltlich Orientierte Räume
- OSM: Open Street Map Project ([link](https://www.openstreetmap.org/))

