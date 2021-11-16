# Welcome to the Kreuzberg-Friedrichshain Parking Project by DSSG

This project folder is the backbone for the Data Ambassadors Parking Project, curated by DSSG. The goal of this repository is to collect and analyse parking data by the district Friedrichshain-Kreuzberg for the hackathon by DSSG.  

## A few guiding questions for starting your data exploration journey (feel free to ignore these if you have other ideas)

### Cross Validation
* How do the officially counted parking spots by the district, registered cars and counted cars by the Cartagger project compare?

### Demographics and Car Data 
* How are provided parking spots per Berlin LOR district connected to the inhabitants' age?
* How are parking spots per LOR connected to the national background of inhabitants? 
* Are provided parking spots per Berlin LOR district connected to gender?
* How do parking zones influence parking in Friedrichshain Kreuzberg?
* How do parking spaces for disabled persons connect with other demographic data?

## Available Datasets
_** Note: All datasets contain information solely from the District of Friedrichshain-Kreuzberg in Berlin, unless specified otherwise._

### General
* [X] [`lor_friedrichshain_kreuzberg.geojson`] Living Areas (LOR, in German) in the District of Friedrichshain-Kreuzberg 
### folder /Parking
* [ ] [`counted_parked_cars_by_district_office.geojson`] Official Parking Spot Count - Incomplete (kindly provided by the Distric Office of Friedrichshain-Kreuzberg) 
   - Only use columns ANZAHL, KLASSENAM and geometry
   - Values of KLASSENAM: use more informative names (not sure what some of them mean)
   - Delete row where KLASSENAM=Anzahl.txt 
* [X] [`parking_spaces_for_disabled_persons.geojson`] Official Parking Spots for Disabled Persons - Complete 
* [X] [`paid_parking_zones.geojson`] Official Paid Parking Zones - Complete 
  - Not sure if it's very informative.
* [X] [`estimated_parking_lanes.geojson`] Estimated Parking Lanes (w/ Parking Spot Count) based on OSM data - Complete 
* [X] [`estimated_parking_spots_kfz.geojson`] Estimated Parking Spots based on OSM data - Complete 
* [X] [`counted_cars_from_cartagger_project.geojson`] Vehicles (in motion | motionless) from Satellite Images Tagged by Volunteers [[The Cartagger Project](https://github.com/hanshack/car-tagging-data-berlin)]

### folder /Demographics
* [ ] [`demographics_age_of_inhabitants.csv`] Age of Inhabitants per LOR 
  - Bezirk,	Prognoseraum, Bezirksregion, Planungsrau: columns are number-coded based on `registered_cars.geojson`, is not obvious how to match these. 
* [ ] [`demographics_background_of_inhabitants.csv`] Ethnic Background of Inhabitants per LOR 
  - Bezirk,	Prognoseraum, Bezirksregion, Planungsrau: columns are number-coded based on `registered_cars.geojson`, is not obvious how to match these. 
* [X] [`registered_cars.geojson`] Registered cars per LOR 

### folder /Extras
* [X] [`service_processed.geojson`] Driveways Lanes [[OSMwiki - Service](https://wiki.openstreetmap.org/wiki/Tag:highway%3Dservice)] 
* [X] [`drive_ways.geojson`] Driveways Entry Points (Intersection of Driveways and Streets) 
* [X] [`streets_processed.geojson`] Complete Street Network 
* [x] [Neukölln Parking Project Data](https://github.com/tifa365/data-ambassadors-parking-project/tree/main/data/raw/neukoelln)
---

**GLOSSARY**:
- LOR: Lebensweltlich Orientierte Räume[web](https://de-m-wikipedia-org.translate.goog/wiki/Lebensweltlich_orientierte_R%C3%A4ume?_x_tr_sl=de&_x_tr_tl=en&_x_tr_hl=de&_x_tr_pto=nui)
- OSM: Open Street Map Project ([web](https://www.openstreetmap.org/))

