# Modelling a military scene using a Discrete Global Grid System
This repository contains visual interpretations of a military scene model created during the graduation project of Theodoros Papakostas for the MSc in Geomatics, Faculty of Architecture, TU Delft. For further details the thesis report will be available in the TUDelft repository.

## Datasets
Both military non classified and civil open source geospatial datasets are used. The military scene of scope is the European region.
- EU offshore military areas (points) - EMODnet human activities, [Military areas](https://ows.emodnet-humanactivities.eu/geonetwork/srv/api/records/579e4a3b-95e4-48c6-8352-914ebae0ae1d) (1/2/21)
- EU offshore military areas (polygons) - EMODnet human activities, [Military areas](https://ows.emodnet-humanactivities.eu/geonetwork/srv/api/records/579e4a3b-95e4-48c6-8352-914ebae0ae1d) (1/2/21)
- EU transport networks - European geodata, [european airports](https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/transport-networks) (1/12/13)
- ETOPO5 - World [digital elevation model](https://www.eea.europa.eu/data-and-maps/data/world-digital-elevation-model-etopo5) (28/6/16)

## Discrete Global Grid System framework
The Discrete Global Grid System framework that was utilised to transform and integrate the datasets is the [H3](https://h3geo.org/) Hexagonal hierarchical geospatial indexing system, provided by Uber.
