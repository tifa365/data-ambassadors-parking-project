# Data Ambassadors Parking Project by DSSG

This project folder is the backbone for the Data Ambassadors Parking Project, curated by DSSG. The goal of this repository is to collect and analyse parking data by the district Friedrichshain-Kreuzberg, in order to generate ideas and evaluate data for the upcoming hackathon by DSSG in November 2021.  

# To-Dos

## A few Guiding Questions for Starting Your Data Exploration Journey

### Cross Validation
* How do the officially counted parking spots by the district, registered cars and counted cars by the Cartagger project compare?

### Demographics and Car Data 
* Do provided parking spots per LOR correlate with age?
* Do provided parking spots per LOR correlate with background of inhabitants? 
* Do provided parking spots per LOR correlate with gender?
* How do parking zones influence parking in Friedrichshain Kreuzberg?
* (Visualisation of parking spaces for disabled persons - how does that correlate with other demographics?)

--> maybe we have to reframe that a bit - I don't think we should only look at correlations but patterns within the different datasets.

## Provided Datasets
* [x] LOR Districts Friedrichshain-Kreuzberg https://github.com/tifa365/data-ambassadors-parking-project/blob/main/data/raw/friedrichshain-kreuzberg/lor_friedrichshain_kreuzberg.GeoJSON
* [X] Official Counted Cars in Friedrichshain-Kreuzberg By Street (Thankfully Provided By Friedrichshain-Kreuzberg) https://github.com/tifa365/data-ambassadors-parking-project/blob/main/data/raw/friedrichshain-kreuzberg/counted_parking-fk.geojson
* **Counted Cars by Natali?**
* [ ] Demographie.xlsx → transform in google sheets or csv https://github.com/tifa365/data-ambassadors-parking-project/blob/main/data/raw/friedrichshain-kreuzberg/Demografie%20Berlin.xlsx
* [x] Registered Cars per LOR in Friedrichshain-Kreuzberg https://github.com/tifa365/data-ambassadors-parking-project/blob/main/data/raw/friedrichshain-kreuzberg/registered_cars_per_lor_fk.geojson.GeoJSON
* [x] Official Parking Spots for Disabled Persons In Friedrichshain-Kreuzberg
https://github.com/tifa365/data-ambassadors-parking-project/blob/main/data/raw/friedrichshain-kreuzberg/parking_spaces_for_disabled_persons_in_fk.geojson
* [x] Paid Parking Zones in Friedrichshain-Kreuzberg https://github.com/tifa365/data-ambassadors-parking-project/blob/main/data/raw/friedrichshain-kreuzberg/paid_parking_zones_friedrichshain_kreuzberg.geojson
* [x] Counted Cars in Friedrichshain-Kreuzberg From Satellite Images Counted By Volunteers (The Cartagger Project). Aerial Images Were Captured between 1th and 6th of April 2019. More Info On https://github.com/hanshack/car-tagging-data-berlin https://github.com/tifa365/data-ambassadors-parking-project/blob/main/data/raw/friedrichshain-kreuzberg/counted_cars_cartagger_project.geojson
* [x] Reference data: Neukölln data? (all the raw data just in case one wants to compare→ data quality) https://github.com/tifa365/data-ambassadors-parking-project/tree/main/data/raw/neukoelln
* [ ](Possibly Overpass API Tags and view for public transport 
* * ([x] ShareNow Rental car stations in Berlin (points)) 

Whenever you have the final data folder with everything needed included, I would ask you (or I can do it as well) to download them to a google shared drive as this is what we are going to share with the volunteers (as maybe not all of them are familiar with github).
